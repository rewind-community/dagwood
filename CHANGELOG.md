# Changelog

## [1.0.1]

Security: remediate Dependabot alerts in development dependencies. Bumped the `bundler` development dependency to `>= 2.2.33` (GHSA-fj7f-vq84-fh43, GHSA-fp4w-jxhp-m23p, GHSA-g98m-96g9-wfjq) and regenerated `Gemfile.lock`, which drops the vulnerable transitive `rexml` (GHSA-2rxp-v6pw-ch6m, GHSA-vmwr-mc7x-5vc3, GHSA-5866-49gr-22v4, GHSA-r55c-59qm-vjw6, GHSA-4xqq-m2hx-25v8, GHSA-vg3r-rm7w-2xgh, GHSA-8cr8-4vfw-mr7h).

## [1.0.0]

Initial release!

## [0.9.0]

Pre-release
