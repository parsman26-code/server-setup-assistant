# Server Setup Assistant

**Alpha release — v0.1.0-alpha.1**

An Agent Skill for planning and maintaining user-owned servers with an approval-gated workflow. It covers VPS preparation, authorized access, panel and domain configuration, DNS, backups, client profiles, troubleshooting, and privacy-safe public documentation.

این مهارتِ عامل برای برنامه‌ریزی و نگه‌داری سرورهای متعلق به کاربر طراحی شده است. روند کار مرحله‌ای است و برای اقدام‌های اثرگذار، تأیید کاربر را لازم می‌داند. موضوع‌ها شامل آماده‌سازی سرور مجازی، دسترسی مجاز، تنظیم پنل و دامنه، DNS، پشتیبان‌گیری، پروفایل‌های اتصال، عیب‌یابی و مستندسازی امن است.

## Safety and scope

- Use only on systems you own or are explicitly authorized to administer.
- The skill does not install or configure traffic hiding, service impersonation, or detection evasion.
- It does not make purchases, enter provider accounts, or perform financial actions for you.
- Review commands and proposed changes before execution. The skill is guidance, not a substitute for backups, access controls, or professional review.
- Never publish passwords, tokens, private keys, UUIDs, connection profiles, QR codes, subscription links, private hostnames, or unredacted backups.
- DNS filtering cannot reliably remove every in-app advertisement.

## دامنه و ایمنی

- فقط روی سامانه‌هایی استفاده کنید که مالک آن هستید یا مجوز روشن مدیریتشان را دارید.
- این مهارت برای پنهان‌سازی ترافیک، جعل هویت سرویس یا گریز از شناسایی، چیزی نصب یا پیکربندی نمی‌کند.
- خرید، ورود به حساب ارائه‌دهنده یا اقدام مالی را به‌جای شما انجام نمی‌دهد.
- پیش از اجرای فرمان یا تغییر پیشنهادی، آن را بررسی کنید. این مهارت جایگزین پشتیبان، کنترل دسترسی یا بازبینی تخصصی نیست.
- گذرواژه، توکن، کلید خصوصی، شناسهٔ اتصال، پروفایل، QR، پیوند اشتراک، نام میزبان خصوصی یا پشتیبان پالایش‌نشده را منتشر نکنید.
- فیلتر DNS حذف همهٔ تبلیغات داخل برنامه‌ها را تضمین نمی‌کند.

## Installation

Install the skill from this repository with the `skills` CLI:

```sh
npx skills add parsman26-code/server-setup-assistant --skill server-setup-assistant
```

For GitHub Copilot in VS Code, the repository also follows the Agent Skills layout under `.agents/skills/`. See the [VS Code Agent Skills documentation](https://code.visualstudio.com/docs/agent-customization/agent-skills) and the [Agent Skills specification](https://agentskills.io/specification) for compatible locations and format details.

برای نصب با ابزار خط فرمان مهارت‌ها، فرمان بالا را اجرا کنید. در VS Code نیز فایل مهارت در مسیر استاندارد `.agents/skills/` قرار دارد. پشتیبانی از مسیرها و قابلیت‌های اختیاری ممکن است بین عامل‌ها تفاوت داشته باشد.

## Version and feedback

This is an early alpha. Expect gaps and review every recommendation before applying it to a live server. Report bugs using GitHub Issues, but do not include secrets or complete connection configurations. For suspected security vulnerabilities, do not post exploit details publicly; use GitHub's private vulnerability reporting if enabled for the repository.

این نسخه آلفای اولیه است و ممکن است کاستی داشته باشد. هر پیشنهاد را پیش از اعمال روی سرور واقعی بررسی کنید. اشکال‌ها را در Issues گزارش کنید، اما هیچ راز یا پیکربندی کامل اتصالی را نفرستید. جزئیات آسیب‌پذیری امنیتی را عمومی منتشر نکنید؛ در صورت فعال‌بودن، از گزارش خصوصی آسیب‌پذیری گیت‌هاب استفاده کنید.

## License

MIT. See [LICENSE](LICENSE).
