# Accessibility Lab Notes

Collected tips and checks for building accessible front-end experiments.

## Automated checks
- Run axe DevTools on every page state.
- Use Lighthouse accessibility audit in CI.
- Add eslint-plugin-jsx-a11y to React projects.

## Manual checks
- Keyboard only: Tab, Shift+Tab, Enter, Space, Escape.
- Check focus order matches visual order.
- Ensure focus indicator is never removed.
- Test with a screen reader (VoiceOver/NVDA).
- Verify all images have meaningful alt text.
- Confirm color contrast meets WCAG AA.
- Test zoom at 200% and 400%.

## Common fixes
- Label inputs explicitly.
- Use native `<button>`, `<a>`, and `<input>` where possible.
- Add `aria-expanded` for disclosure widgets.
- Use `prefers-reduced-motion` before animations.

Last updated: 2026-08-27