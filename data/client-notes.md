# Client Notes & Decisions

> **Date:** June 19, 2026  
> **Source:** Direct client feedback on services proposal

---

## Verbatim Notes

1. "The landing page is a winning card"
2. "Google Business Profile Setup — another winning card, we should take care of it too"
2. "Keep WhatsApp Business Catalog for the last — I need to understand it well"
3. "The Brand Design System Documentation must be made from the existing data on the business itself, not the old stuff created here before the wipe out"
4. "The Instagram Content Strategy Kit is handled — they have their team"
5. "They will use Talabat once they launch their business"
6. "The digital menu with Arabic RTL is a winning card"
7. "Custom Cake Order Builder can be part of the landing page or the menu"
8. "WhatsApp Order Automation stays for the last — it might need some work"
9. "Payment Gateway Integration & Delivery Zone Calculator — Talabat has those handled"
10. "Phase 3 can be a HUGE WIN if done properly — let's leave it to the last until I secure the business with them"

---

## Key Decisions Summary

| Decision | Implication |
|---|---|
| Landing page is priority #1 | Build immediately — single page, bilingual, coming soon posture |
| Google Business Profile is a winning card | Setup immediately — critical for local discovery |
| Digital menu (AR RTL) is priority #2 | Full product catalog, Arabic-native, WhatsApp CTAs |
| Brand system must use real data | Source from `data/brand-identity.md`, Instagram profile, actual business — NOT from old `menu.html` |
| Cake builder merged into page/menu | Not a standalone project — integrate into landing page or menu |
| Instagram strategy is client's | Skip — their team handles content |
| Talabat handles payments + delivery | Don't build payment gateways or delivery logistics |
| WhatsApp tools deferred | Client needs to understand WhatsApp Business first |
| Phase 3 deferred | Build only after client relationship is secured |
| Phase 4 is future | Not in current scope |

---

## Build Rules

1. Source all brand data from `data/` directory research files
2. Arabic RTL first, English LTR second
3. WhatsApp CTA on every product
4. Pre-launch narrative throughout
5. Don't duplicate Talabat's capabilities
6. No dependency on old `src/menu.html` — it was wiped for a reason
