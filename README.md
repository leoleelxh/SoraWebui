# SoraAIV
SoraAIV is an open-source project that simplifies video creation by allowing users to generate videos online with OpenAI's Sora model using text, featuring easy one-click website deployment.
👉 [SoraAIV](https://SoraAIV.com)

English | [简体中文](https://github.com/SoraAIV/SoraAIV/blob/main/README.zh-CN.md) | [日本語](https://github.com/SoraAIV/SoraAIV/blob/main/README.ja-JP.md)


# Project Plan
- ✅ Generate video by words(Use [FakeSoraAPI](https://github.com/SoraAIV/FakeSoraAPI)):

  You can see this feature in 👉 [main](https://github.com/SoraAIV/SoraAIV/tree/main) or 👉 [version-0.1](https://github.com/SoraAIV/SoraAIV/tree/version-0.1)

- ✅ Login with Google:

  You can see this feature in 👉 [login](https://github.com/SoraAIV/SoraAIV/tree/login)

- [ ] Stripe payment：

  Coming soon

- [ ] Add OpenAI’s Sora API：

  Waiting for OpenAI launch Sora's API, then we will launch this feature.


## Quick Started

### Deploy on Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FSoraWebui%2FSoraWebui&project-name=SoraAIV&repository-name=SoraAIV&external-id=https%3A%2F%2Fgithub.com%2FSoraWebui%2FSoraWebui%2Ftree%2Fmain)

### 1. Clone project

```bash
git clone git@github.com:SoraAIV/SoraAIV.git
```

### 2. Install dependencies

```bash
cd SoraAIV && yarn
#or
cd SoraAIV && npm install
#or
cd SoraAIV && pnpm install
```

### 3. copy .env.example and rename it to .env.local

```bash
# website URL
NEXT_PUBLIC_SITE_URL=http://localhost

# openai config
OPENAI_API_KEY=sk-XXXXXX
OPENAI_API_BASE_URL=http://localhost:8081
OPENAI_API_MODEL=sora-1.0-turbo
```

### 4. Run it

```bash
yarn dev
#or
npm run dev
#or
pnpm dev
```

### 5. Open [http://localhost](http://localhost) with your browser to see it.
![success_deploy.jpg](https://SoraAIV.com/success_deploy.jpg)


# Important
SoraAIV requires [FakeSoraAPI](https://github.com/SoraAIV/FakeSoraAPI) to function properly.

