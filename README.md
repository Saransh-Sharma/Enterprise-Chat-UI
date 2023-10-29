# `ENTERPRISE-CHAT-UI` 🤖💬

Welcome to `ENTERPRISE-CHAT-UI` 👋 powered by OpenAI GPT-4 and beyond. This responsive web app comes with Personas, Drawing, Code Execution, PDF imports, Voice support,
data Rendering, AGI functions, chats and much more. 

Or fork & run on Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fenricoros%2Fbig-agi&env=OPENAI_API_KEY,OPENAI_API_HOST&envDescription=OpenAI%20KEY%20for%20your%20deployment.%20Set%20HOST%20only%20if%20non-default.)

## ✨ Key Features 👊

![Ask away, paste a ton, copy the gems](docs/pixels/big-AGI-compo1.png)

- **AI Personas**
- **Polished UI**: installable web app, mobile-friendly, token counters, etc.
- **Fast UX**: Microphone, Camera OCR, Drag files, Voice Synthesis
- **Models**: [OpenAI](https://platform.openai.com/overview), [Anthropic](https://www.anthropic.com/product), [Azure](https://oai.azure.com/), [OpenRouter](https://openrouter.ai/), [Local models](https://github.com/oobabooga/text-generation-webui), and more
- **Private**: use your own API keys and self-host if you like
- **Advanced**: PDF import & Summarization, code execution
- **Integrations**: ElevenLabs, Helicone, Paste.gg, Prodia and more


<br/>

## 🧠 Latest Drops

#### Next

- **Cloudflare API Gateway** support
- **Helicone for Anthropic** support
- **Text Tools** - incl. highlight differences


<br/>

## Why this? 💡

Because the official Chat ___lacks important features___, is ___more limited than the api___, at times
___slow or unavailable___, and you cannot deploy it yourself, remix it, add features, or share it with
your friends.
Our users report that ___big-AGI is faster___, ___more reliable___, and ___features rich___
with features that matter to them.

![Much features, so fun](docs/pixels/big-AGI-compo2b.png)

## Develop 🧩

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=&logo=vercel&logoColor=white)

Clone this repo, install the dependencies, and run the development server:

```bash
git clone https://github.com/enricoros/big-agi.git
cd big-agi
npm install
npm run dev
```

Now the app should be running on `http://localhost:3000`

### Integrations:

* [ElevenLabs](https://elevenlabs.io/) Voice Synthesis (bring your own voice too) - Settings > Text To Speech
* [Helicone](https://www.helicone.ai/) LLM Observability Platform - Models > OpenAI > Advanced > API Host: 'oai.hconeai.com'
* [Paste.gg](https://paste.gg/) Paste Sharing - Chat Menu > Share via paste.gg
* [Prodia](https://prodia.com/) Image Generation - Settings > Image Generation > Api Key & Model

## Deploy with Docker 🐳

For more detailed information on deploying with Docker, please refer to the [docker deployment documentation](docs/deploy-docker.md).

### 🔧 Locally built image

> Firstly, write all your API keys and env vars to an `.env` file, and make sure the env file is using *both build and run*.
> See [docs/environment-variables.md](docs/environment-variables.md) for a list of all environment variables.

```bash

```bash
docker build -t big-agi .
docker run --detach 'big-agi'
``` 

### Pre-built image

> Warning: the UI will still be asking for keys, as the image was built without the API keys

```bash
docker-compose up
```

## Deploy with Cloudflare Pages ☁️

Please refer to the [Cloudflare deployment documentation](docs/deploy-cloudflare.md).

## Deploy with Vercel 🚀

Create your GitHub fork, create a Vercel project over that fork, and deploy it. Or press the button below for convenience.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fenricoros%2Fbig-agi&env=OPENAI_API_KEY,OPENAI_API_HOST&envDescription=OpenAI%20KEY%20for%20your%20deployment.%20Set%20HOST%20only%20if%20non-default.)



<br/>

This project is licensed under the MIT License.

[![GitHub stars](https://img.shields.io/github/stars/enricoros/big-agi)](https://github.com/enricoros/big-agi/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/enricoros/big-agi)](https://github.com/enricoros/big-agi/network)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/enricoros/big-agi)](https://github.com/enricoros/big-agi/pulls)
[![License](https://img.shields.io/github/license/enricoros/big-agi)](https://github.com/enricoros/big-agi/LICENSE)

[//]: # ([![GitHub issues]&#40;https://img.shields.io/github/issues/enricoros/big-agi&#41;]&#40;https://github.com/enricoros/big-agi/issues&#41;)

Made with 💙
