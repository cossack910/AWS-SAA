# ASW CloudTrail

公式
https://aws.amazon.com/jp/cloudtrail/features/

**AWS ユーザーの操作(API コールやユーザのサインインアクティビティ)をロギングするサービス**

- ルートアカウント/IAM ユーザーのオペレーションと API コールをトラッキングしてログを取得するサービス
- CloudTrail ログファイルは暗号化されて S3 に保存 (5GB までは無料)
- KMS(AWS Key Management Service) による暗号化サポート
- デフォルトでは 90 日ログが保管される
- 無料

KMS
https://docs.aws.amazon.com/ja_jp/kms/latest/cryptographic-details/intro.html
