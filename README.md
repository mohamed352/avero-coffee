# Avero Coffee — App Prototype

A clickable mobile-app prototype for **Avero Specialty Coffee**, built to pitch to the shop owner.

## How to run

Double-click `index.html` — it opens in any browser. No installs, no internet needed.

For the real phone-app feel: open Chrome DevTools → Toggle Device Toolbar (Ctrl+Shift+M) → pick a phone (e.g. iPhone 14). Or just open it on your phone's browser.

## Demo flow (for the pitch)

1. **Splash** → tap → **onboarding** → *Get Started*.
2. **Home** — show the loyalty points card (visible from the first second).
3. Tap any drink → pick size/extras → **Add to Order**.
4. Open **Cart** → *Pay & Place Order*.
5. **Tracking screen (the wow moment)** — order moves Received → Preparing, then tap **"Simulate: barista taps Ready"** → the phone **plays an alert chime, vibrates, and pulses** "Your order is ready at the counter!". Points are awarded instantly.
6. **Rewards** — redeem a free drink, watch the balance update.
7. **Orders / Profile** — history, stats, membership.

## The pitch in one line

> "Customers order and pay from their phone, earn points they redeem for free drinks — and a cheap smart device (ESP32 + buzzer, costs a few dollars) at the counter triggers the *order ready* alert, so staff never shout names again."

## Why the owner says yes

- **More sales, less friction** — order-ahead means shorter lines and bigger baskets (extras are one tap).
- **Free marketing loop** — points keep customers coming back to *Avero*, not the shop next door.
- **The smart-alert device is nearly free** — no expensive POS hardware; one tap by the barista notifies the customer instantly.
- **Data** — the owner learns best sellers, peak hours, and loyal customers.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole prototype (screens + styles + logic, single file) |
| `logo.jpg` | Avero logo (splash + branding) |
| `hero.jpeg` | Lifestyle photo used on onboarding/home |

## Notes

- Prototype state (points, cart, orders) resets on page reload — that's fine for a demo.
- The alert sound uses the Web Audio API (no audio file needed) and needs one user tap first (browser policy) — the demo flow naturally includes taps.
