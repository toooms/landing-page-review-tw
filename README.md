# landing-page-review-tw

A Cowork/Claude Code skill that applies **Steve Schoger's** (Tailwind Labs / Refactoring UI) design techniques when building or reviewing landing pages in Tailwind CSS.

## What it does

When you ask Claude to design, review, or critique a landing page, this skill loads Steve's specific, opinionated techniques — not generic advice. It covers:

- **Screenshots as hero visuals** — ring opacity trick, premium shadow sizing, styled containers
- **Typography** — Inter Variable + display optical size, hero headings at 64–80px
- **Text alignment** — when to center vs. left-align (with specific rules)
- **Eyebrow labels** — monospace, uppercase, tracking-wider, gray-600
- **Buttons** — pill-shaped, ~38px tall, clean hierarchy
- **Borders** — replace solid borders with `ring-gray-950/10` opacity rings
- **Feature sections** — zigzag layout, left-aligned headings, screenshot containers
- **Logo clouds** — no title, no opacity, no extra borders
- **Pricing cards** — generous padding, ring treatment, highlighted recommended plan
- **Testimonials** — image backgrounds with dark overlay + white text
- **Decorative borders** — editorial vertical lines + full-width section dividers
- **Color strategy** — neutral gray-950 palette, let the screenshot carry color

## Install

Download `landing-page-review-tw.skill` and drag it into the Cowork plugins panel.

## Usage

Just talk naturally. The skill triggers automatically when you mention landing pages, hero sections, pricing, feature sections, or marketing pages.

```
"Review my hero section" + paste your HTML
"Design a pricing section for my SaaS tool in Tailwind"
"What's wrong with my feature section layout?"
"Build me a testimonials section that looks premium"
```

## Based on

- Steve Schoger's landing page design workflow video
- [Refactoring UI](https://refactoringui.com/) by Adam Wathan & Steve Schoger
- Steve's design tips shared via [@steveschoger](https://twitter.com/steveschoger)
