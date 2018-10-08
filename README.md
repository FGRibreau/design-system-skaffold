Design System scaffolding
=========================

Principles:

- Every components must live separately in `components/{component-name}/index.{html,css,scss,css,vue,js}` and be required separately
- Shared state (e.g. colors) must live inside `core/`

# Usage

```
npm install -s design-system-boostrap
```

Require components (from SASS) with:

```scss
@import "node_modules/design-system-boostrap/components/button";
@import "node_modules/design-system-boostrap/components/input";
// or with node-sass-package-importer

@import "~design-system-boostrap/components/button";
@import "~design-system-boostrap/components/input";
```

# Development

```
npm install
npm run serve
```
