# fio-extras
![gosec](https://github.com/frameloss/fio-extras/workflows/Run%20Gosec/badge.svg)

fio-extras includes a keosd client, and helper for HD key derivation.

These were additions to the [fio-go](https://github.com/fioprotocol/fio-go) library that were removed because they
cause OS incompatibilities, specifically with Windows. Because of either unix sockets or imports from
go-ethereum that are exclusive to Unix-like systems, these won't run on Windows.

