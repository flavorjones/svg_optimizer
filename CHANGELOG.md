# Changelog

<!--
Prefix your message with one of the following:

- [Added] for new features.
- [Changed] for changes in existing functionality.
- [Deprecated] for soon-to-be removed features.
- [Removed] for now removed features.
- [Fixed] for any bug fixes.
- [Security] in case of vulnerabilities.
-->

## v0.2.6

- [Changed] All `<title>` elements are now stripped.
- [Fixed] Complex files with external entities won't raise exceptions. Complex
  files like those generated by Adobe Illustrator files may or may not be
  properly optimized. Pull requests are welcomed.
