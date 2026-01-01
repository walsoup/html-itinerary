## 2024-05-23 - [Search Interaction & Accessibility]
**Learning:** Users on slow connections might think the search is broken without a loading state. Icon-only buttons are invisible to screen readers without labels.
**Action:** Always add `aria-label` to icon-only buttons and provide visual feedback for async operations.
