1.1.1 2016-04-23 (Will reset renew certificates)
==================
  * Clears certiciate when switching between debug modes.
  * Clears certificate when bundle changes (previously bundles were tied to the first domain).
  * Attempt to fix some issues with restify.

1.0.0 / 2016-04-17
==================
  * Remove bundle option.
  * No longer fuzzy match domains with `path-to-regexp`.
  * Allow for nested arrays in `domains` for bundled certificates.
