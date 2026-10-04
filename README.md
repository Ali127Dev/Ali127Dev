<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/header-light.svg" />
  <img alt="Ali Moradi — Backend Software Engineer" src="./assets/header-dark.svg" width="760" />
</picture>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=3200&pause=900&color=C9A961&center=true&vCenter=true&width=520&lines=Designing+systems+that+stay+calm+under+load.;Event-driven+%C2%B7+Observable+%C2%B7+Built+to+scale.;Boring+code.+Reliable+production." alt="tagline" />

<sub>Distributed Systems &nbsp;·&nbsp; System Design &nbsp;·&nbsp; Production Reliability</sub>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=C9A961)](https://linkedin.com/in/ali127dev)
[![Email](https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=C9A961)](mailto:ali127dev@gmail.com)
[![Status](https://img.shields.io/badge/Open_to-Relocation_·_Remote-0d1117?style=for-the-badge&labelColor=C9A961)](#)

</div>

<br/>

```go
package main

// whoami — the short version.
type Engineer struct {
	Name      string
	Role      string
	Speaks    []string
	ThinksIn  []string
	Obsession string
	Motto     string
}

var Ali = Engineer{
	Name:      "Ali Moradi",
	Role:      "Backend Software Engineer",
	Speaks:    []string{"Go", "TypeScript", "SQL"},
	ThinksIn:  []string{"Bounded Contexts", "Events", "Failure Modes"},
	Obsession: "systems that behave predictably at 3 AM",
	Motto:     "boring code, reliable production",
}
```

<br/>

## ⟡ &nbsp;Focus

**🛰 &nbsp;Distributed Systems**<br/>
<sub>Event-driven services, clean boundaries, delivery guarantees that hold through restarts and partitions.</sub>

**🗄 &nbsp;Data & Performance**<br/>
<sub>Schemas, indexes and queries shaped by real access patterns, not guesses.</sub>

**📡 &nbsp;Reliability & Observability**<br/>
<sub>Metrics, traces and logs that answer the question before someone has to ask it.</sub>

<br/>

## ⟡ &nbsp;Open Source

#### 📮 &nbsp;[xoutbox](https://github.com/Ali127Dev/xoutbox)

Broker-agnostic **Transactional Outbox** for Go. Write your state and your events in one transaction, and let the relay deliver them through pluggable **Kafka**, **NATS** or **RabbitMQ** adapters.

[![tag](https://img.shields.io/github/v/tag/Ali127Dev/xoutbox?style=flat-square&label=latest&labelColor=0d1117&color=C9A961)](https://github.com/Ali127Dev/xoutbox/tags)
[![Go](https://img.shields.io/github/go-mod/go-version/Ali127Dev/xoutbox?style=flat-square&labelColor=0d1117&color=00ADD8&logo=go&logoColor=white)](https://github.com/Ali127Dev/xoutbox)
[![Go Reference](https://img.shields.io/badge/pkg.go.dev-reference-0d1117?style=flat-square&logo=go&logoColor=00ADD8&labelColor=0d1117&color=161b22)](https://pkg.go.dev/github.com/Ali127Dev/xoutbox)
[![Go Report Card](https://goreportcard.com/badge/github.com/Ali127Dev/xoutbox?style=flat-square)](https://goreportcard.com/report/github.com/Ali127Dev/xoutbox)

#### 🧯 &nbsp;[xerr](https://github.com/Ali127Dev/xerr)

**Structured error handling** for Go. Typed, contextual errors that stay readable in logs and traces. Gated by golangci-lint CI and running in production.

[![tag](https://img.shields.io/github/v/tag/Ali127Dev/xerr?style=flat-square&label=latest&labelColor=0d1117&color=C9A961)](https://github.com/Ali127Dev/xerr/tags)
[![Go](https://img.shields.io/github/go-mod/go-version/Ali127Dev/xerr?style=flat-square&labelColor=0d1117&color=00ADD8&logo=go&logoColor=white)](https://github.com/Ali127Dev/xerr)
[![Go Reference](https://img.shields.io/badge/pkg.go.dev-reference-0d1117?style=flat-square&logo=go&logoColor=00ADD8&labelColor=0d1117&color=161b22)](https://pkg.go.dev/github.com/Ali127Dev/xerr/v3)
[![Go Report Card](https://goreportcard.com/badge/github.com/Ali127Dev/xerr?style=flat-square)](https://goreportcard.com/report/github.com/Ali127Dev/xerr)


<br/>

## ⟡ &nbsp;Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,ts,js,rust,java,nestjs,nodejs,express,react,nextjs,postgres,mysql,mongodb,redis,kafka,docker,kubernetes,githubactions,gitlab,prometheus,grafana&theme=dark&perline=7" alt="toolbox" />
</p>

<p align="center"><sub>+ NATS JetStream &nbsp;·&nbsp; BullMQ &nbsp;·&nbsp; OpenTelemetry</sub></p>

<br/>

## ⟡ &nbsp;Recent Activity

<!--START_SECTION:activity-->
1. 🚀 Published release [v0.1.0](https://github.com/Ali127Dev/xoutbox/releases/tag/v0.1.0) in [Ali127Dev/xoutbox](https://github.com/Ali127Dev/xoutbox)
2. 🚀 Published release [v3.0.0](https://github.com/Ali127Dev/xerr/releases/tag/v3.0.0) in [Ali127Dev/xerr](https://github.com/Ali127Dev/xerr)
3. 🚀 Published release [v2.1.0](https://github.com/Ali127Dev/xerr/releases/tag/v2.1.0) in [Ali127Dev/xerr](https://github.com/Ali127Dev/xerr)
4. 🚀 Published release [v2.0.0 — Layer-aware error handling](https://github.com/Ali127Dev/xerr/releases/tag/v2.0.0) in [Ali127Dev/xerr](https://github.com/Ali127Dev/xerr)
5. 🎉 Merged PR [#1](https://github.com/Ali127Dev/coin-trust/pull/1) in [Ali127Dev/coin-trust](https://github.com/Ali127Dev/coin-trust)
<!--END_SECTION:activity-->

<br/>

## ⟡ &nbsp;Engineering Philosophy

> [!IMPORTANT]
> **Code should be predictable, maintainable, and boring,**
> **because boring code is the most reliable code when production gets wild.**

<details>
<summary><b>The principles behind it</b></summary>

<br/>

**01 &nbsp;·&nbsp; Simple beats clever**<br/>
<sub>The best architecture is the one the next engineer understands at a glance.</sub>

**02 &nbsp;·&nbsp; Measure, then optimize**<br/>
<sub>Profile first. Every index and every cache earns its place with data.</sub>

**03 &nbsp;·&nbsp; Delivery is a contract**<br/>
<sub>Outbox over dual writes. Idempotency wherever a retry can hurt.</sub>

**04 &nbsp;·&nbsp; Boundaries are features**<br/>
<sub>Bounded contexts let code and teams evolve without stepping on each other.</sub>

**05 &nbsp;·&nbsp; Observe everything**<br/>
<sub>If it isn't measured, it isn't in production yet.</sub>

</details>

<br/>

<div align="center">

<sub>━━━━━━━━━━━━━ ◆ ━━━━━━━━━━━━━</sub>

**Let's build something that scales beautifully, and fails gracefully when it must.**

<sub>📍 Iran &nbsp;·&nbsp; 🌍 Open to relocation &nbsp;·&nbsp; 💻 Remote-ready</sub>

</div>
