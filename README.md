# hide_codecov_warning

GitHub でレビューを行う際に Codecov の warning のせいで見にくいため warning だけ非表示にする Chrome 拡張機能です。

## 動作環境

- Chrome88 以上(Manifest V3 を使っているため)

## 利用方法

- このリポジトリをローカルに落とします(clone や ZIP Download など)
- Google Chrome を開き URL 欄に`chrome://extensions`と入力してアクセスします
- 拡張機能一覧のページが表示されたら、右上の「デベロッパーモード」のトグルを ON にします
- 左上の「パッケージ化されていない拡張機能を読み込む」を押します
- さきほど手元に持ってきた`hide_codecov_warning`のディレクトリを選択します
- ON/OFF はトグルで切り替えられます
- ON にした状態で GitHub のプルリクエストの File Changed などにアクセスすると、Codecov の warning が非表示になっています
