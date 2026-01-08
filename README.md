# <YOUR_NAME>

Building systems that measure, learn, and compound.

> Anything added dilutes everything else.

---

## Now 此刻

- Designing low-latency order book infrastructure in Rust
- Building an AI-native growth optimizer: agents simulating user behavior in sandboxes
- Exploring privacy-first analytics—ephemeral by default, burn after reading
- Tending a small ceramics practice and a growing collection of aroids

---

## Principles 原则

- Measure before you optimize. Optimize before you scale.
- Latency is a design constraint, not an afterthought.
- Privacy as architecture, not policy.
- Ship small, learn fast, compound over years.
- Craft transfers: the patience of ceramics informs the patience of systems.

---

## Selected Work 精选项目

- [**Data Platform**](<PINNED_REPO_1_URL>) — Analytics pipelines, experimentation infra, metrics that drive decisions. `SQL` `Athena` `Python`

- [**Trading Infra**](<PINNED_REPO_2_URL>) — Low-latency ingestion, order book reconstruction, microstructure factor research. `Rust` `performance` `quant`

- [**Agentic Simulator**](<PINNED_REPO_3_URL>) — Synthetic users in sandboxes for growth optimization. Privacy-first, probability-driven. `agents` `simulation` `growth`

- [**Privacy Tooling**](<PINNED_REPO_4_URL>) — Ephemeral data pipelines, consent-aware collection, data sovereignty patterns. `privacy` `infrastructure`

---

## Stack 技术栈

`Rust` `Python` `SQL` `TypeScript` `Athena` `MySQL` `AWS` `GCP`

---

## Craft 手作

Ceramics and horticulture as counterweight to code.

Slow work. Irreversible decisions. Learning to see what emerges rather than what was planned.

---

## Contact 联系

- [GitHub](https://github.com/<YOUR_HANDLE>)
- [Blog](<YOUR_BLOG_URL>)
- [Email](mailto:<YOUR_EMAIL>)
- [X / Twitter](https://x.com/<YOUR_HANDLE>)
- [LinkedIn](https://linkedin.com/in/<YOUR_HANDLE>)

---

<sub><YOUR_CITY></sub>

<!--
## Auto-updating sections (optional)

To add dynamic content like "Latest writing" or "Recent releases", you can use GitHub Actions
with a workflow that updates this README on a schedule.

### Skeleton workflow (.github/workflows/update-readme.yml)

```yaml
name: Update README

on:
  schedule:
    - cron: '0 0 * * *'  # Daily at midnight UTC
  workflow_dispatch:

jobs:
  update:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      
      - name: Update README sections
        run: |
          # Your script here to fetch latest blog posts, releases, etc.
          # Example: python scripts/update_readme.py
          echo "Updating README..."
      
      - name: Commit changes
        run: |
          git config --local user.email "action@github.com"
          git config --local user.name "GitHub Action"
          git add README.md
          git diff --quiet && git diff --staged --quiet || git commit -m "chore: update readme"
          git push
```

### Adding a "Latest Writing" section

1. Create a script that fetches your RSS feed or blog API
2. Parse the latest 3-5 posts
3. Replace a placeholder section in README.md with formatted links
4. The workflow commits and pushes the change

### Adding a "Recent Releases" section

Use the GitHub API to fetch recent releases from your repos:

```python
import requests

def get_latest_releases(username, count=3):
    url = f"https://api.github.com/users/{username}/repos"
    repos = requests.get(url).json()
    # Filter and format releases...
```

Replace the markers like:
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

with generated content.
-->
