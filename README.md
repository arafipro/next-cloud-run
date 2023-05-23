# 参考サイト

https://nextat.co.jp/staff/archives/294

## 手順

1. package.jsonにコードを追加

```diff json
  "private": true,
+ "engines": {
+    "node": "18.x"
+  },
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
+   "gcp-build": "next build"
  },
```

2. GitHubにリポジトリを作成
3. Cloud Runにデプロイ
