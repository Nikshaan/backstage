---
'@backstage/integration': patch
---

Fixed an issue where ESM consumers of `@backstage/integration` failed to import the package due to how it depended on lodash internally.
