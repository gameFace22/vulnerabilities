
iOSには、実行時にアプリケーションが侵害されるのを防ぐいくつかのメカニズムがあります。iOSアプリケーションに影響を与えるセキュリティ問題を理解するためには、プラットフォームのセキュリティ機能を理解し、知っておくことが重要です。 

- コード署名：すべてのアプリケーションがApple発行の証明書を使用して承認されたソースから取得されることを保証する。（Apple発行の証明書を使用）
- アドレス空間配置のランダム化（ASLR）：通常、-fPIE -pieを使用してコンパイルされる