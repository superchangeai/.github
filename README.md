# About Superchange.ai ✨

Welcome!

## Problem

API specs, AI models lifecycle, devtools release notes – important updates are scattered everywhere. Superchange.ai solves a common developer problem: keeping track of changes across multiple services you build on.

## Solution

Superchange.ai aggregates changes and classify updates from countless providers into a single feed, refreshed daily. Instead of monitoring dozens of changelogs and documentation pages, Superchange.ai creates a single feed.

Thereafter you can:

1. Create your own changelog: Select the services, APIs, libraries, or platforms you care about. We curate what we use and love – you too can [contribute with providers you need](https://www.superchange.ai/providers/all#more).
2. Set up smart, filtered alerts: Choose the types of updates you want to know about – security fixes, breaking changes, performance improvements, new features – and skip the rest.
3. Stay in the loop: Decide how and when updates get delivered. Get instant notifications in Slack, a daily email digest, a weekly summary, or even route updates to a custom webhook.

## Components

1. [https://github.com/superchangeai/daily-snapshot](daily-snapshot) Archiving a daily snapshot of the DOM from chosen sources
2. [https://github.com/superchangeai/daily-change](daily-change) Computing and classifying differences using LLM calls
3. [https://github.com/superchangeai/www](www) Vue.js application to browse changes and set up actions at https://www.superchange.ai/
