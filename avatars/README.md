# Member avatars

Static profile photos served from `/avatars/<file>`.

Demo creatives and any member without an uploaded photo fall back to a
deterministic stock portrait — see `apps/web/src/lib/avatars.ts`. Real members
keep their own photo here.

## Committed real-member photos

These handles are wired in `PROFILE_AVATARS` to a committed file (square, ~400×400
JPEG). If a file is ever missing it gracefully falls back to the member's initials.

| Handle          | File                    |
| --------------- | ----------------------- |
| `@briancid`     | `briancid.jpg`          |
| `@tdmlife`      | `tdmlife.jpg`           |
| `@ritagavrilov` | `ritagavrilov.jpg`      |
| `@stevenscope`  | `stevenscope.jpg`       |
