# quasar-protos

Proto files merged from firmwares:
- Yandex.Station 2 (yandexmidi/0.368.1.5.4738413199.20261002.294)
- Yandex.Station Midi (cucumber/0.368.1.10.4679338126.20260921.159)
- Yandex.Station Duo Max (chiron/5000001364)
- Yandex TV magritte (5000001628): quasar daemon (`libquasar_daemons.so` from
  ServicesIosdk.apk) + YandexQcApp DEX descriptors
- Yandex TV chiron (5000001410) / malevich (5000000892): launcher, QC app,
  app store APKs

Files under [`reconstructed/`](reconstructed/) were rebuilt from Yandex "ry"
codegen (no embedded descriptors) — filenames are invented, wire format is
exact. Everything else has original file paths from embedded descriptors.

If Yandex wants removal of this, please contact [me](https://re146.dev).
