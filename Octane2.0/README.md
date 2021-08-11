# GitHub/dZone--data--benchmarkResults/Octane2.0

How to get result

(1) Run Octane 2.0

http://chromium.github.io/octane/

(2) Open console

右上の縦三点→「その他のツール」→「デベロッパーツール」→「Consoleタブ」

Three virtical dots -> Other Tools -> Developer Tools -> Console tab

(3) Copy the result to clipboard (paseboard)

(4) The following oneliners are useful

# On xclip-ready machines
$ xclip -o | sed 's/^[^ ]* //' | cat -n 

# On macOS
$ pbpaste | sed 's/^[^ ]* //' | cat -n 

-EOF-
