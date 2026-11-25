# Fude — update feed

This repository is the automatic-update feed for **Fude (筆)**, a macOS PDF reader.
Fude checks `releases/latest/download/latest.json` and installs new versions by itself.

The files here are encrypted and only work inside Fude. Every update is also signed; Fude installs it only if the
signature matches the developer's key.

このリポジトリは Fude の自動アップデート配信用です。ファイルは暗号化されており、Fude 以外では使用できません。
