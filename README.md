# インフラ練習用レポジトリ

### URL
https://tasobucket.s3.ap-southeast-2.amazonaws.com/index.html

### 技術スタック
GitHub Actions  
-CI, CD, SlackWebHook  
AWS  
-S3, IAM, CloudTrail, CloudWatch, Lamnbda

### Slack Notification

PRが作成されたら通知

![スクリーンショット 2024-06-23 200143](https://github.com/yatami38/tasosite/assets/110647327/d3585b9e-d28d-445a-b70f-fcebb56b921b)

$.userIdentity.Type が Root ではない者が tasobucket にアクセスしたら通知

![スクリーンショット 2024-06-23 220309](https://github.com/yatami38/tasosite/assets/110647327/915280dd-558a-4088-955d-414c21637cff)