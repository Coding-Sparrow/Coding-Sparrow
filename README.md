### Hey, I'm Ravat 👋

I'm a **Senior Software Engineer at [VERO™](https://vero.co)**, where I work on a social network with no ads and no algorithms. Your feed shows what the people you follow post, in the order they post it.

I mostly write **Java** and build **reactive, event-driven services** on [Vert.x](https://vertx.io) and [RxJava](https://github.com/ReactiveX/RxJava). I like to understand how my tools work underneath, and that often means finding where they break.

## 🔐 Security & open source

I read the code of tools I rely on and report what I find.

- **[px0](https://github.com/px0-ai/px0)** (browser IDE for code review): I reported three vulnerabilities, and all three are fixed upstream.
  - [Self-update downloads and runs unsigned binaries](https://github.com/px0-ai/px0/issues/46) (critical)
  - [`/api/raw` serves workspace HTML/SVG as documents, allowing XSS](https://github.com/px0-ai/px0/issues/75), with a [patch](https://github.com/px0-ai/px0/pull/76)
  - [No Content-Security-Policy on the local UI](https://github.com/px0-ai/px0/issues/77), with a [patch](https://github.com/px0-ai/px0/pull/78)
- **[Vert.x](https://vertx.io)**: I wrote a [minimal reproduction](https://github.com/Coding-Sparrow/vertx-service-proxy-codegen-issue) of a service-proxy codegen bug in Vert.x 4.

## 🛠️ Things I've shipped

Plugins for [Omarchy](https://omarchy.org) (Arch + Hyprland), published and verified on the [official plugin marketplace](https://omarchyplugins.com):

- **[System Pulse](https://github.com/Coding-Sparrow/omarchy-systempulse)**: a system monitor for the bar in the style of iStat Menus, covering CPU, memory, disk, network, battery, and temperature. It reads `/proc` and `/sys` directly, so it needs no daemons. [Marketplace ↗](https://omarchyplugins.com/plugin.html?id=coding-sparrow.systempulse)
- **[Cloudflare WARP](https://github.com/Coding-Sparrow/omarchy-cloudflare-warp)**: install WARP, register with Zero Trust, and toggle the VPN, all from the bar. [Marketplace ↗](https://omarchyplugins.com/plugin.html?id=coding-sparrow.cloudflare-warp)

## Stack

`Java` · `Vert.x` · `RxJava` · `Gradle` · `Python` · `Django` · `TypeScript` · `QML` · `Linux`

---

[LinkedIn](https://www.linkedin.com/in/ravat-tailor-43294111b/) · [X](https://x.com/TailorRavat) · [studious.developer@gmail.com](mailto:studious.developer@gmail.com)
