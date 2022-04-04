# Apple's Allowed Autofill Domains

[![Build Status](https://img.shields.io/github/workflow/status/b0o/apple-autofill-domains/update)](https://github.com/b0o/apple-autofill-domains/actions/workflows/update.yaml)
[![Last check: Mon Apr  4 10:28:25 UTC 2022](https://img.shields.io/date/1649068105?label=last%20check)](https://github.com/b0o/apple-autofill-domains/actions/runs/2089247539)
[![Last change: Mon Apr  4 09:33:44 UTC 2022](https://img.shields.io/date/1649064824?color=orange&label=last%20change)](https://github.com/b0o/apple-autofill-domains/commit/3788452)

Apple serves a JSON file containing 250,000 domains at the `https://cdn.smoot.apple.com/static/autofill_tld_whitelist_url` endpoint. This list appears to be used by the Safari web browser to auto-complete domains typed into the address bar.

This repository uses a [GitHub action](https://github.com/b0o/apple-autofill-domains/actions/workflows/update.yaml) to poll the endpoint hourly and commit any changes. This is being done out of curiosity to see how often the list is updated and to observe what changes are made over time.
