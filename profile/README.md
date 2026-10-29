<p align="center">
  <img src="https://raw.githubusercontent.com/miracodeai/.github/main/profile/assets/readme-hero.png" alt="Mira — Ship the code. Catch the bugs. Open-source, self-hosted AI code review with your choice of model." width="100%" />
</p>

<p align="center">
  <strong>Self-hosted AI code review. Your code, your dashboard, your LLM key.</strong>
</p>

<p align="center">
  <a href="https://docs.miracode.ai">Documentation</a> ·
  <a href="https://docs.miracode.ai/quickstart">Get started</a> ·
  <a href="https://discord.gg/uEU6qvYhgm">Discord</a>
</p>

We build **Mira**, an open-source AI code reviewer that gives teams control over how their code is reviewed. Connect GitHub, GitLab, or Forgejo, choose your model, and get actionable feedback on every pull or merge request.

Run the full platform on your own infrastructure: the review engine, codebase index, vulnerability scanning, dashboard, and learning loop. Every feature is included, with no paid tier or license key.

### What Mira offers

- **Reviews with context.** Mira indexes your repository to understand the code around a change, then posts inline feedback and a walkthrough. Confidence thresholds, deduplication, and comment limits help keep reviews focused.
- **Your choice of model.** Bring your own LLM key and use OpenRouter or a supported OpenAI-compatible endpoint, including local models. Pay your provider directly, with no markup from Mira.
- **Rules that fit your team.** Set review guidelines in plain language. Mira also learns from rejected comments and human review patterns on merged pull requests.
- **Visibility across repositories.** Explore package inventories, vulnerability alerts, dependencies, review activity, and model costs from your own dashboard.
- **Self-hosted from day one.** Deploy with Docker and SQLite or Postgres. You control where Mira stores your diffs, indexes, and review history, and which model provider processes your code.

### Dashboard

![Mira dashboard — review activity and code quality metrics](https://raw.githubusercontent.com/miracodeai/.github/main/profile/assets/Dashboard.png)

### Our repositories

| Repository | What you'll find |
| --- | --- |
| [mira](https://github.com/miracodeai/mira) | The AI review engine, dashboard, integrations, and deployment tooling. |
| [docs](https://github.com/miracodeai/docs) | Setup guides, configuration reference, and self-hosting documentation. |

### Get started

Follow the **[quickstart](https://docs.miracode.ai/quickstart)** to deploy Mira and connect your repositories, or explore the **[deployment guide](https://docs.miracode.ai/deployment)** for hosting options.

### Build with us

Bug reports, feature ideas, documentation improvements, and pull requests are welcome. Start with the [Mira repository](https://github.com/miracodeai/mira), [open an issue](https://github.com/miracodeai/mira/issues), or join us on [Discord](https://discord.gg/uEU6qvYhgm) to share feedback and get help.

Mira is licensed under [Apache 2.0](https://github.com/miracodeai/mira/blob/HEAD/LICENSE).
