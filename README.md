『異世界メイドはまさかの俺⁈ 横スクゲーのアソビカタ』
iPhone Safari用 体験プロトタイプ Ver.0.1

内容：HTML5 CanvasとJavaScriptのみで動く試作ゲーム。
未使用：提供されたゲーム画面画像、正式なドット絵、音声、BGM、ノベル。
キャラ・背景・敵はプログラムで描画した仮のピクセル表現です。

■ 操作
iPhone：横画面で左右ボタン・JUMP・攻撃・交代・共鳴。
PC：←→ / A D 移動、Space / W ジャンプ、J 攻撃、K 交代、L 共鳴。
ゲージMAXで「共鳴」を押すとTriple Resonance発動。
敵を倒して右端へ進む。最後の大きな魔物を倒すとクリア。

■ iPhoneで遊ぶための公開手順（GitHub Pages）
1. GitHubアカウントを作る。https://github.com
2. 新規リポジトリを「isekaimaid-demo」の名前で作る。公開範囲はPublic。
3. index.html をリポジトリの一番上の階層（root）へアップロードしてコミット。
4. リポジトリの Settings → Pages → Build and deployment → Source を「Deploy from a branch」にする。
5. Branch: main / (root) → Save。
6. GitHub Pagesに表示されるURL（一般に https://＜ユーザー名＞.github.io/isekaimaid-demo/ ）をSafariで開く。
7. Safariの共有メニューから「ホーム画面に追加」→「Webアプリとして開く」→「追加」。

GitHub Pagesは外部に公開されます。試作のソースコードもPublicリポジトリなら公開されるため、未公開の原稿・個人情報・ライセンスコード等は含めないでください。

■ 補足
- index.html 1ファイルで動きます。サーバー側のプログラムは不要です。
- ローカルファイルをiPhoneの「ファイル」でタップした場合、環境によりJSが動かないことがあります。公開URLで開く方法を推奨します。
- 画面の回転ロックを解除し、横向きで遊んでください。
- iPhone実機での動作確認は行っていません。実機で操作・音声・性能を確認してください。
- これはプロトタイプであり、App Store向けアプリパッケージではありません。
