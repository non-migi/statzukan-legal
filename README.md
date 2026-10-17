# statzukan-legal

「絵で学ぶ統計用語図鑑 / Visual Statistics Glossary」のサポートサイト（GitHub Pages）。

- `/` — サポートトップ（FAQ 付き）
- `/privacy/` — プライバシーポリシー（日英）
- `/terms/` — 利用規約（日英）

公開URL: https://non-migi.github.io/statzukan-legal/


## メモ

1.0 は広告を入れていないため、プライバシーポリシーは「広告なし・トラッキングなし・IDFA なし」で
書いてある。**AdMob などの広告を入れるときは `/privacy/` の 1章・4章・7章を直し、広告の章を足すこと**
（ゲーム理論図鑑の `gametheorylab-legal` の 3章「広告について」がそのまま下敷きになる）。

TelemetryDeck に送るイベントを増やしたときは、2章の表の「例」も合わせて直す
（アプリ側は `StatZukan/Core/Services/AnalyticsManager.swift`）。
