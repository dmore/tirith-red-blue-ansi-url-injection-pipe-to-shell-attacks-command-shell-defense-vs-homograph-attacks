---
name: Dogfood Report
about: Report an issue found during dogfooding
labels: dogfood
---

## Environment

- OS:
- Shell:
- tirith version (`tirith --version`):
- Install method (cargo/brew/deb/manual):

## Doctor output

```
<paste output of `tirith doctor` here>
```

## What happened

<!-- Describe the issue -->

## What you expected

<!-- What should have happened -->

## Command (if applicable)

```
<the command that triggered the issue, redacted if sensitive>
```

## tirith output

```
<paste relevant tirith output here>
```

## Category

- [ ] False positive (benign command flagged)
- [ ] False negative (malicious command not flagged)
- [ ] Latency issue
- [ ] Shell integration issue
- [ ] Policy issue
- [ ] Other
