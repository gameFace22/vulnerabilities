
 Androidでは、AndroidManifest.xmlファイル内のアクティビティのインテントフィルタを宣言することは、アクティビティが他のアプリケーションにエクスポートされる可能性があることを意味します。もしアクティビティが単にアプリケーションの内部使用のみを意図していて、インテントフィルタが宣言されていたら、マルウェアを含む他のアプリケーションは、意図しない使用のためにアクティビティをアクティベートすることができます。</p>  <p>     Twiccaアプリ（バージョン0.7.0から0.9.30まで）の脆弱性の場合、Twiccaのアクティビティを起動すると、SDカードやネットワークにアクセスするパーミッションを持たない別のアプリは、TwiccaユーザのTwitterアカウントを使用して、SDカードに保存されている画像や動画をソーシャルネットワーキングサービスにアップロードできました。

