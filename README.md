<br/>
<div align="center">

A curated list of awesome .NET Security related resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

*List inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 497,248 | 🐛 102 | 📅 2026-08-18 list thing.*

Supported by: [GuardRails.io](https://www.guardrails.io)

</div>
<br/>

# Contents

* [Tools](#tools)
* [Educational](#educational)
* [Companies](#companies)
* [Other](#other)

# Tools

## Libraries

* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) ⭐ 3,173 | 🐛 185 | 🌐 C# | 📅 2024-07-26 - Package that will let you set rate limits for your .NET Core Api.
* [JWT .NET](https://github.com/jwt-dotnet/jwt) ⭐ 2,194 | 🐛 10 | 🌐 C# | 📅 2026-08-12 - Jwt.Net, a JWT (JSON Web Token) implementation for .NET.
* [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer) ⭐ 1,708 | 🐛 18 | 🌐 C# | 📅 2026-08-18 - Cleans HTML to avoid XSS attacks.
* [NetEscapades.AspNetCore.SecurityHeaders](https://github.com/andrewlock/NetEscapades.AspNetCore.SecurityHeaders) ⭐ 855 | 🐛 3 | 🌐 C# | 📅 2026-07-22 - Small package to allow adding security headers to ASP.NET Core websites.
* [NWebsec](https://github.com/NWebsec/NWebsec) ⭐ 550 | 🐛 48 | 🌐 C# | 📅 2023-03-03 - Security libraries for ASP.NET.
* [AspNetSaml](https://github.com/jitbit/AspNetSaml) ⭐ 421 | 🐛 7 | 🌐 C# | 📅 2026-07-25 - SAML client library, allows adding SAML single-sign-on to your ASP.NET app.
* [.NET Core Security Headers](https://github.com/juunas11/aspnetcore-security-headers) ⭐ 276 | 🐛 37 | 🌐 C# | 📅 2025-03-27 - Middleware for adding security headers to an ASP.NET Core application.

## Static Code Analysis

* [DevSkim](https://github.com/Microsoft/DevSkim) ⭐ 1,002 | 🐛 74 | 🌐 C# | 📅 2026-08-16 - DevSkim is a set of IDE plugins and rules that provide security "linting" capabilities.
* [Security Code Scan](https://github.com/security-code-scan/security-code-scan) ⭐ 975 | 🐛 52 | 🌐 C# | 📅 2024-07-08 - Vulnerability Patterns Detector for C# and VB.NET.
* [SonarQube](https://github.com/SonarSource/sonar-dotnet) ⭐ 919 | 🐛 248 | 🌐 C# | 📅 2026-08-18 - SonarC# and SonarVB are static code analyser for C# and VB.​NET languages used as an extension for the SonarQube and SonarCloud platforms. It will allow you to produce stable and easily supported code by helping you to find and to correct bugs, vulnerabilities and smells in your code.
* [Puma Scan](https://github.com/pumasecurity/puma-scan) ⭐ 447 | 🐛 24 | 🌐 C# | 📅 2026-08-07 - Puma Scan is a .NET software secure code analysis tool providing real time, continuous source code analysis.
* [GuardRails](https://www.guardrails.io) - Continuous verification platform that integrates tightly with leading version control systems.

## Vulnerabilities and Security Advisories

* [Snyk](https://github.com/snyk/snyk) ⭐ 5,641 | 🐛 136 | 🌐 TypeScript | 📅 2026-08-18 - CLI and build-time tool to find & fix known vulnerabilities in open-source dependencies.
* [.NET Security Announcements](https://github.com/dotnet/announcements/issues?q=is%3Aopen+is%3Aissue+label%3ASecurity) ⭐ 1,372 | 🐛 399 | 📅 2022-06-29 - Watch this repo to receive security announcements in .NET Core
* [RetireNET](https://github.com/RetireNet/dotnet-retire) ⚠️ Archived - CLI extension to check your project for known vulnerabilities.
* [OWASP Dependency Check](https://github.com/jeremylong/DependencyCheck) ⚠️ Archived - Detects publicly disclosed vulnerabilities in application dependencies.
  * [NuGet tool package](https://www.nuget.org/packages/DependencyCheck.Runner.Tool/) - Nuget tool package for OWASP Dependency Check
* [Audit.NET](https://github.com/OSSIndex/audit.net) ⚠️ Archived - Identify known vulnerabilities in .net NuGet dependencies.
* [Snyk Vulnerability DB](https://snyk.io/vuln?type=nuget) - Commercial but free listing of known vulnerabilities in NuGet libraries.
* [Common Vulnerabilities and Exposures](https://www.cvedetails.com/product/42998/Microsoft-Asp.net-Core.html?vendor_id=26) - Vulnerabilities in .NET Core that were assigned a CVE.
* [National Vulnerability Database](https://nvd.nist.gov/vuln/search/results?form_type=Basic\&results_type=overview\&query=ASP.NET\&queryType=phrase\&search_type=all) - .NET related known vulnerabilities in the National Vulnerability Database.

# Awesome Educational with stars

## Hacking Playgrounds

* [The Most Vulnerable .NET App](https://github.com/AlexGoOn/the-most-vulnerable-dotnet-app) ⭐ 492 | 🐛 0 | 🌐 HTML | 📅 2026-03-06 - A GitHub repository featuring an application with over 50 interactive security vulnerabilities.
* [WebGoat.NET](https://github.com/jerryhoff/WebGoat.NET) ⭐ 257 | 🐛 16 | 🌐 C# | 📅 2023-12-16 - OWASP WebGoat.NET
* [Damn Vulnerable Thick Client App](https://github.com/secvulture/dvta) ⭐ 157 | 🐛 0 | 🌐 C# | 📅 2026-06-21 - DVTA is a Vulnerable Thick Client Application developed in C# .NET
* [ASP.NET Vulnerable Site](http://aspnet.testsparker.com) - Online .NET application that can be used to practice hacking.

## Articles, Guides & Talks

* [Anti-Request Forgery](https://docs.microsoft.com/en-us/aspnet/core/security/anti-request-forgery?view=aspnetcore-2.2) - Prevent Cross-Site Request Forgery (XSRF/CSRF) attacks.
* [Prevent Cross-Site Scripting](https://docs.microsoft.com/en-us/aspnet/core/security/cross-site-scripting?view=aspnetcore-2.2) - Prevent Cross-Site Scripting (XSS).
* [Protect Secrets in Development](https://docs.microsoft.com/en-us/aspnet/core/security/app-secrets?view=aspnetcore-2.2) - Safe storage of app secrets in development
* [.NET Security Cheat Sheet](https://www.owasp.org/index.php/.NET_Security_Cheat_Sheet) - Quick, basic .NET security tips for developers.
* [Hardening the security of your ASP.NET core apps](https://geeklearning.io/hardening-the-security-of-your-asp-net-core-apps/) - Lessons learned after a third-party penetration test.
* [Secure Coding Guidelines](https://docs.microsoft.com/en-us/dotnet/standard/security/secure-coding-guidelines) - Microsoft's take on secure coding guidelines.
* [Security Headers](https://andrewlock.net/adding-default-security-headers-in-asp-net-core/) - Adding Default Security Headers in .NET Core.
* [The ASP.NET Core security headers guide](https://blog.elmah.io/the-asp-net-core-security-headers-guide/) - Another take on adding security headers in ASP.NET Core.
* [Security Best Practices for ASP.NET MVC](https://jamilhallal.blogspot.com/2021/08/building-secure-aspnet-mvc-web.html) - Building Secure ASP.NET MVC Web Applications.

# Other

## Reporting Bugs

* [Report a Security Issue](https://www.microsoft.com/en-us/msrc/faqs-report-an-issue)

## Contributing

Found an awesome project, package, article, or another type of resources related to .NET Security? Submit a pull request!
Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
