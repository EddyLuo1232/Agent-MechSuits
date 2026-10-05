# Agent MechSuits website

The React project page for **Agent MechSuits: Mechanistic Subspace Safety Steering for Multi-Turn CLI Agents**.

[Research code](https://github.com/EddyLuo1232/AgentLens).

## Development

```sh
npm ci
npm run dev
```

The `main` branch deploys automatically to GitHub Pages through `.github/workflows/deploy.yml`.

The project page is hosted at [eddyluo.com/Agent-MechSuits/](https://eddyluo.com/Agent-MechSuits/).
In the repository's **Settings → Pages**, use **GitHub Actions** as the deployment source.
The workflow installs dependencies with `npm ci`, builds with `npm run build`, and deploys `dist`.
Before building, it reads the actual Pages base path into `PAGES_BASE_PATH`, so repository renames
and custom-domain paths are reflected in the generated URLs. All public logo assets use Vite's
`import.meta.env.BASE_URL`. Local builds default to `/Agent-MechSuits/`.

The NeurIPS logo asset comes from the [official NeurIPS Media Kit](https://neurips.cc/public/MediaKit).
The arXiv logo asset comes from [arxiv.org](https://arxiv.org/).
The GitHub icon comes from [Simple Icons](https://simpleicons.org/).
