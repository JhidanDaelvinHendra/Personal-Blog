## 2024-11-09 - Login Form Accessibility and Focus
**Learning:** When generating dynamic error messages (like from PHP), adding `role="alert"` is critical so screen readers immediately announce the error. Additionally, relying purely on default browser focus states in standard forms can be insufficient; explicitly declaring `:focus-visible` with `outline` and `outline-offset` significantly improves keyboard navigation visibility.
**Action:** Always verify error states have `role="alert"` and ensure inputs/buttons have explicit focus indicators in simple HTML/CSS projects.
