# Awesome-Cloud-Hosted-Selenium-Grid

## Top Cloud-Hosted Selenium Grid Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Remote Browser Orchestration, Parallel Test Execution & Grid Infrastructure Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud-Hosted Selenium Grid**. These tools provide a single endpoint for routing WebDriver sessions to remote browsers—enabling parallel test execution, cross-browser coverage, and centralized management of browser infrastructure without maintaining physical device labs or local grid nodes.

**Examples** include BrowserStack Selenium Grid, Sauce Labs Selenium Grid, LambdaTest Selenium Grid, Moon by Aerokube, Selenoid, Zalenium, Gridlastic, TestingBot Grid, TestGrid Selenium Grid, and Experitest Grid (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted Selenium grid hubs, containerized browser orchestration, and Kubernetes-native grid alternatives—ideal for QA engineers, platform teams, and organizations seeking transparent, vendor-neutral test infrastructure without per-session cloud pricing.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global cloud testing and remote browser execution market is estimated at approximately **$2.0 billion to $2.2 billion** (with broader Testing-as-a-Service exceeding **$14 billion**), projected to grow at a CAGR of 8–12%. The sector exhibits a **hybrid structure**: while the broader tooling ecosystem is moderately fragmented across regional providers and emerging open-source orchestration utilities, commercial enterprise-grade cloud Selenium grid infrastructure is **heavily concentrated** around a few dominant market leaders holding significant moats in real-device farm scale, security certifications, and CI/CD ecosystem integrations.

## SaaS/Hosted Platforms

| Product | Company Scale (Valuation / Revenue) | Description | Starting Tier Pricing | Free Tier / Trial Limits |
|---------|-------------------------------------|-------------|-----------------------|--------------------------|
| **[BrowserStack Selenium Grid](https://www.browserstack.com/)** | ~$4.0B valuation / ~$230M ARR | Cloud Selenium grid with access to 3,000+ real browsers and devices. Point existing WebDriver tests at the BrowserStack hub endpoint with access credentials. Automate plans are priced per parallel session. | $59/month (billed annually) or $79/month for 1 parallel desktop Chrome test ($99/month for all desktop browsers) | Free trial with 60 minutes of automated browser testing (1 hour max per session); lifetime free access for approved open-source projects |
| **[Sauce Labs Selenium Grid](https://saucelabs.com/)** | ~$613M valuation / ~$120M–$150M ARR | Cloud Selenium grid supporting Selenium, Playwright, Appium, and Espresso. Virtual Device Cloud for emulators/simulators and Real Device Cloud for physical devices. | $149/month (billed annually) or $199/month for 1 parallel test (Virtual Device Cloud, unlimited minutes) | 28-day free trial with 60 total automated/live testing minutes across up to 3 parallel VMs |
| **[LambdaTest Selenium Grid](https://www.lambdatest.com/)** | ~$400M valuation / ~$30M–$40M ARR | Cloud Selenium grid with 3,000+ browser/OS combinations. Rebranded to TestMu AI in January 2026. Includes HyperExecute orchestration for parallel testing. | $79/month (billed annually) or $99/month for 1 parallel Desktop Web automation test | Free forever tier with 60 minutes/month of automated browser testing and 1 concurrent session (resets monthly); 15-day trial of real device cloud |
| **[Experitest Grid](https://experitest.com/)** | Digital.ai parent: ~$140M–$230M ARR (Experitest ~$25M revenue at acquisition) | Enterprise mobile & cross-browser continuous testing grid (SeeTest) integrated into Digital.ai platform. Supports Selenium/WebDriver, Appium, Jenkins, and ALM tools. | $250/device slot per month for SaaS unmetered remote testing; custom enterprise contract | 14-day to 30-day guided evaluation with up to 600 free device testing minutes upon trial request |
| **[TestGrid Selenium Grid](https://testgrid.io/)** | Bootstrapped / Pre-Series A (~$2M–$5M ARR est.) | AI-powered test automation platform with real devices, real browsers, and full agentic AI platform. Supports Selenium, Appium, Cypress, and Playwright. | $199/seat per month (CoTester Starter package) | 14-day guided proof-of-concept (PoC) evaluation with dedicated engineering onboarding upon trial request |
| **[TestingBot Grid](https://testingbot.com/)** | Bootstrapped / ~$500K–$1M ARR est. | Cloud Selenium grid with 6,100+ browser/OS combinations and real iOS/Android devices. Billing based on test minutes and parallel tests in plan. | $50/month (billed annually) or $70/month for 1 parallel test and 1,000 automated minutes/month | 14-day free trial with 60 total minutes of testing across real devices and browsers |
| **[Gridlastic](https://www.gridlastic.com/)** | Bootstrapped / Micro-SaaS | Auto-scaling Selenium grid on AWS with spot instance support. Hub runs 24/7; nodes auto-launch on demand. Gridlastic Connect provides encrypted tunnels. | $795/month (Professional tier with 25 parallel nodes and ~15,000 credits/approx. 70k–150k minutes) | Free forever plan with 5 free grid starts per month, up to 2 parallel nodes, max 2 hours per session run |
| **[Moon by Aerokube (Cloud)](https://aerokube.com/moon/)** | Bootstrapped / <$1M ARR est. | Kubernetes-native browser automation supporting Selenium, Playwright, Puppeteer, and Cypress. Deploys via Helm with official Chrome, Firefox, and Edge images. | $5/parallel session per month | Free forever tier allowing up to 4 parallel browser sessions without a license key; unlimited free evaluation keys via Moon Assistance Program |

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
