# Portfolio — Project Record

## Project and current status
- **Goal:** a personal website that helps a reader understand my direction and inspect my work.
- **Direction:** AI research (long-term goal). Next step: build research experience through Python/ML projects and undergraduate research. Customer-facing AI delivery is my backup path.
- **Repository:** https://github.com/ac2928/portfolio
- **Current stage:** Review 2 (Draft). Live draft: https://ac2928.github.io/portfolio/ with two layouts (A and B) from the same content. Checks run: keyboard, phone and all links (see section 2).
- Career research (three employer postings and my reflection) is submitted privately in Canvas.

## 1 · Plan

### Reader
| | A: NJIT professor / research lab lead | B: Tech internship recruiter |
|---|---|---|
| Who | Deciding whether to take me on for undergraduate research | Screening students for AI/FDE-style internships |
| Wants | Tested Python code, curiosity about AI, clear explanation of how I check my work | Working projects, team role, résumé and profiles in a few clicks |

**Primary reader: A**, because it matches my AI research direction and my next learning step. B stays a secondary reader.

### Two design directions (same intro, projects and contact action)
| | A: Research notebook | B: Project dashboard |
|---|---|---|
| Feel | Calm, academic, lots of white space | Modern, quick to scan |
| Layout | One column like a short paper: intro → project write-ups → contact | Grid of project cards (title, one line, links to demo/code/tests) |
| Real reference | distill.pub | github.com profile with pinned repository cards |
| What I adapted | Wide readable text, clear headings, figures beside explanations | Small cards that each show a project and link straight to its code |

**Current lean: B**, because a professor can reach my code and tests fastest. Both will be compared before I choose the final version.

### User stories
| # | Story | Acceptance check |
|---|---|---|
| 1 | **Find my best technical work:** As a professor, I can find my individual project and its tests within a few clicks. | From the home page, one project card links to the live demo, the GitHub repo and the test results. |
| 2 | **Understand my role in the team:** As a professor, I can tell what I built in the group project versus my partner. | The group case study names my parts (with links to my PRs) separately from my partner's. |
| 3 | **See how I think:** As a professor, I can read a short explanation of a decision I made and how I checked it. | Each case study has "problem → my decision → how I tested it → what I learned." |
| 4 | **Contact me:** As a professor, I can find my résumé, GitHub, LinkedIn and a professional way to reach me. | All links work, the résumé opens, and everything is reachable on a phone and with the keyboard. |

### Honesty
No invented claims, testimonials or experience. Planned features and unfinished projects will be labeled as planned.

### Help received
Claude (chat assistant) explained the assignment and helped organize my decisions; I chose the direction, reader, designs and stories.

## 2 · Draft (Review 2)

### What I built
- One live page: https://ac2928.github.io/portfolio/ (code: `index.html`, `style.css`).
- Content: intro and working direction, two case studies (Sneaky Robot RPS = individual; Bench & Bolt = group, labeled "in progress"), four more projects, résumé PDF, and contact links (email, GitHub, LinkedIn, this repo).
- Résumé on the site is a version without my phone number.
- Unfinished work is labeled "in progress."

### Two presentation options (same content, only the CSS changes)
| | A · Research notebook | B · Project dashboard |
|---|---|---|
| Layout | One calm column, serif headings, like a short paper | Cards in a grid, quick to scan |
| Reference | distill.pub | GitHub profile pinned repo cards |
| Open directly | https://ac2928.github.io/portfolio/?layout=a | https://ac2928.github.io/portfolio/?layout=b |
| Strength | Easy to read the case-study reasoning in order | A professor sees all projects and links at once |
| Weakness | Projects are further down the page | Long case studies feel cramped in cards |

**Current choice: B (provisional).** My reader (a professor) can reach my code and tests fastest. The tradeoff is that long case studies read better in A. I'll confirm after a classmate tries both.

### Checks I actually ran
| Check | Result |
|---|---|
| Keyboard (Chrome): Tab through the page | Visible focus outline moved through every link and button |
| Keyboard: Enter on "A · Research notebook" | Layout switched |
| Phone: both layouts | Easy to read, links easy to tap, no sideways scrolling |
| Every link (case studies, 4 projects, résumé PDF, GitHub, LinkedIn, email) | All worked |

**Not checked yet (planned):** the classmate task ("find my individual project, tell me what I did in the group project, then find my code, résumé and profiles"), screen reader, Safari keyboard settings.

### Stories status
| # | Story | Status |
|---|---|---|
| 1 | Find my best technical work | Sneaky Robot card links to code, PR and tests. No live demo yet (the game runs locally) |
| 2 | Understand my role in the team | My part is named separately from Nandish's. No PR links yet (code not built) |
| 3 | See how I think | Sneaky Robot has problem → decision → how I checked → what I learned |
| 4 | Contact me | Résumé, GitHub, LinkedIn and email all work on phone and keyboard |

### Help received
- Claude drafted the page code from my content and decisions (reader, layouts, intro in my words, résumé version). I ran the keyboard, phone and link checks myself.