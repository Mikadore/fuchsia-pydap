# Upstream provenance and packaging history

This package extracts the Python DAP client from Fuchsia's
[`src/lib/debug/dap`](https://fuchsia.googlesource.com/fuchsia/+/main/src/lib/debug/dap/)
at commit [`7aa96ac40325b905a5a86a0853890fef7b2fb106`](https://fuchsia.googlesource.com/fuchsia/+/7aa96ac40325b905a5a86a0853890fef7b2fb106/).

The `pydap` package and upstream `client_test.py` are from
`src/lib/debug/dap/python/`. Fuchsia's `BUILD.gn` and the
`src/lib/debug/dap/python/zxdb/` adapter-specific code are omitted.

The local distribution adds `pyproject.toml`, packaging metadata, and this
provenance documentation. The Python client and upstream regression test source
are unchanged. The previous PacketFlow copy incorrectly declared
`BSD-3-Clause`; its included license text has two redistribution conditions, so
the package now correctly declares `BSD-2-Clause` and retains the full license.
