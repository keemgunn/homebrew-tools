## Summary

- 

## Checklist

- [ ] The release URL is immutable and versioned.
- [ ] Every artifact checksum was generated from the published artifact.
- [ ] `brew audit --strict --online <formula>` passes.
- [ ] `brew install --build-from-source <formula>` passes where applicable.
- [ ] `brew test <formula>` passes.
- [ ] No secret, token, or private source URL is committed.
- [ ] GitHub Actions references remain pinned to full commit SHAs.
