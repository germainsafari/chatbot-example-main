## Pre-reqs

Sign up for Open AI and take note of the API key.

Create an assistant in the Open AI Playground and take note of the assistant ID.

## Setup

You need [Node.js](https://nodejs.org/en/) installed to use this code.

Uses pnpm because it's faster than npm.

First install pnpm:

```bash
npm install -g pnpm
```

Then clone this repo then install dependenices:

```bash
git clone git@github.com:ashleydavis/chatbot-example.git
cd chatbot-example
pnpm install
```

## Run the backend

Open a terminal and change into the backend subdirectory:

```bash
cd chatbot-example-main/backend
```

Now set required environment variables.

On MacOS and Linux

```bash
export OPENAI_API_KEY=<your api key>
export ASSISTANT_ID=<your assistant id>
```

Or on Windows:

```bash
set OPENAI_API_KEY=<your api key>
set ASSISTANT_ID=<your assistant id>
```

Run the backend in dev mode:

```bash
pnpm run dev
```

## Run the frontend

Open a terminal and change to the frontend subdirectory:

```bash
cd chatbot-example-main/murafrontend
```

Run the frontend in dev mode:

```bash
pnpm run dev
```

Open a browser and navigate to [http://localhost:1234/](http://localhost:1234/).

## Build the static web page

```bash
cd chatbot-example/frontend
pnpm run build
```

## Build the TypeScript code

Do this if you want to check for compile errors.

```bash
cd chatbot-example/frontend
pnpm run compile
```
