# 100Hires Portfolio Project

## Tools Installed
- Cursor IDE
- Claude Code extension (logged in with Anthropic account)
- Codex extension by OpenAI (logged in)

## Steps Completed
1. Installed Cursor IDE from cursor.com
2. Installed Claude Code extension via Cursor Extensions marketplace
3. Installed Codex (OpenAI) extension via Cursor Extensions marketplace
4. Created a public GitHub repository named 100hires-portfolio
5. Downloaded the repository as ZIP and opened it in Cursor

## Issues Encountered and How I Solved Them
- Git was not installed on the computer, so I could not use the `git clone` command. I solved this by downloading the repository as a ZIP file directly from GitHub and opening the extracted folder in Cursor.

## Notes
This is the first step of the 100Hires portfolio project process. Ready for the next step.

---

## Research Project — AI-Powered SEO Content Production

### Topic
AI-Powered SEO Content Production

### What I Collected
This research project involved collecting and organizing content from 10 leading experts on AI-powered SEO. For each expert I gathered:
- YouTube video transcripts (2 per expert, 20 total) extracted via Supadata API
- LinkedIn posts (1-2 per expert, 8 experts with LinkedIn presence)
- A structured sources file with expert profiles, links, and annotations
- A key studies and data points file compiling the most important research cited across all expert content

### Experts Selected and Why

**1. Ahrefs** — Selected for their original data-driven research on AI search behavior. They publish studies based on hundreds of thousands of data points that the entire SEO industry references.

**2. Nathan Gotch** — Hands-on SEO practitioner with 15+ years of experience and author of AI SEO for Dummies. Shares real workflows and systems, not theory.

**3. Neil Patel** — Co-founder of NP Digital, running SEO for hundreds of companies including Fortune 500s. Provides macro-level data on how AI is reshaping search at scale.

**4. Matt Diggity** — Founder of The Search Initiative. Known for running controlled AI SEO experiments and publishing detailed case studies with real client results.

**5. Exposure Ninja** — UK-based agency, pioneers in AI search optimization. Publishes practical frameworks based on real client campaigns across international brands.

**6. Surfer Academy** — Educational channel from Surfer SEO. Published original research on 400,000+ AI Overview searches. Bridges content optimization with AI search strategy.

**7. Edward Sturm** — Daily digital marketing podcaster (1,000+ consecutive episodes). Covers AI content production and LLM visibility from a hands-on practitioner perspective.

**8. Eric Siu** — CEO of Single Grain and co-host of Marketing School. Brings a business operator's perspective on AI SEO at scale using Claude Code, MCPs, and agentic systems.

**9. Jesse Cunningham** — SEO practitioner focused on AI-powered microsites and n8n automation workflows. Builds and shares actual SEO agents and ranking systems publicly.

**10. Tim The SEO Guru** — Daily SEO content creator specializing in Claude-powered SEO workflows. The most Claude-specific SEO channel available, covering automation and ranking in depth.

### Repository Structure

    research/
    ├── sources.md
    ├── linkedin-posts/
    │   ├── ahrefs.md
    │   ├── nathan-gotch.md
    │   ├── neil-patel.md
    │   ├── matt-diggity.md
    │   ├── exposure-ninja.md
    │   ├── surfer-academy.md
    │   ├── edward-sturm.md
    │   └── eric-siu.md
    ├── youtube-transcripts/
    │   ├── ahrefs_seo-in-2026.md
    │   ├── ahrefs_aeo-course-3-1.md
    │   ├── nathan-gotch_ai-seo-every-day.md
    │   ├── nathan-gotch_seo-with-ai-2026.md
    │   ├── neil-patel_ai-seo-changing-everything-2026.md
    │   ├── neil-patel_old-seo-collapsing.md
    │   ├── matt-diggity_ai-seo-chatgpt-google.md
    │   ├── matt-diggity_chatgpt-prompt-breaks-google.md
    │   ├── exposure-ninja_dominate-ai-search-2026.md
    │   ├── exposure-ninja_what-is-ai-search-optimisation.md
    │   ├── surfer-academy_dominate-ai-search-2026.md
    │   ├── surfer-academy_write-seo-content-ranks.md
    │   ├── edward-sturm_ai-llm-visibility-guide.md
    │   ├── edward-sturm_ai-generated-seo-blog-content.md
    │   ├── eric-siu_ai-seo-right-way-2026.md
    │   ├── eric-siu_ai-seo-100x-business.md
    │   ├── jesse-cunningham_6-seo-n8n-agents.md
    │   ├── jesse-cunningham_ranking-ai-overviews-autopilot.md
    │   ├── tim-seo-guru_1000-hours-claude-seo.md
    │   └── tim-seo-guru_claude-code-seo-rank-1.md
    └── other/
        └── key-studies-and-data.md

### Tools Used
- **Supadata API** — Used to extract YouTube transcripts automatically via MCP integration with Claude
- **YouTube** — Source platform for identifying and selecting expert videos
- **LinkedIn** — Manual collection of posts from each expert's profile
- **GitHub** — Repository structure, version control, and regular commits throughout the process
