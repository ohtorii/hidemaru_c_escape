﻿# 文字列のエクスケープ処理を行う秀丸マクロ

文字列のエスケープとアンエスケープを行います。（C言語を対象としています。）

### エスケープ処理
    (前)
    c:\tmp\hoge.txt

    (後)
    c:\\tmp\\hoge.txt

### アンエスケープ処理
    （前）
    \"ひらがな\"
    \"日本語\"
    c:\\tmp\\hoge.txt

    （後）
    "ひらがな"
    "日本語"
    c:\tmp\hoge.txt


# 動作環境
秀丸エディタver8.20 beta14で動作を確認していますが、秀丸エディタver8以降なら動くと思います。


# インストール
以下ファイルを秀丸エディタのスクリプトディレクトリへコピーして、ショートカットキーに割り当てて下さい。
- cmd_escape_sequence.mac
- cmd_to_cstr.mac
- cmd_unescape_sequence.mac
