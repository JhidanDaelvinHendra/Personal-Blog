## 2024-11-02 - Ensure PHP Error Blocks Have Actionable Content and ARIA Roles
**Learning:** Empty HTML elements populated dynamically by PHP (e.g., `<p class="error-message"></p>`) are poor for accessibility because screen readers might miss them if they lack ARIA roles. Furthermore, leaving them empty means no immediate feedback is announced.
**Action:** Always add `role="alert"` to conditional error messages and ensure they contain fallback actionable text like "Invalid username or password."
