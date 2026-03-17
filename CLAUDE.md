# GutSimple — Design Rules

## DO
- Light, minimal, clean, modern design — shadcn aesthetic
- Neutral palette: whites, grays, one subtle warm stone/amber accent
- Good typography hierarchy, plenty of whitespace
- Font: Inter from Google Fonts
- Mobile responsive
- Light motion: scroll animations via IntersectionObserver, smooth transitions, subtle hover

## DON'T
- NO bright saturated gradients or gradient text
- NO emoji icons (use Lucide icons)
- NO "revolutionary", "game-changing" marketing copy
- NO heavy shadows or busy patterns
- NO dark mode
- NO border-radius > rounded-2xl
- NO cramped spacing or tiny fonts (< 14px)

## Color Palette
| Role         | Tailwind Class      |
|---|---|
| Background   | bg-white            |
| Surface/Card | bg-stone-50         |
| Border       | border-stone-200    |
| Headings     | text-stone-900      |
| Body         | text-stone-700      |
| Muted        | text-stone-500      |
| Accent       | bg-amber-500 / text-amber-600 |
| Accent light | bg-amber-50 / border-amber-200 |

## Stack
- Single HTML file
- Tailwind CSS v3 CDN
- Lucide Icons CDN
- Inter font via Google Fonts

## Sections Order
1. Nav
2. Hero + CTA
3. How It Works (3 steps)
4. Features (6 cards)
5. About
6. Footer
