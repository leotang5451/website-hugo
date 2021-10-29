---
title: "leo貼文"
date: 2021-10-27T18:32:17+08:00
draft: true
---

# 1. 讀取帳戶資料(AC001)

---



### 1.6 返回参数

| Key               | type   | description                    |
| ----------------- | ------ | ------------------------------ |
| user_id           | string | 使用者id                       |
| ml_id             | string | 使用者meeline_id               |
| user_name         | string | 使用者姓名                     |
| user_image        | string | 使用者大頭照                   |
| user_sex          | string | 使用者性別 (男:1 女:2 預設:3 ) |
| user_area         | string | 使用者地區                     |
| note              | string | 使用者個性簽名                 |
| is_allow_red      | string | 紅包是否打開                   |
| is_allow_transfer | string | 是否允許發送                   |

### 1.7 返回 成功 訊息 (StatusValue 1 )

| Index | descriptions |
| ----- | ------------ |
| 1     | 請求成功     |
| 2     | 用户不存在   |

### 1.8 返回 錯誤 訊息 (StatusValue -1 )

| Index | descriptions       |
| ----- | ------------------ |
| 1     | 其他認證錯誤訊息！ |
| 2     | 用户不存在         |
| 3     | 验证错误           |
