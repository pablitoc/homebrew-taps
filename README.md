##Personal Homebrew Tap for deprecated versions that are not longer available view `homebrew-core`.
---
most of these will be from homebrews history.

---
###Add New Tap Repository
```bash
$ brew tap pablitoc/homebrew-taps
```

###Create new tap
```bash
$ brew create <url_for_tarball> --set-name <name_of_formula>@<version>
```

###Test New Formula
```bash
$ brew audit --new-formula <name_of_formula>@<version>
```

###Install New Formula from Personal Repository
```bash
$ brew install pablitoc/<name_of_formula>@<version>
```
