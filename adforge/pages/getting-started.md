---
title: Getting Started
order: 1
---

# Getting Started

Welcome to **d-eeee**! This is your first documentation page.

## Installation

```bash
pnpm add d-eeee
```

## Usage

```tsx
import { Button } from 'd-eeee';

export default function App() {
  return <Button variant="primary">Click me</Button>;
}
```

## Design Tokens

Tokens are defined in `adforge/tokens/` as JSON files that follow the
[Design Tokens Community Group](https://design-tokens.github.io/community-group/format/)
specification. Edit them here and commit — adforge propagates changes automatically.

## Next Steps

- Add your brand colors to `adforge/tokens/colors.json`
- Create new components in `src/components/`
- Add more documentation pages in `adforge/pages/`
