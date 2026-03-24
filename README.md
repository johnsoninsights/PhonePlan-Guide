# PhonePlan Guide

An interactive phone and internet plan comparison tool that helps users find the right service plan based on their needs. Features animated plan cards, auto-pay pricing toggles, and guided quizzes that recommend a plan based on user answers.

## Live Demo

[View on Vercel](https://phone-plan-guide.vercel.app/)

## Features

- **Plan Comparison** — Side-by-side comparison of 3 mobile plans (Essential, Plus, Premium) and 3 internet speed tiers (300 Mbps, 500 Mbps, 1 Gbps)
- **Service Toggle** — Switch between Mobile and Internet plan views
- **Auto-Pay Pricing** — Toggle to show discounted pricing with auto-pay enrolled
- **3D Card Flip** — Click plan cards to reveal additional plan details on the back
- **Interactive Quizzes** — 3-step guided quizzes for both mobile and internet plans that score answers and recommend the best plan
- **Promotional Offers** — Expandable sections highlighting device deals and credits
- **Fully Responsive** — Works across desktop and mobile screen sizes

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox, CSS Variables, keyframe animations, 3D transforms)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)

No build tools, no frameworks, no dependencies — open `index.html` directly in a browser.

## Getting Started

```bash
git clone https://github.com/johnsoninsights/PhonePlan-Guide.git
cd PhonePlan-Guide
open index.html
```

## Project Structure

```
PhonePlan-Guide/
├── index.html   # All HTML, CSS, and JavaScript in a single file
└── LICENSE      # MIT License
```

## How the Quiz Works

Each quiz walks the user through 3 questions and assigns a score to each answer. At the end, the score maps to a recommended plan, which is highlighted and scrolled into view.

**Mobile Quiz questions:**
1. How do you primarily use data? (Light / Moderate / Heavy)
2. Do you frequently travel internationally? (Rarely / Sometimes / Frequently)
3. What matters most when watching video? (Standard / HD / 4K)

**Internet Quiz questions:**
1. How many devices connect to your Wi-Fi? (1–5 / 6–20 / 20+)
2. What are your primary online activities? (Basic / Streaming & WFH / Gaming & 4K)
3. How important is whole-home coverage? (Standard / Important / Crucial)

## License

MIT License — see [LICENSE](LICENSE) for details.
