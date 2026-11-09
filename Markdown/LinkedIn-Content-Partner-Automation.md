# LinkedIn Content Partner: Automation

Part 2 | Connect your AI to the tools that publish, engage, and measure | By Crystal Jones

Part 1 set up your content partner: a project or Gem, your source files, your instructions, and a monthly review. Everything in Part 1 works by hand and costs nothing. This guide connects your AI to tools that do the busywork for you: publishing your approved posts, engaging with people and posts in your field, and pulling your numbers.

Haven't set up Part 1 yet? Start with [LinkedIn Content Partner: Setup](https://github.com/crystaljonespmp/LinkedIn-Content-Partner-Setup).

## What MCP is

MCP stands for Model Context Protocol. It's an open standard that lets an AI assistant connect to your other apps and take action in them. Think of it as USB-C for AI: one plug that works with many tools.

Why it matters:

- **Your AI goes from advisor to doer.** It stops telling you what to do and does it, in your scheduler, your inbox, and LinkedIn.
- **No more copying and pasting.** Without MCP, every post means copy, open LinkedIn, paste, fix the formatting, pick a date and time, and confirm. With MCP, you approve the posts and say one sentence.
- **You stay in control.** You approve what the AI can see and what it can do.

## Which AI you can use

- **Gemini:** works on the free plan. Settings > Personal Intelligence > Connected Apps. Use a personal Google account.
- **Claude:** paid plan needed, about $20 a month for Pro. Settings > Connectors. The Free plan allows only one custom connector, which isn't enough for this workflow.
- **ChatGPT:** paid plan needed, about $20 a month for Plus. Settings > Plugins.
- **Microsoft Copilot:** not an option for this workflow. The personal app has no MCP, free or paid, and the work version needs an admin to approve every connector.

These companies change their plans often, so check before you buy anything.

### Connect a tool in Gemini

1. Open Gemini's **Settings**, then **Personal Intelligence**, then **Connected Apps**.
2. Click **+ Custom** in the top right.
3. Paste the tool's MCP server URL. It starts with https://, and each tool's site lists it.
4. Click **Next**, sign in to the tool, and approve the access it asks for.

## The tools

No single tool does everything. Schedulers publish your posts. Some let your AI read your analytics. Only Reach works inside LinkedIn to engage with other people.

| Tool | Cost | LinkedIn | X | Your AI reads analytics | Engagement |
|---|---|---|---|---|---|
| SocialBu Tier 2 | $129 lifetime | 1,500 posts a month | Included. 20 posts with links a month | Yes | Inbox, Listen |
| AdaptlyPost Tier 1 | $59 lifetime | Unlimited | 200 credits a month, 2 per post | Yes, with 180 days of history | No |
| Schedule & Chill | Free | 500 posts a month, 2 channels | $9 a month add-on | No. Free dashboard | No |
| PostMCP AI | Free | 20 credits a month | Included | Yes, 1 credit per lookup | No |
| Typefully | Free | 10 posts a month, all platforms | Included | No. Analytics are paid only | No |
| BulkPublish | Free | 30 posts a month, 3 in the queue | Pay-as-you-go credits | Yes | No |
| Reach MCP | $49 lifetime | Engagement, not scheduling | No | Shows who engaged | Yes |

What to know about each one:

- **SocialBu:** buy Tier 2 or higher on AppSumo. Tier 1 ($49) has no MCP. X posts without links count toward your 1,500 posts.
- **AdaptlyPost:** each X post uses 2 credits, or 20 if links stay clickable. Thread replies and first comments each count as a post. Founded in January 2026.
- **Schedule & Chill:** free for LinkedIn with a free MCP connector. X is a $9 a month add-on. Its analytics dashboard is free, but your AI can't read it. Launched in November 2026 by one builder.
- **PostMCP AI:** 20 free credits a month, and X is included. Each analytics lookup also uses a credit, so use LinkedIn's free export for your monthly review.
- **Typefully:** 10 free posts a month across all platforms. Each post in an X thread counts as one, so a 4-post thread uses 4.
- **BulkPublish:** the MCP connector works on the free plan, but the plan is tight: 1 post a day, 3 scheduled at a time, and 10 API requests a day. X costs extra.
- **Reach MCP:** works inside LinkedIn: finding people, finding posts, comments, connection requests, and messages. It's built around LinkedIn's limits, with a dedicated residential IP for each account, actions sent one at a time, daily quotas below LinkedIn's thresholds, and a numbered preview so nothing goes out until you approve it. It runs on the Kanbox engine, which 2,000+ teams have used for three years. Setup uses a Chrome extension that connects to your LinkedIn session without sharing your password. It also reads LinkedIn posts straight from a link. LinkedIn articles still have to be pasted.

## Recommended combos

### Combo 1: Lifetime deals plus free

