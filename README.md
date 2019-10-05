# quiz
## 概要
csvに書いてある問題を読み込んで、コマンドラインからの入力を回答として受け取り、最後に正解数を表示する時間制限付きクイズです。

![image](https://user-images.githubusercontent.com/17466118/66254304-83521b00-e7af-11e9-9bba-d77f535c6ace.png)

## 使い方
- limitというオプションで制限時間（秒）を指定してプログラムを実行すると、クイズが開始されます。
- 解答を入力していき、指定した制限時間が来るか全ての問題を解ききると終了になります。
- 不正解だった場合には正しい回答が表示され、次の問題へと進みます。
- プログラムの終了時に何問中何問正解したかが表示されます。