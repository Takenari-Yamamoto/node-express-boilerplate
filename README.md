# node-express-boilerplate

Node / Express のボイラープレート  
MongoDBの接続と基本的な CRUD 操作がPostman で確認できる程度なので随時追加していく

## Setup

```
git clone https://github.com/Takenari-Yamamoto/node-express-boilerplate.git
```
```
cd node-express-boilerplate
npm install 
npm run dev
```

`.env`の内容は個人のNotionに書いてます。

## API確認方法

```
npm run dev
```
`http://localhost:5000/api/posts`  
`http://localhost:5000/api/${id}`

params
- title: string
- content: string

 ## Todo
 
 認証機能  
 バリデーション
 
etc…
