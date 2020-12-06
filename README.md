# zip-entry-search

ZIPファイル内のファイル名を検索する

## 開発環境

- .NET 5.0
- Windowns Forms

## 使い方

1. フォルダパスに検索したいZIPファイルを含むフォルダパスを指定する
2. 検索文字列に検索した正規表現形式に文字列を指定する。右の▼を押すとサンプルを入力できる
3. 処理開始ボタンを押下する
4. 対象結果が見つかるとlogsフォルダ内にヒットしたZIPファイルパスをリストしたテキストファイルを作成する

## 注意事項

- ZIPファイル内のファイル名はShift-JISとして処理する
- フォルダ内の検索はサブフォルダも含めて検索する
