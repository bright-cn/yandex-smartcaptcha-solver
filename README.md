# Yandex SmartCaptcha 破解工具  

[![推广](https://github.com/bright-cn/Awesome-Web-Scraping/raw/main/Proxies%20and%20scrapers%20GitHub%20bonus%20banner%20CN.png)](https://www.bright.cn/products/web-unlocker/captcha-solver/yandex-captcha)

借助 Bright Data 先进的 CAPTCHA 破解技术，轻松绕过 Yandex SmartCaptcha。利用机器学习算法、[自动 IP 轮换](https://www.bright.cn/solutions/rotating-proxies)和强大的代理基础设施，确保顺畅、稳定地访问目标网站。  

Bright Data 的 CAPTCHA 破解是 [**抓取浏览器**](https://www.bright.cn/products/scraping-browser)和 [**网络解锁器 API**](https://www.bright.cn/products/web-unlocker)的内置功能，可提供完整的解决方案，应对最复杂的 CAPTCHA 挑战。  


## 功能  
- **快速破解 CAPTCHA**：自动破解 Yandex SmartCaptcha，准确率高、速度快。  
- **IP 轮换**：通过自动重试和动态 IP 调整避免封禁。  
- **浏览器指纹识别**：模拟真实用户活动，以[绕过复杂的机器人检测](https://www.bright.cn/blog/web-data/anti-scraping-techniques)。  
- **JavaScript 渲染**：处理大量使用 JavaScript 的网站上的动态内容。  
- **全球地理覆盖**：精准解锁全球任何地区的内容。  
- **无缝集成**：可与 Puppeteer、Playwright 和 Selenium 等工具轻松配合使用。  
- **事件监控**：跟踪 CAPTCHA 破解事件，例如检测、成功或失败。  

## 为什么选择 Yandex SmartCaptcha 破解工具  

### **深受全球 20,000 多家客户信赖**  
Bright Data 的验证码破解凭借卓越的可靠性和性能，深受开发者、企业和大型组织信赖。  

### **由优质代理网络提供支持**  
我们的代理基础设施拥有超过 1 亿个 IP，并具备高级地理位置定向功能，可确保顺畅、不间断地破解 CAPTCHA。  

### **AI 驱动的 CAPTCHA 破解**  
我们的 CAPTCHA 破解工具采用先进的 AI 逻辑，自动检测、分析和破解 CAPTCHA。它可处理重试、指纹识别和请求标头，从而绕过最复杂的反机器人措施。  

### **专为开发者打造**  
- 可轻松集成 Puppeteer、Playwright 和 Selenium。  
- 可全面自定义 CAPTCHA 破解行为设置。  
- 通过自动重试和动态 IP 调整，确保爬虫任务不间断运行。

> **专业提示 💡**
>> 已经有 CAPTCHA 破解方案？搭配我们适用于 [Puppeteer](https://www.bright.cn/integration/puppeteer)、[Playwright](https://www.bright.cn/integration/playwright) 和 [Selenium](https://www.bright.cn/integration/selenium) 的代理，进一步减少 CAPTCHA 挑战。

## 工作原理  

Bright Data 的验证码破解功能已集成到**抓取浏览器**和**网络解锁器**中，让 CAPTCHA 破解变得轻而易举。  

### **自动破解 CAPTCHA**  
CAPTCHA 破解工具会实时自动检测并解决 CAPTCHA。只需启用此功能，它便会处理从检测到破解的所有流程。  

#### 工作流程示例：  
1. **检测 CAPTCHA**：破解工具识别 CAPTCHA 类型（例如 PerimeterX）。  
2. **破解 CAPTCHA**：破解工具使用 AI 逻辑解决 CAPTCHA。  
3. **失败后重试**：如果破解失败，系统会自动使用新 IP 重试。  
4. **返回结果**：破解成功后，系统即可无缝访问目标网站。  

## 支持的 CAPTCHA 类型  

Bright Data 的 CAPTCHA 破解支持多种 CAPTCHA 类型，包括：  

- [**DataDome**](https://www.bright.cn/products/web-unlocker/captcha-solver/datadome)
- [**reCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/recaptcha)
- [**点击式 CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/click-captcha)
- [**Cloudflare**](https://brightdata.com/products/web-unlocker/captcha-solver/Cloudflare)
- [**PerimeterX**](https://www.bright.cn/products/web-unlocker/captcha-solver/perimeterx)
- [**SimpleCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/simplecaptcha)
- [**FunCaptcha**](https://www.bright.cn/products/web-unlocker/captcha-solver/funcaptcha)
- [**Cloudflare Turnstile**](https://www.bright.cn/products/web-unlocker/captcha-solver/cloudflare-turnstile)
- [**AWS WAF CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/aws-waf-captcha)
- [**GeeTest CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/geetest-captcha)
- [**KeyCAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/keycaptcha)
- [**拼图 CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/puzzle-captcha)
- [**Yandex CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/yandex-captcha)
- [**图片 CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/image-captcha)
- [**文本 CAPTCHA**](https://www.bright.cn/products/web-unlocker/captcha-solver/text-captcha)

## 高级自定义  

[Bright Data 的 CAPTCHA 破解工具](https://github.com/bright-cn/Captcha-solver)支持高级自定义，可针对特定场景精细调整破解逻辑。

### **Yandex SmartCaptcha 挑战的自定义选项**  
```javascript
// Define default options for different CAPTCHA types
function getCaptchaOptions(captchaType, customOptions = {}) {
  const defaultOptions = {
    timeout: 30000, // Maximum time (in ms) to wait for CAPTCHA solving
    check_timeout: 500, // Interval (in ms) to check the CAPTCHA's status
    wait_networkidle: { timeout: 1000 }, // Wait until the network is idle for 1 second
    debug: false // Debug mode (disabled by default)
  };

  // Define CAPTCHA-specific selectors
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

  // Get the correct selectors for the given CAPTCHA type
  const selectedOptions = captchaSelectors[captchaType] || {};

  // Merge default options with selected CAPTCHA-specific options and any custom overrides
  return { ...defaultOptions, ...selectedOptions, ...customOptions };
}

// Example usage for different CAPTCHA types
const ddOptions = getCaptchaOptions('DataDome', { timeout: 40000, debug: true });
const recaptchaOptions = getCaptchaOptions('reCAPTCHA', { debug: true });
const hcaptchaOptions = getCaptchaOptions('hCaptcha');

console.log(ddOptions);
console.log(recaptchaOptions);
console.log(hcaptchaOptions);

// Example error handling
try {
  if (!document.querySelector(ddOptions.selector)) {
    throw new Error(`CAPTCHA element not found using selector: ${ddOptions.selector}`);
  }

  // Your CAPTCHA-solving logic here
  solveCaptcha(ddOptions);
} catch (error) {
  console.error('Failed to solve CAPTCHA:', error.message);
}
```

## **事件监控**  
跟踪 CAPTCHA 破解事件，以处理高级用例：  
- `Captcha.detected`：检测到 CAPTCHA，破解已开始。  
- `Captcha.solveFinished`：CAPTCHA 破解成功。  
- `Captcha.solveFailed`：CAPTCHA 破解失败。  

## **定价**

| **套餐**         | **价格（每 1,000 个结果）** | **每月费用** | **说明**                                  |  
|-------------------|------------------------|------------------|------------------------------------------------|  
| **免费套餐** | 免费 | $0 | 每月 5,000 次免费请求，无需信用卡。 |
| **按使用量付费** | $1.50                 | 无需承诺    | 适合临时网页抓取需求。               |  
| **成长版**        | $1.30                 | $499             | 专为扩展中的团队量身打造。                    |  
| **商业版**      | $1.10                 | $999             | 适合大规模爬虫任务。  |  
| **高级版**       | $1.00                 | $1,999           | 提供高级功能和优先支持。       |  
| **企业版**    | 定制报价          | 联系我们       | 为顶级企业需求提供定制套餐。   |  

🚀 **特别优惠**：首次充值可获得等额赠金，最高 **$500**！  

## **开发者喜爱 Yandex SmartCaptcha 破解工具的原因**  
- **轻松集成**：可与 Puppeteer、Playwright 和 Selenium 无缝配合使用。  
- **先进的 AI 逻辑**：自动处理重试、CAPTCHA 破解、指纹识别、IP 轮换和高级请求标头。  
- **内置浏览器**：进行 JavaScript 渲染时，无需管理外部浏览器。  
- **实时洞察**：通过实时控制面板监控网络性能。  
- **卓越支持**：提供全天候全球客户支持，并且每天都会添加新功能。  

## **常见问题**  

### **Yandex SmartCaptcha 破解工具如何工作？**  
该破解工具采用先进的 AI 逻辑，自动检测并破解 Yandex SmartCaptcha。  

### **它能同时处理多个 CAPTCHA 吗？**  
可以。该解决方案可扩展并发处理多种 CAPTCHA 类型，确保访问不中断。  

### **如果 CAPTCHA 破解失败会怎样？**  
系统会自动尝试重试。如果问题仍然存在，请联系我们的全天候支持团队进行故障排查。  

---

## **告别 Yandex SmartCaptcha**  
立即开始免费试用，体验[使用 Bright Data 无缝破解 Yandex SmartCaptcha！](https://www.bright.cn/products/web-unlocker/captcha-solver/yandex-captcha) 
