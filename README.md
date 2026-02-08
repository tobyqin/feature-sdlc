# Feature Ops

Comprehensive research on **Feature Operations (FeatureOps)** practices at leading tech companies — covering how Amazon, Netflix, Meta, Spotify, Shopify, Microsoft, ByteDance, and Alibaba deploy fearlessly, experiment continuously, and ship confidently.

🌐 **Live Site:** [https://tobyqin.cn/feature-sdlc/](https://tobyqin.cn/feature-sdlc/)

## What's Inside

- **8 Company Deep Dives** — Detailed analysis of FeatureOps practices at Amazon, Netflix, Meta, Spotify, Shopify, Microsoft, ByteDance, and Alibaba
- **Comparison Matrix** — Side-by-side comparison across 10 dimensions: architecture, experimentation, deployment strategies, and more
- **Solution Design** — 3-tier architecture guide from MVP (startup) to Growth (mid-size) to Enterprise (large organization)
- **AI Integration** — 12 AI-powered scenarios for intelligent experiment design, autonomous optimization, and cross-experiment learning
- **Business Planning** — Complete Lean Canvas with market analysis, competitive landscape, and go-to-market strategy

## Getting Started

### Prerequisites

- [Hugo](https://gohugo.io/installation/) **v0.146.0 or later** (extended edition recommended)
- [Git](https://git-scm.com/)

To install or upgrade Hugo on macOS:

```bash
# Via Homebrew
brew install hugo

# Or download the latest release from https://github.com/gohugoio/hugo/releases
```

### Clone the Repository

```bash
git clone --recurse-submodules https://github.com/tobyqin/feature-sdlc.git
cd feature-sdlc
```

If you already cloned without `--recurse-submodules`, initialize the theme submodule manually:

```bash
git submodule update --init --recursive
```

### Run Locally

Start the Hugo development server:

```bash
hugo server
```

Then open [http://localhost:1313/feature-sdlc/](http://localhost:1313/feature-sdlc/) in your browser.

### Build for Production

```bash
hugo --minify
```

The generated static site will be in the `public/` directory.

## Project Structure

```
feature-sdlc/
├── content/
│   ├── _index.md              # Homepage
│   ├── docs/                  # Documentation (solution design, lean canvas, AI integration)
│   ├── posts/                 # Blog posts
│   └── research/              # Company-specific FeatureOps research
├── research/                  # Raw research markdown files
├── themes/hextra/             # Hextra Hugo theme (git submodule)
└── hugo.yaml                  # Hugo configuration
```

## Contributing

Contributions are welcome! Feel free to:

- 📂 Open a [Pull Request](https://github.com/tobyqin/feature-sdlc/pulls)
- 🐛 Report [Issues](https://github.com/tobyqin/feature-sdlc/issues)
- 📝 Improve documentation or add new research

## License

This project is open source. All research is freely accessible to help improve the industry knowledge base.
