# Awesome-Cloud-Hosted-Selenium-Grid

# Top Cloud-Hosted Selenium Grid Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Remote Browser Orchestration, Parallel Test Execution & Grid Infrastructure Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud-Hosted Selenium Grid**. These tools provide a single endpoint for routing WebDriver sessions to remote browsers—enabling parallel test execution, cross-browser coverage, and centralized management of browser infrastructure without maintaining physical device labs or local grid nodes.

**Examples** include BrowserStack Selenium Grid, Sauce Labs Selenium Grid, LambdaTest Selenium Grid, Moon by Aerokube, Selenoid, Zalenium, Gridlastic, TestingBot Grid, TestGrid Selenium Grid, and Experitest Grid (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted Selenium grid hubs, containerized browser orchestration, and Kubernetes-native grid alternatives—ideal for QA engineers, platform teams, and organizations seeking transparent, vendor-neutral test infrastructure without per-session cloud pricing.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[BrowserStack Selenium Grid](https://www.browserstack.com/)** | Cloud Selenium grid with access to 3,000+ real browsers and devices. Point existing WebDriver tests at the BrowserStack hub endpoint with access credentials. Automate plans are priced per parallel session [citation:1]. | Live manual testing from $29/month; Automate plans roughly $150–$250 per parallel session/month at small scale [citation:1] | Limited free trial minutes; free for open-source projects on application [citation:1] |
| **[Sauce Labs Selenium Grid](https://saucelabs.com/)** | Cloud Selenium grid supporting Selenium, Playwright, Appium, and Espresso. Virtual Device Cloud for emulators/simulators and Real Device Cloud for physical devices [citation:2]. | Live Testing: $39/month (annual, 1 parallel); Virtual Device Cloud: $149/month (annual, 1 parallel); Real Device Cloud: $199/month (annual, 1 parallel) [citation:2] | No general free tier; free accounts for qualifying open-source projects; trials arranged through sales [citation:2] |
| **[LambdaTest Selenium Grid](https://www.lambdatest.com/)** | Cloud Selenium grid with 3,000+ browser/OS combinations. Rebranded to TestMu AI in January 2026. Includes HyperExecute orchestration for parallel testing [citation:12]. | Automated testing from $79/month (Desktop Web, annual); Live from $15/month (Virtual Live) [citation:12] | Free lifetime tier: 60 minutes of automated testing; resets monthly [citation:12] |
| **[Moon by Aerokube (Cloud)](https://aerokube.com/moon/)** | Kubernetes-native browser automation supporting Selenium, Playwright, Puppeteer, and Cypress. Deploys via Helm with official Chrome, Firefox, and Edge images [citation:4]. | $5 per parallel session per month [citation:4] | Free evaluation license keys of any size until production via Moon Assistance Program [citation:4] |
| **[Gridlastic](https://www.gridlastic.com/)** | Auto-scaling Selenium grid on AWS with spot instance support. Hub runs 24/7; nodes auto-launch on demand. Gridlastic Connect provides encrypted tunnels for testing behind firewalls. | Credit-based pricing tied to EC2 instance costs; spot instances offer ~59% discount over on-demand [citation:7] | No published free tier; trial via sales |
| **[TestingBot Grid](https://testingbot.com/)** | Cloud Selenium grid with 6,100+ browser/OS combinations and real iOS/Android devices. Billing based on test minutes and parallel tests in plan; queue time and vendor-side failures not billed [citation:8]. | Contact sales for current plans; billing based on test minutes and parallel tests [citation:8] | Free minutes pool included for evaluation; free forever for qualifying open-source projects [citation:8] |
| **[TestGrid Selenium Grid](https://testgrid.io/)** | AI-powered test automation platform with real devices, real browsers, and full agentic AI platform. Supports Selenium, Appium, Cypress, and Playwright [citation:9]. | Starter: $199 per seat/month [citation:9] | Guided proof-of-concept (1–2 weeks) rather than self-serve trial; no permanent free tier [citation:9] |
| **[Experitest Grid](https://experitest.com/)** | Mobile-focused test automation grid (SeeTest) with support for iOS, Android, Windows Phone, and BlackBerry. Integrates with Selenium/WebDriver, Jenkins, and ALM tools [citation:10]. | Quote-only (enterprise contract) | No published free tier; trial via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Selenium Grid 4](https://github.com/SeleniumHQ/selenium)** | [![Stars](https://img.shields.io/github/stars/SeleniumHQ/selenium?style=social&color=white)](https://github.com/SeleniumHQ/selenium/stargazers) | Reference hub-and-node architecture for distributed WebDriver execution. Grid 4 supports distributed tracing, GraphQL status queries, and relay for Appium. |
| **[docker-selenium](https://github.com/SeleniumHQ/docker-selenium)** | [![Stars](https://img.shields.io/github/stars/SeleniumHQ/docker-selenium?style=social&color=white)](https://github.com/SeleniumHQ/docker-selenium/stargazers) | Official Docker images for Grid 4 with Chrome, Firefox, and Edge nodes. Ready-to-run hub and node containers. |
| **[Moon by Aerokube](https://github.com/aerokube/moon)** | [![Stars](https://img.shields.io/github/stars/aerokube/moon?style=social&color=white)](https://github.com/aerokube/moon/stargazers) | Kubernetes-native browser automation supporting Selenium, Playwright, Puppeteer, and Cypress. Stateless, lightweight, with live screen and video recording. |
| **[Selenoid (Archived)](https://github.com/aerokube/selenoid)** | [![Stars](https://img.shields.io/github/stars/aerokube/selenoid?style=social&color=white)](https://github.com/aerokube/selenoid/stargazers) | Original Go-based Docker-container-per-session Selenium hub. Archived December 2024; evaluate WebSummoner or Moon as migration targets. |
| **[Zalenium (Archived)](https://github.com/zalando/zalenium)** | [![Stars](https://img.shields.io/github/stars/zalando/zalenium?style=social&color=white)](https://github.com/zalando/zalenium/stargazers) | Docker-based Grid with video recording, live preview, and dashboard. Archived; supports test step referencing in recorded video via cookies [citation:6]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Callisto](https://github.com/wrike/callisto)** | [![Stars](https://img.shields.io/github/stars/wrike/callisto?style=social&color=white)](https://github.com/wrike/callisto/stargazers) | Open-source Kubernetes-native implementation of Selenium Grid [citation:5][citation:14]. |
| **[Selenoid4K8s](https://github.com/alcounit/selenoid4k8s)** | [![Stars](https://img.shields.io/github/stars/alcounit/selenoid4k8s?style=social&color=white)](https://github.com/alcounit/selenoid4k8s/stargazers) | Fork of Selenoid enabling on-demand browser sessions in Kubernetes clusters [citation:5]. |
| **[WebSummoner](https://github.com/WebSummoner/websummoner)** | [![Stars](https://img.shields.io/github/stars/WebSummoner/websummoner?style=social&color=white)](https://github.com/WebSummoner/websummoner/stargazers) | Maintained Selenoid successor. Go-based, Apache-2.0, Selenoid API compatible; ephemeral Docker containers per session. |

**Frameworks for building custom systems**: Combine **Selenium Grid 4** or **docker-selenium** for standards-compliant WebDriver routing, **Moon** or **Callisto** for Kubernetes-native browser orchestration, and **WebSummoner** for Docker-native ephemeral sessions—creating a fully self-hosted cloud-hosted grid environment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Selenium grid hubs, whether self-hosted or cloud, execute arbitrary browser automation commands; ensure proper authentication, network isolation, and session cleanup to prevent resource exhaustion or unauthorized use.
- Self-hosted grid solutions require capacity planning, browser image updates, and monitoring; archived projects (Selenoid, Zalenium) should be evaluated for migration rather than new deployments.

---

**Made for QA engineers, test automation architects, platform teams, and developers building scalable browser test infrastructure.**  
Let's make cloud-hosted Selenium grid management more open, efficient, and maintainable.
