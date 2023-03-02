---
title: Analytics
description: Set up analytics
---

# Analytics

In this step, we'll set up analytics.

## PostHog

Neorepo uses [PostHog](https://posthog.com/) to track analytics. PostHog is an open-source product analytics platform. It's designed to be self-hosted, so you can use it to track your own analytics.

You can use PostHog to track your own analytics.

## Add your environment variables

1. Open the Vercel project you created in the previous step
2. Click the "Environment Variables" tab
3. Add the following environment variables (replace example values with your own)):
   - `POSTHOG_API_KEY`
   - `POSTHOG_HOST`
