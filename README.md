# Repro for TypeScript ESLint bug

## Steps

1. `npm install`
2. `npm run typecheck src/repro.ts`

## Actual output

```
src/repro.ts:1:32 - error TS2307: Cannot find module '@typescript-eslint/utils' or its corresponding type declarations.

1 import { AST_NODE_TYPES } from "@typescript-eslint/utils";
                                 ~~~~~~~~~~~~~~~~~~~~~~~~~~


Found 1 error in src/repro.ts:1
``

## Expected output

No errors
