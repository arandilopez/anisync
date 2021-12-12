# Readme for Developers
## Security

### Bundler-Audit

[bundler-audit](https://rubygems.org/gems/bundler-audit) provides patch-level verification for Bundled apps.

Update audit db:

`$ bin/bundler-audit update`

Run checks:

`$ bin/bundler-audit check`
 
Or run it all in one command:

`$ bin/bundler-audit check --update`
