## 2026-11-06 - Login Form Accessibility and Error Handling
**Learning:** Empty error message blocks without `role="alert"` provide no context for screen readers on form submission failure, and missing autocomplete attributes hinder user experience.
**Action:** Always add an actionable message and `role="alert"` to error message containers, and provide appropriate `autocomplete` attributes to standard inputs like username and password.
