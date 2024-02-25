# SoraAIV
SoraAIV は、ユーザーがテキストを使って OpenAI の Sora モデルでオンラインビデオを生成できるようにすることで、ビデオ作成を簡素化するオープンソースプロジェクトです。
👉 [soraaiv](https://soraaiv.com)

[English](https://github.com/SoraAIV/SoraAIV/blob/main/README.md) | [简体中文](https://github.com/SoraAIV/SoraAIV/blob/main/README.zh-CN.md) | 日本語


# プロジェクトプラン
- ✅ 単語で動画を生成 ([FakeSoraAPI](https://github.com/SoraAIV/FakeSoraAPI) を使用):

  この機能は、👉 [main](https://github.com/SoraAIV/SoraAIV/tree/main) または 👉 [version-0.1](https://github.com/SoraAIV/SoraAIV/tree/version-0.1) で見ることができます

- ✅ Google でログイン:

  この機能は、👉 [login](https://github.com/SoraAIV/SoraAIV/tree/login) で見ることができます

- [ ] Stripe 決済：

  準備中

- [ ] OpenAI の Sora API を追加する：

  OpenAI が Sora の API を起動するのを待ってから、この機能を起動します。


## クイックスタート

### Vercel でデプロイ
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FSoraWebui%2FSoraWebui&project-name=SoraAIV&repository-name=SoraAIV&external-id=https%3A%2F%2Fgithub.com%2FSoraWebui%2FSoraWebui%2Ftree%2Fmain)

### 1. プロジェクトをクローン

```bash
git clone git@github.com:SoraAIV/SoraAIV.git
```

### 2. 依存関係をインストール

```bash
cd SoraAIV && yarn
#もしくは
cd SoraAIV && npm install
#もしくは
cd SoraAIV && pnpm install
```

### 3. .env.example をコピーし、.env.local にリネームする

```bash
# web サイト URL
NEXT_PUBLIC_SITE_URL=http://localhost

# openai 設定
OPENAI_API_KEY=sk-XXXXXX
OPENAI_API_BASE_URL=http://localhost:8081
OPENAI_API_MODEL=sora-1.0-turbo
```

### 4. 実行

```bash
yarn dev
#もしくは
npm run dev
#もしくは
pnpm dev
```

### 5. [http://localhost](http://localhost) をブラウザで開いてご覧ください。
![success_deploy.jpg](https://SoraAIV.com/success_deploy.jpg)


# 重要
SoraAIV が正しく機能するには [FakeSoraAPI](https://github.com/SoraAIV/FakeSoraAPI) が必要です。

