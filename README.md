# OpenAI ChatGPT & GPT-3 Chat App

This is a chat application built using GPT-3, and updated to include GPT-3.5 (ChatGPT) as well.
ChatGPT is the default, using the "gpt-3.5-turbo" model. To use GPT-3 set the model to
"text-davinci-003" in `generate.js`.
It uses [Next.js](https://nextjs.org/), and builds off of the OpenAI API [quickstart tutorial](https://beta.openai.com/docs/quickstart). Edit the prompt in the generate.js file to describe the kind of chat character you'd like.
You can test out the prompts in [ChatGPT](https://chat.openai.com/), and also in the OpenAI Playground Chat example in [Chat mode](https://platform.openai.com/playground/p/default-chat?mode=chat) for GPT-3.5 and [Completion mode](https://platform.openai.com/playground/p/default-chat?mode=complete) for GPT-3.

## Setup

Install

```bash
$ npm install
```

Make a copy of the example environment variables file

```bash
$ cp .env.example .env
```

Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file, and add your prompt as well.

Run the app

```bash
$ npm run dev
```
