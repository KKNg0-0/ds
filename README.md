# Deno Shiritori
- 直前の単語を、表示できるようにする
- 任意の単語を、入力できるようにする
- 直前の単語の末尾と、入力した単語の先頭を比較して、同じ場合だけ単語を更新する。違う場合は、エラーを表示する
- 末尾が「ん」で終わる単語が入力されたら、ゲームを終了する
- 過去に使用した単語が入力されたら、ゲームを終了する
- ゲーム中や終了後に、最初からやり直せるリセット機能をつける
- Enterキーで送信する
- ホーム画面の実装
- マルチプレイヤー（二人）の実装
- ランダムな単語で始まる（単語のランダム生成でない）
- 過去に使用された単語の表示

# Run using Command Prompt
- deno run --allow-net --allow-read --watch server.js

# Reference:
- enter to press button:
https://stackoverflow.com/questions/12955222/how-do-i-trigger-an-html-button-when-the-enter-key-is-pressed-in-a-textbox/24245592#24245592

- centering the input and button box:
https://stackoverflow.com/questions/34669062/input-type-doesnt-center

- center vertically and horizontally:
https://www.w3schools.com/css/css_align.asp

- random number generator:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random

# Deployed URL
- https://deno-shiritori-hikage.deno.dev/home.html