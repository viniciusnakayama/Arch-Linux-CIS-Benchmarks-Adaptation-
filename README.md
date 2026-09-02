# CIS-Inspired Hardening Guide for Arch Linux / EndeavourOS

A self-authored hardening guide for Arch Linux (and derivatives like EndeavourOS), adapting controls inspired by the CIS Benchmarks — which don't have an official version for this distro.

Each control lives in its own folder under `controls/`, with the before/after state, the script used, and a short write-up of what was done and why.

## Structure

```
controls/
└── N.N-control-name/
    ├── before.png     # state before the fix
    ├── after.png      # state after the fix
    ├── script.sh       # commented script used to check/apply the control
    └── notes.md        # what was done, why it matters, any trade-offs
```

See `controls/0.0-example-control/` for a filled-out template.

## Status

 In progress.

## References

- CIS Benchmarks — https://www.cisecurity.org/cis-benchmarks
- ArchWiki, Security section — https://wiki.archlinux.org/title/Security

## License

MIT

