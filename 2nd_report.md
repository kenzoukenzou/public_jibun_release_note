## 今週のハイライト

### インプット📕

#### 読んだ本
今週は以下の書籍を読み進めました。

- リーダブルコード

#### 意図に関して
今開発しているプロジェクトは、基本自分1人で実装していて、コードレビューもほとんど入っていないような状況です。
したがって、基盤コードを自分は理解できるけれど、自分以外の人（新しく入ってくる人など）が理解できない可能性があると考えました。

「リーダブルコード」を読み既存のプロジェクトについては、以下の修正を加えました。

1. AWS構成など可視化が難しいところはドキュメントに書き出す
2. サービスの概要や、新規事業として走り出した背景などをドキュメントにする
3. 自分で見返しても意図が分かりにくコードは、意図やそのコードが必要である背景などをコメントとして残す

#### 結果
ドキュメント整理などは短期的なリターンを得られるような行動ではないと思いますが、今後自分以外の人がコミットメントしてくれる場面や、プロジェクト自体を引継ぎする際には確実に役に立つであろう情報を整理することができました。

- 適宜リファクタリングして可読性の高いコードを書く習慣
- ドキュメントを書く習慣
- 議事録を残し整理する習慣
- テストを書く習慣

これらを社内に波及させていきたいと思っています。