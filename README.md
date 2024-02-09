Run
```bash
npm install
npx biome check --changed --no-errors-on-unmatched --files-ignore-unknown=true --since=head .
# or alternatively, if already on the main branch
npx biome check --changed --no-errors-on-unmatched --files-ignore-unknown=true .
```
