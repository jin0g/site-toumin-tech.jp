# 作業メモ

## 方針
- CSSは`assets/css/style.css`で共通管理し、HTMLは各ページを個別構成。
- GitHub Pagesで拡張子なしルーティングに合わせ、内部リンクは`.html`拡張子を含めない。
- 画像やスクリプトは`assets/`配下にまとめ、ディレクトリは1階層で管理する。

## 今回実施した主な変更
- 画像アセットを`assets/image/`直下にフラット化し、用途のわかる命名（例: `hero-home.jpg`）。
- 未使用・重複のアセットとページ（`shisha.html`, `assets/image/map.png`, `assets/image/president.png`）を削除。
- カラーリングはCanvaの「Desert Sunset」パレットを採用し、`style.css`のカスタムプロパティで統一。
- ナビゲーション／フッターなど全リンクを拡張子なしに統一。
- 旧`materials/`ディレクトリと`CNAME`を整理済み。

## 運用注意
- 画像追加時は`assets/image/`直下へ配置し、命名規則を守る。
- 新規ページは必要最小限で作り、リンクがないページは残さない。
- `.nojekyll`は未配置のため、先頭に`_`が付くディレクトリ名は使用しない。
