<p align="center"><img src="https://raw.githubusercontent.com/ugcapi/.github/main/profile/logo.png" width="80" alt="UGC API logo"></p>

# UGC API

**The posting API for user-generated content.**

UGC API publishes and schedules videos, photo slideshows and images to the TikTok and Instagram accounts you connect. Send a post once and it goes out to every account you choose, as the right format on each platform: a TikTok video and an Instagram Reel, or a TikTok photo post and an Instagram carousel, with optional Story frames. It's built for UGC agencies, creator networks and apps that generate content for many accounts.

[Website](https://ugcapi.dev) · [Docs](https://ugcapi.dev/docs/quickstart/) · [Pricing](https://ugcapi.dev/pricing/) · [Claude plugin](https://github.com/ugcapi/plugin) · [Agent skill](https://github.com/ugcapi/agent-skill) · [n8n node](https://github.com/ugcapi/n8n-nodes-ugcapi)

## What you can do

- **Publish once to many accounts.** One request posts to any mix of connected TikTok and Instagram accounts, now or at a scheduled time. See [create a post](https://ugcapi.dev/docs/create-a-post/) and [formats and options](https://ugcapi.dev/docs/formats-and-options/).
- **Run campaigns.** Spread hundreds of posts across creator accounts on a cadence (posts per day, local times, timezone), preview the schedule and credits first, and cancel what hasn't gone out. See [campaigns](https://ugcapi.dev/docs/campaigns/).
- **Connect creators without passwords.** Send a connect link; the creator signs in to TikTok or Instagram themselves and the account appears in your workspace. See [connect accounts](https://ugcapi.dev/docs/connect-accounts/).
- **Know what happened.** Every post reports a result per account and placement, with public URLs, error reasons, retries, signed [webhooks](https://ugcapi.dev/docs/webhooks/) and [engagement stats](https://ugcapi.dev/docs/stats/).
- **Work as a team.** Invite teammates to a shared workspace with its own accounts, posts, credits and API keys.

Pricing is prepaid: $10 per 1,000 posts, 50 free when you sign up, and credits never expire. Failed and cancelled posts are refunded.

## Use it from your stack

| Where | How | Start here |
| --- | --- | --- |
| Your backend | REST API with an API key | [Quickstart](https://ugcapi.dev/docs/quickstart/) · [Authentication](https://ugcapi.dev/docs/authentication/) |
| Claude and other MCP clients | Remote MCP server at `https://ugcapi.dev/mcp` (OAuth) | [MCP docs](https://ugcapi.dev/docs/mcp/) · [Claude plugin](https://github.com/ugcapi/plugin) |
| AI agents | Agent skill with posting rules and workflows | [ugcapi/agent-skill](https://github.com/ugcapi/agent-skill) |
| n8n | Community node `n8n-nodes-ugcapi` | [ugcapi/n8n-nodes-ugcapi](https://github.com/ugcapi/n8n-nodes-ugcapi) · [n8n and Make guide](https://ugcapi.dev/guides/ugc-api-for-n8n-and-make/) |
| LLM context | Plain-text API summary | [llms.txt](https://ugcapi.dev/llms.txt) |

## Formats and platforms

- [UGC video API](https://ugcapi.dev/formats/ugc-video-api/) · [Slideshow API](https://ugcapi.dev/formats/slideshow-api/) · [TikTok photo carousel API](https://ugcapi.dev/formats/tiktok-photo-carousel-api/) · [Instagram Story API](https://ugcapi.dev/formats/instagram-story-api/)
- [TikTok posting API](https://ugcapi.dev/platforms/tiktok-posting-api/) · [Instagram posting API](https://ugcapi.dev/platforms/instagram-posting-api/)

## Who uses it

- [UGC agencies](https://ugcapi.dev/use-cases/ugc-agencies/) running many creator accounts
- [Creator networks](https://ugcapi.dev/use-cases/creator-networks/) that post on behalf of their members
- [UGC generator apps](https://ugcapi.dev/use-cases/ugc-generator-apps/) and [AI UGC tools](https://ugcapi.dev/use-cases/ai-ugc-tools/) that publish what they make
- [E-commerce brands](https://ugcapi.dev/use-cases/ecommerce-brands/) posting product content at volume

## Guides

- [Schedule UGC across many accounts](https://ugcapi.dev/guides/schedule-ugc-across-many-accounts/)
- [Post a TikTok slideshow via API](https://ugcapi.dev/guides/post-tiktok-slideshow-via-api/)
- [Post an Instagram carousel and Story](https://ugcapi.dev/guides/post-to-instagram-carousel-and-story/)
- [UGC posting cadence](https://ugcapi.dev/guides/ugc-posting-cadence/)
- [White-label social account connect](https://ugcapi.dev/guides/white-label-social-account-connect/)
- Comparisons: [Post for Me](https://ugcapi.dev/compare/post-for-me-alternative/) · [Ayrshare](https://ugcapi.dev/compare/ayrshare-alternative/) · [Upload-Post](https://ugcapi.dev/compare/upload-post-alternative/) · [Buffer API](https://ugcapi.dev/compare/buffer-api-alternative/) · [TikTok API vs UGC API](https://ugcapi.dev/compare/tiktok-api-vs-ugc-api/)

## Support

Email [hello@ugcapi.dev](mailto:hello@ugcapi.dev), or open an issue in the repository for the integration you're using. Keep API keys, account tokens and private content out of public issues. [Privacy](https://ugcapi.dev/privacy/) · [Terms](https://ugcapi.dev/terms/)

UGC API is not affiliated with TikTok or Meta. Facebook Pages and YouTube Shorts are not available yet.
