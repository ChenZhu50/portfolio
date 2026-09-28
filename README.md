# Chen Zhu · 朱琛 — Portfolio

Bilingual (English / 中文) software engineering portfolio.

**Live site:** https://chenzhu50.github.io/portfolio/

## What's on the site

- **Featured work:** the bilingual website and GEO work for [This Good Comedy](https://www.thisgoodcomedy.com/en/).
- **Engineering projects:**
  - AI-guided robotic testing at Google (internal, code not public)
  - [Lifetime Financial Planner](https://github.com/kalvinliang965/ABCD-LFP): Monte Carlo simulation moved into a worker pool
  - [BERT Attention Visualizer](https://bert-attention-visualizer.vercel.app/): used in a linguistics course with 300+ students
  - [Events Around](https://events-around-demo.onrender.com/): full-stack event search on the Ticketmaster Discovery API with MongoDB favorites. It runs on Render's free tier, so the first load after idle can take about a minute.
- **Experience, education, and contact** sections.

## How it's built

- A single `index.html` with inline CSS and JavaScript, no build step and no framework.
- The EN / 中文 switch swaps copy from an in-page dictionary. The chosen language is remembered in `localStorage`.
- No analytics or tracking scripts.
- Deployed with GitHub Pages from the `main` branch.

## Run locally

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## 中文说明

这是朱琛的中英双语作品集，在线地址：https://chenzhu50.github.io/portfolio/ 。页面内容包括工作经历、项目（含已上线的 Events Around 活动搜索网站）、教育背景和联系方式。整个网站是一个不依赖框架的静态 HTML 文件，通过 GitHub Pages 部署，不含任何追踪脚本。
