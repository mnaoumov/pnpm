---
"pacquet": patch
---

`pnpm -s <script>` and `pnpm --sequential <script>` no longer fail with `unexpected argument '-s' found`. Written before a script name without `run`, `-s` is `--sequential`, as it is in `pnpm run -s <script>` [pnpm/pnpm#16446](https://github.com/pnpm/pnpm/issues/16446).
