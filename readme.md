# ✨ ghostlexly-auth ✨

A blend of the clsx library and tailwind-merge for working on tailwindcss projects.

## Installation

`npm`

```
yarn install clsx-tailwind-merge
```

`yarn`

```
yarn add clsx-tailwind-merge
```

## Usage

```tsx
import { cn } from "clsx-tailwind-merge";

const isUserVerified = true;

<div
  className={cn(
    "absolute top-[10%] z-30 h-9 w-9 rounded-full border-2 border-gray-300 bg-white",
    isUserVerified ? `border-green-900` : `border-red-900`
  )}
/>;
```
