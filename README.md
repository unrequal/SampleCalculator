-自作した電卓のAndroidアプリです。僕の経験の参考となりますと幸いです。

-通常の計算の機能に加え、「一文字削除ボタン」、「過去ログの表示」、「メモリー機能」を実装いたしました。

「←ボタン」が一文字削除ボタン、「KEEPボタン」が簡易的なメモリー機能となっております。

-計算の際にはBigDecimalを用いることにより計算の誤差(丸め誤差)をなくし、計算時以外の数値の保持は全てStringを用いることにより、一貫性を持たせて変換のミスを防ぐよう工夫いたしました。

また、細かいバグが無いよう細心の注意を払いました。(メモリー機能の使用時に、小数点の複数入力を防ぐ、等)

-このリポジトリには以下の4つのファイルが含まれています。

1.README.md - このテキストファイルです。

2.MainActivity.txt - アプリのMainActivity.javaのソースコードです。

3.Screenshot.png - 実際にAndroid端末で動かした際のスクリーンショットです。

4.Sample_Calculator_By_Kaito_Hayafune.apk - 本アプリのインストーラーです。実際にAndroid端末にダウンロードしていただくとアプリを起動することができます。

-本アプリの作成にあたって、有山圭二様のこちらのサイトを参考にさせていただきました。

https://anharu.keiji.io

特別に、有山様より上記のファイルの公開の許諾をいただいております。

本アプリの内容の全部、または一部について、著作者から文書による許諾を得ずに複製することは禁じられています。

Copyright © 2019 Kaito Hayafune
