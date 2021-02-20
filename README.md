<div align="center">
    <img src="assets/logo.png" width="400" height="400" alt="Slack Icon and Deno Icon merged">
    <h1>Deno Slack SDK</h1>
    <p>
        <b>Deno ports for <a href="https://github.com/slackapi/node-slack-sdk">node-slack-sdk</a> and <a href="https://github.com/slackapi/bolt">bolt</a></b>
    </p>
    <p>
        <img alt="runtime - deno" src="https://img.shields.io/badge/runtime-deno-brightgreen">
        <img alt="total - 8" src="https://img.shields.io/badge/total-8-blue">
        <img alt="typescript - 100%" src="https://img.shields.io/badge/typescript-100%25-blue">
    </p>
    <p>
        <b><a href="https://github.com/KhushrajRathod/Blueprint">View Blueprint</a> -- <a href="https://github.com/KhushrajRathod/DenoModules">Other deno modules</a></b>
    </p>
    <br>
    <br>
    <br>
</div>


# Table of Contents

- [Bolt](#bolt) - Abstraction over the Slack SDK

- [Slack SDK](#slack-sdk)
    - [Web API](#web-api)
    - [Socket Mode](#socket-mode)
    - [OAuth](#oauth)
    - [RTM API](#rtm-api)
    - [Webhook](#webhook)

- [Helpers](#helpers)
    - [Logger](#logger)
    - [Types](#types)

- [Deprecated](#deprecated)
    - [Interactive messages](#interactive-messages) - Use Bolt instead
    - [Events API](#events-api) - Use Bolt instead

# Bolt

<p>
    <img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/slack-bolt/Deno?label=checks" >
    <img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/slack-bolt" >
    <img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/slack-bolt">
    <img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/slack-bolt" >
    <img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/slack-bolt">
    <img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/slack-bolt">
</p>

<b><a href="https://github.com/KhushrajRathod/slack-bolt">View on GitHub</a></b> -- <b><a href="https://deno.land/x/slack_bolt">View on deno.land</a></b>

- Description: TypeScript framework to build Slack apps in a flash with the latest platform features ⚡️
- Node Equivalent: [@slack/bolt](https://www.npmjs.com/package/@slack/bolt)

# Slack SDK

## Web API

<p>
    <img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/slack-web-api/Deno?label=checks" >
    <img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/slack-web-api" >
    <img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/slack-web-api">
    <img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/slack-web-api" >
    <img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/slack-web-api">
    <img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/slack-web-api">
</p>

<b><a href="https://github.com/KhushrajRathod/slack-web-api">View on GitHub</a></b> -- <b><a href="https://deno.land/x/slack_web_api">View on deno.land</a></b>

- Description: Simple, convenient, and configurable HTTP client for making requests to Slack’s [Web API](https://api.slack.com/web)
- Node Equivalent: [@slack/web-api](https://www.npmjs.com/package/@slack/web-api)

## Socket Mode

<p>
    <img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/slack-socket-mode/Deno?label=checks" >
    <img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/slack-socket-mode" >
    <img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/slack-socket-mode">
    <img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/slack-socket-mode" >
    <img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/slack-socket-mode">
    <img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/slack-socket-mode">
</p>

<b><a href="https://github.com/KhushrajRathod/slack-socket-mode">View on GitHub</a></b> -- <b><a href="https://deno.land/x/slack_socket_mode">View on deno.land</a></b>

- Description: Recieve events from Slack's [Events API](https://api.slack.com/apis/connections/events-api) over a WebSocket connection
- Node Equivalent: [@slack/socket-mode](https://www.npmjs.com/package/@slack/socket-mode)

## OAuth

<p>
    <img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/slack-oauth/Deno?label=checks" >
    <img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/slack-oauth" >
    <img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/slack-oauth">
    <img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/slack-oauth" >
    <img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/slack-oauth">
    <img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/slack-oauth">
</p>

<b><a href="https://github.com/KhushrajRathod/slack-oauth">View on GitHub</a></b> -- <b><a href="https://deno.land/x/slack_oauth">View on deno.land</a></b>

- Description: Setup the OAuth flow for Slack apps easily
- Node Equivalent: [@slack/oauth](https://www.npmjs.com/package/@slack/oauth)

## RTM API

<p>
    <img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/slack-rtm-api/Deno?label=checks" >
    <img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/slack-rtm-api" >
    <img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/slack-rtm-api">
    <img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/slack-rtm-api" >
    <img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/slack-rtm-api">
    <img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/slack-rtm-api">
</p>

<b><a href="https://github.com/KhushrajRathod/slack-rtm-api">View on GitHub</a></b> -- <b><a href="https://deno.land/x/slack_rtm_api">View on deno.land</a></b>

- Description: Connect to the Slack platform over a persistent Websocket connection.
- Node Equivalent: [@slack/rtm-api](https://www.npmjs.com/package/@slack/rtm-api)

## Webhook

<p>
    <img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/slack-webhook/Deno?label=checks" >
    <img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/slack-webhook" >
    <img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/slack-webhook">
    <img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/slack-webhook" >
    <img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/slack-webhook">
    <img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/slack-webhook">
</p>

<b><a href="https://github.com/KhushrajRathod/slack-webhook">View on GitHub</a></b> -- <b><a href="https://deno.land/x/slack_webhook">View on deno.land</a></b>

- Description: Helper for making requests to [Slack's Incoming Webhooks](https://api.slack.com/incoming-webhooks)
- Node Equivalent: [@slack/webhook](https://www.npmjs.com/package/@slack/webhook)

# Helpers

## Logger

<p>
    <img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/slack-logger/Deno?label=checks" >
    <img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/slack-logger" >
    <img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/slack-logger">
    <img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/slack-logger" >
    <img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/slack-logger">
    <img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/slack-logger">
</p>

<b><a href="https://github.com/KhushrajRathod/slack-logger">View on GitHub</a></b> -- <b><a href="https://deno.land/x/slack_logger">View on deno.land</a></b>

- Description: Logger for [slack-deno](https://github.com/slack-deno) packages
- Node Equivalent: [@slack/logger](https://www.npmjs.com/package/@slack/logger)

## Types

<p>
    <img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/slack-types/Deno?label=checks">
    <img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/slack-types" >
    <img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/slack-types">
    <img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/slack-types" >
    <img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/slack-types">
    <img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/slack-types">
</p>

<b><a href="https://github.com/KhushrajRathod/slack-types">View on GitHub</a></b> -- <b><a href="https://deno.land/x/slack_types">View on deno.land</a></b>

- Description: Types for [slack-deno](https://github.com/slack-deno)
- Node Equivalent: [@slack/types](https://www.npmjs.com/package/@slack/types)

# Deprecated

## Interactive messages

Use [Bolt](#bolt) instead

## Events API

Use [Bolt](#bolt) instead