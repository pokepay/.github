# Pokepay


## Partner SDK for Pokepay enterprise

Partner APIを利用するためのライブラリです.
Partner APIは、組織が運用するサーバとPokepayサーバとの間の連携のためのものです。
このAPIの通信には、クライアント証明書が必要であることに加え、独自の暗号化処理が必要であり、暗号化・復号化のための仕様を正しく理解し、正確に実装するハードルが高いため、SDKの利用を推奨しています.

各言語のSDKは、APIの仕様ファイルから半自動的に生成し、テスト実施後、それぞれ手動でリリースしています.
APIドキュメントは、各SDK内に含まれています.

|言語|github repository|package repository|
|---|---|---|
|C#|[pokepay-partner-csharp-sdk](https://github.com/pokepay/pokepay-partner-csharp-sdk)|https://www.nuget.org/packages/pokepay-partner-csharp-sdk|
|Java|[partner-java-sdk](https://github.com/pokepay/partner-java-sdk)|
|NodeJS|[pokepay-partner-node-sdk](https://github.com/pokepay/pokepay-partner-node-sdk)|https://www.npmjs.com/package/@pokepay/pokepay-partner-sdk|
|PHP|[partner-php-sdk](https://github.com/pokepay/partner-php-sdk)|https://packagist.org/packages/pokepay/partner-php-sdk
|Python|[pokepay_partner_python_sdk](https://github.com/pokepay/pokepay_partner_python_sdk)|
|Ruby|[pokepay_partner_ruby_sdk](https://github.com/pokepay/pokepay_partner_ruby_sdk)|https://rubygems.org/gems/pokepay_partner_ruby_sdk|


## Mobile SDK for Pokepay enterprise

Bank APIを利用するためのライブラリです.
Bank APIは、エンドユーザが所有するスマートフォンや、店舗等に配置するレジ端末からPokepayに接続するためのAPIです。

詳細なドキュメントを別途ございますので、組み込みをご検討の際は、弊社営業宛にご連絡ください.

|プラットフォーム|github repository|
|---|---|
|iOS|[ios-sdk](https://github.com/pokepay/ios-sdk)|
|Android|[android-sdk](https://github.com/pokepay/android-sdk)|
|Flutter|[flutter-sdk](https://github.com/pokepay/flutter-sdk)|

