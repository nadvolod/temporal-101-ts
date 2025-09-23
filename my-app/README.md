# Building Invincible Apps Using Temporal

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2500&pause=900&color=00C2FF&center=true&vCenter=true&repeat=true&width=700&lines=Temporal+%2B+TypeScript" alt="Animated headline rotating topics" />
</p>

This repository contains code samples and tutorials for building applications using [Temporal](https://temporal.io/), an open-source platform for orchestrating microservices and managing complex workflows.

This is part of the Building Invincible Apps Using Temporal Udemy [course](TBD)

## Resources

- [Temporal Documentation](https://docs.temporal.io/)

## Your Instructor: Nikolay Advolodkin

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2500&pause=900&color=00C2FF&center=true&vCenter=true&repeat=true&width=700&lines=AI‑Driven+Development;Live+Demos+%26+Testing+Hacks;Temporal+%2B+TypeScript+%2B+Playwright" alt="Animated headline rotating topics" />
</p>

<img alt="Nikolay Advolodkin" src="https://b1472923.smushcdn.com/1472923/wp-content/uploads/2024/10/IMG_1980-scaled.jpg?lossy=0&strip=1&webp=1" width="300">

- 🔭 I'm the Chief Engineer at [Ultimate QA](www.ultimateqa.com) where we deliver world-class software development and Developer Advocacy as a Service.
- 💬 Ask me about environmentalism, veganism, test automation, and fitness
- ⚡ Fun fact: I'm a Ukrainian, Russian, Jew that was born in Uzbekistan and raised in US (confusing, I know haha)
- ✨ Follow for AI‑Driven Development tips, live demos, and testing hacks:
  - ▶️ [YouTube — AI Tool Demos and Tech Heartbeat Podcast](https://www.youtube.com/ultimateqa?sub_confirmation=1)
  - 🧪 [Testing with Playwright — weekly newsletter](https://testing-with-playwright.beehiiv.com/)
  - ⚡ [JS Testing Tips — bite‑size code tips](https://ultimateqa.kit.com/js-testing-tips)
  - 💼 [LinkedIn — articles & updates](https://www.linkedin.com/in/nikolayadvolodkin/)
  - 🐦 [X (Twitter) — quick takes & threads](https://twitter.com/intent/follow?screen_name=nikolay_a00)

## Get Started - Hello World

This is the default project that is scaffolded out when you run `npx @temporalio/create@latest ./myfolder`.

The [Hello World Tutorial](https://learn.temporal.io/getting_started/typescript/hello_world_in_typescript/) walks through the code in this sample.

### Running this sample

1. `temporal server start-dev` to start [Temporal Server](https://github.com/temporalio/cli/#installation).
1. `npm install` to install dependencies.
1. `npm run start.watch` to start the Worker.
1. In another shell, `npm run workflow` to run the Workflow Client.

The Workflow should return:

```bash
Hello, Temporal!
```
