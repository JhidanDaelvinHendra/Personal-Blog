## 2024-11-10 - Login Form UX & Accessibility
**Learning:** The login page had an empty error message element and lacked autocomplete attributes for credentials, leading to poor screen reader experience and frustrating form filling.
**Action:** Added `role="alert"` and descriptive text to the error message. Added `autocomplete="username"` and `autocomplete="current-password"` to inputs.
