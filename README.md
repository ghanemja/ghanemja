# Hi, I'm Janelle Ghanem

Builder of AI-native tools across research, education, and productivity. This is my portfolio hub — each card below links to a live demo and source.

[![GitHub Profile](https://img.shields.io/badge/GitHub-ghanemja-181717?logo=github)](https://github.com/ghanemja)
[![Hugging Face](https://img.shields.io/badge/HF-jang0294-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/jang0294)
[![Portfolio Site](https://img.shields.io/badge/Site-ghanemja.github.io-1f6feb)](https://ghanemja.github.io)

---

## Live Projects

All backends are deployed as Docker Spaces on Hugging Face (`jang0294/<name>`). Frontends are deployed on Netlify. They share a single auth + env pattern — see [brain-university/PORTFOLIO_ENV.md](https://github.com/ghanemja/brain-university/blob/main/PORTFOLIO_ENV.md).

### Brain University
AI tutor + arXiv video render + podcast studio. Multiprocess SSE rendering, local Gemma backend, first-time tutorial walkthrough.

[![Backend](https://img.shields.io/badge/Backend-HF%20Space-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/spaces/jang0294/brain-university)
[![Frontend](https://img.shields.io/badge/Frontend-Netlify-00C7B7?logo=netlify&logoColor=white)](https://brain-university.netlify.app)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?logo=github)](https://github.com/ghanemja/brain-university)

### CharterScope
Analyze any company / charter / org against a configurable rubric. CLI + web wrapper.

[![Backend](https://img.shields.io/badge/Backend-HF%20Space-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/spaces/jang0294/charterscope)
[![Frontend](https://img.shields.io/badge/Frontend-Netlify-00C7B7?logo=netlify&logoColor=white)](https://charterscope.netlify.app)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?logo=github)](https://github.com/ghanemja/charterscope)

### Inbox Zero Board
Kanban-style triage view for your inbox. Drag-drop, snooze, batch archive.

[![Frontend](https://img.shields.io/badge/Frontend-Netlify-00C7B7?logo=netlify&logoColor=white)](https://inbox-zero-board.netlify.app)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?logo=github)](https://github.com/ghanemja/inbox-zero-board)

### YarnFlow (crochet)
Pattern visualizer and stitch counter for crochet projects.

[![Frontend](https://img.shields.io/badge/Frontend-Netlify-00C7B7?logo=netlify&logoColor=white)](https://yarnflow.netlify.app)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?logo=github)](https://github.com/ghanemja/crochet)

### Stencil
Reusable Claude skill for templated content generation. Not a hosted app — install as a Claude skill.

[![Source](https://img.shields.io/badge/Source-GitHub-181717?logo=github)](https://github.com/ghanemja/stencil)

---

## In Progress / Private

| Project | What it is |
| --- | --- |
| cadme | Resume + portfolio generator |
| brainchamp | Spaced-repetition layer on top of brain-university |
| pptgpt | Slide-deck generation from prompts |
| claudeHotline | Voice interface to Claude |

These are private while the APIs settle. Reach out if you want a walkthrough.

---

## Stack

- **Backends:** FastAPI + Docker on HF Spaces, shared bearer-token auth middleware
- **Frontends:** Netlify, vanilla JS / React via CDN, Tailwind
- **AI:** Anthropic Claude, OpenAI, local Gemma for offline demos
- **Infra:** Single shared `PORTFOLIO_ENV.md` of 9 env vars across all Spaces

---

## Contact

- Email: janghanem@gmail.com
- GitHub: [@ghanemja](https://github.com/ghanemja)
- Hugging Face: [@jang0294](https://huggingface.co/jang0294)
