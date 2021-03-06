<a href="https://unly.org"><img src="https://storage.googleapis.com/unly/images/ICON_UNLY.png" align="right" height="20" alt="Unly logo" title="Unly logo" /></a>
[![Maintainability](https://api.codeclimate.com/v1/badges/3f3f2c0a4106abcb9a1d/maintainability)](https://codeclimate.com/github/UnlyEd/next-right-now/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/3f3f2c0a4106abcb9a1d/test_coverage)](https://codeclimate.com/github/UnlyEd/next-right-now/test_coverage)
[![Locize Latest version](https://img.shields.io/badge/dynamic/json.svg?style=plastic&color=2096F3&label=locize&query=%24.versions%5B%27latest%27%5D.translatedPercentage&url=https://api.locize.app/badgedata/658fc999-dfa8-4307-b9d7-b4870ad5b968&suffix=%+translated&link=https://www.locize.com&prefix=latest:+)](https://www.locize.app/p/w7jrmdie/statistics/badges)
[![Locize Production version](https://img.shields.io/badge/dynamic/json.svg?style=plastic&color=2096F3&label=locize&query=%24.versions%5B%27production%27%5D.translatedPercentage&url=https://api.locize.app/badgedata/658fc999-dfa8-4307-b9d7-b4870ad5b968&suffix=%+translated&link=https://www.locize.com&prefix=production:+)](https://www.locize.app/p/w7jrmdie/statistics/badges)

Next Right Now
===

Next Right Now (NRN) is meant to help you build **production-grade** projects using the **Next.js framework**.

NRN is maintained with several purposes in mind:
- To be used as a **boilerplate** to quickly deploy a **new** project.
    - It is used in production by ourselves, and thus covers enterprise-grade features and needs.
    - It has been used to build production-grade websites within 2h time during a French COVID-19 hackathon. (March 2020)
    - It has been used to build [NRN Admin](https://github.com/UnlyEd/next-right-now-admin)
- To be used as an **educational** resource, meant to be used as a **learning/teaching** resource, even if you don't use it as a boilerplate.
- Provide various boilerplate [presets](./concepts/presets), to get started with the preset that matches the closest your needs.
- To be **flexible** and allow for extensive **customisation**, based on your own needs and use-cases.

Don't hesitate to share your opinion about your ["getting started"](https://github.com/UnlyEd/next-right-now/issues/14) experience and your [feedback about opt-in 3rd parties](https://github.com/UnlyEd/next-right-now/issues/13)!

:point_right: [**Documentation: Overview & benefits (getting started)**](https://unlyed.github.io/next-right-now/). :point_left:

---

# Documentation

There are several sources of documentation:
- [**General documentation**](https://unlyed.github.io/next-right-now/) contains general documentation about the NRN project.
    - Great to learn about our concepts and get an overview of all features NRN has to offer
- **Demo documentation**, which is different for each preset and showcases built-in features within that preset.
    - Great to see code usage examples

Both documentations are related and there are many links from the demos toward the general doc.

---

# Overview of available presets

> Make sure to check the **Doc** link of each preset below, to better understand what are the built-in features within each preset.

| Preset | Links | Demo | Features | Notes |
|:-------|:------|:-----|:---------|:------|
| `v2-mst-aptd-gcms-lcz-sty` | -&nbsp;[Doc](https://unlyed.github.io/next-right-now/available-presets/v2-mst-aptd-gcms-lcz-sty) <br /> -&nbsp;[Branch](https://github.com/UnlyEd/next-right-now/tree/v2-mst-aptd-gcms-lcz-sty) <br /> -&nbsp;[PR](https://github.com/UnlyEd/next-right-now/pull/68) | -&nbsp;[Customer&nbsp;1](https://nrn-v2-mst-aptd-gcms-lcz-sty-c1.now.sh/) <br /> -&nbsp;[Customer&nbsp;2](https://nrn-v2-mst-aptd-gcms-lcz-sty-c2.now.sh/) <br /> -&nbsp;[Admin site](https://nrn-admin.unly.now.sh/) | -&nbsp;Analytics (Amplitude)<br />-&nbsp;GraphQL (GraphCMS)<br />-&nbsp;I18n (GraphCMS + Locize)<br />-&nbsp;Monitoring (Sentry) | -&nbsp;Features a very rich (and complex) application with lots of tooling. <br />-&nbsp;Beware Locize [static i18n](https://unlyed.github.io/next-right-now/concepts/i18n#a-few-words-on-static-i18n) support doesn't come for free. |
| `v1-ssr-mst-aptd-gcms-lcz-sty` (**deprecated**) | -&nbsp;[Doc](https://unlyed.github.io/next-right-now/available-presets/v1-ssr-mst-aptd-gcms-lcz-sty) <br /> -&nbsp;[Branch](https://github.com/UnlyEd/next-right-now/tree/v1-ssr-mst-aptd-gcms-lcz-sty) | -&nbsp;[Customer&nbsp;1](https://nrn-v1-ssr-mst-aptd-gcms-lcz-sty-c1.now.sh/) <br /> -&nbsp;[Customer&nbsp;2](https://nrn-v1-ssr-mst-aptd-gcms-lcz-sty-c2.now.sh/) <br /> -&nbsp;[Admin site](https://nrn-admin.unly.now.sh/) | -&nbsp;Analytics (Amplitude)<br />-&nbsp;GraphQL (GraphCMS)<br />-&nbsp;I18n (GraphCMS + Locize)<br />-&nbsp;Monitoring (Sentry) | -&nbsp;Features a very rich (and complex) application with lots of tooling. <br />-&nbsp;Beware Locize [static i18n](https://unlyed.github.io/next-right-now/concepts/i18n#a-few-words-on-static-i18n) support doesn't come for free. |

---

# FAQ

[Go to our community FAQ](https://unlyed.github.io/next-right-now/faq).

---

# Contributing

[Go to our contributing guide](https://unlyed.github.io/next-right-now/contributing).

---

# License

[MIT](LICENSE)

---

# Vulnerability disclosure

[See our policy](https://github.com/UnlyEd/Unly).

---

# Contributors and maintainers

This project is being maintained by:
- [Unly] Ambroise Dhenain ([Vadorequest](https://github.com/vadorequest)) **(active)**

Special thanks to:
- [Contributor] Hugo Martin ([Demmonius](https://github.com/Demmonius)) - Github Actions CI/CD pipeline

---

# **[ABOUT UNLY]** <a href="https://unly.org"><img src="https://storage.googleapis.com/unly/images/ICON_UNLY.png" height="40" align="right" alt="Unly logo" title="Unly logo" /></a>

> [Unly](https://unly.org) is a socially responsible company, fighting inequality and facilitating access to higher education.
> Unly is committed to making education more inclusive, through responsible funding for students.

We provide technological solutions to help students find the necessary funding for their studies.

We proudly participate in many TechForGood initiatives. To support and learn more about our actions to make education accessible, visit :
- https://twitter.com/UnlyEd
- https://www.facebook.com/UnlyEd/
- https://www.linkedin.com/company/unly
- [Interested to work with us?](https://jobs.zenploy.io/unly/about)

Tech tips and tricks from our CTO on our [Medium page](https://medium.com/unly-org/tech/home)!

#TECHFORGOOD #EDUCATIONFORALL
