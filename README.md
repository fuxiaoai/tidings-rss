<div align="center">
  <img src="https://tidings.info/apple-touch-icon.png" width="96" height="96" alt="Tidings app icon">
  <h1>Tidings RSS</h1>
  <p><strong>High-quality feeds, organized into OPML bundles you can import directly.</strong></p>
  <p>Start with the Top 200, then use topic bundles or the 719-source directory when you want more. Catalog last checked: 2026-08-20.</p>
  <p><a href="README.zh-CN.md">简体中文</a> · <a href="#downloads">Download OPML</a> · <a href="RSS-GUIDE.md">RSS guide</a> · <a href="#complete-source-directory">Browse every source</a> · <a href="CONTRIBUTING.md">Suggest a feed</a> · <a href="https://tidings.info/">Get Tidings</a></p>
  <p>
    <a href="https://github.com/fuxiaoai/tidings-rss/actions/workflows/validate.yml"><img alt="Catalog validation" src="https://github.com/fuxiaoai/tidings-rss/actions/workflows/validate.yml/badge.svg"></a>
    <a href="https://github.com/fuxiaoai/tidings-rss/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/fuxiaoai/tidings-rss?style=flat-square"></a>
    <a href="LICENSE"><img alt="CC0-1.0" src="https://img.shields.io/badge/license-CC0--1.0-blue?style=flat-square"></a>
  </p>
</div>

For a first import, choose the Top 200. It keeps established publishers, long-running independent writers, first-party sources, and authors with strong community recognition from the 719-source directory. All 14 categories are represented, without leaving you hundreds of subscriptions to prune.

The Top 200 balances Chinese and English sources across AI, engineering, security, technology media, newsletters, research, news, product, business, blogs, communities, culture, video, and podcasts. Use a topic bundle when you want more depth, or the complete collection when you want an archive to organize yourself.

## Downloads

If you are unsure, choose the Top 200. Topic bundles overlap; the complete collection contains each feed URL once.

