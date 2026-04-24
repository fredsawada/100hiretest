# Portfolio Project – YouTube Content Strategy for B2B SaaS

Thank you for the opportunity.

This repository is part of my application for the Junior Growth Marketing Specialist role. I chose **Topic 5: YouTube content strategy for B2B SaaS**.

## Why I Chose This Topic

I chose YouTube content strategy for B2B SaaS because SaaS buyers often research problems, tools, and vendors before speaking with sales. YouTube can support that buying journey by making complex products easier to understand through tutorials, product-led education, founder-led content, webinars, interviews, and video podcasts.

For a B2B SaaS company, YouTube can help:

- educate buyers before they enter a sales call,
- create demand for the product category,
- build trust with real operators and subject-matter experts,
- repurpose long-form video into LinkedIn, newsletter, blog, and sales assets,
- support search discovery for high-intent problems.

## Research Goal

The goal of this project is to collect recent content from 10 high-signal experts and identify repeatable patterns that could later become a practical playbook for B2B SaaS YouTube strategy.

I am looking for answers to questions like:

- What types of YouTube videos work best for B2B SaaS?
- How do strong B2B SaaS teams choose topics?
- How should YouTube connect to pipeline, demos, trust, and sales conversations?
- How do teams repurpose YouTube content into LinkedIn posts, newsletters, and sales enablement?
- Which metrics matter beyond views and subscribers?

## Selected Experts

| # | Expert | Why This Expert Is Relevant |
|---|---|---|
| 1 | Sam Oh | Helped build Ahrefs' B2B SaaS YouTube engine and teaches YouTube for B2B. |
| 2 | Sarah Nitz | Focuses specifically on YouTube growth and SEO for B2B SaaS founders. |
| 3 | Kyle Denhoff | Leads/has led B2B media and content strategy at HubSpot across YouTube, newsletters, podcasts, and owned media. |
| 4 | Chris Savage | CEO/co-founder of Wistia, a company focused on business video, brand shows, and video analytics. |
| 5 | Tyler Lessard | Long-time B2B video strategist connected to Vidyard, video selling, demand generation, and buyer education. |
| 6 | Ian Faison | Founder of Caspian Studios, focused on B2B video podcasts, serialized content, and repeatable show formats. |
| 7 | Jamar Diggs | Teaches how to use YouTube as a business and lead-generation tool, not just a creator platform. |
| 8 | Justin Simon | Focuses on content distribution and repurposing, which is essential for making YouTube useful in B2B. |
| 9 | Devin Reed | Former B2B SaaS content leader at Gong and Clari; useful for connecting long-form content to business outcomes. |
| 10 | T.K. Kader | Strong example of founder-led SaaS content using YouTube to teach GTM and growth strategy. |

The full source list is in [`research/sources.md`](research/sources.md).

## Repository Structure

```text
research/
  sources.md
  linkedin-posts/
    sam-oh/
    sarah-nitz/
    kyle-denhoff/
    chris-savage/
    tyler-lessard/
    ian-faison/
    jamar-diggs/
    justin-simon/
    devin-reed/
    tk-kader/
  youtube-transcripts/
    video-list.csv
    *.md
  other/
    methodology.md
    synthesis-notes.md
    collection-log.md
    claude-codex-prompts.md
    git-commands.md
scripts/
  fetch_youtube_transcripts.py
requirements.txt
README.md
```

## Collection Method

### YouTube / Video Content

I prepared a video collection list in:

```text
research/youtube-transcripts/video-list.csv
```

I also added a transcript helper script:

```text
scripts/fetch_youtube_transcripts.py
```

The script uses the free `youtube-transcript-api` package when a YouTube video has captions available. If the free method fails for a video, I will manually collect the transcript or notes from the source page and paste them into the matching Markdown file.

### LinkedIn Posts

LinkedIn posts will be collected manually because LinkedIn often requires login and blocks scraping. For each expert, I created a folder under:

```text
research/linkedin-posts/
```

Each expert folder has a template for collecting 3-5 recent posts with:

- post URL,
- date,
- summary,
- key takeaway,
- relevance to B2B SaaS YouTube strategy.

## Initial Research Themes

Early patterns I am tracking:

1. **B2B SaaS YouTube should be buyer-led, not company-led.** Strong videos answer real questions buyers already have.
2. **Product-led education works well when it teaches the problem, not only the tool.** Strong SaaS channels connect education to use cases naturally.
3. **YouTube is not only a hosting platform.** It can work as search, education, trust-building, and demand creation.
4. **Series and repeatable formats beat random posting.** Many experts emphasize consistent shows, topic buckets, and serial content.
5. **Distribution matters as much as production.** Strong videos should become LinkedIn posts, newsletter ideas, blog content, clips, and sales enablement assets.
6. **Metrics should connect to business outcomes.** Useful signals include qualified leads, demo mentions, customer conversations, watch time, and ICP engagement.

## Current Status

- [x] Repository created
- [x] Topic selected
- [x] Research structure prepared
- [x] 10 high-signal experts selected
- [x] Source list drafted
- [x] YouTube transcript collection list prepared
- [ ] YouTube transcripts collected and cleaned
- [ ] LinkedIn posts manually collected
- [ ] Final synthesis expanded from notes

## Tools Used / Planned

- Cursor IDE
- Claude Code extension
- Codex extension
- GitHub
- YouTube transcript collection script
- Manual LinkedIn review
- Markdown source organization

## Repository Link

[https://github.com/fredsawada/100hiretest.git](https://github.com/fredsawada/100hiretest.git)
