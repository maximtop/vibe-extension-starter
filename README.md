# Vibe Extension Starter

A minimal starter for building a small personal Chrome/Chromium extension with
an AI coding agent.

It intentionally has no framework, build step, package manager, or tests. Start
with one browser annoyance and ask the agent for the smallest visible result.

## Start in five minutes

1. Get the repository:
   - with Git: `git clone https://github.com/maximtop/vibe-extension-starter.git`
   - without Git: click **Code → Download ZIP**, then unzip it
2. Open the repository folder in your AI coding editor or agent.
3. Describe one thing you want to change in the browser.

For example:

> On example.com, replace every letter “A” with a fish emoji. Make the smallest
> working version, then tell me exactly how to load and test it in Chrome.

The agent should read [`AGENTS.md`](AGENTS.md) and [`manifest.json`](manifest.json),
then add only the files the extension actually needs.

## Load it in Chrome

1. Open `chrome://extensions`.
2. Enable **Developer mode**.
3. Click **Load unpacked**.
4. Select this repository folder — the one containing `manifest.json`.
5. Open the test page and check that the requested change is visible.

After every code change:

1. Click **Reload** on the extension card in `chrome://extensions`.
2. Reload the test page.
3. Try the same action again.

## Pick a small first idea

A good workshop idea:

- can be seen on one test page;
- fits in one sentence;
- works without a backend, login, payment, or store publication;
- can be checked manually in a couple of minutes.

Simple examples:

- replace a letter or word with an emoji;
- hide a distracting block on a website;
- highlight items that match a rule;
- add a button that copies useful text or links;
- change the appearance of one site.

## What is included

- `manifest.json` — the minimal Manifest V3 description of the extension;
- `AGENTS.md` — beginner-friendly instructions for the AI agent;
- `README.md` — the setup and loading steps you are reading now.

Chrome/Chromium is the default target. If you want Firefox, Safari, or another
browser, say so explicitly in your request to the agent.

Useful official guides:

- [Chrome Extensions: Get started](https://developer.chrome.com/docs/extensions/get-started)
- [Hello World and Load unpacked](https://developer.chrome.com/docs/extensions/get-started/tutorial/hello-world)

