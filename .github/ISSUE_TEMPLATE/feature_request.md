---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: ''
assignees: ''

---

name: 🚀 Feature Request
description: Suggest a new feature or improvement
title: "[FEATURE] <short description>"
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: "## 💡 Feature Description\nDescribe the feature clearly."

  - type: textarea
    id: reason
    attributes:
      label: "✅ Why is this Needed?"
      description: "Explain why this feature is important."
      placeholder: "This feature is useful because..."

  - type: textarea
    id: implementation
    attributes:
      label: "📜 Suggested Implementation"
      description: "Describe how the feature should work."
      placeholder: "Feature implementation details..."