| Piece | What it covers | Cost |
|---|---|---|
| SocialBu Tier 2 | Schedules LinkedIn and X. Your AI reads analytics through it. Inbox and Listen | $129 one time |
| Reach MCP | LinkedIn engagement and reading LinkedIn posts | $49 one time |
| Gemini Gem | Drafting | $0 |
| LinkedIn analytics export | Monthly review | $0 |
| **Total** | | **$178 one time** |

**Budget swap:**

| Piece | What it covers | Cost |
|---|---|---|
| AdaptlyPost Tier 1, in place of SocialBu | Schedules LinkedIn and X. Your AI reads analytics through it | $59 one time |
| Reach MCP | LinkedIn engagement and reading LinkedIn posts | $49 one time |
| Gemini Gem | Drafting | $0 |
| LinkedIn analytics export | Monthly review | $0 |
| **Total** | | **$108 one time** |

### Combo 2: Free only

| Piece | What it covers | Cost |
|---|---|---|
| Gemini Gem | Drafting | $0 |
| Schedule & Chill | Schedules LinkedIn, 500 posts a month | $0 |
| PostMCP AI | Schedules X, 20 credits a month | $0 |
| LinkedIn analytics export | Monthly review | $0 |
| **Total** | | **$0** |

Typefully's free plan is the alternate for X.

### Combo 3: Free plus Reach

| Piece | What it covers | Cost |
|---|---|---|
| Everything in Combo 2 | Drafting, scheduling, monthly review | $0 |
| Reach MCP | LinkedIn engagement and reading LinkedIn posts | $49 one time |
| **Total** | | **$49 one time** |

Combo 2 publishes your posts, but it does nothing to put you in front of other people. Combo 3 adds the piece that builds relationships.

Drafting in Claude or ChatGPT instead of Gemini? Add about $20 a month for the paid plan to any combo.

*Prices checked November 5 to 8, 2026. Confirm on each vendor's site before you buy.*

## Before you connect anything

- **Approve every post.** Tell your AI to show you the list before it schedules. Never let it publish on its own.
- **Start with one tool.** Get one tool working before you add another.
- **Check the tier.** MCP isn't on every plan. SocialBu, for example, needs Tier 2 on AppSumo.
- **Prices and plans change.** Lifetime deals come and go. Check the vendor's page the day you buy.

## Analytics with automation

The monthly review from Part 1 still runs the same way. Automation changes how you get the numbers:

- **No more export.** With SocialBu, AdaptlyPost, or PostMCP connected, say "Pull my numbers for last month" and your AI gets them itself.
- **See who engaged, not just how many.** Reach shows who liked and commented on your posts from the last 30 days. The question that matters: are recruiters and hiring managers the ones engaging?
- **Check in mid-month.** You don't have to wait for the end of the month to see how things are going.
- **Compare plan to results.** Your AI can match what you scheduled against how each post did.

On Combo 2, keep using LinkedIn's free export. Schedule & Chill's analytics aren't available to your AI, and PostMCP charges a credit for each lookup.

## Add these to your project instructions

Paste the sections that match your tools at the end of your project instructions. Fill in every [bracket].

```text
SCHEDULING
- When I say "schedule," show me the list of approved posts with dates and times, then schedule only those posts in [tool name]. Never publish immediately. Never schedule anything I have not approved. Confirm what was scheduled.
- [Only if you use a separate tool for X] Schedule my approved X posts in [X tool name].

ENGAGEMENT
- When I say "find people," search LinkedIn for [the people you want to reach, like recruiters and hiring managers for my target roles] and show me a numbered list with why each one is worth connecting with. For the ones I pick, draft a short, specific connection note. Send nothing until I approve.
- When I say "find posts," search LinkedIn for posts about [topics in my field] from the last week and show me a numbered list. For the ones I pick, draft a comment that adds something from my experience. Send nothing until I approve.
- When I say "follow up," summarize my unread LinkedIn messages and draft replies. Send nothing until I approve.
- When I share a LinkedIn post link, read it with Reach.

ANALYTICS
- When I say "monthly review" without attaching a file, pull last month's post numbers from [tool name], then run the monthly review the same way.
- [Only if you use Reach] Also pull who liked and commented on my posts in the last 30 days, and tell me how many are recruiters, hiring managers, or people in my target industries.
- When I say "check in," pull this month's numbers so far and tell me what's working. Save recommendations for the monthly review.
```

## Starter prompts

- "Schedule my approved posts on our days and times."
- "Find 5 posts about [topic] from this week and draft comments."
- "Find 10 recruiters for [target role] and draft connection notes."
- "Follow up: summarize my unread LinkedIn messages and draft replies."
- "Pull my numbers for last month and run my monthly review."
- "Check in: how are this month's posts doing so far?"

**Also on X?** See the bonus guide, [Network and Find Jobs on X](Bonus-Network-and-Find-Jobs-on-X.md).