| Collection | Feeds | Download | Best for |
| --- | ---: | --- | --- |
| ⭐ Top 200 (recommended) | `200` | [Download `tidings-top200.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-top200.opml) | Broad, high-quality coverage with a much smaller cleanup cost |
| 📚 Complete collection | `719` | [Download `tidings-all.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-all.opml) | Keeping the full directory or pruning it yourself |
| ✍️ Chinese independent blogs | `349` | [Download `tidings-blogs.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-blogs.opml) | Active Chinese personal writing |
| 👥 Technical communities | `14` | [Download `tidings-communities.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-communities.opml) | V2EX, LINUX DO, Reddit, Hacker News, and other active discussions |
| 🔐 Security | `8` | [Download `tidings-security.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-security.opml) | Vulnerabilities, defensive guidance, security research, and news |
| 📰 Technology media | `10` | [Download `tidings-tech-media.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-tech-media.opml) | Technology news, products, and long-form reporting |
| 📮 Technical newsletters | `10` | [Download `tidings-weeklies.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-weeklies.opml) | AI, JavaScript, Go, Rust, and Chinese technology weeklies |
| 💬 WeChat official accounts | `30` | [Download `tidings-wechat.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-wechat.opml) | Reading selected WeChat articles outside the app |
| 🏢 Company technology | `40` | [Download `tidings-company-tech.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-company-tech.opml) | First-party engineering, AI, security, and research writing |
| 🤖 Artificial intelligence | `100` | [Download `tidings-ai.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-ai.opml) | Models, research, tools, and technical viewpoints |
| 🗞️ Fresh news | `44` | [Download `tidings-news.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-news.opml) | International, technology, security, and Chinese news |
| 🔬 Research and science | `27` | [Download `tidings-research.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-research.opml) | Papers, journals, labs, and science reporting |
| 🛠️ Engineering and technology | `420` | [Download `tidings-engineering.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-engineering.opml) | Software, architecture, developer tools, and engineering practice |
| 🎬 Video channels | `93` | [Download `tidings-videos.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-videos.opml) | AI, software, science, and business video |
| 🎧 Podcasts | `73` | [Download `tidings-podcasts.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-podcasts.opml) | Technology, business, science, and Chinese shows |
| 🀄 Chinese-language sources | `469` | [Download `tidings-chinese.opml`](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/tidings-chinese.opml) | Chinese articles, communities, video, and audio |

[RSS guide](RSS-GUIDE.md) · [Browse OPML](opml/) · [SHA-256 checksums](https://github.com/fuxiaoai/tidings-rss/releases/latest/download/SHA256SUMS.txt) · [Catalog summary](reports/catalog-summary.md) · [Machine-readable catalog](data/feeds.json)

## What makes the cut

The Top 200 begins with authorship and editorial reputation: first-party institutional work, writers with a durable body of work, and creators with established community recognition. Recent publishing, useful feed text, and endpoint stability remain hard requirements. Similar sections from one publisher are deduplicated, and fast-moving release logs or generated searches do not outrank authored work merely because they update often.

Candidates are checked through the Tidings production parser three times. A Top 200 feed must return articles and real publication dates in every round. This review ran on the current network and preferred official, directly reachable endpoints; it is not a permanent availability guarantee for every mainland region or carrier, and a few overseas sources may still depend on local network conditions. See the [selection report](reports/top200-curation.json) for the recorded results.

Chinese independent blogs are judged mainly on recent writing and useful article content. WeChat feeds must connect quickly and produce recent articles in Tidings. Company technology feeds are unique by organization and technical direction; when an official website covers the same direction, it replaces the matching WeChat feed.

Feeds move and disappear, so the directory is checked regularly. If a source is missing, broken, or misclassified, [send a suggestion](CONTRIBUTING.md).

## Read with Tidings

**Website: [tidings.info](https://tidings.info/)**

Tidings is currently available for macOS 12 and later.

Any compatible reader can import these files. Tidings is the recommended reader for importing the complete directory: it preserves the OPML groups and keeps RSS, Atom, JSON Feed, video subscriptions, and supported community threads in one library.

[![RSS bundles imported into Tidings](https://cdn.jsdelivr.net/gh/fuxiaoai/tidings-rss@v1.1.0/assets/tidings-import-news-research.png)](assets/tidings-import-news-research.png)

### AI from the unread list into every article

Tidings is an AI-native RSS reader. When unread articles pile up, AI Radar groups related stories, surfaces the important developments, and keeps links back to the original sources. Open a long article for a quick AI summary, then ask follow-up questions about any detail without leaving the article.

For foreign-language reading, AI generates translations paragraph by paragraph and places them alongside the source text.

After reading, activated Pro users can export unlimited Markdown or write directly to Obsidian, with the option to include the AI summary; PDF export remains free.

AI features use an independent AI provider selected by the user, which may require its own account, API key, or separate payment. The Tidings Pro license unlocks the software features; it does not include model usage. See the [website](https://tidings.info/) for current features and licensing.

| AI article summary | Ask the current article |
| :---: | :---: |
| [![Tidings AI article summary](https://tidings.info/assets/screenshots/ai-summary-en.webp)](https://tidings.info/assets/screenshots/ai-summary-en.webp) | [![Tidings article Q&A](https://tidings.info/assets/screenshots/ask-article-en.webp)](https://tidings.info/assets/screenshots/ask-article-en.webp) |
| Get the main points first, then decide where to read closely. | Ask follow-up questions using the current article as context. |
| **Daily AI Radar** | **AI-powered translation** |
| [![Tidings Daily AI Radar](https://tidings.info/assets/screenshots/ai-radar-en.webp)](https://tidings.info/assets/screenshots/ai-radar-en.webp) | [![Tidings AI-powered translation](https://tidings.info/assets/screenshots/bilingual-en.webp)](https://tidings.info/assets/screenshots/bilingual-en.webp) |
| Group daily unread articles, surface important developments, and return to the cited source. | Read AI-generated translations paragraph by paragraph beside the source text. |
| **Video subscriptions** | **Community threads** |
| [![Tidings video subscriptions](https://tidings.info/assets/screenshots/videos-feed-en.webp)](https://tidings.info/assets/screenshots/videos-feed-en.webp) | [![Tidings community threads](https://tidings.info/assets/screenshots/forum-en.webp)](https://tidings.info/assets/screenshots/forum-en.webp) |
| Browse video subscriptions in their own view. | Read structured discussions from supported sites. |
| **Third-party account sync** | **Millisecond global search** |
| [![Tidings connects to a FreshRSS account](assets/tidings/freshrss-sync-zh.webp)](assets/tidings/freshrss-sync-zh.webp) | [![Tidings global search](assets/tidings/global-search-zh.webp)](assets/tidings/global-search-zh.webp) |
| Connect FreshRSS to sync subscriptions, categories, read state, and saved items in both directions. | Press `⌘ G` while reading to find a feed or article title and jump straight to it. |

The complete directory follows, with source names, descriptions, categories, and bundle membership.

<!-- SOURCE_APPENDIX_START -->
## Complete source directory

All 719 feeds in the complete collection are listed below with their primary category and bundles. This appendix is generated from `data/feeds.json`.

<details>
<summary>🤖 Artificial Intelligence · 38</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [AI](https://blog.google/innovation-and-ai/technology/ai/) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://blog.google/technology/ai/rss/) | ai, all, engineering |
| [AI Musings by Mu](https://kelvinmu.substack.com) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://kelvinmu.substack.com/feed) | ai, all, engineering |
| [AI 开发者日报](https://ainews.liduos.com) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://ainews.liduos.com/rss.xml) | ai, all, chinese, engineering, top200 |
| [Anthropic News](https://www.anthropic.com/news) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://rsshub.bestblogs.dev/anthropic/news) | ai, all, company-tech, engineering, top200 |
| [Apple Machine Learning Research](https://machinelearning.apple.com) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://machinelearning.apple.com/rss.xml) | ai, all, company-tech, engineering, research, top200 |
| [Artificial Intelligence](https://aws.amazon.com/blogs/machine-learning/) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://aws.amazon.com/blogs/amazon-ai/feed/) | ai, all, company-tech, engineering, top200 |
| [cs.AI updates on arXiv.org](http://rss.arxiv.org/rss/cs.AI) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://rss.arxiv.org/rss/cs.AI) | ai, all, engineering, research |
| [cs.CL updates on arXiv.org](http://rss.arxiv.org/rss/cs.CL) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://export.arxiv.org/rss/cs.CL) | ai, all, engineering, research, top200 |
| [cs.CV updates on arXiv.org](http://rss.arxiv.org/rss/cs.CV) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://export.arxiv.org/rss/cs.CV) | ai, all, chinese, engineering, research |
| [cs.LG updates on arXiv.org](http://rss.arxiv.org/rss/cs.LG) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://export.arxiv.org/rss/cs.LG) | ai, all, chinese, engineering, research |
| [DeepSeek](https://wechat2rss.bestblogs.dev/feed/1709da4f538d4ce4fb6d7a8ba1a5a1c297919601.xml) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://wechat2rss.bestblogs.dev/feed/1709da4f538d4ce4fb6d7a8ba1a5a1c297919601.xml) | ai, all, chinese, company-tech, engineering, top200, wechat |
| [Google DeepMind News](https://deepmind.google/blog/) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://deepmind.com/blog/feed/basic/) | ai, all, company-tech, engineering, top200 |
| [Hacker News - Newest: "AI"](https://news.ycombinator.com/newest) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://hnrss.org/newest?q=AI) | ai, all, engineering |
| [Hacker News - Newest: "LLM"](https://news.ycombinator.com/newest) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://hnrss.org/newest?q=LLM) | ai, all, engineering |
| [Hugging Face - Blog](https://huggingface.co/blog) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://huggingface.co/blog/feed.xml) | ai, all, company-tech, engineering, top200 |
| [MIT News - Artificial intelligence](https://news.mit.edu/rss/topic/artificial-intelligence2) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://news.mit.edu/rss/topic/artificial-intelligence2) | ai, all, engineering, research, top200 |
| [OpenAI News](https://openai.com/news) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://openai.com/news/rss.xml) | ai, all, company-tech, engineering, top200 |
| [Recent Commits to openclaw:main](https://github.com/openclaw/openclaw/commits/main) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://github.com/openclaw/openclaw/commits/main.atom) | ai, all, engineering |
| [Release notes from claude-code](https://github.com/anthropics/claude-code/releases) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://github.com/anthropics/claude-code/releases.atom) | ai, all, engineering |
| [Release notes from codex](https://github.com/openai/codex/releases) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://github.com/openai/codex/releases.atom) | ai, all, engineering |
| [Release notes from gemini-cli](https://github.com/google-gemini/gemini-cli/releases) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://github.com/google-gemini/gemini-cli/releases.atom) | ai, all, engineering |
| [Release notes from langchain](https://github.com/langchain-ai/langchain/releases) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://github.com/langchain-ai/langchain/releases.atom) | ai, all, engineering |
| [Release notes from modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol/releases) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://github.com/modelcontextprotocol/specification/releases.atom) | ai, all, engineering |
| [Release notes from openclaw](https://github.com/openclaw/openclaw/releases) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://github.com/openclaw/openclaw/releases.atom) | ai, all, engineering |
| [Release notes from servers](https://github.com/modelcontextprotocol/servers/releases) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://github.com/modelcontextprotocol/servers/releases.atom) | ai, all, engineering |
| [Simon Willison's Weblog](http://simonwillison.net/) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://simonwillison.net/atom/everything/) | ai, all, engineering, top200 |
| [The latest research from Google](https://research.google/blog/) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://research.google/blog/rss/) | ai, all, company-tech, engineering, research, top200 |
| [大模型智能](https://wechat2rss.bestblogs.dev/feed/bfc6440c1a2443fab9a6bf607137d41db5cd5c93.xml) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://wechat2rss.bestblogs.dev/feed/bfc6440c1a2443fab9a6bf607137d41db5cd5c93.xml) | ai, all, chinese, engineering |
| [我爱计算机视觉](https://wechat2rss.xlab.app/feed/b81ffcfff1107b5265cd7e39de610dc7ca72caf4.xml) | WeChat article feed covering 计算机视觉研究与应用. | Artificial Intelligence | [RSS](https://wechat2rss.xlab.app/feed/b81ffcfff1107b5265cd7e39de610dc7ca72caf4.xml) | ai, all, chinese, engineering, top200, wechat |
| [新智元](https://wechat2rss.xlab.app/feed/ede30346413ea70dbef5d485ea5cbb95cca446e7.xml) | WeChat article feed covering 人工智能产业与研究. | Artificial Intelligence | [RSS](https://wechat2rss.xlab.app/feed/ede30346413ea70dbef5d485ea5cbb95cca446e7.xml) | ai, all, chinese, engineering, top200, wechat |
| [智谱](https://wechat2rss.bestblogs.dev/feed/433d2134dca54d80804daf32e8be546155be3300.xml) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://wechat2rss.bestblogs.dev/feed/433d2134dca54d80804daf32e8be546155be3300.xml) | ai, all, chinese, engineering, top200 |
| [月之暗面 Kimi](https://wechat2rss.bestblogs.dev/feed/c5c43d4bc17bae656763859ed0903bb6314ec6fe.xml) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://wechat2rss.bestblogs.dev/feed/c5c43d4bc17bae656763859ed0903bb6314ec6fe.xml) | ai, all, chinese, company-tech, engineering, wechat |
| [机器之心](https://wechat2rss.bestblogs.dev/feed/8d97af31b0de9e48da74558af128a4673d78c9a3.xml) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://wechat2rss.bestblogs.dev/feed/8d97af31b0de9e48da74558af128a4673d78c9a3.xml) | ai, all, chinese, engineering, top200, wechat |
| [机器之心SOTA模型](https://wechat2rss.bestblogs.dev/feed/2f520471856d56c7b3a95cd09eb777149b32828a.xml) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://wechat2rss.bestblogs.dev/feed/2f520471856d56c7b3a95cd09eb777149b32828a.xml) | ai, all, chinese, engineering, wechat |
| [腾讯混元](https://wechat2rss.bestblogs.dev/feed/306ce19a1ca590c9c2df781789e828d1acfa1356.xml) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://wechat2rss.bestblogs.dev/feed/306ce19a1ca590c9c2df781789e828d1acfa1356.xml) | ai, all, chinese, company-tech, engineering, top200, wechat |
| [通义实验室](https://wechat2rss.bestblogs.dev/feed/4ebee6222ae08705b8aabc9116f0defbcb6b17c6.xml) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://wechat2rss.bestblogs.dev/feed/4ebee6222ae08705b8aabc9116f0defbcb6b17c6.xml) | ai, all, chinese, company-tech, engineering, research, top200, wechat |
| [量子位](https://www.qbitai.com) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://www.qbitai.com/feed) | ai, all, chinese, engineering, top200 |
| [阶跃StepFun](https://wechat2rss.bestblogs.dev/feed/3e2714d06aa36142e8ed6b3f4e5cf9090a069dd2.xml) | Artificial intelligence feed. | Artificial Intelligence | [RSS](https://wechat2rss.bestblogs.dev/feed/3e2714d06aa36142e8ed6b3f4e5cf9090a069dd2.xml) | ai, all, chinese, company-tech, engineering, wechat |

</details>

<details>
<summary>🛠️ Engineering & Technology · 348</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [1A23 Studio](https://1a23.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://1a23.com/feed/) | all, blogs, chinese, engineering |
| [251 的魔法实验室](https://blog.251.sh/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.251.sh/feed/) | all, blogs, chinese, engineering |
| [49th LunaSea](https://maki49.github.io/) | Chinese independent blog. | Engineering & Technology | [RSS](https://maki49.github.io/feed.xml) | all, blogs, chinese, engineering |
| [51CTO技术栈](https://wechat2rss.bestblogs.dev/feed/d1fabe6c569ffc44979075dde2f57c65e07c3045.xml) | Engineering and technology feed. | Engineering & Technology | [RSS](https://wechat2rss.bestblogs.dev/feed/d1fabe6c569ffc44979075dde2f57c65e07c3045.xml) | all, chinese, engineering |
| [9to5Mac](https://9to5mac.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://9to5mac.com/feed) | all, engineering |
| [@Lenciel](https://lenciel.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://lenciel.com/feed.xml) | all, blogs, chinese, engineering |
| [Abyss的小屋](https://www.rsnocsi.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.rsnocsi.cn/feed) | ai, all, blogs, chinese, engineering, top200 |
| [admin](https://blog.liua.us.ci/rss.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.liua.us.ci/rss.xml) | ai, all, blogs, chinese, engineering |
| [ALBERTAZ](https://albertaz.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.albertaz.com/rss.xml) | all, blogs, chinese, engineering |
| [Alberto De Bortoli](https://albertodebortoli.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://albertodebortoli.com/rss/) | all, engineering |
| [Alliot's blog](https://blog.alliot.tech/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.iots.vip/atom.xml) | all, blogs, chinese, engineering |
| [Amiya的书桌](https://blog.sayori.org/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.sayori.org/rss.xml) | all, blogs, chinese, engineering, top200 |
| [Android Performance](https://androidperformance.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.androidperformance.com/atom.xml) | all, blogs, chinese, engineering, top200 |
| [Apple Newsroom](https://www.apple.com/newsroom/rss-feed.rss) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.apple.com/newsroom/rss-feed.rss) | all, engineering |
| [AppleInsider News](https://appleinsider.com/rss/news) | Engineering and technology feed. | Engineering & Technology | [RSS](https://appleinsider.com/rss/news/) | all, engineering |
| [Archive: 2026 - GitHub Changelog](https://github.blog/changelog/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://github.blog/changelog/feed/) | all, engineering |
| [Arthur's Review](https://blog.leesaitool.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.leesaitool.com/feed.xml) | ai, all, blogs, chinese, engineering |
| [Articles on Smashing Magazine — For Web Designers And Developers](https://www.smashingmagazine.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://rss1.smashingmagazine.com/feed/) | all, engineering |
| [AWS Architecture Blog](https://aws.amazon.com/blogs/architecture/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.awsarchitectureblog.com/atom.xml) | all, company-tech, engineering |
| [AWS News Blog](https://aws.amazon.com/blogs/aws/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://aws.amazon.com/blogs/aws/feed/) | all, company-tech, engineering |
| [Bboysoul's Blog](https://www.bboy.app/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.bboy.app/atom.xml) | all, blogs, chinese, engineering, top200 |
| [Bensz](https://blognas.hwb0307.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blognas.hwb0307.com/feed/) | all, blogs, chinese, engineering |
| [Blog \| Phodal - A Growth Engineer](http://www.phodal.com/blog/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.phodal.com/blog/feeds/rss/) | all, blogs, chinese, engineering |
| [Blog — Philo Li](https://philoli.com/) | Chinese independent blog. | Engineering & Technology | [RSS](http://lulalap.com/atom.xml) | all, blogs, chinese, engineering |
| [Canva - Engineering Blog](https://www.canva.dev/blog/engineering/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.canva.dev/blog/engineering/feed.xml) | all, company-tech, engineering, top200 |
| [CatCoding](http://catcoding.me/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://catcoding.me/atom.xml) | all, blogs, chinese, engineering |
| [CHEGVA](https://chegva.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://chegva.com/feed/) | all, blogs, chinese, engineering |
| [ChrAlpha's Blog](https://blog.ichr.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.ichr.me/atom.xml) | all, blogs, chinese, engineering |
| [Clark](https://www.dongyao.ren) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.dongyao.ren/feed/) | all, blogs, chinese, engineering |
| [Cloud Blog](https://cloud.google.com/blog/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://cloudblog.withgoogle.com/rss/) | all, engineering |
| [Company \| The JetBrains Blog](https://blog.jetbrains.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://blog.jetbrains.com/blog/feed) | all, engineering |
| [Cult of Mac](https://www.cultofmac.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.cultofmac.com/feed) | all, engineering |
| [Data4Fun](https://data4fun.cc/) | Chinese independent blog. | Engineering & Technology | [RSS](https://data4fun.cc/index.xml) | ai, all, blogs, chinese, engineering |
| [Databricks](https://www.databricks.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.databricks.com/feed) | all, engineering, top200 |
| [Dax 的博客](https://daolanx.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://daolanx.me/zh/rss.xml) | all, blogs, chinese, engineering |
| [dbaplus社群](https://wechat2rss.xlab.app/feed/3b9cc8887fccb80d3f083cd6eb8c344628d101b6.xml) | WeChat article feed covering 数据库与企业级技术. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/3b9cc8887fccb80d3f083cd6eb8c344628d101b6.xml) | all, chinese, engineering, wechat |
| [ddadaal.me](https://ddadaal.me) | Chinese independent blog. | Engineering & Technology | [RSS](https://ddadaal.me/rss.xml) | all, blogs, chinese, engineering |
| [Debug客栈](https://blog.debuginn.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.debuginn.com/index.xml) | all, blogs, chinese, engineering |
| [Deepzz's Blog](https://deepzz.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://deepzz.com/feed) | all, blogs, chinese, engineering |
| [Dennis](https://www.domon.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.domon.cn/rss/) | all, blogs, chinese, engineering |
| [DGideas' Blog](https://dgideas.net) | Chinese independent blog. | Engineering & Technology | [RSS](https://dgideas.net/feed/) | all, blogs, chinese, engineering |
| [distjr_的博客](https://blog.distjr.top/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.distjr.top/atom.xml) | all, blogs, chinese, engineering |
| [Dorck's Blog](https://dorck.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://dorck.cn/feed.xml) | all, blogs, chinese, engineering |
| [EdNovas的小站](https://ednovas.xyz/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://ednovas.xyz/atom.xml) | all, blogs, chinese, engineering |
| [Elastic Blog - Elasticsearch, Kibana, and ELK Stack](https://www.elastic.co) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.elastic.co/blog/feed) | all, engineering, top200 |
| [Engineering at Meta](https://engineering.fb.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://engineering.fb.com/feed/) | all, company-tech, engineering |
| [Engineering at Slack](https://slack.engineering) | Engineering and technology feed. | Engineering & Technology | [RSS](https://slack.engineering/feed/) | all, company-tech, engineering, top200 |
| [Environment + Energy – The Conversation](https://theconversation.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://theconversation.com/au/environment/articles.atom) | all, engineering |
| [Eric's Blog](https://wsdjeg.net/) | Chinese independent blog. | Engineering & Technology | [RSS](https://wsdjeg.net/feed.xml) | all, blogs, chinese, engineering, top200 |
| [Etsy Engineering \| Code as Craft](http://www.etsy.com/codeascraft/rss) | Engineering and technology feed. | Engineering & Technology | [RSS](https://codeascraft.com/feed/atom/) | all, company-tech, engineering, top200 |
| [Feld Thoughts](https://feld.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://feld.com/feed) | all, engineering |
| [Fengc's Blog](https://fengcblog.880200.xyz) | Chinese independent blog. | Engineering & Technology | [RSS](https://rssweball.top/feed/afaf2a3c-e11a-4783-a358-9e2d20d76a69.xml) | ai, all, blogs, chinese, engineering |
| [for_the_zero的个人博客](https://ftz.is-a.dev) | Chinese independent blog. | Engineering & Technology | [RSS](https://ftz.is-a.dev/rss.xml) | ai, all, blogs, chinese, engineering |
| [forecho's Blog](https://blog.forecho.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.forecho.com/atom.xml) | all, blogs, chinese, engineering |
| [freeCodeCamp Programming Tutorials: Python, JavaScript, Git & More](https://www.freecodecamp.org/news/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.freecodecamp.org/news/rss/) | all, engineering, top200 |
| [Frytea](https://frytea.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.frytea.com/index.xml) | all, blogs, chinese, engineering |
| [GamerNoTitle](https://bili33.top) | Chinese independent blog. | Engineering & Technology | [RSS](https://bili33.top/atom.xml) | all, blogs, chinese, engineering |
| [GISerlab · 地理空间](https://blog.giserlab.cn) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.giserlab.cn/feed.xml) | all, blogs, chinese, engineering |
| [Good Good Good](https://www.goodgoodgood.co) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.goodgoodgood.co/articles/rss.xml) | all, engineering |
| [Haku](https://re.karlbaey.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://re.karlbaey.top/rss.xml) | all, blogs, chinese, engineering |
| [HCLonely Blog](https://blog.hclonely.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.hclonely.com/atom.xml) | all, blogs, chinese, engineering |
| [Henry Z's blog](https://changchen.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://changchen.me/atom.xml) | all, blogs, chinese, engineering |
| [hsfzxjy 的博客](https://i.hsfzxjy.site/) | Chinese independent blog. | Engineering & Technology | [RSS](https://i.hsfzxjy.site/rss.xml) | all, blogs, chinese, engineering |
| [https://blog.fivest.one/feed](https://blog.fivest.one) | Chinese independent blog. | Engineering & Technology | [RSS](http://blog.fivest.one/feed) | all, blogs, chinese, engineering |
| [I'm OWenT](https://owent.net/) | Chinese independent blog. | Engineering & Technology | [RSS](https://owent.net/index.xml) | all, blogs, chinese, engineering |
| [icodex \| 前端技术博客 \| 专注 React、TypeScript、AI 与性能优化 Blog](https://icodex.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://icodex.me/atom.xml) | all, blogs, chinese, engineering, top200 |
| [idealclover](https://idealclover.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://idealclover.top/feed) | all, blogs, chinese, engineering |
| [ImCBC](https://imcbc.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.bbing.com.cn/index.xml) | all, blogs, chinese, engineering |
| [inessential.com](https://inessential.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://inessential.com/xml/rss.xml) | all, engineering |
| [Innei](https://innei.in) | Chinese independent blog. | Engineering & Technology | [RSS](https://innei.ren/feed) | all, blogs, chinese, engineering |
| [IntelliJ IDEA : IntelliJ IDEA – the Leading IDE for Professional Development in Java and Kotlin \| The JetBrains Blog](https://blog.jetbrains.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://blogs.jetbrains.com/idea/feed/) | all, engineering |
| [ISLAND](https://youngxhui.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://youngxhui.top/index.xml) | all, blogs, chinese, engineering |
| [iTimothy](https://xiaozhou.net/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://xiaozhou.net/atom.xml) | all, blogs, chinese, engineering |
| [Jack Pu's Blog (蒲小花的博客－ポーのブログ)](https://www.jackpu.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.jackpu.com/rss/) | all, blogs, chinese, engineering |
| [Jacky Wong](https://jw1.ai/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://jw1.dev/atom.xml) | all, blogs, chinese, engineering |
| [jdjwzx233的博客](https://jdjwzx233.cn) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.jdjwzx233.cn/atom.xml) | all, blogs, chinese, engineering |
| [Jimmy Song – Jimmy Song's Blog](https://jimmysong.io/) | Chinese independent blog. | Engineering & Technology | [RSS](https://jimmysong.io/index.xml) | all, blogs, chinese, engineering |
| [Josherich’s Blog](https://josherich.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.josherich.me/feed.xml) | all, blogs, chinese, engineering |
| [keggin's blog](https://keggin.tech) | Chinese independent blog. | Engineering & Technology | [RSS](https://keggin.tech/rss.xml) | all, blogs, chinese, engineering |
| [Kerry的学习笔记](https://kerrynotes.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://kerrynotes.com/feed/) | all, blogs, chinese, engineering |
| [kok的笔记本](https://wocai.de/) | Chinese independent blog. | Engineering & Technology | [RSS](https://wocai.de/index.xml/) | all, blogs, chinese, engineering |
| [Kotlin : A concise multiplatform language developed by JetBrains \| The JetBrains Blog](https://blog.jetbrains.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://blog.jetbrains.com/kotlin/feed/) | all, engineering |
| [laike9m's blog](https://laike9m.com/blog/rss) | Chinese independent blog. | Engineering & Technology | [RSS](https://laike9m.com/blog/rss/) | all, blogs, chinese, engineering, top200 |
| [LearnData 开源笔记](https://newzone.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://newzone.top/rss.xml) | all, blogs, chinese, engineering |
| [Lex Blog](https://dreams.plus/) | Chinese independent blog. | Engineering & Technology | [RSS](https://dreams.plus/rss.xml) | all, blogs, chinese, engineering |
| [LiaoKe的博客](https://blog.liao-ke.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.liao-ke.com/rss.xml) | all, blogs, chinese, engineering |
| [LiesAuer's Blog](https://www.liesauer.net/blog/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.liesauer.net/blog/feed/) | all, blogs, chinese, engineering, top200 |
| [Lifehacker](https://lifehacker.com/feed/rss) | Engineering and technology feed. | Engineering & Technology | [RSS](https://lifehacker.com/rss) | all, engineering |
| [LiuShen's Blog - 清羽飞扬](https://blog.liushen.fun/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.liushen.fun/atom.xml) | all, blogs, chinese, engineering |
| [Long Luo's Life Notes](https://www.longluo.me/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.longluo.me/atom.xml) | all, blogs, chinese, engineering |
| [Longlong's Blog](https://blog.xlonglong.cn) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.xlonglong.cn/feed/) | all, blogs, chinese, engineering |
| [Louis C Deng's Blog](https://blog.aeilot.top/index.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.aeilot.top/index.xml) | all, blogs, chinese, engineering |
| [lucifer的网络博客](https://lucifer.ren/blog) | Chinese independent blog. | Engineering & Technology | [RSS](https://lucifer.ren/blog/atom.xml) | all, blogs, chinese, engineering |
| [luozhiyun`s Blog](https://www.luozhiyun.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.luozhiyun.com/feed) | all, blogs, chinese, engineering |
| [LV88](https://lv88fg.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://scvoet.me/feed) | all, blogs, chinese, engineering |
| [MacTalk-池建强的 Blog](https://macshuo.com) | Chinese independent blog. | Engineering & Technology | [RSS](http://macshuo.com/?feed=rss2) | all, blogs, chinese, engineering, top200 |
| [Martin Fowler](https://martinfowler.com/feed.atom) | Engineering and technology feed. | Engineering & Technology | [RSS](https://martinfowler.com/feed.atom) | all, engineering, top200 |
| [Mengke's blog - Mengke's coding journey](https://www.mengke.me/blog) | Chinese independent blog. | Engineering & Technology | [RSS](https://mengke.me/feed.xml) | all, blogs, chinese, engineering |
| [mephisto.cc](https://mephisto.cc/) | Chinese independent blog. | Engineering & Technology | [RSS](https://mephisto.cc/index.xml) | all, blogs, chinese, engineering |
| [Microsoft Azure Blog](https://azure.microsoft.com/en-us/blog/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://azure.microsoft.com/en-us/blog/feed/) | all, company-tech, engineering, top200 |
| [Mobility](https://lichuanyang.top/) | Chinese independent blog. | Engineering & Technology | [RSS](http://lichuanyang.top/atom.xml) | all, blogs, chinese, engineering |
| [Mokeyjay's Blog - 超能小紫](https://mok.moe) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.mokeyjay.com/feed) | all, blogs, chinese, engineering |
| [Mosu](https://mosuzi.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.mosuzi.com/atom.xml) | all, blogs, chinese, engineering |
| [Mox的笔记库](https://mocusez.site/zh-CN/) | Chinese independent blog. | Engineering & Technology | [RSS](https://mocusez.site/zh-CN/atom.xml) | all, blogs, chinese, engineering |
| [Muyun99 的杂谈](https://muyun.work/) | Chinese independent blog. | Engineering & Technology | [RSS](https://muyun.work/feed/) | all, blogs, chinese, engineering |
| [My](https://dayzmod.kdns.fr/) | Chinese independent blog. | Engineering & Technology | [RSS](https://dayzmod.kdns.fr/rss.xml) | all, blogs, chinese, engineering |
| [NBlog](https://blog.nocp.space) | Chinese independent blog. | Engineering & Technology | [RSS](https://nocp.space/rss/feed.json) | all, blogs, chinese, engineering |
| [Netflix TechBlog - Medium](https://netflixtechblog.com?source=rss----2615bd06b42e---4) | Engineering and technology feed. | Engineering & Technology | [RSS](https://netflixtechblog.com/feed) | all, company-tech, engineering, top200 |
| [News – CNET](https://www.cnet.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.cnet.com/rss/news/) | all, engineering |
| [Nicksxs's Blog](https://nicksxs.me/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://nicksxs.me/atom.xml) | all, blogs, chinese, engineering, top200 |
| [Niracler 的博物志](https://niracler.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://niracler.com/rss.xml) | all, blogs, chinese, engineering |
| [Node.js Blog](https://nodejs.org/en) | Engineering and technology feed. | Engineering & Technology | [RSS](https://nodejs.org/en/feed/blog.xml) | all, engineering, top200 |
| [NPR Topics: Environment](https://www.npr.org/templates/story/story.php?storyId=1025) | Engineering and technology feed. | Engineering & Technology | [RSS](https://feeds.npr.org/1025/rss.xml) | all, engineering |
| [NYT > Climate and Environment](https://www.nytimes.com/section/climate) | Engineering and technology feed. | Engineering & Technology | [RSS](https://rss.nytimes.com/services/xml/rss/nyt/Climate.xml) | all, engineering |
| [obaby 𝐢‍𝐧⃝ void](https://zhongxiaojie.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://h4ck.org.cn/feed/) | ai, all, blogs, chinese, engineering, top200 |
| [oldj's blog](https://oldj.net) | Chinese independent blog. | Engineering & Technology | [RSS](https://oldj.net/feed) | all, blogs, chinese, engineering |
| [OneCoder](https://www.coderli.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.coderli.com/feed.xml) | all, blogs, chinese, engineering |
| [OneV's Den](https://onevcat.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://onevcat.com/feed.xml) | all, blogs, chinese, engineering, top200 |
| [OnionTalk](https://hateonion.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://hateonion.me/index.xml) | all, blogs, chinese, engineering |
| [Oragekk&apos;s Blog](https://oragekk.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://oragekk.me/rss.xml) | all, blogs, chinese, engineering |
| [Origin](https://blog.singee.me/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.singee.me/atom.xml) | all, blogs, chinese, engineering |
| [Panda Home](https://old-panda.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://old-panda.com/feed/) | all, blogs, chinese, engineering |
| [Peng's Blog](https://pengs.top/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://pengs.top/atom.xml) | all, blogs, chinese, engineering |
| [piglei](https://www.piglei.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.piglei.com/feeds/latest/) | all, blogs, chinese, engineering |
| [Prakati India](https://prakati.in/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.prakati.in/feed/) | all, engineering |
| [ProAndroidDev - Medium](https://proandroiddev.com?source=rss----c72404660798---4) | Engineering and technology feed. | Engineering & Technology | [RSS](https://proandroiddev.com/feed) | all, engineering |
| [pseudoyu](https://www.pseudoyu.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.pseudoyu.com/zh/index.xml) | all, blogs, chinese, engineering, top200 |
| [Public Object](https://publicobject.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://publicobject.com/rss/) | all, engineering |
| [Python Insider](https://blog.python.org/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://blog.python.org/feeds/posts/default) | all, engineering, top200 |
| [Qaiu blog](https://blog.qaiu.top) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.qaiu.top/rss.xml) | all, blogs, chinese, engineering |
| [QingCCL](https://qingccl.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://qingccl.github.io/rss.xml) | all, blogs, chinese, engineering |
| [QP's Blog](https://www.szqp.site) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.szqp.site/feed) | all, blogs, chinese, engineering |
| [Qunar技术沙龙](https://wechat2rss.bestblogs.dev/feed/84c072f8d34d1690f2783d7dda6013cf6d892b7f.xml) | Engineering and technology feed. | Engineering & Technology | [RSS](https://wechat2rss.bestblogs.dev/feed/84c072f8d34d1690f2783d7dda6013cf6d892b7f.xml) | all, chinese, company-tech, engineering, wechat |
| [Random Thoughts](https://blog.joway.io/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.joway.io/index.xml) | all, blogs, chinese, engineering |
| [Randy's Blog](https://lutaonan.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://lutaonan.com/rss.xml) | all, blogs, chinese, engineering |
| [Raz1ner](https://raz1ner.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://raz1ner.com/atom.xml) | all, blogs, chinese, engineering |
| [ReadWrite](https://readwrite.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://readwrite.com/feed/) | all, engineering |
| [Redis Blog](https://redis.io/en/blog) | Engineering and technology feed. | Engineering & Technology | [RSS](https://redis.io/feed/) | all, engineering |
| [Release notes from biome](https://github.com/biomejs/biome/releases) | Engineering and technology feed. | Engineering & Technology | [RSS](https://github.com/biomejs/biome/releases.atom) | all, engineering |
| [Release notes from bun](https://github.com/oven-sh/bun/releases) | Engineering and technology feed. | Engineering & Technology | [RSS](https://github.com/oven-sh/bun/releases.atom) | all, engineering |
| [Release notes from NetNewsWire](https://github.com/Ranchero-Software/NetNewsWire/releases) | Engineering and technology feed. | Engineering & Technology | [RSS](https://github.com/Ranchero-Software/NetNewsWire/releases.atom) | all, engineering |
| [Release notes from zed](https://github.com/zed-industries/zed/releases) | Engineering and technology feed. | Engineering & Technology | [RSS](https://github.com/zed-industries/zed/releases.atom) | all, engineering |
| [Replicate's blog](https://replicate.com/blog) | Engineering and technology feed. | Engineering & Technology | [RSS](https://replicate.com/blog/rss) | all, engineering |
| [Rokcso's Blog](https://rokcso.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://rokcso.com/index.xml) | ai, all, blogs, chinese, engineering |
| [ROYWANG](https://roy.wang/feed/index.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://roy.wang/feed/) | all, blogs, chinese, engineering |
| [Roy的个人站](https://geofftools.cn/blog/) | Chinese independent blog. | Engineering & Technology | [RSS](https://geofftools.cn/blog/atom.xml) | all, blogs, chinese, engineering |
| [Rust Blog](https://blog.rust-lang.org/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://blog.rust-lang.org/feed.xml) | all, engineering, top200 |
| [rxliuli blog](https://blog.rxliuli.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.rxliuli.com/atom.xml) | all, blogs, chinese, engineering, top200 |
| [RYANUO](https://ryanuo.cc) | Chinese independent blog. | Engineering & Technology | [RSS](https://ryanuo.cc/sitemap.xml) | ai, all, blogs, chinese, engineering, top200 |
| [Ryan‘s World](https://blog.12ms.xyz/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.12ms.xyz/feed/) | all, blogs, chinese, engineering |
| [S T C H E N G](https://cheng.st/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://cheng.st/atom.xml) | all, blogs, chinese, engineering |
| [Sehnsucht](https://blog.sehnsucht.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.sehnsucht.top/rss.xml) | all, blogs, chinese, engineering |
| [Sekyoro的博客小屋](https://www.sekyoro.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.sekyoro.top/atom.xml) | ai, all, blogs, chinese, engineering |
| [Seven's blog](https://blog.diqigan.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.diqigan.cn/atom.xml) | all, blogs, chinese, engineering, top200 |
| [Shanwer's Blog](https://blog.shanwer.top) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.shanwer.top/feed/) | all, blogs, chinese, engineering |
| [sjdhome](https://sjdhome.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://sjdhome.com/blog/atom.xml) | all, blogs, chinese, engineering, top200 |
| [Skywind Inside](https://skywind.me/blog) | Chinese independent blog. | Engineering & Technology | [RSS](http://www.skywind.me/blog/feed) | all, blogs, chinese, engineering |
| [SkyWT](https://skywt.cn) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.skywt.cn/feed/) | all, blogs, chinese, engineering |
| [Slashdot](https://slashdot.org/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://rss.slashdot.org/Slashdot/slashdotMain) | all, engineering |
| [smallyu的博客](https://smallyu.net/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://smallyu.net/atom.xml) | all, blogs, chinese, engineering, top200 |
| [Spotify Engineering](https://engineering.atspotify.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://engineering.atspotify.com/feed/) | all, company-tech, engineering, top200 |
| [Stack Overflow Blog](https://stackoverflow.blog/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://blog.stackoverflow.com/feed/) | all, engineering, top200 |
| [Steve Sun](https://sund.site/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.sund.site/index.xml) | all, blogs, chinese, engineering |
| [Stratechery by Ben Thompson](https://stratechery.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://stratechery.com/feed/) | all, engineering |
| [Stray Episode](https://farer.org/) | Chinese independent blog. | Engineering & Technology | [RSS](https://farer.org/rss/) | all, blogs, chinese, engineering |
| [Stripe Blog](https://stripe.com/blog) | Engineering and technology feed. | Engineering & Technology | [RSS](https://stripe.com/blog/feed.rss) | all, company-tech, engineering, top200 |
| [StudyingLover's Blog](https://www.studyinglover.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://studyinglover.com/atom.xml) | ai, all, blogs, chinese, engineering |
| [SUMSEC](https://sumsec.me) | Chinese independent blog. | Engineering & Technology | [RSS](https://sumsec.me/resources/atom.xml) | all, blogs, chinese, engineering |
| [Sunset 的重构博客](https://blog.sunmkt.uk/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.sunmkt.uk/feed.xml) | all, blogs, chinese, engineering |
| [Supabase Blog](https://supabase.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://supabase.com/rss.xml) | all, engineering, top200 |
| [Super Blog](https://superpung.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://superpung.com/atom.xml) | all, blogs, chinese, engineering |
| [Surmon.me](https://surmon.me) | Chinese independent blog. | Engineering & Technology | [RSS](https://surmon.me/rss.xml) | all, blogs, chinese, engineering |
| [Swift by Sundell](https://www.swiftbysundell.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.swiftbysundell.com/feed.rss) | all, engineering |
| [Swift.org](https://www.swift.org/atom.xml) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.swift.org/atom.xml) | all, engineering |
| [Taxodium](https://taxodium.ink/) | Chinese independent blog. | Engineering & Technology | [RSS](https://taxodium.ink/rss.xml) | all, blogs, chinese, engineering, top200 |
| [Terrarum::异世界丨居正博客](https://blog.skyju.cc/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.skyju.cc/index.xml) | all, blogs, chinese, engineering |
| [The Airbnb Tech Blog - Medium](https://medium.com/airbnb-engineering?source=rss----53c7c27702d5---4) | Engineering and technology feed. | Engineering & Technology | [RSS](https://medium.com/feed/airbnb-engineering) | all, company-tech, engineering, top200 |
| [The ASF Blog](https://news.apache.org/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://news.apache.org/feed) | all, engineering |
| [The Cloudflare Blog](https://blog.cloudflare.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://blog.cloudflare.com/rss) | all, company-tech, engineering, top200 |
| [The GitHub Blog](https://github.blog/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://github.blog/feed/) | all, company-tech, engineering, top200 |
| [The Intercom Blog](https://www.intercom.com/blog/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.intercom.com/blog/feed) | all, engineering |
| [The JetBrains Blog](https://blog.jetbrains.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://blog.jetbrains.com/feed/) | all, company-tech, engineering, top200 |
| [The Loop](https://www.loopinsight.com) | Engineering and technology feed. | Engineering & Technology | [RSS](https://www.loopinsight.com/feed) | all, engineering |
| [The New Stack](https://thenewstack.io/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://thenewstack.io/feed/) | all, engineering, top200 |
| [Tianhe Gao](https://tianheg.co/) | Chinese independent blog. | Engineering & Technology | [RSS](https://tianheg.co/index.xml) | all, blogs, chinese, engineering, top200 |
| [TrumanDu's Blog](http://blog.trumandu.top/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](http://blog.trumandu.top/atom.xml) | all, blogs, chinese, engineering |
| [Turing Post](https://www.turingpost.com/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://rss.beehiiv.com/feeds/UJIoBuf5BX.xml) | all, engineering |
| [Tw93 Blog](https://tw93.fun) | Chinese independent blog. | Engineering & Technology | [RSS](https://tw93.fun/feed.xml) | all, blogs, chinese, engineering, top200 |
| [Use Case: copilot - GitHub Changelog](https://github.blog/changelog/label/copilot/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://github.blog/changelog/label/copilot/feed/) | all, engineering |
| [Usubeni Fantasy](https://ssshooter.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://ssshooter.com/rss.xml) | all, blogs, chinese, engineering, top200 |
| [UWillno's Blog](https://uwillno.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://uwillno.com/rss.xml) | all, blogs, chinese, engineering |
| [Vercel News](https://vercel.com/atom) | Engineering and technology feed. | Engineering & Technology | [RSS](https://vercel.com/atom) | all, engineering, top200 |
| [Visual Studio Blog](https://devblogs.microsoft.com/visualstudio/) | Engineering and technology feed. | Engineering & Technology | [RSS](https://devblogs.microsoft.com/visualstudio/feed/) | all, engineering |
| [vivo互联网技术](https://wechat2rss.bestblogs.dev/feed/b3ceb5cb1e4602ca55704650a157ec9c5b2f0d31.xml) | Engineering and technology feed. | Engineering & Technology | [RSS](https://wechat2rss.bestblogs.dev/feed/b3ceb5cb1e4602ca55704650a157ec9c5b2f0d31.xml) | all, chinese, company-tech, engineering, wechat |
| [Watermelonabc的Blog](https://watermelonabc.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://watermelonabc.top/atom.xml) | all, blogs, chinese, engineering |
| [Weishu's Notes](https://weishu.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://weishu.me/atom.xml) | all, blogs, chinese, engineering, top200 |
| [wmhwiki](https://wmhwiki.cn) | Chinese independent blog. | Engineering & Technology | [RSS](https://wmhwiki.cn/rss.xml) | all, blogs, chinese, engineering |
| [WuSiYu Blog](https://wusiyu.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://wusiyu.me/feed/) | all, blogs, chinese, engineering |
| [x7aNote](https://xeonzilla.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://xeonzilla.top/index.xml) | all, blogs, chinese, engineering |
| [XINDOO](https://zxs.io/) | Chinese independent blog. | Engineering & Technology | [RSS](https://zxs.io/feed) | all, blogs, chinese, engineering |
| [YangXuan's Blog](https://yangxuan.ai) | Chinese independent blog. | Engineering & Technology | [RSS](https://yangxuan.ai/feed/) | ai, all, blogs, chinese, engineering |
| [yCENzh's Blog](https://fuwari.oh1.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://fuwari.oh1.top/rss.xml) | all, blogs, chinese, engineering |
| [YeungYeah's Context](https://scottyeung.top/) | Chinese independent blog. | Engineering & Technology | [RSS](http://scottyeung.top/atom.xml) | all, blogs, chinese, engineering |
| [Yi's Blog](https://ycao.net/) | Chinese independent blog. | Engineering & Technology | [RSS](https://ycao.top/feed.xml) | all, blogs, chinese, engineering |
| [Yiran's Blog](https://zdyxry.github.io/) | Chinese independent blog. | Engineering & Technology | [RSS](https://zdyxry.github.io/atom.xml) | all, blogs, chinese, engineering, top200 |
| [YOLO Blog](https://www.yolo.blue/blog) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.yolo.blue/blog/rss.xml) | all, blogs, chinese, engineering |
| [ypingcn](https://blog.ypingcn.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.ypingcn.com/feed.xml) | all, blogs, chinese, engineering |
| [zhecydn的博客站](https://blog.zhecydn.asia) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.zhecydn.asia/feed/) | all, blogs, chinese, engineering |
| [一纸忘忧](https://www.ikxin.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.ikxin.com/feed/) | all, blogs, chinese, engineering |
| [东东's Blog](https://blog.yasking.org/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.yasking.org/atom.xml) | all, blogs, chinese, engineering, top200 |
| [东方星痕](https://ystyle.top) | Chinese independent blog. | Engineering & Technology | [RSS](https://ystyle.top/atom.xml) | all, blogs, chinese, engineering |
| [中文博客 on 范叶亮 \| Leo Van](https://leovan.me/cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://leovan.me/cn/index.xml) | all, blogs, chinese, engineering |
| [串串狗小刊 ⭐️](https://www.ccgxk.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.ccgxk.com/rss.php) | all, blogs, chinese, engineering |
| [九仞之行](https://styunlen.cn) | Chinese independent blog. | Engineering & Technology | [RSS](https://styunlen.cn/feed) | all, blogs, chinese, engineering |
| [了迹奇有没](https://whrss.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://whrss.com/feed) | all, blogs, chinese, engineering |
| [二丫讲梵](https://wiki.eryajf.net) | Chinese independent blog. | Engineering & Technology | [RSS](https://wiki.eryajf.net/rss.xml) | all, blogs, chinese, engineering, top200 |
| [仲平](https://blog.zopiya.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.7wate.com/rss.xml) | all, blogs, chinese, engineering |
| [任霏的个人博客网站](https://blog.renfei.net) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.renfei.net/rss.xml) | all, blogs, chinese, engineering |
| [伪斜杠青年](https://i.lckiss.com) | Chinese independent blog. | Engineering & Technology | [RSS](http://i.lckiss.com/?feed=rss2) | all, blogs, chinese, engineering |
| [依云's Blog](https://blog.lilydjwg.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.lilydjwg.me/posts.rss) | all, blogs, chinese, engineering |
| [侯锐的思考与分享](https://www.nosuchfield.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.nosuchfield.com/atom.xml) | all, blogs, chinese, engineering |
| [保罗的小宇宙](https://paugram.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://paugram.com/feed) | all, blogs, chinese, engineering |
| [傥师妹TangShiMei的小空间](https://blog.224418.xyz/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.224418.xyz/rss2.xml) | all, blogs, chinese, engineering |
| [傲雪の](https://www.oxue.de/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.oxue.de/rss.xml) | all, blogs, chinese, engineering |
| [农码生涯，无酒无花 – The coding life, no wine, no shine.](https://nicrosoft.net/blog) | Chinese independent blog. | Engineering & Technology | [RSS](https://nicrosoft.net/blog/feed/) | all, blogs, chinese, engineering, top200 |
| [冰冻大西瓜](https://bddxg.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://bddxg.top/feed.rss) | ai, all, blogs, chinese, engineering |
| [刘郎阁](https://vjo.cc/) | Chinese independent blog. | Engineering & Technology | [RSS](https://vjo.cc/feed/) | all, blogs, chinese, engineering |
| [创见思考——怎样度过这一生](https://www.fengcan.net) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.fengcan.net/feed/) | ai, all, blogs, chinese, engineering |
| [初然忆](https://www.imcry.vip/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.imcry.vip/index.xml) | all, blogs, chinese, engineering |
| [北门清燕](https://bmqy.net/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.bmqy.net/feed.xml) | all, blogs, chinese, engineering |
| [千古八方的博客](https://rangotec.com/feed) | Chinese independent blog. | Engineering & Technology | [RSS](https://rangotec.com/feed) | all, blogs, chinese, engineering |
| [千里之豪的格物垛](https://blog.gadore.top) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.gadore.top/feed.xml) | all, blogs, chinese, engineering, top200 |
| [半方池水半方田](https://blog.uuanqin.top/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://uuanqin.top/atom.xml) | all, blogs, chinese, engineering |
| [博客 on Neil的自留地](https://neilmin.com/zh/posts/) | Chinese independent blog. | Engineering & Technology | [RSS](https://neilmin.com/zh/posts/index.xml) | all, blogs, chinese, engineering |
| [卡片创作实验室](https://cnfeat.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.cnfeat.com/feed.xml) | all, blogs, chinese, engineering |
| [卡瓦邦噶！](https://www.kawabangga.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.kawabangga.com/feed) | all, blogs, chinese, engineering, top200 |
| [又耳笔记](https://youerning.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://youerning.top/index.xml) | all, blogs, chinese, engineering |
| [后端技术杂谈](https://www.rowkey.cn/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://rowkey.cn/atom.xml) | all, blogs, chinese, engineering, top200 |
| [哔哩哔哩技术](https://wechat2rss.xlab.app/feed/434235d4815fdb8447ff3127fc053ceb8b3aada6.xml) | WeChat article feed covering 音视频、基础架构与工程实践. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/434235d4815fdb8447ff3127fc053ceb8b3aada6.xml) | all, chinese, company-tech, engineering, wechat |
| [唐巧的博客](https://blog.devtang.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.devtang.com/atom.xml) | all, blogs, chinese, engineering, top200 |
| [喵二の小博客](https://www.miaoer.net) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.miaoer.net/feed) | all, blogs, chinese, engineering |
| [喵喵小站・博客志](https://www.mmbkz.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.mmbkz.cn/feed) | all, blogs, chinese, engineering, top200 |
| [土木坛子](https://tumutanzi.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://tumutanzi.com/feed) | all, blogs, chinese, engineering |
| [土法炼钢兴趣小组的算法知识备份](https://quant67.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://quant67.com/rss.xml) | all, blogs, chinese, engineering |
| [土豆不好吃](https://dmesg.app) | Chinese independent blog. | Engineering & Technology | [RSS](https://dmesg.app/feed) | all, blogs, chinese, engineering |
| [坠月川](https://www.hujingnb.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://hujingnb.com/feed) | all, blogs, chinese, engineering |
| [夜法之书](https://blog.17lai.site) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.17lai.site/atom.xml) | all, blogs, chinese, engineering, top200 |
| [失眠海峡](https://blog.imalan.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.imalan.cn/feed.xml) | all, blogs, chinese, engineering |
| [如有乐享](https://51.ruyo.net) | Chinese independent blog. | Engineering & Technology | [RSS](https://51.ruyo.net/feed) | all, blogs, chinese, engineering, top200 |
| [姓王者的博客](https://xingwangzhe.fun/) | Chinese independent blog. | Engineering & Technology | [RSS](https://xingwangzhe.fun/rss.xml) | all, blogs, chinese, engineering |
| [字节跳动技术团队](https://wechat2rss.xlab.app/feed/4025ea55575daf8bfd8227e68b28d9638b073267.xml) | WeChat article feed covering 基础架构与工程实践. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/4025ea55575daf8bfd8227e68b28d9638b073267.xml) | all, chinese, company-tech, engineering, wechat |
| [寒夜雨](https://www.coderlock.site/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.coderlock.site/index.php/feed/) | ai, all, blogs, chinese, engineering, top200 |
| [小众软件](https://wechat2rss.xlab.app/feed/3261d5a75cfef238650a2cabd4bbf99669c2f334.xml) | WeChat article feed covering 软件与效率工具. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/3261d5a75cfef238650a2cabd4bbf99669c2f334.xml) | all, chinese, engineering, wechat |
| [崎径 其镜](http://www.z16388.top/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](http://www.z16388.top/atom.xml) | all, blogs, chinese, engineering |
| [嵌入式工程猫的博客](https://blog.vvzero.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.vvzero.com/atom.xml) | all, blogs, chinese, engineering |
| [差评](https://wechat2rss.xlab.app/feed/8d839de8dd3290a1f1be7a94423cccb30c1b087d.xml) | WeChat article feed covering 消费科技与互联网观察. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/8d839de8dd3290a1f1be7a94423cccb30c1b087d.xml) | all, chinese, engineering, wechat |
| [张戈博客](https://zhang.ge) | Chinese independent blog. | Engineering & Technology | [RSS](https://zhang.ge/feed) | all, blogs, chinese, engineering |
| [张洪Heo](https://blog.zhheo.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.zhheo.com/rss.xml) | all, blogs, chinese, engineering, top200 |
| [张鑫旭-鑫空间-鑫生活](https://www.zhangxinxu.com/wordpress) | Chinese independent blog. | Engineering & Technology | [RSS](http://www.zhangxinxu.com/wordpress/?feed=rss2) | all, blogs, chinese, engineering, top200 |
| [得物技术](https://wechat2rss.xlab.app/feed/f3a42bd249ec6e8834ae761d8d0f85a949950944.xml) | WeChat article feed covering 业务系统与工程实践. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/f3a42bd249ec6e8834ae761d8d0f85a949950944.xml) | all, chinese, company-tech, engineering, wechat |
| [愆伏](https://www.tortorse.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.tortorse.com/atom.xml) | all, blogs, chinese, engineering, top200 |
| [我不是咕咕鸽](https://blog.laoda.de) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.laoda.de/rss.xml) | all, blogs, chinese, engineering |
| [所谓空想](https://www.alxh.page) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.alxh.page/feed.rss) | all, blogs, chinese, engineering |
| [把酒诗代码](https://102no.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://102no.com/atom.xml) | all, blogs, chinese, engineering |
| [披萨盒的赛博日志](https://blog.pushihao.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.pushihao.com/atom.xml) | ai, all, blogs, chinese, engineering |
| [敖苛记](https://blog.kayro.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.kayro.cn/atom.xml) | all, blogs, chinese, engineering |
| [文武科技柜](https://www.wangdu.site) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.wangdu.site/feed) | all, blogs, chinese, engineering |
| [文艺数学君](https://mathpretty.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://mathpretty.com/feed/) | all, blogs, chinese, engineering |
| [方永、南天紫雲](https://www.vinoca.org) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.vinoca.org/atom.xml) | all, blogs, chinese, engineering |
| [明立非\|Mingnify的博客](https://mingnify.com/zh/blog/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://mingnify.com/zh/blog/atom.xml) | ai, all, blogs, chinese, engineering |
| [星觅海的博客](https://www.xmhai.cn) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.xmhai.cn/rss.xml) | all, blogs, chinese, engineering |
| [映屿](https://blog.verdant.ee/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.glowisle.me/atom.xml) | all, blogs, chinese, engineering |
| [晓空blog](https://blog.moeworld.tech) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.moeworld.tech/feed/) | all, blogs, chinese, engineering |
| [晴雀堂](https://blog.verynb.net/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://hehysh.github.io/atom.xml) | all, blogs, chinese, engineering |
| [朝舞网](https://ii74.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://ii74.com/feed.php) | all, blogs, chinese, engineering |
| [杜老师说](https://dusays.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://dusays.com/atom.xml) | all, blogs, chinese, engineering |
| [枫林灯语](https://blog.mfwt.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.mfwt.top/index.php/feed/) | all, blogs, chinese, engineering |
| [橙树志 ｜ citydatum](https://citydatum.cn) | Chinese independent blog. | Engineering & Technology | [RSS](https://citydatum.cn/feed) | all, blogs, chinese, engineering |
| [欧雷流](https://ourai.ws/) | Chinese independent blog. | Engineering & Technology | [RSS](https://ourai.ws/atom.xml) | all, blogs, chinese, engineering |
| [歌词经理](https://blog.lyric.im/feed/atom) | Chinese independent blog. | Engineering & Technology | [RSS](https://quaily.com/lyric/feed/atom) | all, blogs, chinese, engineering |
| [残页的小博客](https://blog.canyie.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.canyie.top/atom.xml) | all, blogs, chinese, engineering |
| [泠泫凝的异次元空间](https://lxnchan.cn/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://lxnchan.cn/atom.xml) | all, blogs, chinese, engineering |
| [泫言](https://blog.cugxuan.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.cugxuan.cn/atom.xml) | all, blogs, chinese, engineering |
| [流动](https://liudon.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://liudon.com/index.xml) | all, blogs, chinese, engineering |
| [浅时光博客](https://www.dqzboy.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.dqzboy.com/feed) | all, blogs, chinese, engineering |
| [涛叔](https://tao.zz.ac) | Chinese independent blog. | Engineering & Technology | [RSS](https://taoshu.in/feed.xml) | all, blogs, chinese, engineering |
| [润土分享](https://runtushare.net) | Chinese independent blog. | Engineering & Technology | [RSS](http://xiaix.me/rss/) | all, blogs, chinese, engineering |
| [清竹志-(原清竹茶馆)](https://blog.vadxq.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.vadxq.com/atom.xml) | all, blogs, chinese, engineering |
| [游魂博客](https://www.iyouhun.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.iyouhun.com/rss.php) | all, blogs, chinese, engineering |
| [澄沨的漫游茶记](https://champhoon.xyz/) | Chinese independent blog. | Engineering & Technology | [RSS](https://champhoon.xyz/atom.xml) | all, blogs, chinese, engineering |
| [烧饼博客](https://u.sb/) | Chinese independent blog. | Engineering & Technology | [RSS](https://u.sb/rss.xml) | all, blogs, chinese, engineering |
| [爱奇艺技术产品团队](https://wechat2rss.xlab.app/feed/16a4ec12a83a52e1f6e941bce030a4d64ee26c47.xml) | WeChat article feed covering 音视频与工程实践. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/16a4ec12a83a52e1f6e941bce030a4d64ee26c47.xml) | all, chinese, company-tech, engineering, wechat |
| [猫涅的秘密结社](http://www.maonie.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.maonie.top/atom.xml) | all, blogs, chinese, engineering |
| [猿客随笔](https://monkeyke.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://monkeyke.com/index.xml) | all, blogs, chinese, engineering |
| [王圆圆 - ICONPIK](https://www.iconpik.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.iconpik.com/rss/) | ai, all, blogs, chinese, engineering, top200 |
| [王欣说AI](https://wangxin.io/) | Chinese independent blog. | Engineering & Technology | [RSS](https://wangxin.io/atom.xml) | all, blogs, chinese, engineering |
| [王登科-DK博客](https://greatdk.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://greatdk.com/feed) | all, blogs, chinese, engineering |
| [王福强的个人博客：一个架构士的思考与沉淀](http://afoo.me) | Chinese independent blog. | Engineering & Technology | [RSS](https://afoo.me/feeds.xml) | all, blogs, chinese, engineering, top200 |
| [瓦解的生活记事](https://hin.cool/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://hin.cool/atom.xml) | all, blogs, chinese, engineering |
| [白宦成](https://www.ixiqin.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.ixiqin.com/feed/) | all, blogs, chinese, engineering |
| [白菜](https://blog.baicai.me/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.baicai.me/index.xml) | all, blogs, chinese, engineering |
| [皓子的小站](https://howiehz.top) | Chinese independent blog. | Engineering & Technology | [RSS](https://howiehz.top/rss.xml) | all, blogs, chinese, engineering, top200 |
| [看川博客](https://kanchuan.com/blog) | Chinese independent blog. | Engineering & Technology | [RSS](https://kanchuan.com/feed.xml) | all, blogs, chinese, engineering |
| [码农明明桑](https://isming.me/?utm_source=rss) | Chinese independent blog. | Engineering & Technology | [RSS](https://isming.me/index.xml) | all, blogs, chinese, engineering |
| [码录集](https://www.coderlog.net) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.coderlog.net/rss.xml) | ai, all, blogs, chinese, engineering |
| [空屿](https://pinaland.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://pinaland.cn/feed/) | all, blogs, chinese, engineering |
| [空鸣深语](https://blog.deepchirp.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.deepchirp.com/atom.xml) | all, blogs, chinese, engineering |
| [竹林里有冰的博客](https://zhul.in) | Chinese independent blog. | Engineering & Technology | [RSS](https://zhul.in/rss.xml) | all, blogs, chinese, engineering |
| [粥里有勺糖](https://sugarat.top) | Chinese independent blog. | Engineering & Technology | [RSS](https://sugarat.top/feed.rss) | all, blogs, chinese, engineering, top200 |
| [繁星点点](https://blog.52013120.xyz) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.52013120.xyz/rss.xml) | all, blogs, chinese, engineering |
| [维基萌](https://www.wikimoe.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.wikimoe.com/rss.php) | all, blogs, chinese, engineering, top200 |
| [罗磊的独立博客](https://luolei.org) | Chinese independent blog. | Engineering & Technology | [RSS](http://luolei.org/feed/) | all, blogs, chinese, engineering |
| [美团技术团队](https://wechat2rss.xlab.app/feed/eb4d04149424a874693a51c6fdda0dba8673f5e4.xml) | WeChat article feed covering 后端、算法与工程实践. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/eb4d04149424a874693a51c6fdda0dba8673f5e4.xml) | all, chinese, company-tech, engineering, wechat |
| [翔宇工作流](https://xiangyugongzuoliu.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://xiangyugongzuoliu.com/latest/rss/) | ai, all, blogs, chinese, engineering |
| [老范讲故事｜AI、大模型与商业世界的故事](https://lukefan.com) | Chinese independent blog. | Engineering & Technology | [RSS](http://lukefan.com/?feed=rss2) | all, blogs, chinese, engineering, top200 |
| [肘子的 Swift 记事本 ｜ Fatbobman's Blog](https://fatbobman.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://fatbobman.com/zh/rss.xml) | all, blogs, chinese, engineering |
| [胡涂说](https://hutusi.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://hutusi.com/feed.xml) | all, blogs, chinese, engineering, top200 |
| [腾讯技术工程](https://wechat2rss.xlab.app/feed/9685937b45fe9c7a526dbc32e4f24ba879a65b9a.xml) | WeChat article feed covering 工程实践. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/9685937b45fe9c7a526dbc32e4f24ba879a65b9a.xml) | all, chinese, company-tech, engineering, wechat |
| [草梅友仁的博客](https://blog.cmyr.ltd/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.cmyr.ltd/atom.xml) | all, blogs, chinese, engineering |
| [莫尔索随笔](https://liduos.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://liduos.com/atom.xml) | all, blogs, chinese, engineering |
| [蒙需](https://jiangcl.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://jiangcl.com/feed) | all, blogs, chinese, engineering |
| [虹墨空间站](https://www.imaegoo.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.imaegoo.com/atom.xml) | all, blogs, chinese, engineering, top200 |
| [蚊子的前端博客](https://www.xiabingbao.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.xiabingbao.com/atom.xml) | all, blogs, chinese, engineering |
| [謝懿Shine](https://www.futseyi.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://xieyi.org/rss.xml) | ai, all, blogs, chinese, engineering |
| [豌豆花下猫](https://pythoncat.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://pythoncat.top/rss.xml) | all, blogs, chinese, engineering, top200 |
| [路由器评测](https://wechat2rss.xlab.app/feed/2fa034e4b97f23d870d5b8e749e805d508761a41.xml) | WeChat article feed covering 网络设备与家庭网络. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/2fa034e4b97f23d870d5b8e749e805d508761a41.xml) | all, chinese, engineering, wechat |
| [轶哥博客](https://www.wyr.me) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.wyr.me/rss.xml) | all, blogs, chinese, engineering |
| [辉哥奇谭](https://wechat2rss.xlab.app/feed/1b01bd297483509251779f1a02bb90223786a923.xml) | WeChat article feed covering 科技、商业与个人思考. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/1b01bd297483509251779f1a02bb90223786a923.xml) | all, chinese, engineering, wechat |
| [运维咖啡吧](https://blog.ops-coffee.com/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.ops-coffee.cn/feed.xml) | all, blogs, chinese, engineering |
| [运维开发绿皮书](https://www.geekery.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.geekery.cn/rss.xml) | all, blogs, chinese, engineering |
| [远飞闲记](https://heyuanfei.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://leonhe.cn/index.xml) | all, blogs, chinese, engineering |
| [迷途小书童的Note](https://xugaoxiang.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://xugaoxiang.com/feed) | all, blogs, chinese, engineering |
| [逸思杂陈](https://blog.ponder.work/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.ponder.work/atom.xml) | all, blogs, chinese, engineering |
| [酥米的小站](https://www.sumi233.top/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.sumi233.top/rss.xml) | all, blogs, chinese, engineering |
| [阁子](https://dfine.tech/atom.xml) | Chinese independent blog. | Engineering & Technology | [RSS](https://dfine.tech/atom.xml) | all, blogs, chinese, engineering, top200 |
| [阿尔的代码屋 \| 全栈技术笔记](https://blog.algieba12.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.algieba12.cn/atom.xml) | ai, all, blogs, chinese, engineering |
| [阿掖山·博客](https://blog.mountaye.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.mountaye.com/feed.xml) | all, blogs, chinese, engineering |
| [阿里云开发者](https://wechat2rss.xlab.app/feed/c74ed6db00cfbf16f2a048a165b4453f982681f0.xml) | WeChat article feed covering 云计算与开发实践. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/c74ed6db00cfbf16f2a048a165b4453f982681f0.xml) | all, chinese, company-tech, engineering, wechat |
| [集智俱乐部](https://wechat2rss.xlab.app/feed/8540570d27c0bfe0a219173cf1ace83ae79445cb.xml) | WeChat article feed covering 复杂科学与交叉研究. | Engineering & Technology | [RSS](https://wechat2rss.xlab.app/feed/8540570d27c0bfe0a219173cf1ace83ae79445cb.xml) | all, chinese, engineering, wechat |
| [雪猫社](https://www.yukicat.net) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.yukicat.net/feed/) | all, blogs, chinese, engineering |
| [雪的数字花园 ❄️](https://blog.rnm.gv.uy/) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.rnm.gv.uy/atom.xml) | all, blogs, chinese, engineering |
| [青石坞](https://www.qs5.org/) | Chinese independent blog. | Engineering & Technology | [RSS](https://www.qs5.org/feed/) | all, blogs, chinese, engineering |
| [非学·派'](https://fxpai.com) | Chinese independent blog. | Engineering & Technology | [RSS](https://fxpai.com/feed) | all, blogs, chinese, engineering |
| [顶尖研发](https://bestcoder.cn/) | Chinese independent blog. | Engineering & Technology | [RSS](https://bestcoder.cn/feed) | all, blogs, chinese, engineering |
| [首页 on black8](https://0x8.net/) | Chinese independent blog. | Engineering & Technology | [RSS](https://unixetc.com/index.xml) | all, blogs, chinese, engineering |
| [鸟窝](https://colobu.com/) | Chinese independent blog. | Engineering & Technology | [RSS](https://colobu.com/atom.xml) | all, blogs, chinese, engineering, top200 |
| [黑羽的个人博客](https://blog.thetbw.xyz) | Chinese independent blog. | Engineering & Technology | [RSS](https://blog.thetbw.xyz/atom.xml) | all, blogs, chinese, engineering, top200 |
| [𝟞𝟙𝟡'𝕤 𝔹𝕃𝕆𝔾](https://619.pp.ua) | Chinese independent blog. | Engineering & Technology | [RSS](https://66619.eu.org/feed/) | all, blogs, chinese, engineering |

</details>

<details>
<summary>🛡️ Security · 8</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [Krebs on Security](https://krebsonsecurity.com) | Brian Krebs reports on cybercrime, data breaches, and digital fraud. | Security | [RSS](https://krebsonsecurity.com/feed/) | all, engineering, news, security, top200 |
| [ZDNET Security](https://www.zdnet.com/) | Enterprise security, vulnerabilities, threat intelligence, and security products. | Security | [RSS](https://www.zdnet.com/topic/security/rss.xml) | all, engineering, news, security, top200 |
| [Schneier on Security](https://www.schneier.com/) | Bruce Schneier on security engineering, privacy, and public policy. | Security | [RSS](https://www.schneier.com/blog/index.rdf) | all, engineering, news, security, top200 |
| [Security Affairs](https://securityaffairs.com/) | Global coverage of cyberattacks, malware, vulnerabilities, and security incidents. | Security | [RSS](https://securityaffairs.co/wordpress/feed) | all, engineering, news, security, top200 |
| [腾讯玄武实验室](https://wechat2rss.xlab.app/feed/923c0e2f33b6d39c8a826a90f185725f0edb10e8.xml) | Vulnerability research, offensive and defensive techniques, and security practice from Tencent Xuanwu Lab. | Security | [RSS](https://wechat2rss.xlab.app/feed/923c0e2f33b6d39c8a826a90f185725f0edb10e8.xml) | all, chinese, company-tech, engineering, security, top200, wechat |
| [安全客](https://www.anquanke.com) | Chinese vulnerability analysis, security research, and industry coverage. | Security | [RSS](https://api.anquanke.com/data/v1/rss) | all, chinese, engineering, news, security, top200 |
| [CISA](https://www.cisa.gov/news-events) | Cybersecurity advisories, vulnerabilities, and defensive guidance from CISA. | Security | [RSS](https://www.cisa.gov/news.xml) | all, engineering, news, security, top200 |
| [FreeBuf 网络安全行业门户](https://www.freebuf.com/) | Chinese cybersecurity coverage spanning security research, vulnerability analysis, and the industry. | Security | [RSS](https://www.freebuf.com/feed) | all, chinese, engineering, news, security, top200 |

</details>

<details>
<summary>📰 Technology Media · 10</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [Ars Technica](https://arstechnica.com) | Technology reporting on software, hardware, science, and internet policy. | Technology Media | [RSS](https://feeds.arstechnica.com/arstechnica/index) | all, engineering, news, tech-media, top200 |
| [36氪](http://36kr.com) | Chinese business and technology coverage focused on startups, internet products, and industry shifts. | Technology Media | [RSS](https://www.36kr.com/feed) | all, chinese, news, tech-media, top200 |
| [Engadget](https://www.engadget.com/) | Consumer electronics, software services, and technology product reviews. | Technology Media | [RSS](https://www.engadget.com/rss.xml) | all, news, tech-media, top200 |
| [IT之家](https://www.ithome.com/) | Chinese technology news covering hardware, software, mobile devices, and internet companies. | Technology Media | [RSS](https://www.ithome.com/rss/) | all, chinese, news, tech-media, top200 |
| [TechCrunch](https://techcrunch.com/) | Startups, venture capital, internet products, and the technology industry. | Technology Media | [RSS](https://techcrunch.com/feed/) | all, news, tech-media, top200 |
| [The Verge — News](https://www.theverge.com) | Consumer technology, internet platforms, science, and digital culture. | Technology Media | [RSS](https://www.theverge.com/rss/index.xml) | all, news, tech-media, top200 |
| [WIRED](https://www.wired.com) | In-depth reporting on technology, science, business, and digital society. | Technology Media | [RSS](https://www.wired.com/feed/rss) | all, news, tech-media, top200 |
| [少数派](https://sspai.com) | Digital tools, productivity methods, software experiences, and personal workflows. | Technology Media | [RSS](https://sspai.com/feed) | all, chinese, news, tech-media, top200 |
| [爱范儿](https://www.ifanr.com?utm_source=rss&utm_medium=rss&utm_campaign=) | Chinese coverage of consumer technology, smart devices, and product trends. | Technology Media | [RSS](https://www.ifanr.com/feed) | all, chinese, news, tech-media, top200 |
| [MIT Technology Review](https://www.technologyreview.com/) | In-depth reporting on AI, computing, climate, and biotechnology. | Technology Media | [RSS](https://www.technologyreview.com/feed/) | all, news, tech-media, top200 |

</details>

<details>
<summary>📮 Tech Newsletters & Weeklies · 10</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [AI Weekly](https://aiweekly.co/) | Tracks what influential AI experts and organizations are reading and sharing across models, agents, funding, policy, and research. | Tech Newsletters & Weeklies | [RSS](https://aiweekly.co/feed) | ai, all, engineering, weeklies |
| [Last Week in AI](https://lastweekin.ai) | A weekly digest of AI research, products, and policy. | Tech Newsletters & Weeklies | [RSS](https://lastweekin.ai/feed) | ai, all, engineering, top200, weeklies |
| [The Batch](https://www.deeplearning.ai/the-batch/) | DeepLearning.AI’s weekly digest of AI news and research. | Tech Newsletters & Weeklies | [RSS](https://rsshub.bestblogs.dev/deeplearning/the-batch) | ai, all, engineering, top200, weeklies |
| [AIGC Weekly](https://quaily.com/op7418/feed/atom) | A Chinese weekly on generative-AI products, tools, and industry developments. | Tech Newsletters & Weeklies | [RSS](https://quaily.com/op7418/feed/atom) | all, engineering, news, top200, weeklies |
| [Golang Weekly](https://golangweekly.com/) | A weekly selection of Go articles, tools, projects, and community news. | Tech Newsletters & Weeklies | [RSS](https://golangweekly.com/rss/) | all, engineering, news, top200, weeklies |
| [大橘和朋友们的周刊](https://rrorangeandfriends.de) | An independent weekly selection of technology, products, and thoughtful reading. | Tech Newsletters & Weeklies | [RSS](https://rrorangeandfriends.de/feed.xml) | all, chinese, engineering, news, weeklies |
| [潮流周刊](https://weekly.tw93.fun/) | A Chinese weekly of technology notes, open-source projects, products, and life. | Tech Newsletters & Weeklies | [RSS](https://weekly.tw93.fun/rss.xml) | all, chinese, engineering, news, top200, weeklies |
| [JavaScript Weekly](https://javascriptweekly.com/) | A weekly selection of JavaScript news, articles, tools, and projects. | Tech Newsletters & Weeklies | [RSS](https://javascriptweekly.com/rss/) | all, engineering, top200, weeklies |
| [This Week in Rust](https://this-week-in-rust.org/) | A weekly digest of Rust projects, articles, releases, and community updates. | Tech Newsletters & Weeklies | [RSS](https://this-week-in-rust.org/atom.xml) | all, engineering, top200, weeklies |
| [阮一峰的网络日志](https://www.ruanyifeng.com/blog/) | Ruan Yifeng’s technical writing and weekly selection of developer tools, internet topics, and open-source projects. | Tech Newsletters & Weeklies | [RSS](https://www.ruanyifeng.com/blog/atom.xml) | all, blogs, chinese, engineering, top200, weeklies |

</details>

<details>
<summary>🔬 Research & Science · 19</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [AAAS: Science: Table of Contents](https://www.science.org/loi/science?af=R) | Research and science feed. | Research & Science | [RSS](https://www.science.org/action/showFeed?type=etoc&feed=rss&jc=science) | all, research, top200 |
| [All Top News -- ScienceDaily](https://www.sciencedaily.com/news/top/) | Research and science feed. | Research & Science | [RSS](https://www.sciencedaily.com/rss/top/science.xml) | all, research |
| [Amazon Science](https://www.amazon.science/) | Research and science feed. | Research & Science | [RSS](https://www.amazon.science/index.rss) | all, company-tech, research |
| [BBC News — Science](https://www.bbc.co.uk/news/science_and_environment) | Research and science feed. | Research & Science | [RSS](https://feeds.bbci.co.uk/news/science_and_environment/rss.xml) | all, research, top200 |
| [eLife: latest articles](https://elifesciences.org) | Research and science feed. | Research & Science | [RSS](https://elifesciences.org/rss/recent.xml) | all, research, top200 |
| [FlowingData](https://flowingdata.com) | Research and science feed. | Research & Science | [RSS](https://flowingdata.com/feed) | all, research, top200 |
| [Latest Science News -- ScienceDaily](https://www.sciencedaily.com/news/) | Research and science feed. | Research & Science | [RSS](https://www.sciencedaily.com/rss/all.xml) | all, research |
| [NASA](https://www.nasa.gov) | Research and science feed. | Research & Science | [RSS](https://www.nasa.gov/news-release/feed/) | all, research, top200 |
| [Nature](http://feeds.nature.com/nature/rss/current) | Research and science feed. | Research & Science | [RSS](https://www.nature.com/nature.rss) | all, research, top200 |
| [NYT > Science](https://www.nytimes.com/section/science) | Research and science feed. | Research & Science | [RSS](https://rss.nytimes.com/services/xml/rss/nyt/Science.xml) | all, research, top200 |
| [Phys.org - latest science and technology news stories](https://phys.org/) | Research and science feed. | Research & Science | [RSS](https://phys.org/rss-feed/) | all, research, top200 |
| [PLOS One](https://journals.plos.org/plosone/) | Research and science feed. | Research & Science | [RSS](https://journals.plos.org/plosone/feed/atom) | all, research, top200 |
| [Quanta Magazine](https://www.quantamagazine.org) | Research and science feed. | Research & Science | [RSS](https://www.quantamagazine.org/feed/) | all, research, top200 |
| [Science Latest](https://www.wired.com) | Research and science feed. | Research & Science | [RSS](https://www.wired.com/feed/category/science/latest/rss) | all, research |
| [Scientific American Content: Global](https://www.scientificamerican.com) | Research and science feed. | Research & Science | [RSS](http://rss.sciam.com/ScientificAmerican-Global) | all, research, top200 |
| [Space \| The Guardian](https://www.theguardian.com/science/space) | Research and science feed. | Research & Science | [RSS](https://www.theguardian.com/science/space/rss) | all, research, top200 |
| [Space – latest in science and technology \| New Scientist](https://www.newscientist.com/subject/space/) | Research and science feed. | Research & Science | [RSS](https://www.newscientist.com/subject/space/feed/) | all, research, top200 |
| [腾讯研究院](https://wechat2rss.bestblogs.dev/feed/6152301e0978bffb0a8284cab339262b9764dcfb.xml) | Research and science feed. | Research & Science | [RSS](https://wechat2rss.bestblogs.dev/feed/6152301e0978bffb0a8284cab339262b9764dcfb.xml) | all, chinese, company-tech, research, wechat |
| [阿里研究院](https://wechat2rss.bestblogs.dev/feed/e2f1190c120f7f3d74b630bfcfe9e58296bd535c.xml) | Research and science feed. | Research & Science | [RSS](https://wechat2rss.bestblogs.dev/feed/e2f1190c120f7f3d74b630bfcfe9e58296bd535c.xml) | all, chinese, company-tech, research, wechat |

</details>

<details>
<summary>🗞️ News · 22</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [Al Jazeera – Breaking News, World News and Video from Al Jazeera](https://www.aljazeera.com) | News feed. | News | [RSS](https://www.aljazeera.com/xml/rss/all.xml) | all, news, top200 |
| [BBC News — News](https://www.bbc.co.uk/news/world) | News feed. | News | [RSS](https://feeds.bbci.co.uk/news/world/rss.xml) | all, news, top200 |
| [Cointelegraph.com News](https://cointelegraph.com) | News feed. | News | [RSS](https://cointelegraph.com/rss/tag/blockchain) | all, news, top200 |
| [HackerNews每日摘要 on SuperTechFans](https://supertechfans.com/cn/) | News feed. | News | [RSS](https://www.supertechfans.com/cn/index.xml) | all, chinese, news |
| [InfoQ — News](https://www.infoq.com) | News feed. | News | [RSS](https://feed.infoq.com/) | all, news, top200 |
| [InfoQ 推荐](https://www.infoq.cn) | News feed. | News | [RSS](https://plink.anyfeeder.com/infoq/recommend) | all, chinese, news |
| [MIT 科技评论 - 本周热榜](https://www.mittrchina.com/hot) | News feed. | News | [RSS](https://rsshub.bestblogs.dev/mittrchina/hot) | all, chinese, news |
| [News from Google](https://blog.google/) | News feed. | News | [RSS](https://blog.google/rss) | all, engineering, news |
| [NPR Topics: World](https://www.npr.org/templates/story/story.php?storyId=1004) | News feed. | News | [RSS](https://feeds.npr.org/1004/rss.xml) | all, news, top200 |
| [NYT > Technology](https://www.nytimes.com/section/technology) | News feed. | News | [RSS](https://rss.nytimes.com/services/xml/rss/nyt/Technology.xml) | all, news, top200 |
| [NYT > World News](https://www.nytimes.com/section/world) | News feed. | News | [RSS](https://rss.nytimes.com/services/xml/rss/nyt/World.xml) | all, news |
| [ProPublica](https://www.propublica.org/) | News feed. | News | [RSS](https://www.propublica.org/feeds/propublica/main) | all, news, top200 |
| [Top stories - Google News](https://news.google.com/?hl=en-US&gl=US&ceid=US:en) | News feed. | News | [RSS](https://news.google.com/rss) | all, news |
| [World](https://www.washingtonpost.com) | News feed. | News | [RSS](https://feeds.washingtonpost.com/rss/world) | all, news |
| [World news \| The Guardian](https://www.theguardian.com/world) | News feed. | News | [RSS](https://www.theguardian.com/world/rss) | all, news, top200 |
| [World News, Today World News, Latest International News, World Breaking News, Trending News of World - Times of India](https://timesofindia.indiatimes.com/world) | News feed. | News | [RSS](https://timesofindia.indiatimes.com/rssfeeds/296589292.cms) | all, news |
| [奇客Solidot–传递最新科技情报](https://www.solidot.org) | News feed. | News | [RSS](https://www.solidot.org/index.rss) | all, chinese, news, top200 |
| [掘金本周最热](https://juejin.im/recommended?sort=weekly_hottest) | News feed. | News | [RSS](https://rsshub.bestblogs.dev/juejin/trending/all/weekly) | all, chinese, news |
| [站长之家](http://www.chinaz.com) | News feed. | News | [RSS](https://app.chinaz.com/?app=rss) | all, chinese, news |
| [蓝点网](https://www.landian.news) | News feed. | News | [RSS](https://www.landiannews.com/feed) | all, chinese, news |
| [虎嗅](https://www.huxiu.com) | News feed. | News | [RSS](https://rss.huxiu.com/) | all, chinese, news, top200 |
| [钛媒体：引领未来商业与生活新知](http://www.tmtpost.com) | News feed. | News | [RSS](https://www.tmtpost.com/feed) | all, chinese, news, top200 |

</details>

<details>
<summary>🎨 Product & Design · 5</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [61’s life](https://61.life/) | Chinese independent blog. | Product & Design | [RSS](https://61.life/feed.xml) | all, blogs, chinese, top200 |
| [jax](https://cdjax.com) | Chinese independent blog. | Product & Design | [RSS](https://cdjax.com/?feed=rss2) | all, blogs, chinese, top200 |
| [Velas电波站](https://www.velasx.com/) | Chinese independent blog. | Product & Design | [RSS](https://www.velasx.com/feed) | all, blogs, chinese, top200 |
| [拾月的博客](https://www.skyue.com/) | Chinese independent blog. | Product & Design | [RSS](https://www.skyue.com/feed/) | all, blogs, chinese, top200 |
| [阿里云设计中心](https://wechat2rss.xlab.app/feed/31e04606d37f684059e23a8fd3e05f1db0186495.xml) | WeChat article feed covering 产品设计与用户体验. | Product & Design | [RSS](https://wechat2rss.xlab.app/feed/31e04606d37f684059e23a8fd3e05f1db0186495.xml) | all, chinese, company-tech, top200, wechat |

</details>

<details>
<summary>💼 Business & Startups · 5</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [Macin](https://macin.org/atom.xml) | Chinese independent blog. | Business & Startups | [RSS](https://www.macin.org/atom.xml) | all, blogs, chinese, top200 |
| [扯氮集](http://weiwuhui.com) | Chinese independent blog. | Business & Startups | [RSS](http://weiwuhui.com/feed) | all, blogs, chinese |
| [知足常乐-水星投资理财的基本意念](http://mercurychong.blogspot.com/) | Chinese independent blog. | Business & Startups | [RSS](http://mercurychong.blogspot.com/feeds/posts/default) | all, blogs, chinese, top200 |
| [虹线](https://1q43.blog) | Chinese independent blog. | Business & Startups | [RSS](https://1q43.blog/feed) | all, blogs, chinese, top200 |
| [雷蒙三十｜幫助忙碌現代人的聰明工作、好好生活的生產力指南](https://raymondhouch.com) | Chinese independent blog. | Business & Startups | [RSS](https://raymondhouch.com/feed) | all, blogs, chinese, top200 |

</details>

<details>
<summary>✍️ Personal Blogs · 64</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [ABB00717](https://blog.abb00717.com) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.abb00717.com/index.xml) | all, blogs, chinese, top200 |
| [Another Dayu](https://anotherdayu.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://anotherdayu.com/feed/) | all, blogs, chinese, top200 |
| [Blog \| Lyunvy](https://blog.lyunvy.top/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.lyunvy.top/atom.xml) | all, blogs, chinese |
| [BMPI](https://www.bmpi.dev/) | Chinese independent blog. | Personal Blogs | [RSS](https://www.bmpi.dev/index.xml) | all, blogs, chinese |
| [by Upsangel](https://upsangel.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://upsangel.com/feed/) | all, blogs, chinese |
| [Conge](https://conge.livingwithfcs.org/) | Chinese independent blog. | Personal Blogs | [RSS](https://conge.github.io/feed.xml) | all, blogs, chinese |
| [Cosmos的博客](https://cosmo-polite.com) | Chinese independent blog. | Personal Blogs | [RSS](https://cosmo-polite.com/feed/) | all, blogs, chinese |
| [David Blog](https://blog.blahaj.uk/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.blahaj.uk/feed) | all, blogs, chinese |
| [Deep Router](https://deeprouter.org/) | Chinese independent blog. | Personal Blogs | [RSS](https://deeprouter.org/rss/feed.xml) | all, blogs, chinese |
| [Dejavu's Blog](https://blog.dejavu.moe/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.dejavu.moe/index.xml) | all, blogs, chinese |
| [Dort 的博客](https://blog.dort.me/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.dort.me/rss.xml) | all, blogs, chinese, top200 |
| [Evan's Space](https://www.evan.xin) | Chinese independent blog. | Personal Blogs | [RSS](https://evan.xin/feed) | all, blogs, chinese |
| [Fei's Tours & Tales](https://www.feifun.cn/feed.xml) | Chinese independent blog. | Personal Blogs | [RSS](https://www.feifun.cn/feed.xml) | all, blogs, chinese |
| [Fernweh](https://blog.wohin.me/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.wohin.me/index.xml) | all, blogs, chinese |
| [GentleLucky](https://blog.gentlelucky.com/zh/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.gentlelucky.com/zh/index.xml) | all, blogs, chinese |
| [happy xiao](https://happyxiao.com) | Chinese independent blog. | Personal Blogs | [RSS](https://happyxiao.com/feed) | all, blogs, chinese, top200 |
| [ImPatrick](https://impatrick.blog) | Chinese independent blog. | Personal Blogs | [RSS](https://impatrick.blog/feed/) | all, blogs, chinese |
| [Jake blog](https://jaketao.com) | Chinese independent blog. | Personal Blogs | [RSS](https://jaketao.com/feed/) | all, blogs, chinese, top200 |
| [Jame](https://jame.work/) | Chinese independent blog. | Personal Blogs | [RSS](https://jame.work/feed.xml) | all, blogs, chinese, top200 |
| [JustZht's EchoChamber](https://www.justzht.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://www.justzht.com/rss/) | all, blogs, chinese, top200 |
| [jz's ramblings](https://ramble.imzh.me/) | Chinese independent blog. | Personal Blogs | [RSS](https://ramble.imzh.me/index.xml) | all, blogs, chinese |
| [LCZBlog](https://blog.licaoz.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.licaoz.com/feed/) | all, blogs, chinese |
| [LoRexxar's Blog \| 信息技术分享](https://lorexxar.cn/atom.xml) | Chinese independent blog. | Personal Blogs | [RSS](https://lorexxar.cn/atom.xml) | all, blogs, chinese |
| [M-x Chris-An-Emacser](https://chriszheng.science/) | Chinese independent blog. | Personal Blogs | [RSS](https://chriszheng.science/atom.xml) | all, blogs, chinese, top200 |
| [Markon Review](https://markonreview.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://markonreview.com/rss/) | all, blogs, chinese |
| [Redish101 Blog](https://blog.redish101.top/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.redish101.top/atom.xml) | all, blogs, chinese |
| [Save the Web Project](https://blog.save-web.org) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.save-web.org/feed/) | all, blogs, chinese |
| [SEISAMUSE](https://www.seis-jun.xyz/atom.xml) | Chinese independent blog. | Personal Blogs | [RSS](https://www.seis-jun.xyz/atom.xml) | all, blogs, chinese, top200 |
| [Shuibaco • 水八口](http://shuiba.co/) | Chinese independent blog. | Personal Blogs | [RSS](https://shuiba.co/feed) | all, blogs, chinese, top200 |
| [Spring](https://spring.io) | Independent blog. | Personal Blogs | [RSS](https://spring.io/blog.atom) | all, engineering |
| [SuperGrey 的筆記本](https://blog.supergrey.uk) | Chinese independent blog. | Personal Blogs | [RSS](https://supergrey.bearblog.dev/rss/) | all, blogs, chinese |
| [tplate](https://trle5.xyz) | Chinese independent blog. | Personal Blogs | [RSS](https://trle5.xyz/atom.xml) | all, blogs, chinese |
| [whyes 的博客](http://whyes.org/) | Chinese independent blog. | Personal Blogs | [RSS](https://whyes.org/feed.xml) | all, blogs, chinese |
| [WSH](https://www.wsh233.cn) | Chinese independent blog. | Personal Blogs | [RSS](https://www.wsh233.cn/feed.xml) | all, blogs, chinese, top200 |
| [Wulu's Blog](https://wulu.zone/posts/) | Chinese independent blog. | Personal Blogs | [RSS](https://wulu.zone/feed/post.xml) | all, blogs, chinese |
| [一派胡言 · Blog](https://yipai.me/blog) | Chinese independent blog. | Personal Blogs | [RSS](https://yipai.me/feed) | all, blogs, chinese, top200 |
| [不吐不快](https://mianao.info/atom.xml) | Chinese independent blog. | Personal Blogs | [RSS](https://mianao.info/atom.xml) | all, blogs, chinese, top200 |
| [专享生活](https://zhjwork.online) | Chinese independent blog. | Personal Blogs | [RSS](https://zhjwork.online/feed) | all, blogs, chinese |
| [云心怀鹤](https://bluehe.cn/) | Chinese independent blog. | Personal Blogs | [RSS](https://bluehe.cn/feed/) | all, blogs, chinese |
| [卢昌海个人主页](http://www.changhai.org) | Chinese independent blog. | Personal Blogs | [RSS](https://www.changhai.org/feed.xml) | all, blogs, chinese, top200 |
| [印记](https://yinji.org/) | Chinese independent blog. | Personal Blogs | [RSS](https://yinji.org/feed) | all, blogs, chinese, top200 |
| [双绞麻痹](https://numb.tech/atom.xml) | Chinese independent blog. | Personal Blogs | [RSS](https://numb.tech/atom.xml) | all, blogs, chinese |
| [叶寻的博客](https://cyrusyip.org/zh-cn/) | Chinese independent blog. | Personal Blogs | [RSS](https://cyrusyip.org/zh-cn/index.xml) | all, blogs, chinese |
| [叶泯希](https://blog.418121.xyz/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.418121.xyz/rss2.xml) | all, blogs, chinese |
| [同和故事匯](https://hocassian.cn/) | Chinese independent blog. | Personal Blogs | [RSS](https://hocassian.cn/feed/) | all, blogs, chinese |
| [四喜丸子](https://fourhappylions.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://fourhappylions.com/index.xml) | all, blogs, chinese, top200 |
| [如鱼饮水](https://wangjiezhe.com/atom.xml) | Chinese independent blog. | Personal Blogs | [RSS](https://wangjiezhe.com/atom.xml) | all, blogs, chinese, top200 |
| [小陶持续精进](https://whyya.xyz/) | Chinese independent blog. | Personal Blogs | [RSS](https://whyya.xyz/rss.xml) | all, blogs, chinese |
| [局域自由博客](https://localfreedom.pages.dev/) | Chinese independent blog. | Personal Blogs | [RSS](https://localfreedom.pages.dev/index.xml) | all, blogs, chinese, top200 |
| [廊桥遗梦](https://blog.moran.im/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.moran.im/rss.xml) | all, blogs, chinese, top200 |
| [懋和道人](https://blog.dao.js.cn) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.dao.js.cn/atom.xml) | all, blogs, chinese |
| [明天的乌云](https://blog.xlab.app/atom.xml) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.xlab.app/atom.xml) | all, blogs, chinese |
| [木鸟杂记](https://www.qtmuniao.com) | Chinese independent blog. | Personal Blogs | [RSS](https://www.qtmuniao.com/atom.xml) | all, blogs, chinese |
| [林林杂语](https://www.xiaozonglin.cn/) | Chinese independent blog. | Personal Blogs | [RSS](https://www.xiaozonglin.cn/feed/) | all, blogs, chinese |
| [柴郡猫](https://www.cheshirex.com) | Chinese independent blog. | Personal Blogs | [RSS](https://www.cheshirex.com/feed) | all, blogs, chinese |
| [梅之夏](https://blog.mcenahle.page/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.mcenahle.page/feed.xml) | all, blogs, chinese, top200 |
| [涵哲子居](https://iluc.cn/) | Chinese independent blog. | Personal Blogs | [RSS](https://iluc.cn/rss.xml) | all, blogs, chinese, top200 |
| [玉明-风起于青萍之末](https://xdym11235.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://xdym11235.com/feed) | all, blogs, chinese |
| [祝融说。](https://zhurongshuo.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://zhurongshuo.com/index.xml) | all, blogs, chinese, top200 |
| [纸短情长](https://www.gtdstudy.com/) | Chinese independent blog. | Personal Blogs | [RSS](http://yibie.github.io/index.xml) | all, blogs, chinese |
| [讀角獸](https://ducorn.com) | Chinese independent blog. | Personal Blogs | [RSS](https://ducorn.com/feed.xml) | all, blogs, chinese |
| [資工小廢物 - JN](https://blog.giveanornot.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://blog.giveanornot.com/index.xml) | all, blogs, chinese, top200 |
| [闲人LIFE](https://www.xianrenlife.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://www.xianrenlife.com/feeds/posts/default) | all, blogs, chinese, top200 |
| [陈杨树下](https://demochen.com/) | Chinese independent blog. | Personal Blogs | [RSS](https://www.demochen.com/atom.xml) | all, blogs, chinese |

</details>

<details>
<summary>👥 Communities · 14</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [V2EX](https://www.v2ex.com/) | New discussions from the Chinese technology community. | Communities | [RSS](https://v2ex.com/index.xml) | all, chinese, communities, news |
| [LINUX DO · 文档共建](https://linux.do/c/wiki/42) | Tutorials, study notes, and community-maintained documents from LINUX DO. | Communities | [RSS](https://linuxdorss.longpink.com/wiki.xml) | all, chinese, communities, engineering, top200 |
| [Reddit · Linux, Self-Hosted, DevOps & AI](https://www.reddit.com/r/linux+selfhosted+devops+LocalLLaMA+MachineLearning/new/) | A combined feed of new Linux, self-hosting, DevOps, LocalLLaMA, and machine-learning posts. | Communities | [RSS](https://www.reddit.com/r/linux+selfhosted+devops+LocalLLaMA+MachineLearning/new/.rss) | ai, all, communities, engineering |
| [Lobsters](https://lobste.rs/) | Community-curated discussions about software, programming, and computer science. | Communities | [RSS](https://lobste.rs/rss) | all, communities, engineering, top200 |
| [Python Core Development](https://discuss.python.org/c/core-dev/23) | Discussions about Python core development and interpreter design. | Communities | [RSS](https://discuss.python.org/c/core-dev/23.rss?order=created) | all, communities, engineering |
| [Rust Internals · Language Design](https://internals.rust-lang.org/c/language-design/21) | Discussions about Rust language design and compiler internals. | Communities | [RSS](https://internals.rust-lang.org/c/language-design/21.rss?order=created) | all, communities, engineering |
| [NixOS Development](https://discourse.nixos.org/c/dev/14) | Discussions about NixOS development, packaging, and infrastructure. | Communities | [RSS](https://discourse.nixos.org/c/dev/14.rss?order=created) | all, communities, engineering, top200 |
| [OpenAI Developer Community · API](https://community.openai.com/c/api/7) | Discussions about using, debugging, and integrating the OpenAI API. | Communities | [RSS](https://community.openai.com/c/api/7.rss?order=created) | ai, all, communities, engineering |
| [Kubernetes · General Discussions](https://discuss.kubernetes.io/c/general-discussions/6) | Discussions about Kubernetes configuration, cluster operations, and troubleshooting. | Communities | [RSS](https://discuss.kubernetes.io/c/general-discussions/6.rss?order=created) | all, communities, engineering |
| [V2EX · 技术](https://www.v2ex.com/?tab=tech) | New topics from V2EX’s technology section, focused on programming, architecture, and developer tools. | Communities | [RSS](https://www.v2ex.com/feed/tab/tech.xml) | all, chinese, communities, engineering, top200 |
| [V2EX · 创意](https://www.v2ex.com/?tab=creative) | New topics from V2EX’s creative section, centered on indie products, design, and launches. | Communities | [RSS](https://www.v2ex.com/feed/tab/creative.xml) | all, chinese, communities, engineering |
| [Show HN](https://news.ycombinator.com/shownew) | New products, open-source projects, and personal work shared on Hacker News. | Communities | [RSS](https://hnrss.org/show) | all, communities, engineering |
| [Ask HN](https://news.ycombinator.com/ask) | Hacker News questions on technical choices, career experience, and the industry. | Communities | [RSS](https://hnrss.org/ask) | all, communities, engineering |
| [Hacker News](https://news.ycombinator.com/) | Popular technology, startup, and product discussions from the Hacker News front page. | Communities | [RSS](https://news.ycombinator.com/rss) | all, communities, engineering, top200 |

</details>

<details>
<summary>📚 Culture & Ideas · 10</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [KAIX.IN](https://kaix.in/) | Chinese independent blog. | Culture & Ideas | [RSS](https://kaix.in/feed/) | all, blogs, chinese, top200 |
| [Maohang Gao's Blog](http://kangaroogao.com/atom.xml) | Chinese independent blog. | Culture & Ideas | [RSS](https://kangaroogao.com/atom.xml) | all, blogs, chinese, top200 |
| [ShineKid](https://shinekid.com) | Chinese independent blog. | Culture & Ideas | [RSS](https://shinekid.com/feed/) | all, blogs, chinese, top200 |
| [Tripper Press - Take Photo, Think Seriously.](https://tripper.press) | Chinese independent blog. | Culture & Ideas | [RSS](https://tripper.press/atom.xml) | all, blogs, chinese, top200 |
| [东评西就](https://dongjunke.cn/) | Chinese independent blog. | Culture & Ideas | [RSS](https://dongjunke.cn/atom.xml) | all, blogs, chinese, top200 |
| [先生制造](https://wechat2rss.xlab.app/feed/313326d41db4f54b1cc09e7c986a5ac4e5f88ca0.xml) | WeChat article feed covering 人物与社会记录. | Culture & Ideas | [RSS](https://wechat2rss.xlab.app/feed/313326d41db4f54b1cc09e7c986a5ac4e5f88ca0.xml) | all, chinese, top200, wechat |
| [叉息的空中咖啡馆](https://www.xchere.xyz/atom.xml) | Chinese independent blog. | Culture & Ideas | [RSS](https://www.xchere.xyz/atom.xml) | all, blogs, chinese |
| [浅黑科技](https://wechat2rss.xlab.app/feed/6111a6d5ecf28cfdd4fc9b664244c05ddacef15c.xml) | WeChat article feed covering 科技人物与产业故事. | Culture & Ideas | [RSS](https://wechat2rss.xlab.app/feed/6111a6d5ecf28cfdd4fc9b664244c05ddacef15c.xml) | all, chinese, wechat |
| [赫赫文王](https://kqh.me/) | Chinese independent blog. | Culture & Ideas | [RSS](https://kqh.me/index.xml) | all, blogs, chinese, top200 |
| [静风说](https://www.jfsay.com) | Chinese independent blog. | Culture & Ideas | [RSS](http://www.jfsay.com/feed) | all, blogs, chinese, top200 |

</details>

<details>
<summary>🎬 Videos · 93</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCYO_jab_esuFRV4b17AJtAw) | all, top200, videos |
| [a16z](https://www.youtube.com/channel/UC9cn0TuPq4dnbTY-CBsm8XA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC9cn0TuPq4dnbTY-CBsm8XA) | all, videos |
| [Acquired](https://www.youtube.com/channel/UCyFqFYfTW2VoIQKylJ04Rtw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCyFqFYfTW2VoIQKylJ04Rtw) | all, videos |
| [AI Engineer](https://www.youtube.com/channel/UCLKPca3kwwd-B59HNr-_lvA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCLKPca3kwwd-B59HNr-_lvA) | ai, all, videos |
| [AI Explained](https://www.youtube.com/channel/UCNJ1Ymd5yFuUPtn21xtRbbw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCNJ1Ymd5yFuUPtn21xtRbbw) | ai, all, videos |
| [AI Master](https://www.youtube.com/channel/UC0yHbz4OxdQFwmVX2BBQqLg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC0yHbz4OxdQFwmVX2BBQqLg) | ai, all, videos |
| [AI Search](https://www.youtube.com/channel/UCIgnGlGkVRhd4qNFcEwLL4A) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCIgnGlGkVRhd4qNFcEwLL4A) | ai, all, videos |
| [AICodeKing](https://www.youtube.com/channel/UC0m81bQuthaQZmFbXEY9QSw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC0m81bQuthaQZmFbXEY9QSw) | ai, all, videos |
| [Alex Kantrowitz](https://www.youtube.com/channel/UCye1YedIypHffYb8k6Gp9wg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCye1YedIypHffYb8k6Gp9wg) | all, videos |
| [Ali Abdaal](https://www.youtube.com/channel/UCoOae5nYA7VqaXzerajD0lg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCoOae5nYA7VqaXzerajD0lg) | all, videos |
| [All-In Podcast](https://www.youtube.com/channel/UCESLZhusAkFfsNsApnjF_Cg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCESLZhusAkFfsNsApnjF_Cg) | all, videos |
| [Andrej Karpathy](https://www.youtube.com/channel/UCXUPKJO5MZQN11PqgIvyuvQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCXUPKJO5MZQN11PqgIvyuvQ) | ai, all, videos |
| [Andrew Huberman](https://www.youtube.com/channel/UC2D2CMWXMOVWx7giW1n3LIg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC2D2CMWXMOVWx7giW1n3LIg) | all, videos |
| [Android Developers](https://www.youtube.com/channel/UCVHFbqXqoYvEWM1Ddxl0QDg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?user=androiddevelopers) | all, videos |
| [AssemblyAI](https://www.youtube.com/channel/UCtatfZMf-8EkIwASXM4ts0A) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCtatfZMf-8EkIwASXM4ts0A) | ai, all, videos |
| [BBC Earth](https://www.youtube.com/channel/UCwmZiChSryoWQCZMIQezgTg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCwmZiChSryoWQCZMIQezgTg) | all, videos |
| [Beyond Coding](https://www.youtube.com/channel/UCdMz6KKEDW_1Qqas-ya7S6w) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCdMz6KKEDW_1Qqas-ya7S6w) | all, videos |
| [Bloomberg Originals](https://www.youtube.com/channel/UCUMZ7gohGI9HcU9VNsr2FJQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?user=Bloomberg) | all, videos |
| [Branch Education](https://www.youtube.com/channel/UCdp4_l1vPmpN-gDbUwhaRUQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCdp4_l1vPmpN-gDbUwhaRUQ) | all, videos |
| [Business Insider](https://www.youtube.com/channel/UCcyq283he07B7_KUX07mmtA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?user=businessinsider) | all, videos |
| [ByteByteGo](https://www.youtube.com/channel/UCZgt6AzoyjslHTC9dz0UoTw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCZgt6AzoyjslHTC9dz0UoTw) | all, videos |
| [CNET](https://www.youtube.com/channel/UCOmcA3f_RrH6b9NmcNa4tdg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?user=CNETTV) | all, videos |
| [Computerphile](https://www.youtube.com/channel/UC9-y-6csu5WGm29I7JiwpnA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC9-y-6csu5WGm29I7JiwpnA) | all, videos |
| [Curious Refuge](https://www.youtube.com/channel/UClnFtyUEaxQOCd1s5NKYGFA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UClnFtyUEaxQOCd1s5NKYGFA) | all, videos |
| [DeepLearningAI — Video](https://www.youtube.com/channel/UCcIXc5mJsHVYTZR1maL5l9w) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCcIXc5mJsHVYTZR1maL5l9w) | ai, all, videos |
| [Dwarkesh Patel](https://www.youtube.com/channel/UCXl4i9dYBrFOabk0xGmbkRA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCXl4i9dYBrFOabk0xGmbkRA) | all, videos |
| [Elizabeth Alli - DesignerUp](https://www.youtube.com/channel/UCw2R8kz3aotYtV9utqf0uaw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCw2R8kz3aotYtV9utqf0uaw) | all, videos |
| [EO](https://www.youtube.com/channel/UClWTCPVi-AU9TeCN6FkGARg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UClWTCPVi-AU9TeCN6FkGARg) | all, videos |
| [Fireship](https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCsBjURrPoezykLs9EqgamOA) | all, videos |
| [freeCodeCamp.org](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC8butISFwT-Wl7EV0hUK0BQ) | all, videos |
| [Google](https://www.youtube.com/channel/UCK8sQmJBp8GCxrOtXWBpyEA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCK8sQmJBp8GCxrOtXWBpyEA) | all, videos |
| [Google DeepMind](https://www.youtube.com/channel/UCP7jMXSY2xbc3KCAE0MHQ-A) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCP7jMXSY2xbc3KCAE0MHQ-A) | ai, all, videos |
| [Greg Isenberg](https://www.youtube.com/channel/UCPjNBjflYl0-HQtUvOx0Ibw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCPjNBjflYl0-HQtUvOx0Ibw) | all, videos |
| [How I AI](https://www.youtube.com/channel/UCRYY7IEbkHLH_ScJCu9eWDQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCRYY7IEbkHLH_ScJCu9eWDQ) | ai, all, videos |
| [Hung-yi Lee](https://www.youtube.com/channel/UC2ggjtuuWvxrHHHiaDH1dlQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC2ggjtuuWvxrHHHiaDH1dlQ) | ai, all, videos |
| [Hussein Nasser](https://www.youtube.com/channel/UC_ML5xP23TOWKUcc-oAE_Eg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC_ML5xP23TOWKUcc-oAE_Eg) | all, videos |
| [Invest Like The Best](https://www.youtube.com/channel/UCpQBb0fToph3jrDulwz1iUQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCpQBb0fToph3jrDulwz1iUQ) | all, videos |
| [Justin Sung](https://www.youtube.com/channel/UC2Zs9v2hL2qZZ7vsAENsg4w) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC2Zs9v2hL2qZZ7vsAENsg4w) | all, videos |
| [Kurzgesagt – In a Nutshell](https://www.youtube.com/channel/UCsXVk37bltHxD1rDPwtNM8Q) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCsXVk37bltHxD1rDPwtNM8Q) | all, videos |
| [LangChain](https://www.youtube.com/channel/UCC-lyoTfSrcJzA1ab3APAgw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCC-lyoTfSrcJzA1ab3APAgw) | ai, all, videos |
| [Last Week in AI — Video](https://www.youtube.com/channel/UCKARTq-t5SPMzwtft8FWwnA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCKARTq-t5SPMzwtft8FWwnA) | ai, all, videos |
| [leerob](https://www.youtube.com/channel/UCZMli3czZnd1uoc1ShTouQw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCZMli3czZnd1uoc1ShTouQw) | ai, all, videos |
| [Lenny's Podcast](https://www.youtube.com/channel/UC6t1O76G0jYXOAoYCm153dA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC6t1O76G0jYXOAoYCm153dA) | all, videos |
| [Lex Fridman](https://www.youtube.com/channel/UCSHZKyawb77ixDdsGog4iWA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCSHZKyawb77ixDdsGog4iWA) | all, videos |
| [Liam Ottley](https://www.youtube.com/channel/UCui4jxDaMb53Gdh-AZUTPAg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCui4jxDaMb53Gdh-AZUTPAg) | ai, all, videos |
| [Linus Tech Tips](https://www.youtube.com/channel/UCXuqSBlHAE6Xw-yeJA0Tunw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?user=LinusTechTips) | all, videos |
| [Luma](https://www.youtube.com/channel/UC45T0I4p7A3dI0XvhivafZQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC45T0I4p7A3dI0XvhivafZQ) | all, videos |
| [Machine Learning Street Talk](https://www.youtube.com/channel/UCMLtBahI5DMrt0NPvDSoIRQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCMLtBahI5DMrt0NPvDSoIRQ) | ai, all, videos |
| [MacRumors](https://www.youtube.com/channel/UCaFGDBmGK_jw66u3av2Ysjw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?user=macrumors) | all, videos |
| [Marie Forleo](https://www.youtube.com/channel/UCuoxrRDDgk3UUnxR4tlkJYQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?user=marieforleo) | all, videos |
| [Matt Wolfe](https://www.youtube.com/channel/UChpleBmo18P08aKCIgti38g) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UChpleBmo18P08aKCIgti38g) | ai, all, videos |
| [Matthew Berman](https://www.youtube.com/channel/UCawZsQWqfGSbCI5yjkdVkTA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCawZsQWqfGSbCI5yjkdVkTA) | ai, all, videos |
| [MrBeast](https://www.youtube.com/channel/UCX6OQ3DkcsbYNE6H8uQQuVA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCX6OQ3DkcsbYNE6H8uQQuVA) | all, videos |
| [mrblock 區塊先生](https://www.youtube.com/channel/UCN2hSM8fBcvZBa8OOKc24eg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCN2hSM8fBcvZBa8OOKc24eg) | all, chinese, videos |
| [Nature on PBS](https://www.youtube.com/channel/UCcBp_9YPyma4c3HTadmRJ3Q) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCcBp_9YPyma4c3HTadmRJ3Q) | all, videos |
| [nature video](https://www.youtube.com/channel/UC7c8mE90qCtu11z47U0KErg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC7c8mE90qCtu11z47U0KErg) | all, videos |
| [Naval](https://www.youtube.com/channel/UCh_dVD10YuSghle8g6yjePg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCh_dVD10YuSghle8g6yjePg) | all, videos |
| [Nick Saraev](https://www.youtube.com/channel/UCbo-KbSjJDG6JWQ_MTZ_rNA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCbo-KbSjJDG6JWQ_MTZ_rNA) | ai, all, videos |
| [Nikhil Kamath](https://www.youtube.com/channel/UCnC8SAZzQiBGYVSKZ_S3y4Q) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCnC8SAZzQiBGYVSKZ_S3y4Q) | all, videos |
| [NNgroup](https://www.youtube.com/channel/UC2oCugzU6W8-h95W7eBTUEg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC2oCugzU6W8-h95W7eBTUEg) | all, videos |
| [No Priors: AI, Machine Learning, Tech, & Startups](https://www.youtube.com/channel/UCSI7h9hydQ40K5MJHnCrQvw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCSI7h9hydQ40K5MJHnCrQvw) | ai, all, videos |
| [OpenAI](https://www.youtube.com/channel/UCXZCJLdBC09xxGZ6gcdrc6A) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCXZCJLdBC09xxGZ6gcdrc6A) | ai, all, videos |
| [Patrick Boyle](https://www.youtube.com/channel/UCASM0cgfkJxQ1ICmRilfHLw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCASM0cgfkJxQ1ICmRilfHLw) | all, videos |
| [Pika Labs](https://www.youtube.com/channel/UC0SclYU4iiQRihtmDnak-gQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC0SclYU4iiQRihtmDnak-gQ) | ai, all, videos |
| [PowerfulJRE](https://www.youtube.com/channel/UCzQUP1qoWDoEbmsQxvdjxgQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCzQUP1qoWDoEbmsQxvdjxgQ) | all, videos |
| [Product School](https://www.youtube.com/channel/UC6hlQ0x6kPbAGjYkoz53cvA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC6hlQ0x6kPbAGjYkoz53cvA) | all, videos |
| [Real Engineering](https://www.youtube.com/channel/UCR1IuLEqb6UEA_zQ81kwXfg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCR1IuLEqb6UEA_zQ81kwXfg) | all, videos |
| [Riley Brown](https://www.youtube.com/channel/UCMcoud_ZW7cfxeIugBflSBw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCMcoud_ZW7cfxeIugBflSBw) | ai, all, videos |
| [Runway](https://www.youtube.com/channel/UCUBqu_z5uP0AZhYtuyFZB3g) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCUBqu_z5uP0AZhYtuyFZB3g) | ai, all, videos |
| [Ryan Peterman](https://www.youtube.com/channel/UCzB7YGrrxDC_POenf86H3_Q) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCzB7YGrrxDC_POenf86H3_Q) | all, videos |
| [Sabin Civil Engineering](https://www.youtube.com/channel/UCqZQJ4600a9wIfMPbYc60OQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCqZQJ4600a9wIfMPbYc60OQ) | all, videos |
| [Sequoia Capital](https://www.youtube.com/channel/UCWrF0oN6unbXrWsTN7RctTw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCWrF0oN6unbXrWsTN7RctTw) | all, videos |
| [Silicon Valley Girl](https://www.youtube.com/channel/UCiq1FIgtEK7LRAOB1JXTPig) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCiq1FIgtEK7LRAOB1JXTPig) | all, videos |
| [SpaceX](https://www.youtube.com/channel/UCtI0Hodo5o5dUb67FeUjDeA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?user=spacexchannel) | all, videos |
| [Spring I/O](https://www.youtube.com/channel/UCLMPXsvSrhNPN3i9h-u8PYg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCLMPXsvSrhNPN3i9h-u8PYg) | all, videos |
| [StatQuest with Josh Starmer](https://www.youtube.com/channel/UCtYLUTtgS3k1Fg4y5tAhLbw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCtYLUTtgS3k1Fg4y5tAhLbw) | all, videos |
| [Tao Prompts](https://www.youtube.com/channel/UCc1qMq2UBJD9cSKbeBwGoZQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCc1qMq2UBJD9cSKbeBwGoZQ) | ai, all, videos |
| [TED](https://www.youtube.com/channel/UCAuUUnT6oDeKwE6v1NGQxug) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCAuUUnT6oDeKwE6v1NGQxug) | all, videos |
| [The AI Advantage](https://www.youtube.com/channel/UCHhYXsLBEVVnbvsq57n1MTQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCHhYXsLBEVVnbvsq57n1MTQ) | ai, all, videos |
| [The Futur](https://www.youtube.com/channel/UC-b3c7kxa5vU-bnmaROgvog) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC-b3c7kxa5vU-bnmaROgvog) | all, videos |
| [The Knowledge Project Podcast](https://www.youtube.com/channel/UCLtTf_uKt0Itd0NG7txrwXA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCLtTf_uKt0Itd0NG7txrwXA) | all, videos |
| [The Pragmatic Engineer](https://www.youtube.com/channel/UCPbwhExawYrn9xxI21TFfyw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCPbwhExawYrn9xxI21TFfyw) | all, videos |
| [The Verge — Video](https://www.youtube.com/channel/UCddiUEpeqJcYeBxX1IVBKvQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?user=TheVerge) | all, videos |
| [Tina Huang](https://www.youtube.com/channel/UC2UXDak6o7rBm23k3Vv5dww) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC2UXDak6o7rBm23k3Vv5dww) | ai, all, videos |
| [Traversy Media](https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UC29ju8bIPH5as8OGnQzwJyA) | all, videos |
| [Web Dev Simplified](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCFbNIlppjAuEX4znoulh0Cw) | all, videos |
| [Wes Roth](https://www.youtube.com/channel/UCqcbQf6yw5KzRoDDcZ_wBSw) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCqcbQf6yw5KzRoDDcZ_wBSw) | ai, all, videos |
| [Y Combinator](https://www.youtube.com/channel/UCcefcZRL2oaA_uBNeo5UOWg) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCcefcZRL2oaA_uBNeo5UOWg) | all, top200, videos |
| [Yannic Kilcher](https://www.youtube.com/channel/UCZHmQk67mSJgfCCTn7xBfew) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCZHmQk67mSJgfCCTn7xBfew) | ai, all, videos |
| [yobi321](https://www.youtube.com/channel/UCB_DbqNN9w30tnyWJSrIwyA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCB_DbqNN9w30tnyWJSrIwyA) | all, videos |
| [一席YiXi](https://www.youtube.com/channel/UCKFB_rVEFEF3l-onQGvGx1A) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCKFB_rVEFEF3l-onQGvGx1A) | all, chinese, videos |
| [一条Yit](https://www.youtube.com/channel/UCulFhrW_YCwkq_BP16C82mA) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCulFhrW_YCwkq_BP16C82mA) | all, chinese, videos |
| [李永乐老师](https://www.youtube.com/channel/UCvNxfitQbWkmLuCd44UfrYQ) | Video channel. | Videos | [RSS](https://www.youtube.com/feeds/videos.xml?channel_id=UCvNxfitQbWkmLuCd44UfrYQ) | all, chinese, videos |

</details>

<details>
<summary>🎧 Podcasts · 73</summary>

| Source | Description | Primary category | Feed | Bundles |
| --- | --- | --- | --- | --- |
| [30 for 30 Podcasts](http://espnradio.espn.com/espnradio/index) | Podcast. | Podcasts | [RSS](https://feeds.megaphone.fm/ESP5765452710) | all, podcasts |
| [42章经 — Podcast](https://www.xiaoyuzhoufm.com/podcast/648b0b641c48983391a63f98) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/648b0b641c48983391a63f98) | all, chinese, podcasts |
| [AI炼金术 — Podcast](https://www.xiaoyuzhoufm.com/podcast/63e9ef4de99bdef7d39944c8) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/63e9ef4de99bdef7d39944c8) | ai, all, chinese, podcasts |
| [Darknet Diaries](https://darknetdiaries.com/) | Podcast. | Podcasts | [RSS](https://feeds.megaphone.fm/darknetdiaries) | all, podcasts, top200 |
| [Discovery](http://www.bbc.co.uk/programmes/p002w557) | Podcast. | Podcasts | [RSS](https://podcasts.files.bbci.co.uk/p002w557.rss) | all, podcasts |
| [Fragmented - AI Developer Podcast](https://fragmentedpodcast.com/) | Podcast. | Podcasts | [RSS](https://feeds.simplecast.com/LpAGSLnY) | ai, all, podcasts |
| [Gastropod](https://gastropod.com/) | Podcast. | Podcasts | [RSS](https://www.omnycontent.com/d/playlist/aaea4e69-af51-495e-afc9-a9760146922b/2a195077-f014-41d2-8313-ab190186b4c2/277bcd5c-0a05-4c14-8ba6-ab190186b4d5/podcast.rss) | all, podcasts |
| [Hacking Humans](https://thecyberwire.com/podcasts/hacking-humans) | Podcast. | Podcasts | [RSS](https://feeds.megaphone.fm/hacking-humans) | all, podcasts |
| [Hanselminutes with Scott Hanselman](https://www.hanselminutes.com) | Podcast. | Podcasts | [RSS](https://feeds.simplecast.com/gvtxUiIf) | all, podcasts, top200 |
| [Invest Like the Best with Patrick O'Shaughnessy](https://colossus.com/) | Podcast. | Podcasts | [RSS](https://investlikethebest.libsyn.com/rss) | all, podcasts, top200 |
| [Invisibilia](https://www.npr.org/podcasts/510307/invisibilia) | Podcast. | Podcasts | [RSS](https://feeds.npr.org/510307/podcast.xml) | all, podcasts |
| [Planet Money](https://www.npr.org/podcasts/510289/planet-money) | Podcast. | Podcasts | [RSS](https://feeds.npr.org/510289/podcast.xml) | all, podcasts |
| [Reply All](http://gimletmedia.com/shows/reply-all) | Podcast. | Podcasts | [RSS](https://feeds.megaphone.fm/replyall) | all, podcasts |
| [The Cynical Developer](https://cynical.dev/) | Podcast. | Podcasts | [RSS](https://cynicaldeveloper.com/feed/podcast) | all, podcasts |
| [The Startup Junkies Podcast](https://www.startupjunkie.org/podcast) | Podcast. | Podcasts | [RSS](https://startupjunkie.libsyn.com/rss) | all, podcasts |
| [The Vergecast](https://www.theverge.com/the-vergecast) | Podcast. | Podcasts | [RSS](https://feeds.megaphone.fm/vergecast) | all, podcasts |
| [Throughline](https://www.npr.org/podcasts/510333/throughline) | Podcast. | Podcasts | [RSS](https://feeds.npr.org/510333/podcast.xml) | all, podcasts |
| [TIANYU2FM — 对谈未知领域](https://www.xiaoyuzhoufm.com/podcast/5f22729f9504bbdb77253e46) | Podcast. | Podcasts | [RSS](https://rsshub.xiaowuaiblog.com/xiaoyuzhou/podcast/5f22729f9504bbdb77253e46) | all, chinese, podcasts |
| [What's Next｜科技早知道](https://www.xiaoyuzhoufm.com/podcast/5e74b52c418a84a046ecaceb) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e74b52c418a84a046ecaceb) | all, chinese, podcasts, top200 |
| [一席](https://www.xiaoyuzhoufm.com/podcast/5e285326418a84a04627343f) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e285326418a84a04627343f) | all, chinese, podcasts |
| [三五环](https://www.xiaoyuzhoufm.com/podcast/5e280fab418a84a0461faa3c) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e280fab418a84a0461faa3c) | all, chinese, podcasts |
| [不合时宜](https://www.xiaoyuzhoufm.com/podcast/5e280fb8418a84a0461fd076) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e280fb8418a84a0461fd076) | all, chinese, podcasts |
| [东亚观察局](https://www.xiaoyuzhoufm.com/podcast/5e9a4e25418a84a046bc6156) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e9a4e25418a84a046bc6156) | all, chinese, podcasts |
| [东腔西调](https://www.xiaoyuzhoufm.com/podcast/5f72b66083c34e85dd14fde9) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5f72b66083c34e85dd14fde9) | all, chinese, podcasts |
| [乱翻书](https://www.xiaoyuzhoufm.com/podcast/61358d971c5d56efe5bcb5d2) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/61358d971c5d56efe5bcb5d2) | all, chinese, podcasts |
| [人民公园说AI](https://www.xiaoyuzhoufm.com/podcast/65257ff6e8ce9deaf70a65e9) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/65257ff6e8ce9deaf70a65e9) | ai, all, chinese, podcasts |
| [保持偏见](https://www.xiaoyuzhoufm.com/podcast/663e3c95af1e22bb157dcee3) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/663e3c95af1e22bb157dcee3) | all, chinese, podcasts |
| [信号与噪声](https://www.xiaoyuzhoufm.com/podcast/6819d5a7e37664602a344e0e) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/6819d5a7e37664602a344e0e) | ai, all, chinese, podcasts |
| [凹凸电波](https://www.xiaoyuzhoufm.com/podcast/5e2839ca418a84a0462431b7) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e2839ca418a84a0462431b7) | all, chinese, podcasts |
| [十字路口Crossing — Podcast](https://www.xiaoyuzhoufm.com/podcast/60502e253c92d4f62c2a9577) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/60502e253c92d4f62c2a9577) | ai, all, chinese, podcasts |
| [半拿铁 \| 商业沉浮录](https://www.xiaoyuzhoufm.com/podcast/62382c1103bea1ebfffa1c00) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/62382c1103bea1ebfffa1c00) | all, chinese, podcasts, top200 |
| [卫诗婕｜漫谈Light the Star](https://www.xiaoyuzhoufm.com/podcast/6627fda4b56459544087d86a) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/6627fda4b56459544087d86a) | all, chinese, podcasts |
| [商业就是这样](https://www.xiaoyuzhoufm.com/podcast/6022a180ef5fdaddc30bb101) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/6022a180ef5fdaddc30bb101) | all, chinese, podcasts |
| [声东击西](https://www.xiaoyuzhoufm.com/podcast/5e2831ed418a84a046231c00) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e2831ed418a84a046231c00) | all, chinese, podcasts |
| [声动早咖啡](https://www.xiaoyuzhoufm.com/podcast/60de7c003dd577b40d5a40f3) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/60de7c003dd577b40d5a40f3) | all, chinese, podcasts, top200 |
| [天真不天真](https://www.xiaoyuzhoufm.com/podcast/65cef9e3cace72dff8d98de3) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/65cef9e3cace72dff8d98de3) | all, chinese, podcasts |
| [屠龙之术](https://www.xiaoyuzhoufm.com/podcast/6507bc165c88d2412626b401) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/6507bc165c88d2412626b401) | all, chinese, podcasts |
| [岩中花述](https://www.xiaoyuzhoufm.com/podcast/625635587bfca4e73e990703) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/625635587bfca4e73e990703) | all, chinese, podcasts |
| [开始连接 LinkStart](https://www.xiaoyuzhoufm.com/podcast/63ff0da51b1faf8a0b70b337) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/63ff0da51b1faf8a0b70b337) | all, chinese, podcasts |
| [张小珺Jùn｜商业访谈录](https://www.xiaoyuzhoufm.com/podcast/626b46ea9cbbf0451cf5a962) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/626b46ea9cbbf0451cf5a962) | all, chinese, podcasts |
| [忽左忽右](https://www.xiaoyuzhoufm.com/podcast/5e4ee557418a84a0466737b7) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e4ee557418a84a0466737b7) | all, chinese, podcasts, top200 |
| [慢速生长](https://www.xiaoyuzhoufm.com/podcast/668d00c38fcadceb90158ac1) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/668d00c38fcadceb90158ac1) | all, chinese, podcasts |
| [捕蛇者说](https://www.xiaoyuzhoufm.com/podcast/5e2864f7418a84a04628f2da) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e2864f7418a84a04628f2da) | all, chinese, podcasts |
| [搞钱女孩](https://www.xiaoyuzhoufm.com/podcast/63d945ece725b5378a158d29) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/63d945ece725b5378a158d29) | all, chinese, podcasts |
| [文化有限](https://www.xiaoyuzhoufm.com/podcast/5e4515bd418a84a046e2b11a) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e4515bd418a84a046e2b11a) | all, chinese, podcasts, top200 |
| [晚点聊 LateTalk](https://www.xiaoyuzhoufm.com/podcast/61933ace1b4320461e91fd55) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/61933ace1b4320461e91fd55) | all, chinese, podcasts, top200 |
| [李诞](https://www.xiaoyuzhoufm.com/podcast/65bb55f6513a776b57dedb32) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/65bb55f6513a776b57dedb32) | all, chinese, podcasts |
| [枫言枫语 — Podcast](https://www.xiaoyuzhoufm.com/podcast/5e2864f5418a84a04628e249) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e2864f5418a84a04628e249) | all, chinese, podcasts |
| [此话当真](https://www.xiaoyuzhoufm.com/podcast/646f194853a5e5ea1408d97c) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/646f194853a5e5ea1408d97c) | all, chinese, podcasts |
| [游荡集](https://www.xiaoyuzhoufm.com/podcast/6163ca67c8c1d14e83366b31) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/6163ca67c8c1d14e83366b31) | all, chinese, podcasts |
| [牛油果烤面包](https://www.xiaoyuzhoufm.com/podcast/5e7c8b2b418a84a046e3ecbc) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e7c8b2b418a84a046e3ecbc) | all, chinese, podcasts |
| [独树不成林](https://www.xiaoyuzhoufm.com/podcast/64acd33c7a3d479103fbd32d) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/64acd33c7a3d479103fbd32d) | all, chinese, podcasts |
| [疯投圈](https://www.xiaoyuzhoufm.com/podcast/5e280faf418a84a0461fbd39) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e280faf418a84a0461fbd39) | all, chinese, podcasts |
| [皮蛋漫游记](https://www.xiaoyuzhoufm.com/podcast/6281264ad22bcf3950c80b56) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/6281264ad22bcf3950c80b56) | all, chinese, podcasts |
| [看理想圆桌](https://www.xiaoyuzhoufm.com/podcast/5e4ff4c7418a84a046977618) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e4ff4c7418a84a046977618) | all, chinese, podcasts |
| [知行小酒馆](https://www.xiaoyuzhoufm.com/podcast/6013f9f58e2f7ee375cf4216) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/6013f9f58e2f7ee375cf4216) | all, chinese, podcasts, top200 |
| [硅谷101 — Podcast](https://www.xiaoyuzhoufm.com/podcast/5e5c52c9418a84a04625e6cc) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e5c52c9418a84a04625e6cc) | all, chinese, podcasts, top200 |
| [硬地骇客](https://www.xiaoyuzhoufm.com/podcast/640ee2438be5d40013fe4a87) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/640ee2438be5d40013fe4a87) | all, chinese, podcasts |
| [科技乱炖](https://www.xiaoyuzhoufm.com/podcast/5e4243cd418a84a0469573fb) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e4243cd418a84a0469573fb) | all, chinese, podcasts |
| [第一财经](https://www.xiaoyuzhoufm.com/podcast/64c75555e8176c3ff81de98c) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/64c75555e8176c3ff81de98c) | all, chinese, podcasts |
| [纵横四海](https://www.xiaoyuzhoufm.com/podcast/62694abdb221dd5908417d1e) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/62694abdb221dd5908417d1e) | all, chinese, podcasts |
| [罗永浩的十字路口](https://www.xiaoyuzhoufm.com/podcast/68981df29e7bcd326eb91d88) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/68981df29e7bcd326eb91d88) | all, chinese, podcasts |
| [肥话连篇](https://www.xiaoyuzhoufm.com/podcast/61d50d72ee197a3aac3dac42) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/61d50d72ee197a3aac3dac42) | all, chinese, podcasts |
| [自习室 STUDY ROOM](https://www.xiaoyuzhoufm.com/podcast/65a5fb7540d4ef949c0140ac) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/65a5fb7540d4ef949c0140ac) | all, chinese, podcasts |
| [自我进化论](https://www.xiaoyuzhoufm.com/podcast/5e5de5cb418a84a0467beb90) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e5de5cb418a84a0467beb90) | all, chinese, podcasts |
| [蒋方舟·一寸](https://www.xiaoyuzhoufm.com/podcast/67c7eeb07ac3e30992e75a2f) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/67c7eeb07ac3e30992e75a2f) | all, chinese, podcasts |
| [诗梳风](https://www.xiaoyuzhoufm.com/podcast/696496f4db4738160d5fabde) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/696496f4db4738160d5fabde) | all, chinese, podcasts |
| [谭立人](https://www.xiaoyuzhoufm.com/podcast/65a2d0f07242f9fc1c1df60a) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/65a2d0f07242f9fc1c1df60a) | all, chinese, podcasts |
| [起朱楼宴宾客](https://www.xiaoyuzhoufm.com/podcast/61dd99a47b29652ff572257b) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/61dd99a47b29652ff572257b) | all, chinese, podcasts |
| [跨国串门儿计划](https://www.xiaoyuzhoufm.com/podcast/670f3da40d2f24f28978736f) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/670f3da40d2f24f28978736f) | ai, all, chinese, podcasts |
| [随机波动StochasticVolatility](https://www.xiaoyuzhoufm.com/podcast/5e7cc741418a84a046b0c2bd) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/5e7cc741418a84a046b0c2bd) | all, chinese, podcasts |
| [面基](https://www.xiaoyuzhoufm.com/podcast/6388760f22567e8ea6ad070f) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/6388760f22567e8ea6ad070f) | all, chinese, podcasts |
| [高能量](https://www.xiaoyuzhoufm.com/podcast/62c6ae08c4eaa82b112b9c84) | Podcast. | Podcasts | [RSS](https://rsshub.bestblogs.dev/xiaoyuzhou/podcast/62c6ae08c4eaa82b112b9c84) | all, chinese, podcasts |

</details>

<!-- SOURCE_APPENDIX_END -->

## Reference projects

This project publishes public feed endpoints and original catalog metadata, not article copies. See [SOURCES.md](SOURCES.md) and [NOTICE.md](NOTICE.md) for provenance and rights.

- [chinese-independent-blogs](https://github.com/timqian/chinese-independent-blogs)
- [Wechat2RSS](https://wechat2rss.xlab.app/list/all)
- [RSSHub](https://github.com/DIYgod/RSSHub)
- [awesome-rss-feeds](https://github.com/plenaryapp/awesome-rss-feeds)
- [awesome-rsshub-routes](https://github.com/JackyST0/awesome-rsshub-routes)
