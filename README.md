# Yandex SmartCaptcha Solver  

[![Promo](https://github.com/bright-cn/LinkedIn-Scraper/raw/main/Proxies%20and%20scrapers%20GitHub%20bonus%20banner.png)](https://www.bright.cn/products/web-unlocker/captcha-solver/yandex-captcha)

使用 Bright Data 高级 CAPTCHA 解决方案轻松绕过 Yandex SmartCaptcha。通过利用机器学习算法、[自动 IP 轮换](https://www.bright.cn/solutions/rotating-proxies)以及强大的代理基础设施，确保对目标站点的无缝且稳定的访问。  

Bright Data 的 CAPTCHA Solver 是我们 [**抓取浏览器**](https://www.bright.cn/products/scraping-browser) 和 [**网络解锁器 API**](https://www.bright.cn/products/web-unlocker) 的内置功能，可为您处理最复杂的 CAPTCHA 挑战，提供完整解决方案。  

## 功能  
- **快速解决 CAPTCHA**：自动高准确率、高速度地解决 Yandex SmartCaptcha。  
- **IP 轮换**：通过自动重试和动态 IP 调整来避免封禁。  
- **浏览器指纹**：模拟真实用户行为，[绕过复杂的机器人检测](https://www.bright.cn/blog/web-data/anti-scraping-techniques)。  
- **JavaScript 渲染**：应对 JavaScript 密集型网站上的动态内容。  
- **全球地域覆盖**：精准解锁任意全球区域的内容。  
- **无缝集成**：可与 Puppeteer、Playwright 和 Selenium 等工具轻松配合使用。  
- **事件监控**：监测 CAPTCHA 解决事件，如检测到、成功或失败等。  

## 为什么选择 Yandex SmartCaptcha Solver  

### **受到全球 20,000+ 客户信赖**  
Bright Data 的 CAPTCHA Solver 以卓越的可靠性和性能赢得开发者、企业和组织的信赖。  

### **由高端代理网络提供支持**  
拥有超过 1 亿个 IP 地址和强大的地理定位功能，我们的代理基础设施能确保顺畅且持续的 CAPTCHA 解决过程。  

### **AI 驱动的 CAPTCHA 解决**  
我们的 CAPTCHA Solver 采用先进的 AI 逻辑自动检测、分析并解决 CAPTCHA。它会处理重试、指纹和请求头等问题，助您绕过最复杂的反爬措施。  

### **为开发者打造**  
- 便于与 Puppeteer、Playwright 和 Selenium 进行集成。  
- 完全可自定义 CAPTCHA 解决策略。  
- 自动重试和动态 IP 调整，保障采集过程的连续性。

> **专业提示 💡**  
>> 已经拥有 CAPTCHA 解决方案？可配合我们为 [Puppeteer](https://www.bright.cn/integration/puppeteer)、[Playwright](https://www.bright.cn/integration/playwright) 和 [Selenium](https://www.bright.cn/integration/selenium) 提供的代理，尽量降低 CAPTCHA 出现频率。

## 工作原理  

Bright Data 的 CAPTCHA Solver 集成在 **Scraping Browser** 和 **Web Unlocker** 中，让您能够轻松应对所有 CAPTCHA。  

### **自动解决 CAPTCHA**  
CAPTCHA Solver 会实时自动检测并处理 CAPTCHA。只需启用此功能，它就会从检测到解决全程自动化。  

#### 示例工作流程：  
1. **检测 CAPTCHA**：检测到 CAPTCHA 类型（例如 PerimeterX）。  
2. **解决 CAPTCHA**：使用 AI 逻辑解决 CAPTCHA。  
3. **解决失败则重试**：若解决失败，系统会自动尝试更换 IP 并重试。  
4. **返回结果**：一旦成功通过，系统会直接允许访问目标站点。  

## 支持的 CAPTCHA 类型  

Bright Data 的 CAPTCHA Solver 支持多种类型的 CAPTCHA，包括：  

- [**DataDome**](https://www.bright.cn/products/web-unlocker/captcha-solver/datadome)
- [**reCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/recaptcha)
- [**Click Captcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/click-captcha)
- [**Cloudflare**](https://www.bright.cn/products/web-unlocker/captcha-solver/Cloudflare)
- [**PerimeterX**](https://www.bright.cn/products/web-unlocker/captcha-solver/perimeterx)
- [**SimpleCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/simplecaptcha)
- [**FunCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/funcaptcha)
- [**Cloudflare Turnstile**](https://www.bright.cn/products/web-unlocker/captcha-solver/cloudflare-turnstile)
- [**AWS WAF Captcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/aws-waf-captcha)
- [**GeeTest CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/geetest-captcha)
- [**KeyCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/keycaptcha)
- [**Puzzle CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/puzzle-captcha)
- [**Yandex CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/yandex-captcha)
- [**Image CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/image-captcha)
- [**Text CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/text-captcha)

## 高级定制  

[Bright Data 的 CAPTCHA Solver](https://github.com/bright-cn/Captcha-solver) 支持高级定制，可根据特定场景对解决逻辑进行微调。

### **针对 Yandex SmartCaptcha 挑战的自定义选项**  
```javascript
// 为不同类型的 CAPTCHA 定义默认选项
function getCaptchaOptions(captchaType, customOptions = {}) {
  const defaultOptions = {
    timeout: 30000, // 等待 CAPTCHA 解决的最大时间（毫秒）
    check_timeout: 500, // 检查 CAPTCHA 状态的时间间隔（毫秒）
    wait_networkidle: { timeout: 1000 }, // 等待网络闲置 1 秒
    debug: false // 调试模式（默认关闭）
  };

  // 定义针对不同 CAPTCHA 的选择器
  const captchaSelectors = {
    DataDome: { selector: '#datadome-captcha', success_selector: '#captcha-success' },
    reCAPTCHA: { selector: '.g-recaptcha', success_selector: '.recaptcha-success' },
    ClickCaptcha: { selector: '.click-captcha', success_selector: '.captcha-passed' },
    hCaptcha: { selector: '.h-captcha', success_selector: '.hcaptcha-success' },
    PerimeterX: { selector: '#px-captcha', success_selector: '#px-success' },
    SimpleCaptcha: { selector: '.simple-captcha', success_selector: '.captcha-done' },
    FunCaptcha: { selector: '.funcaptcha', success_selector: '.funcaptcha-success' },
    CloudflareTurnstile: { selector: '.cf-turnstile', success_selector: '.cf-success' },
    AWSWAF: { selector: '#aws-waf-captcha', success_selector: '#aws-waf-success' },
    GeeTest: { selector: '.geetest-captcha', success_selector: '.geetest-success' },
    KeyCAPTCHA: { selector: '#keycaptcha', success_selector: '#keycaptcha-success' },
    PuzzleCAPTCHA: { selector: '.puzzle-captcha', success_selector: '.puzzle-solved' },
    YandexCAPTCHA: { selector: '#yandex-captcha', success_selector: '#yandex-success' },
    ImageCAPTCHA: { selector: '.image-captcha', success_selector: '.image-captcha-success' },
    TextCAPTCHA: { selector: '.text-captcha', success_selector: '.text-captcha-success' }
  };

  // 获取对应 CAPTCHA 类型的选择器
  const selectedOptions = captchaSelectors[captchaType] || {};

  // 将默认选项、CAPTCHA 类型专属选项和自定义选项合并
  return { ...defaultOptions, ...selectedOptions, ...customOptions };
}

// 不同 CAPTCHA 类型的示例用法
const ddOptions = getCaptchaOptions('DataDome', { timeout: 40000, debug: true });
const recaptchaOptions = getCaptchaOptions('reCAPTCHA', { debug: true });
const hcaptchaOptions = getCaptchaOptions('hCaptcha');

console.log(ddOptions);
console.log(recaptchaOptions);
console.log(hcaptchaOptions);

// 示例错误处理
try {
  if (!document.querySelector(ddOptions.selector)) {
    throw new Error(`未找到 CAPTCHA 元素，使用选择器：${ddOptions.selector}`);
  }

  // 在此处编写您的 CAPTCHA 解决逻辑
  solveCaptcha(ddOptions);
} catch (error) {
  console.error('无法解决 CAPTCHA：', error.message);
}
```

## 事件监控  
针对高级应用场景，您可以监控 CAPTCHA 解决事件：  
- `Captcha.detected`: 发现 CAPTCHA 并开始解决。  
- `Captcha.solveFinished`: 成功解决 CAPTCHA。  
- `Captcha.solveFailed`: 解决失败。  

## 定价

| **方案**            | **价格（每 1K 结果）**   | **月度费用**   | **描述**                                     |  
|---------------------|-------------------------|---------------|----------------------------------------------|  
| **按量付费**        | $1.50                  | 无需承诺       | 适合临时性采集需求。                         |  
| **Growth**          | $1.27                  | $499          | 为需要扩展的团队定制。                       |  
| **Business**        | $1.12                  | $999          | 适合大规模采集业务。                         |  
| **Premium**         | $1.05                  | $1,999        | 高级功能+优先支持。                          |  
| **Enterprise**      | 定制报价                | 联系我们       | 满足顶级企业需求的定制解决方案。             |  

🚀 **特别优惠**：首次充值可获得最高 **$500** 金额的同额匹配！  

## 为什么开发者喜爱 Yandex SmartCaptcha Solver  
- **简单集成**：可与 Puppeteer、Playwright 和 Selenium 无缝结合。  
- **先进 AI 逻辑**：自动处理重试、CAPTCHA 解决、指纹、IP 轮换和高级请求头等。  
- **内置浏览器**：无需管理外部浏览器即可渲染 JavaScript。  
- **实时洞察**：可通过实时仪表板监测网络性能。  
- **优质支持**：全球范围内 24/7 客服支持，功能持续更新。  

## 常见问题

### **Yandex SmartCaptcha Solver 如何工作？**  
该解决方案使用先进的 AI 逻辑自动检测并解决 Yandex SmartCaptcha。  

### **能同时处理多个 CAPTCHA 吗？**  
可以，系统可同时处理多种 CAPTCHA 类型，保证访问不中断。  

### **如果 CAPTCHA 解决失败怎么办？**  
系统会自动重试。如仍无法解决，请联系我们 24/7 全天候客服进行排障。  

---

## 告别 Yandex SmartCaptcha  
立即开始免费试用，体验 Bright Data 为您带来的无缝 [Yandex SmartCaptcha 解决方案](https://www.bright.cn/products/web-unlocker/captcha-solver/yandex-captcha)！  
