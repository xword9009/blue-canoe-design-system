# Blue-Canoe Design Principles (v20250314.1)

## Purpose
The Blue-Canoe Design System ensures that all user-facing materials (web, email, documents, dashboards) are consistent, professional, and rooted in natural visual harmony using the Golden Ratio (1.618). It is built for clarity, simplicity, and flexibility.

## Core Principles
1. **Golden Ratio (1.618)** drives all spacing, sizing, and layout.
2. **Inter font** is the default, with system fallbacks.
3. **Modular CSS system** for future theming and flexibility.
4. **Consistency across all platforms.**
5. **Version-controlled and documented.**

## How to Use
1. **Include blue-canoe-base.css in every project.**
2. **Stick to defined classes and structure for buttons, cards, forms, layouts.**
3. **Use utility spacing classes for quick adjustments.**

## Versioning
- Every change is tracked with a version.
- Current version: `v20250314.1`.
- Format: `vYYYYMMDD.X` for clarity and tracking.

## Extension
- Add themes (color/font variations) without changing base.
- Planned dark mode, print themes, and branding variations.

## Do Not Change Directly
| Do Not Change                     | Why                                   |
|-----------------------------------|---------------------------------------|
| `blue-canoe-base.css` without versioning | Ensures consistency and tracking.   |
| Core variables unless updating system | Breaks the design logic.            |

## Future Extensions
- Dark mode, custom themes.
- Email templates, printable documents.
- Admin panel styling (Usermin, Roundcube).

---
*Authored: Blue-Canoe | Date: 2025-03-14*
