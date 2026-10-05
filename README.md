<!-- tyhp-readme:start -->
# tyhpdef/danharrin-livewire-rate-limiting

Tyhp type definitions for `danharrin/livewire-rate-limiting` `2.3.0`.

```bash
composer require --dev tyhpdef/danharrin-livewire-rate-limiting:2.3.0
```

This is a metapackage. Composer also installs `tyhpdef/danharrin-livewire-rate-limiting-impl` (type files).
Require **this** name, not `tyhpdef/danharrin-livewire-rate-limiting-impl`.

See https://tyhplang.com.

## Maintain `danharrin/livewire-rate-limiting`? Ship the types yourself

If you are a Packagist maintainer of `danharrin/livewire-rate-limiting`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/danharrin-livewire-rate-limiting-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `danharrin/livewire-rate-limiting` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/danharrin-livewire-rate-limiting": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `danharrin/livewire-rate-limiting` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `danharrin/livewire-rate-limiting` with a real constraint,
   `"replace": { "tyhpdef/danharrin-livewire-rate-limiting": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `danharrin/livewire-rate-limiting` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/danharrin-livewire-rate-limiting` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
