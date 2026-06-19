# Services Proposal — Cravio JO

> **Date:** June 19, 2026  
> **Status:** Proposed — awaiting client confirmation

---

## Full Services Catalog with Client Feedback

### 🚀 Phase 1 — Pre-Launch Essentials

| # | Service | Effort | Impact | Client Decision |
|---|---|---|---|---|
| 1 | **Landing Page + Coming Soon** | Low | High | ✅ **WINNING CARD** — Do immediately |
| 2 | **WhatsApp Business Catalog** | Low | High | ⏳ **DEFER to last** — Need to understand it better |
| 3 | **Google Business Profile Setup** | Low | High | ✅ **WINNING CARD** — Do immediately |
| 4 | **Brand Design System Documentation** | Medium | Medium | ✅ **Do it** — BUT must be built from existing business data (Instagram, actual brand assets), NOT from the old menu.html mockup |
| 5 | **Instagram Content Strategy Kit** | Low | Medium | ❌ **Skip** — They have their own team handling this |

### 🛒 Phase 2 — Launch Core

| # | Service | Effort | Impact | Client Decision |
|---|---|---|---|---|
| 6 | **Online Ordering Platform** | High | High | *(Not explicitly addressed — needs discussion)* |
| 7 | **Digital Menu with Arabic RTL** | Medium | High | ✅ **WINNING CARD** — Do immediately |
| 8 | **Custom Cake Order Builder** | High | Medium | 🔀 **Merge** — Can be part of the landing page or the digital menu, not a standalone service |
| 9 | **WhatsApp Order Automation** | High | High | ⏳ **DEFER to last** — "It might need some work" |
| 10 | **Payment Gateway Integration** | Medium | High | ❌ **Skip** — Talabat handles payment processing |
| 11 | **Delivery Zone Calculator** | Medium | Medium | ❌ **Skip** — Talabat handles delivery logistics |

### 📈 Phase 3 — Growth & Retention

| # | Service | Effort | Impact | Client Decision |
|---|---|---|---|---|
| 12 | **Customer Loyalty & CRM** | High | Medium | ⏳ **DEFER** — "HUGE WIN if done properly" but leave for last until business is secured |
| 13 | **Instagram-to-Cart Deep Linking** | Medium | Medium | ⏳ **DEFER** — Part of Phase 3 |
| 14 | **Corporate Ordering Portal** | High | Medium | ⏳ **DEFER** — Part of Phase 3 |
| 15 | **Gift Card & Voucher System** | Medium | Medium | ⏳ **DEFER** — Part of Phase 3 |
| 16 | **Delivery Platform Integration Hub** | High | Medium | ❌ **Moot** — They will use Talabat once launched |
| 17 | **Analytics Dashboard** | Medium | Medium | ⏳ **DEFER** — Part of Phase 3 |
| 18 | **Email/SMS Marketing Automation** | Medium | Medium | ⏳ **DEFER** — Part of Phase 3 |

### 🎨 Phase 4 — Brand & Experience

| # | Service | Effort | Impact | Client Decision |
|---|---|---|---|---|
| 19 | **Real Product Photography** | Medium | High | *(Not explicitly addressed — future consideration)* |
| 20 | **Packaging Design System** | Medium | Medium | *(Not explicitly addressed — future consideration)* |
| 21 | **SEO & Local Search Optimization** | Low | Medium | *(Not explicitly addressed — likely part of landing page)* |
| 22 | **Seasonal Campaign Builder** | Medium | Medium | *(Not explicitly addressed — future consideration)* |

---

## Client's Explicit Instructions (Verbatim Notes)

1. > "The landing page is a winning card"
2. > "WhatsApp Business Catalog — keep for the last, I need to understand it well"
3. > "Brand Design System Documentation must be made from the existing data on the business itself, not the old stuff created here before the wipe out"
4. > "Instagram Content Strategy Kit — they have their team, they handle it"
5. > "They will use Talabat once they launch their business"
6. > "The digital menu with Arabic RTL is a winning card"
7. > "Custom Cake Order Builder can be part of the landing page or the menu"
8. > "WhatsApp Order Automation stays for the last, it might need some work"
9. > "Payment Gateway Integration & Delivery Zone Calculator — Talabat has those handled"
10. > "Phase 3 can be a HUGE WIN if done properly, let's leave it to the last until I secure the business with them"

---

## Refined Priority — What We Build NOW

### Immediate Build (Phase 1 — Now)

| Priority | Deliverable | Rationale |
|---|---|---|
| **P1** | **Landing Page** | "Winning card" — single page, bilingual AR/EN, Coming Soon + email/WhatsApp capture, brand showcase |
| **P2** | **Digital Menu (AR RTL)** | "Winning card" — full product catalog, Arabic-first RTL, real product data from research, WhatsApp order CTA per item |
| **P3** | **Google Business Profile** | "Winning card" — low effort, high discoverability, pre-launch setup, critical for "dessert near me" searches |
| **P4** | **Custom Cake Order Builder** | Merged into landing page or menu — step-by-step cake customization flow |
| **P5** | **Brand Design System** | Built from actual Cravio data (Instagram, logo, colors), not old mockups |

### Deferred (For Later)

| When | Deliverable | Trigger |
|---|---|---|
| After launch | WhatsApp Business Catalog + Automation | Once client understands WhatsApp Business tools |
| After business secured | Phase 3 (Loyalty, CRM, Corporate, Gifting, Analytics, Email) | "HUGE WIN" — but only after relationship is locked |
| Moot | Payment Gateway, Delivery Zones, Delivery Integration | Talabat covers these |

### Skipped (Client Has Own Solution)

| Service | Reason |
|---|---|
| Instagram Content Strategy | Client has their own team |
| Payment Gateway Integration | Talabat handles it |
| Delivery Zone Calculator | Talabat handles it |
| Delivery Platform Integration Hub | Client will use Talabat |

---

## Quick Reference — What We Build NOW

| Do NOW | Defer | Skip |
|---|---|---|
| Landing Page | WhatsApp catalog + automation | IG strategy (their team) |
| Digital Menu (AR RTL) | Phase 3 (loyalty, CRM, gifting) | Payments & delivery (Talabat) |
| Google Business Profile | Phase 4 (photography, packaging) | — |
| Cake Builder (merged) | — | — |
| Brand Design System (from real data) | — | — |

---

## Key Constraints & Rules for Build

1. **Brand fidelity:** Every design decision must reference actual Cravio brand data from the `data/` directory — colors verified from research, not assumed from old mockups
2. **Arabic RTL first:** The digital menu must be Arabic-native with proper RTL layout, not an afterthought
3. **WhatsApp-first CTAs:** Every product and page must drive to WhatsApp ordering (+962 77 012 8014)
4. **Talabat awareness:** Don't build what Talabat already provides (payments, delivery, logistics)
5. **Pre-launch posture:** Everything should support a "Coming Soon" narrative — hype-building, not transactional (yet)
