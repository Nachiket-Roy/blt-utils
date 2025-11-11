# @blt/utils

Reusable utility helper functions for the BLT ecosystem.

## Installation

```bash
npm install @blt/utils
```

## Usage

Before:
```js
new Date(app.ban_date).toLocaleDateString();
```
After: 
```bash
import { formatDate } from "@blt/utils";
formatDate(app.ban_date);
```
