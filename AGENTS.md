# 作業メモ

## 共通ルール
1. CSSは`assets/css/style.css`に集約し、HTMLの共通化は行わずページ単位で管理する。
2. 内部リンクは拡張子なしで指定し、GitHub Pagesのフラットなルーティングに合わせる。
3. 静的アセットは`assets/`直下に置き、`assets/css`・`assets/image`（必要時`assets/js`）など一階層構造で整理する。
4. 画像は用途が分かるファイル名で管理し、サブディレクトリを作らない。
5. `_`から始まるディレクトリはJekyllで無視されるため作らない（`.nojekyll`も配置しない）。
6. サイト内でリンクされないページや素材は保持しない。

## 最近の変更概要
- Canva「Desert Sunset」パレットに合わせて`style.css`のカスタムプロパティを刷新。
- 画像アセットを`assets/image/hero-*.jpg`などフラットな命名で再配置。
- 未使用の`shisha.html`と画像（`map.png`, `president.png`）を削除。
- 全ページのナビゲーションとフッターリンクから`.html`拡張子を除去。
- 旧`materials/`以下のファイルと`CNAME`を整理。
