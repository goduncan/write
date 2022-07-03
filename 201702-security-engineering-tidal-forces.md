# Security Engineering and Tidal Forces


February 2017.

Last month I published a post on the Auth0 engineering blog which describes some of the work I have been doing there. The post is about Cloud Security Monitoring but buried inside is an open source Slack bot audit-droid. The bot is a good example of what Auth0's CTO is talking about [here](https://twitter.com/woloski/status/817082369584697345):

```
    serverless/faas biggest impact isn't no-ops IMO, but the mindset shift to think and ship function-sized software inside the org
    — Matias Woloski (@woloski) January 5, 2017
```

The requirement was to scale the Security team's response capability to handle the increase in security alerts. We chained together existing serverless technologies and integrated them with the companies ChatOps culture. Delivering quickly and iterating based on a feedback loop.

This approach contrasts with a tradition Enterprise information security solution which likely would have been a long and expensive tender for a [SIEM](https://en.wikipedia.org/wiki/Security_information_and_event_management) - resulting in a new appliance and a new process to shoe horn in.

There have been some interesting posts about the [tidal forces](https://securosis.com/blog/tidal-forces-the-trends-tearing-apart-security-as-we-know-it) "tearing apart security as we know it". While the tag line is a little melodramatic; you can feel real change within our industry. I see a maturing of the Infosec discipline from being vendor-led to being engineering-led (arguably as a direct result of expensive vendor solutions not returning any measurable valuable). And, the change is also influenced by the devops cultural shift happening to engineering.

It's an exciting time to be a security engineer as these tidal forces are empowering; you can raise the security bar of your company at the speed you can push code.
