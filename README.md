# このレポジトリについて
- https://github.com/being24/latex-template-ja を参考にしています.
  - devcontainerで環境を閉じています.
- 研究室向けです. 研究計画書など, レポートを書く際に使用することを想定しています.
  - custard的にはQuartoがおすすめです.


# 使い方
git, ghはドキュメントを参照するか, AIに聞くと良いです.

また, dockerを用意しておきましょう. devcontainerについては[こちら](https://code.visualstudio.com/docs/devcontainers/containers)をご参照ください.

## レポジトリ作成
このレポジトリはテンプレートです. `gh repo create`で流用できます.
`gh repo create my_report --template="custard-1855/report_template_tex" --private --clone`

## 開く
`code`でVScodeを起動し, devcontainerを起動します.
