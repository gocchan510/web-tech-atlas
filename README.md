# Web技術アトラス（Tech Genealogy Atlas）

🌐 **ライブ: https://gocchan510.github.io/web-tech-atlas/**

Web/フロントエンド技術を**縦軸＝時系列の系譜フロー図**としてまとめた、インタラクティブな図鑑シリーズ。各ページは単体の HTML（ライブラリ依存なし・ダークモード対応・検索/フィルタ付き）で、ブラウザで開くだけで動きます。

**入口（おすすめ）→ [`daisyui-hub.html`](daisyui-hub.html)** … daisyUI を中心に「前提 ← / 比較 ↔ / 応用 → / ルーツ ↓」の4方向へ知識を広げる**放射状マップ**。各ノードから該当編へ飛べる、アトラス全体のハブ。「学習順（表層→深層）」モードつき。

## 収録ページ

| ページ | 内容 |
|---|---|
| [daisyui-hub.html](daisyui-hub.html) | **入口** — daisyUI起点の知識展開マップ（学習ロードマップ付き） |
| [css-frontend-lineage-flow.html](css-frontend-lineage-flow.html) | CSS / フロントエンド エコシステム（前史〜2026、約205技術） |
| [prog-lang-genealogy.html](prog-lang-genealogy.html) | プログラミング言語 系統樹（58言語、1957〜） |
| [reactivity-state-lineage.html](reactivity-state-lineage.html) | リアクティビティ / 状態管理（39ノード） |
| [cloud-evolution-lineage.html](cloud-evolution-lineage.html) | クラウド進化史（仮想化→IaaS→PaaS→コンテナ→サーバーレス→エッジ） |
| [ai-llm-coding-lineage.html](ai-llm-coding-lineage.html) | AI / LLM・AIコーディング（Transformer→各社LLM→ツール→MCP） |
| [rendering-arch-lineage.html](rendering-arch-lineage.html) | レンダリング / 配信（古典SSR→CSR→SSG→SSR復権→hydration→アイランド→RSC→edge） |
| [browser-web-standards-lineage.html](browser-web-standards-lineage.html) | ブラウザ / エンジン / Web標準（KHTML→WebKit→Blink、W3C/WHATWG/HTML5） |
| [js-engine-runtime-lineage.html](js-engine-runtime-lineage.html) | JSエンジン / ランタイム（SpiderMonkey/V8、JIT変遷、Node/Deno/Bun/Workers） |
| [vcs-git-lineage.html](vcs-git-lineage.html) | バージョン管理 / Git（SCCS→CVS→SVN→Git/Mercurial、GitHub/GitLab、Git Flow/GitOps） |

各ページ上部のナビ「Web技術アトラス:」から相互に行き来できます。

## 見方

- **縦＝時間**（上が古い→下が新しい）。**色＝系統**。**矢印＝影響/発展関係**（ホバーで系譜が強調）。
- 上部の**検索ボックス**・**系統フィルタ**で絞り込み。各ノード下のバーは難易度/複雑度/重要度（編によって意味が変わる）。

## 公開

GitHub Pages で公開する場合、入口はリポジトリのルート（`index.html` が `daisyui-hub.html` へリダイレクト）。

---
データは各技術の登場年・影響関係を調べて作成。誤り・追加したい技術があれば Issue / PR を歓迎。
