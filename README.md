# Chris Young Voice Plugin

Write content in Chris Young's authentic voice using real source material.

## What it does

This plugin gives Claude the ability to write blog posts, articles, and content in Chris Young's voice — the James Beard Award-winning co-author of *Modernist Cuisine*, former Head Chef of R&D at The Fat Duck, and founder of Combustion Inc.

It follows a **source-first workflow**: before writing anything, Claude searches for real material (YouTube transcripts, blog posts, product specs) and grounds every story, quote, and data point in verified sources. No fabricated anecdotes, no made-up quotes.

## Components

| Component | Name | Purpose |
|-----------|------|---------|
| Skill | `chris-young` | Voice guidelines, editorial rules, source-first workflow, product reference |

## Triggers

The skill activates when you ask Claude to:

- Write blog posts, articles, or content about BBQ, grilling, smoking, meat science, cooking, or food science in Chris's voice
- - Work with transcripts or notes for Chris's voice
  - - Reference Combustion Inc. products
    - - Use the `/chris-young` command
     
      - ## Connected tools
     
      - For best results, connect these in your Cowork session:
     
      - - **Google Drive** — to search the YouTube transcript library (folder ID: `1bDSWBoc0Gww-SoefJjL4K47FO-GZkYJ0`)
        - - **Web search** — to pull content from chrisyoungcooks.com and combustion.inc
         
          - The skill works without these tools but produces better content when it can access real source material.
         
          - ## Key principles
         
          - 1. **Never fabricate personal stories** — every anecdote must come from source material
            2. 2. **Lead with the payoff** — open with the result and the claim, not scene-setting
               3. 3. **Weave science into cooking** — no front-loaded theory sections
                  4. 4. **Products as instruments** — Combustion products appear naturally in experiments, not as ads
                     5. 5. **Cut aggressively** — if it doesn't advance understanding, it doesn't belong
                       
                        6. ## Usage
                       
                        7. Just ask Claude to write content in Chris's voice. Examples:
                       
                        8. - "Write a blog post about reverse searing steaks"
                           - - "Here's a transcript from Chris's latest video — turn it into a blog post"
                             - - "Write a TESTED experiment piece about cooking brisket from frozen"
                              
                               - ## Installation
                              
                               - Install by opening the `.plugin` file in Claude Desktop (Cowork mode).
