## 2026-11-04 - Login Form Accessibility
**Learning:** Using width: 100% with padding causes inputs to overflow their containers unless box-sizing: border-box is applied. Error messages that conditionally render need role="alert" and actual text to be useful to screen readers and sighted users alike.
**Action:** Always check form elements for box-sizing properties when setting width to 100%, and ensure dynamic error messages have appropriate ARIA roles.
