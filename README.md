### Hey, I'm Blake 👋

I'm a software architect from Wisconsin, and I really love to build.

I've spent the last 18 years in open source. These days that's mostly [**Exceptionless**](https://github.com/exceptionless/Exceptionless) (real-time error, log, and metrics observability) and the [**FoundatioFx**](https://github.com/FoundatioFx) ecosystem (the foundational primitives the .NET community runs in production), built with a really great group of contributors.

I'm also **VP at [CodeSmith Tools](https://codesmithtools.com/)**, where I work on **CodeSmith Generator** and the rest of the developer tooling for the teams that depend on it.

Full-time day job: **Principal Software Engineer at [Liaison International](https://www.liaisonedu.com/)**, working on the [**Outcomes**](https://www.liaisonedu.com/higher-education-crm/outcomes/) product and deep integrations across the broader Liaison product suite.

🏆 3× Microsoft MVP, Visual Studio and Development Technologies (Open Source / C#), 2017, 2018, and 2019.

---

### 📦 Open source, in numbers

> **4 billion+ all-time downloads** and **6,500+ ⭐** across the public OSS packages I help maintain.
> *(public registry data, refreshed 2026-05-02)*

| Package group | All-time downloads | Packages | ⭐ |
|---|---:|---:|---:|
| [stack-trace](https://github.com/felixge/node-stack-trace) (npm) | 3,915,441,384 | 1 | 461 |
| [Foundatio](https://github.com/FoundatioFx/Foundatio) (.NET) | 44,888,215 | 36 | 2,229 |
| [Exceptionless](https://github.com/exceptionless/Exceptionless) (.NET) | 34,257,283 | 33 | 3,271 |
| Geocoding, TinyIoC, and CodeSmith (.NET) | 10,869,959 | 31 | 504 |
| Other npm (tracekit, grunt-dom-munger, angular-dialog-service, ng-filters, @derekpitt/fw) | 8,513,015 | 5 | n/a |
| [Exceptionless JS SDK](https://github.com/exceptionless/Exceptionless.JavaScript) (npm) | 217,526 | 7 | 60 |
| **Combined total** | **4,014,187,382** | **113** | **6,525** |

These are really fun projects to work on, and the numbers are fun to look at every great while. But the real reason I keep at it is the chance to help other developers and drive value for the people running this stuff in production. Most of my work lives in .NET, but I do a ton of JavaScript too (about half of my published packages are over on npm), plus a fair bit of Python for the Home Assistant tinkering I do on the side. The goal is the same in every language: ship things that make someone else's day easier while solving genuinely hard technical problems along the way.

---

### 🛠️ Stuff I work on

#### [Exceptionless](https://github.com/exceptionless/Exceptionless)

I've been on this one from the very first commit. Today it's a real-time error, log, and metrics platform with thousands of customers on the hosted side and a long tail of self-hosted deployments running on large Elasticsearch clusters.

Combined, that's **billions of HTTP requests a month**. That kind of scale lives rent-free in my head and shapes every architectural decision I make.

I've helped carry the platform through every major migration with documented self-host upgrade paths:

| Migration | Path |
|---|---|
| Search engine | MongoDB → Elasticsearch (every ES major through current) |
| Runtime | .NET Framework → .NET Core → current LTS |
| Deployment | Windows / IIS → Linux / Docker / Kubernetes |
| Frontend | KnockoutJS → AngularJS → SvelteKit (next-gen UI in flight today) |

#### [FoundatioFx](https://github.com/FoundatioFx)

Pluggable .NET infrastructure: caching, queues, messaging, distributed locks, file storage, and search. I work across the core libraries and most of the cloud and messaging providers.

Production-ready providers across:

| Capability | Backends |
|---|---|
| Caching | In-memory, Redis, hybrid (L1 + L2) |
| Queues | In-memory, Redis, AWS SQS, Azure Storage |
| Messaging | In-memory, Redis (sharded pub/sub), RabbitMQ, AWS SNS/SQS, Azure Service Bus, Kafka |
| File storage | Local, AWS S3, Azure Blob, MinIO |
| Distributed locks | In-memory, Redis |
| Search | Elasticsearch (every major through current) |

When we cut a major release, we coordinate it across 15+ NuGet packages out the same day. That release-day choreography is honestly one of my favorite parts of the job.

#### [CodeSmith Tools](https://codesmithtools.com/)

I've been at CodeSmith for almost two decades. **CodeSmith Generator** is a long-running commercial code generation product for .NET, and I own a lot of the engineering surface around it: Visual Studio integration, MSBuild integration, schema and data providers, the release pipeline, and the daily technical support that comes with a tool teams have depended on for years. We also work on open source ([codesmithtools on GitHub](https://github.com/codesmithtools)).

🏆 Honorary Visual Studio Insider Partner

---

### 🤖 What's pulling me in right now

Agentic development. The tooling has finally crossed the line where it can take real engineering work off your plate, and the pieces I'm building are reusable enough to hand to anyone else.

If that's your world too, I'd love to compare notes.

---

### 🧠 Things I really care about

- **Quality and craftsmanship.** Code I'd be proud to hand to the next maintainer. Tests that prove the thing works, names that read like the problem, no clever tricks where a clear line will do.
- **Consistency.** Same patterns across the ecosystem, same naming, same error model, same release cadence. People shouldn't have to relearn the library every time they touch it.
- **UI consistency.** Same components, same spacing, same interactions across every screen. I'd rather ship one good design system the whole product can lean on than a dozen one-off pages that drift apart over time.
- **Distributed architecture and scale.** Systems that hold up when traffic doesn't behave, providers that swap without breaking the contract, primitives that compose into something bigger than themselves.
- **Messaging that survives failure.** Delivery semantics, fan-out, dead-letter queues, broker acknowledgments, partition recovery. The stuff that decides whether your Sunday is quiet.
- **Concurrency correctness.** Race conditions, deadlocks, async lifecycle, graceful shutdown. I've debugged enough of these to know they hide in plain sight, so I write libraries assuming the next person isn't looking for them.
- **Search infrastructure.** Elasticsearch end-to-end, query parsers, application-side join patterns, date-math expressions.
- **Attention to detail.** The little things, like error messages that actually help, log lines you can grep for, sensible defaults, and small APIs you can hold in your head. Multiply them across a decade and they become the thing.
- **APIs that survive a decade.** Small surface, primitives that compose, predictable upgrade paths, no surprises for the people running it in production. I'd rather ship one good primitive than three clever abstractions.
- **Open source as a long game.** Every release, every migration, no shortcuts. The work that compounds is the work worth doing.

---

### ✍️ From the blog

I write about .NET and JavaScript, distributed systems, observability, agentic development, and the occasional home-automation rabbit hole. Latest posts live at [blakeniemyjski.com](https://blakeniemyjski.com).

<!-- BLOG-POST-LIST:START -->
- [Agentic Driven Development &lpar;ADD&rpar;: AGENTS.md, Skills, and the Full Workflow](https://blakeniemyjski.com/blog/agentic-driven-development/)
- [How-to get notifications when your mailbox is opened](https://blakeniemyjski.com/blog/how-to-get-notifications-when-your-mailbox-is-opened/)
- [Disturbing trends in smart home products and services](https://blakeniemyjski.com/blog/disturbing-trends-in-smart-home-products-and-services/)
- [Securing smart home devices with ESPHome and Home Assistant](https://blakeniemyjski.com/blog/securing-smart-home-devices-with-esphome-and-home-assistant/)
- [Building and maintaining a smart home presentation](https://blakeniemyjski.com/blog/building-and-maintaining-a-smart-home-presentation/)
<!-- BLOG-POST-LIST:END -->

<sub>Stats above come from public NuGet / npm registry APIs and GitHub contributor data, refreshed 2026-05-02. The pipeline that produces them lives at [niemyjski/repo-stats](https://github.com/niemyjski/repo-stats).</sub>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=niemyjski" alt="niemyjski" /></p>
