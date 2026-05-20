# DESIGN.md — SlipDee Website

## Product

SlipDee is a Thai bank slip expense tracker for iOS.

The website should present SlipDee as a simple, friendly, privacy-first app that helps Thai users import bank slip screenshots, review detected details, and save income/expense records.

SlipDee is not a bank, not a crypto app, not a payment processor, and not an investment app.

## Website Goal

The website should help visitors quickly understand:

1. What SlipDee does
2. Why it is useful
3. How it works
4. Why it is privacy-friendly
5. That the app is coming soon to the App Store

The site should be lightweight and compatible with GitHub Pages.

Use static HTML and CSS only unless JavaScript is truly necessary.

## Design Direction

Use a clean, minimal iOS fintech landing page style.

The design should feel:

- Friendly
- Trustworthy
- Calm
- Private
- Modern
- Thai-user friendly
- App Store ready
- Premium but simple

Avoid:

- Crypto/trading style
- Real bank branding
- Real Thai bank logos
- Heavy gradients
- Dark neon UI
- Overly technical financial language
- Complex dashboard visuals

## Visual Identity

### Color Palette

Use these CSS variables:

```css
:root {
  --sd-bg: #f8fafc;
  --sd-bg-soft: #f1f5f9;
  --sd-card: #ffffff;

  --sd-primary: #14b8a6;
  --sd-primary-dark: #0f766e;
  --sd-primary-soft: #ccfbf1;

  --sd-text: #0f172a;
  --sd-text-muted: #64748b;
  --sd-border: #e2e8f0;

  --sd-income: #16a34a;
  --sd-income-soft: #dcfce7;

  --sd-expense: #f97316;
  --sd-expense-soft: #ffedd5;

  --sd-warning: #f59e0b;
  --sd-warning-soft: #fef3c7;

  --sd-error: #dc2626;
  --sd-error-soft: #fee2e2;
}