<!-- tyhp-readme:start -->
# tyhpdef/symfony-ux-twig-component

Tyhp type definitions for `symfony/ux-twig-component` `3.4.0`.

```bash
composer require --dev tyhpdef/symfony-ux-twig-component:3.4.0
```

This is a metapackage. Composer also installs `tyhpdef/symfony-ux-twig-component-impl` (type files).
Require **this** name, not `tyhpdef/symfony-ux-twig-component-impl`.

See https://tyhplang.com.

## Maintain `symfony/ux-twig-component`? Ship the types yourself

If you are a Packagist maintainer of `symfony/ux-twig-component`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-ux-twig-component-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/ux-twig-component` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-ux-twig-component": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/ux-twig-component` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/ux-twig-component` with a real constraint,
   `"replace": { "tyhpdef/symfony-ux-twig-component": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/ux-twig-component` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-ux-twig-component` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
