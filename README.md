# erablue_mini
erablue_resortを小さい画面で遊ぶための設定集

## Q. なんこれ？
[erablue_resort](https://github.com/erablue-resort/erablue_resort/wiki)を小さい画面で遊ぶための設定集

1. erablue_resortはデフォルトでは1600*900のウィンドウサイズで実行されるため、小さい画面では大部分を埋めつくしてしまう
1. でもウィンドウサイズを単に小さくするとウィンドウから溢れる
1. 文字サイズを小さくしたら表示が崩れる
1. 文字サイズの変更による表示崩れはサポートしていない、詰んだ

…とならないよう、筆者がなるべく表示が崩れる場所が少なくなるような設定をご紹介
(もちろん表示崩れは**ゼロにはなりません**が、なるべく違和感なく遊べる…はず)


## Q. 使い方は？
1. `erablue_resort\CSV`フォルダに[ここ](https://github.com/daughter-patch/erablue_mini/releases/latest)からDLした`_default.config`を上書きする
1. `erablue_resort`直下の`emuera.config`を削除（または退避）して、Emueraの設定を初期化する
1. Emueraを起動する
1. (選んだ設定によっては) `[200] - OPTION` > `[3] - 機能切り替え` > `[600] サイド領域表示切り替え` からサイド領域を非表示にする
