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
[![Go Reference](https://img.shields.io/badge/pkg.go.dev-reference-0d1117?style=flat-square&logo=go&logoColor=00ADD8&labelColor=0d1117&color=161b22)](https://pkg.go.dev/github.com/Ali127Dev/xoutbox)
[![Go Report Card](https://goreportcard.com/badge/github.com/Ali127Dev/xoutbox?style=flat-square)](https://goreportcard.com/report/github.com/Ali127Dev/xoutbox)

</td>
<td width="50%" valign="top">

### 🧯 &nbsp;[xerr](https://github.com/Ali127Dev/xerr)

**Structured error handling** for Go. Typed, contextual errors that stay readable in logs and traces. Gated by golangci-lint CI and running in production.

[![tag](https://img.shields.io/github/v/tag/Ali127Dev/xerr?style=flat-square&label=latest&labelColor=0d1117&color=C9A961)](https://github.com/Ali127Dev/xerr/tags)
[![Go](https://img.shields.io/github/go-mod/go-version/Ali127Dev/xerr?style=flat-square&labelColor=0d1117&color=00ADD8&logo=go&logoColor=white)](https://github.com/Ali127Dev/xerr)
[![Go Reference](https://img.shields.io/badge/pkg.go.dev-reference-0d1117?style=flat-square&logo=go&logoColor=00ADD8&labelColor=0d1117&color=161b22)](https://pkg.go.dev/github.com/Ali127Dev/xerr/v3)
[![Go Report Card](https://goreportcard.com/badge/github.com/Ali127Dev/xerr?style=flat-square)](https://goreportcard.com/report/github.com/Ali127Dev/xerr)

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

## ⟡ &nbsp;Tech Radar

```mermaid
%%{init: {"theme": "dark", "themeVariables": {"quadrant1Fill": "#1c1a14", "quadrant2Fill": "#14161a", "quadrant3Fill": "#0d1117", "quadrant4Fill": "#14161a", "quadrantPointFill": "#C9A961", "quadrantTitleFill": "#C9A961", "quadrantPointTextFill": "#e6edf3", "quadrantXAxisTextFill": "#8b949e", "quadrantYAxisTextFill": "#8b949e", "quadrantInternalBorderStrokeFill": "#30363d", "quadrantExternalBorderStrokeFill": "#C9A961"}}}%%
quadrantChart
    x-axis Occasional --> Daily Driver
    y-axis Exploring --> Expert
    quadrant-1 Core Arsenal
    quadrant-2 Deep but Selective
    quadrant-3 On the Radar
    quadrant-4 Growing Fast
    Go: [0.92, 0.9]
    PostgreSQL: [0.86, 0.84]
    TypeScript: [0.74, 0.8]
    Redis: [0.7, 0.74]
    NATS JetStream: [0.66, 0.62]
    Docker: [0.8, 0.66]
    NestJS: [0.45, 0.78]
    Kafka: [0.32, 0.6]
    OpenTelemetry: [0.58, 0.42]
    Kubernetes: [0.4, 0.36]
    Rust: [0.18, 0.3]
    Java: [0.12, 0.42]
```

<br/>

## ⟡ &nbsp;Recent Activity

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

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
