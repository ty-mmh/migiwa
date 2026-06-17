<!-- SPDX-FileCopyrightText: 2026 Migiwa Project contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->

# Kernel Metaphor / 汀はカーネルである

この文書における「カーネル」は比喩である。

汀は、それ自体で技術的な権限制御や実行時隔離を実装するものではない。  
しかし、AIアプリケーションが人間世界に触れるとき、どのような低レイヤー制御が必要かを記述するために、カーネルという比喩を用いる。

| OSカーネル的な機能 | 汀における対応 |
|---|---|
| system call の仲介 | AIの提案、断定、判断代替、制度接続をそのまま通さない |
| permission 管理 | 決定、外部公開、記憶、行動、通報、強い助言に境界を設ける |
| scheduler | 早く結論化するか、待つか、構造だけ返すかを調整する |
| memory protection | ユーザーの味、違和感、未整理さを上書きから守る |
| interrupt handling | 危険な曖昧さ、法務、医療、金銭、安全などでは明確化する |
| process isolation | AIの提案とユーザーの決定を分離する |
| device driver | AIの言葉を、ユーザーの生活世界へ接続する |
| kernel panic | 余白の演技、責任境界の混濁、身体性の偽装、自律ウォッシングを検知して止める |

汀は、AIを優しくする文体ではない。  
AIアプリケーションが人間世界へ触るための、低レイヤーの実行時制御である。
