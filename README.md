<p align="center"><a href="https://rudderstack.com"><img src="https://raw.githubusercontent.com/rudderlabs/rudder-server/master/resources/RudderStack.png" alt="RudderStack - An Open Source Customer Data Platform" height="90"/></a></p>
<h1 align="center"></h1>
<p align="center"><b>The warehouse-first customer data pipeline built for devs</b></p>
<br/>

# dbt-rudderstack-attribution

This repository contains DBT code related to the Attribution use case. We have tried to build a DBT model that can create "session" abstractions on top of web page views of a user on one or more RudderStack web properties. The session information from these DBT models can then be used in conjunction with transaction and referrer data for various attribution related analysis. 
|:------|
 

Questions? Please join our [Slack channel](https://resources.rudderstack.com/join-rudderstack-slack) or read about us on [Product Hunt](https://www.producthunt.com/posts/rudderstack). 

# Why Use dbt-rudderstack-attribution

Any individual or organization using RudderStack to capture web page view data can use the DBT models available in this repository to create session abstractions of users' web browsing activities. 

# Key Features

DBT model code for creating session abstractions on top of web page view data captured using RudderStack 

# Get Started

This repostiory can be imported directly into a DBT project 

# License

RudderStack dbt-rudderstack-attribution is released under the [MIT License][mit_license].

# Contribute

We would love to see you contribute to RudderStack. Get more information on how to contribute [here](CONTRIBUTING.md).

# Follow Us

- [RudderStack Blog][rudderstack-blog]
- [Slack][slack]
- [Twitter][twitter]
- [LinkedIn][linkedin]
- [dev.to][devto]
- [Medium][medium]
- [YouTube][youtube]
- [HackerNews][hackernews]
- [Product Hunt][producthunt]

# :clap:  Our Supporters

[![Stargazers repo roster for @rudderlabs/dbt-rudderstack-attribution](https://reporoster.com/stars/rudderlabs/dbt-rudderstack-attribution)](https://github.com/rudderlabs/dbt-rudderstack-attribution/stargazers)

[![Forkers repo roster for @rudderlabs/dbt-rudderstack-attribution](https://reporoster.com/forks/rudderlabs/dbt-rudderstack-attribution)](https://github.com/rudderlabs/dbt-rudderstack-attribution/network/members)

<!----variables---->

[slack]: https://resources.rudderstack.com/join-rudderstack-slack
[twitter]: https://twitter.com/rudderstack
[linkedin]: https://www.linkedin.com/company/rudderlabs/
[devto]: https://dev.to/rudderstack
[medium]: https://rudderstack.medium.com/
[youtube]: https://www.youtube.com/channel/UCgV-B77bV_-LOmKYHw8jvBw
[rudderstack-blog]: https://rudderstack.com/blog/
[hackernews]: https://news.ycombinator.com/item?id=21081756
[producthunt]: https://www.producthunt.com/posts/rudderstack
[mit_license]: https://opensource.org/licenses/MIT
[agplv3_license]: https://www.gnu.org/licenses/agpl-3.0-standalone.html
[sspl_license]: https://www.mongodb.com/licensing/server-side-public-license
[config-generator]: https://github.com/rudderlabs/config-generator
[config-generator-section]: https://github.com/rudderlabs/rudder-server/blob/master/README.md#rudderstack-config-generator
[rudder-logo]: https://repository-images.githubusercontent.com/197743848/b352c900-dbc8-11e9-9d45-4deb9274101f
