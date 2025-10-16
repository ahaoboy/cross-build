# cross-build

```yml
- uses: ahaoboy/cross-build@v1
  with:
    bin: cross-build
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
    target: "x86_64-unknown-linux-musl"
```