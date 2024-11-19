# FileStreamReader implements on Sysmac Studio by ST for practice
IEC 61131-3のStructured Text(ST)で記述したCASEステートマシンの使用例です。SDカードからのファイル読み出しをストリームのように処理する機構を実装しています。コードの参照及び実行には、OMRON社のSysmac Studioが必要です。

## 環境
Sysmac Studio Version 1.60

## 使い方
1. このリポジトリの`git clone`または、Zipをダウンロードします。
2. sdディレクトリのファイルを"C:\OMRON\Data\SimulatorData\CARD\Memory001"にコピーします。
3. "POU/プログラム/Main"の内容を確認します。
4. リビルドします。
5. シミュレータを実行します。
6. ウォッチウィンドウで"Main.iMessage"の変化を確認します。

## 説明
FileStreamReaderは、CASEステートマシンの説明に係る使用例です。ストリーム風とするため、一連のFB、FUNから成ります。CASEステートマシンについては[こちら](https://zenn.dev/kitam/articles/02b0981535e25b)を、FileStreamReaderについては[こちら](https://zenn.dev/kitam/articles/02b0981535e25b)を参照ください。

## ファイルハッシュ値
取得したSysmac Studioプロジェクトは、ハッシュ値の確認を推奨します。

| ファイル名 | sha256 |
| --- | --- |
| FileStreamReader.scm2 | cafd142bb651ca832fc40b89025bf4e2352f5bac67848c81c5bbb813327cffa6 |
