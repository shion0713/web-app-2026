# API 仕様

## POST /api/persons
説明：req.body.name、req.body.age、req.body.emailを受け取ってpersonsに保存する
リクエスト：{"name":"木村星音", "age":19, "email": "@~"}
レスポンス：{"message" : "登録成功"}

## GET /api/persons
説明：名前、年齢、メールを表示する。
レスポンス：[{“id" : 1,"name" : "木村星音","age" : 19, "email" : "@~"}]