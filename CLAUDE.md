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

## Color Palette (Design System Tokens — gs-* Tailwind classes)
| Token              | Hex       | Role                                  |
|---|---|---|
| gs-primary         | #1F3A5F   | Navy — headings, footer bg, trust     |
| gs-secondary       | #2FA4A9   | Teal — primary CTAs, interactive      |
| gs-secondary-dk    | #238E93   | Teal hover state                      |
| gs-accent          | #5BC0EB   | Sky blue — icons, highlights          |
| gs-bg              | #F7F9FB   | Off-white — default page background   |
| gs-warm            | #F4EDE4   | Warm cream — Features section bg      |
| gs-teal-tint       | #EAF5F6   | Light teal — eyebrow badges, F6 card  |
| gs-teal-border     | #B3DDE0   | Teal border                           |
| gs-warm-border     | #E5D9CE   | Warm card border                      |
| gs-body            | #3D556E   | Body text — dark blue-gray            |
| gs-muted           | #6E8A9E   | Muted / helper text                   |
| gs-border          | #D6E4EE   | Default borders                       |

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
