<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=3200&pause=900&color=C9A961&center=true&vCenter=true&width=520&lines=Designing+systems+that+stay+calm+under+load.;Event-driven+%C2%B7+Observable+%C2%B7+Built+to+scale.;Boring+code.+Reliable+production." alt="tagline" />

# 𝐀𝐋𝐈 𝐌𝐎𝐑𝐀𝐃𝐈

**B A C K E N D &nbsp; S O F T W A R E &nbsp; E N G I N E E R**

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

<table>
<tr>
<td width="33%" valign="top" align="center">

### 🛰
**Distributed Systems**

<sub>Event-driven services, clean boundaries, delivery guarantees that hold through restarts and partitions.</sub>

</td>
<td width="33%" valign="top" align="center">

### 🗄
**Data & Performance**

<sub>Schemas, indexes and queries shaped by real access patterns, not guesses.</sub>

</td>
<td width="33%" valign="top" align="center">

### 📡
**Reliability & Observability**

<sub>Metrics, traces and logs that answer the question before someone has to ask it.</sub>

</td>
</tr>
</table>

<br/>

## ⟡ &nbsp;Open Source

<table>
<tr>
<td width="50%" valign="top">

### 📮 &nbsp;[xoutbox](https://github.com/Ali127Dev/xoutbox)

Broker-agnostic **Transactional Outbox** for Go. Write your state and your events in one transaction, and let the relay deliver them through pluggable **Kafka**, **NATS** or **RabbitMQ** adapters.

[![tag](https://img.shields.io/github/v/tag/Ali127Dev/xoutbox?style=flat-square&label=latest&labelColor=0d1117&color=C9A961)](https://github.com/Ali127Dev/xoutbox/tags)
[![Go](https://img.shields.io/github/go-mod/go-version/Ali127Dev/xoutbox?style=flat-square&labelColor=0d1117&color=00ADD8&logo=go&logoColor=white)](https://github.com/Ali127Dev/xoutbox)

</td>
<td width="50%" valign="top">

### 🧯 &nbsp;[xerr](https://github.com/Ali127Dev/xerr)

**Structured error handling** for Go. Typed, contextual errors that stay readable in logs and traces. Gated by golangci-lint CI and running in production.

[![tag](https://img.shields.io/github/v/tag/Ali127Dev/xerr?style=flat-square&label=latest&labelColor=0d1117&color=C9A961)](https://github.com/Ali127Dev/xerr/tags)
[![Go](https://img.shields.io/github/go-mod/go-version/Ali127Dev/xerr?style=flat-square&labelColor=0d1117&color=00ADD8&logo=go&logoColor=white)](https://github.com/Ali127Dev/xerr)

</td>
</tr>
</table>

<br/>

## ⟡ &nbsp;Toolbox

<table>
<tr>
<td align="right" width="190"><sub><b>LANGUAGES</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=go,ts,js,rust,java&theme=dark" height="40" alt="languages" /></td>
</tr>
<tr>
<td align="right"><sub><b>FRAMEWORKS</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=nestjs,express,nodejs,react,nextjs&theme=dark" height="40" alt="frameworks" /></td>
</tr>
<tr>
<td align="right"><sub><b>DATA &amp; MESSAGING</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,kafka&theme=dark" height="40" alt="data" /> &nbsp;<sub>+ NATS JetStream · BullMQ</sub></td>
</tr>
<tr>
<td align="right"><sub><b>INFRA &amp; OBSERVABILITY</b></sub></td>
<td><img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,gitlab,prometheus,grafana&theme=dark" height="40" alt="infra" /> &nbsp;<sub>+ OpenTelemetry</sub></td>
</tr>
</table>

<br/>

## ⟡ &nbsp;Engineering Philosophy

> [!IMPORTANT]
> **Code should be predictable, maintainable, and boring,**
> **because boring code is the most reliable code when production gets wild.**

<details>
<summary><b>The principles behind it</b> <sub>(click to expand)</sub></summary>

<br/>

| | Principle | In practice |
|:--:|:--|:--|
| 01 | **Simple beats clever** | The best architecture is the one the next engineer understands at a glance. |
| 02 | **Measure, then optimize** | Profile first. Every index and every cache earns its place with data. |
| 03 | **Delivery is a contract** | Outbox over dual writes. Idempotency wherever a retry can hurt. |
| 04 | **Boundaries are features** | Bounded contexts let code and teams evolve without stepping on each other. |
| 05 | **Observe everything** | If it isn't measured, it isn't in production yet. |

</details>

<br/>

<div align="center">

<sub>━━━━━━━━━━━━━ ◆ ━━━━━━━━━━━━━</sub>

**Let's build something that scales beautifully, and fails gracefully when it must.**

<sub>📍 Iran &nbsp;·&nbsp; 🌍 Open to relocation &nbsp;·&nbsp; 💻 Remote-ready</sub>

</div>
