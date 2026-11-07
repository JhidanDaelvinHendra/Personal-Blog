## 2026-11-07 - Adding Accessible Error Messages and Auto-complete to Login
**Learning:** PHP login forms often contain empty error placeholders that screen readers ignore. Additionally, missing autocomplete attributes reduce accessibility for users relying on password managers.
**Action:** Add `role="alert"` and clear error text inside conditional error blocks, and always include appropriate `autocomplete` attributes (`username`, `current-password`) on login inputs.
