<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d9ff,100:0077b5&height=200&section=header&text=Husnul%20Nawafil&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=フスヌル　ナワフィル&descSize=20&descAlignY=55"/>

**Backend engineer. I build systems that stay fast under load and boring under failure.**

Go · Rust · TypeScript · Python &nbsp;·&nbsp; Jakarta, Indonesia 🇮🇩

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/husnulnawafil)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nawafilhusnul@gmail.com)

</div>

## About

I work on the parts of a product users never see but always depend on: high-throughput APIs, event-driven microservices, and the data layers underneath them — mostly in Go, increasingly in Rust.

How I work:

- **Design for failure first.** Timeouts, retries, idempotency, backpressure. Production always finds the failure mode you didn't handle.
- **Simplicity is a feature.** The fastest code is the code that doesn't run, and the most reliable dependency is the one you didn't add.
- **Own it end to end.** Schema design, API contracts, deployment, observability. I build it, I run it, I get paged for it.
- **Measure before optimizing.** Traces and profiles over hunches. p99s over averages.

```go
// The bar every service I ship has to clear.
type Service interface {
	Serve(ctx context.Context) error    // honors deadlines, propagates cancellation
	Healthz() error                     // tells the truth, even when it hurts
	Shutdown(ctx context.Context) error // graceful — finish the work, release the locks
}
```

## Stack

|                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Languages**        | ![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat-square&logo=go&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=flat-square&logo=rust&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white)                         |
| **Data & storage**   | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=flat-square&logo=redis&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white) ![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **Cloud & delivery** | ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazonwebservices&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-%234285F4.svg?style=flat-square&logo=googlecloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-%232C5263.svg?style=flat-square&logo=jenkins&logoColor=white)                                                                                                             |

Day to day: microservices and clean architecture, OpenAPI-first design, Linux, and Neovim.

## Now

- Going deeper on Rust for systems-level work 🦀
- Studying Japanese — 日本語を勉強しています 🇯🇵
- Open-water swimming when I'm away from the keyboard 🏊

---

<div align="center">

Always happy to talk systems design, Go, or why your p99 looks like that.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d9ff,100:0077b5&height=100&section=footer"/>

</div>
