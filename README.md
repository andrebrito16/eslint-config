# My Personal ESLint config

## Setup

### Next.js

1. Install dependencies:

```
npm i -D eslint @andrebrito16/eslint-config
```

2. Modify eslintrc.json:

```json
{
  "extends": [
    "@andrebrito16/eslint-config/next",
    "next/core-web-vitals"
  ]
}
```