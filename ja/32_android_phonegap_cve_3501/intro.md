
<p>      Cordova framework でビルドされた Android アプリは、コンテンツを表示するために WebView コンポーネントを使用します。Cordova アプリは表示、あるいは XMLHttpRequest 経由での通信を許可される URL ホワイトリストを特殊化する可能性があります。しかし、このホワイトリストは非 http チャネルで通信するために JavaScript 経由で指示された時、 WebView コンポーネントによって使用されません。  </p> <p>   具体的に、インターネット上の届きうるサーバーに接続するアプリケーション JavaScript  からWebSocket 接続を開くことが可能です。もし攻撃者がアプリ内の任意の JavaScript を実行することが可能なら、攻撃者は HTTP ホワイトリストを回避して接続をどんなサーバーにも開くことが可能になります。</p> <p>    これは一般的な Android 上のハイブリッドアプリ構造の制限事項であり、 Apache Cordova に限ったことではありません。</p>