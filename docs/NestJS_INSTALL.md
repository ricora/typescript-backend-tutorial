# NestJSの環境構築

## 必要なもの
  
- Node.js

## 環境構築

### Nest CLIのインストール（最初だけ。2つ目以降のプロジェクトでは不要！）

```
npm i -g @nestjs/cli
```

### プロジェクトを作成して移動。

```
nest new プロジェクト名
```

gitリポジトリを作らない場合は、`-g` オプションを付けて、

```
nest new -g プロジェクト名
```

とする。

```
? Which package manager would you ❤️  to use?
```

と聞かれたら、 `npm` を選択して、**ENTER**。

```
cd プロジェクト名
```

## 実行方法

```
npm run start
```