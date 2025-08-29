# Lifecycle Email Flow Specifications (Days 1–7)

Objective: Launch foundational flows to drive repeat purchases, UGC, and review velocity. Where Etsy direct email capture is constrained, leverage: (a) Packaging insert with QR to signup landing page (outside Etsy policies compliance); (b) Social bio links; (c) Post-purchase thank-you message requesting optional signup for care tips & early color drops.

ESP Options: MailerLite / Klaviyo (if standalone site planned) OR simple ConvertKit embedded form.

## 1. Flows Overview
| Flow | Trigger | Audience Filter | Goal | KPIs |
|------|---------|-----------------|------|------|
| Welcome Series | New subscriber (QR / form) | Not yet purchased | Introduce brand & drive first purchase | Signup→Order Conv %, CTR |
| Browse Abandon (Light) | Subscriber visits landing (tracked link) but no purchase in 24h | Engaged, no order | Nudge to return | Recovery Rate |
| Cart Abandon (If ecom site later) | Adds item, no checkout in 4h/24h | Intent high | Recover sale | Recovered Revenue |
| Post-Purchase Thank You | Order marked complete | All customers | Reinforce brand + care + review ask | Review Rate, UGC submissions |
| Review / UGC Reminder | 10 days after delivery | Not yet reviewed | Secure review & photo | Review submission %, photo rate |
| Replenishment / Color Drop | 45–60 days post purchase | Past purchasers | Encourage 2nd purchase (new color) | Repeat Rate |
| Lapsed Winback | 120 days no purchase | Past purchasers | Reactivate dormant | Winback % |

## 2. Flow Copy (Drafts)

### 2.1 Welcome Series (3 Emails)
1. Subject: Welcome to Mareshop – Your Cozy Handmade Knitwear Awaits
   - Hook: Thank you + brand story (dragon scale signature; mother-daughter craftsmanship).
   - CTA: Shop Best Sellers (Dragon Scale Gloves) / Secondary: Follow on Instagram.
   - Incentive (Optional test): Limited intro offer (e.g., free gift wrap or 5% off first order) – ensure margin check.
2. Subject: How We Make Dragon Scale Gloves (Behind the Stitches)
   - Content: Process photos (texture macro, materials). Sustainability & care instructions preview.
   - CTA: Explore Dragon Scale Collection.
3. Subject: Pick Your Color – Most Loved Combinations
   - Content: Swatch collage + style tips (typing at desk, cosplay, gifting).
   - CTA: Shop Colors / Reply to request a custom combo.

### 2.2 Browse Abandon (1–2 Touches)
1. Subject: Still thinking about those cozy gloves?
   - Snippet: Your perfect pair is still being hand-knit (once you order).
   - CTA: Return to your favorites.
   - Secondary: Highlight gift-ready packaging.
2. Subject (Optional Test): Limited yarn batch – secure your color
   - Scarcity framing with integrity (use only if real constraint).

### 2.3 Cart Abandon (Future Site)
1. Subject: Nearly yours – complete your handmade order
   - Body: Items summary + benefits (warm, finger freedom, handmade in Latvia).
   - CTA: Complete Order
   - Trust: 1,400+ 5★ reviews excerpt.
2. Subject: Need a different color? Just reply.
   - Provide customization reassurance.

### 2.4 Post-Purchase Thank You
Subject: Your Mareshop Order Is Being Crafted 🧶
- Body: Appreciation + what happens next (production time, shipping timeline).
- Care Basics: Gentle hand wash, dry flat.
- CTA: Follow Instagram for behind-the-scenes.
- Soft Ask: "If you love your items when they arrive, a review helps our small studio enormously."

### 2.5 Review / UGC Reminder
Subject: How are your new dragon scale gloves?
- Timing: 10 days after delivery (estimate shipping + 3 days).
- Body: Quick check-in, ask for honest review. Encourage photo ("Reply or tag us @maresho_p – we feature customer looks").
- Incentive (Test later): Entry into monthly color giveaway for photo share (check platform compliance).

### 2.6 Replenishment / Color Drop
Subject: New color drops – add to your collection
- Body: Showcase 3 new/seasonal colors + bundle reminder.
- CTA: Shop New Colors | Add a matching headband.

### 2.7 Lapsed Winback
Subject: We saved a new color for you
- Body: Acknowledge time gap, show what's new, social proof snippet.
- CTA: Rediscover Best Sellers.
- Optional Incentive: Modest (free gift wrap) to protect margin.

## 3. Timing Summary
| Flow | Email # | Delay from Trigger |
|------|---------|-------------------|
| Welcome | 1 | Immediate |
| Welcome | 2 | +2 days |
| Welcome | 3 | +4 days |
| Browse Abandon | 1 | 24h after session |
| Browse Abandon | 2 | +48h (if no click) |
| Cart Abandon | 1 | 4h after abandonment |
| Cart Abandon | 2 | +20h |
| Post-Purchase | 1 | Order Complete (Immediate) |
| Review Reminder | 1 | +10 days after delivery est |
| Replenishment | 1 | +45–60 days |
| Winback | 1 | +120 days inactivity |

## 4. Segmentation Rules
- New vs Returning: Tag on first purchase.
- High AOV customers: Future VIP segment after ≥2 orders + lifetime spend threshold.
- Color Preference: Track clicks on color swatch links for personalization (future phase).

## 5. Compliance & Etsy Considerations
- Do not divert Etsy customers off-platform prior to purchase (respect ToS).
- Post-purchase insert card: Offer optional tips & early color alerts (value-first) + QR.
- Clear unsubscribe link in all emails (GDPR compliance – EU base).

## 6. Measurement Plan
| Flow | Primary Success Metric | Supporting |
|------|------------------------|------------|
| Welcome | First Order Conv % | Open Rate, CTR |
| Browse Abandon | Revisit Rate | Click to Order % |
| Cart Abandon | Recovered Revenue | Open Rate |
| Post-Purchase | Review Rate | UGC photo submissions |
| Review Reminder | Incremental Reviews | Photo Attach Rate |
| Replenishment | 2nd Purchase Rate | AOV uplift |
| Winback | Reactivation Rate | Revenue per send |

## 7. Technical Setup Checklist
- Create signup landing page (simple: headline, value bullets, form).
- Configure UTM parameters for tracking (medium=email, source=flow, campaign=welcome_v1).
- Set up event properties: first_purchase_date, last_purchase_date, order_count.
- Insert dynamic fields: customer first name, product type purchased.

## 8. Future Enhancements
- Dynamic product recommendations (top sellers) once data volume adequate.
- Split test subject lines (curiosity vs benefit) in Welcome 1.
- Introduce VIP early access color pre-order after 50+ subscribers.

---
Prepared: Day 5 deliverable.
