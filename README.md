# Portfolio site

> My PM portfolio, built and documented like a product. Live at **https://lakshmiprasanna93.github.io**

**Status:** 🟢 Live · **Built:** Nov 2026

## 1. Problem
- Hiring managers and clients skim a PM's profile in under a minute. A resume can't show how I make decisions.
- GitHub is where my AI builds live, so my portfolio should live there too.

## 2. Goal & success metrics
| Metric | Target |
|---|---|
| Time to understand "who / what / proof" | < 30 seconds (hero + stats) |
| Accessibility | WCAG 2.1 AA (contrast, keyboard navigation, skip link, reduced motion) |
| Page weight | Single HTML file, no JS, no build step |

## 3. Key decisions & trade-offs
| Decision | Options | Why |
|---|---|---|
| Hosting | GitHub Pages vs Netlify/Notion | Shows up on my GitHub profile, free, versioned |
| Stack | React/Next vs plain HTML/CSS | No build step, loads instantly, anyone can edit it |
| Content | Full case studies vs anonymized summaries | Protects employer confidentiality while still showing how I decide |
| Dark mode | Toggle vs system preference | Zero JS; follows the reader's OS setting |

## 4. What's next
- Separate case-study pages as builds accumulate
- Custom domain
- Lightweight analytics (privacy-friendly)
