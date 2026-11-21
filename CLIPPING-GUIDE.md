# GTA 6 clipping: where the paid campaigns are, and how to start

Short guide for people who commented CLIP. Checked on 20 November 2026. Rates and budgets change every day, so check each campaign page yourself before you start.

## What clipping is

Big streamers play GTA 6 for hours. They pay editors ("clippers") to cut the best moments into short vertical clips for Reels, Shorts, TikTok and X. You get paid by the views your clips get, not by the hour.

## Where to find paid campaigns

1. **Content Rewards on Whop** (whop.com, search "GTA 6", "gaming clipping" or "content rewards"). Each campaign owner sets a rate per 1,000 views, a cap per clip and a minimum payout, and approves every clip before it pays.
2. **A streamer's own clipping program.** Many big streamers run one through their Discord. Read their pinned rules.
3. **Your own stream or your own gameplay.** No permission problem at all.

## What it pays

Across 50 public campaigns in September 2026, the typical rate was about $1 per 1,000 views, with a range from $0.05 to $3. Many campaigns have a cap per clip and stop paying when their budget is spent. So 100,000 views on one clip at $1 per 1,000 is about $100, if the campaign approves it and still has budget.

## Rules that keep you paid

- Clip only streams a campaign or the streamer allows. Clipping random streams can get your account struck.
- Add something: a hook line, captions, a short comment. Plain re-uploads are often rejected and earn less.
- Keep the streamer's handle on screen if the brief asks for it.
- No leaked or pre-release footage, no "free download" or "play early" posts, no piracy.
- Rockstar's video policy is written for fan videos. It does not clearly say paid clips are allowed, so stay inside a campaign's rules.

## The free plugin (in this folder)

This folder is a Claude Code plugin with 16 skills: it finds live campaigns, ranks trending GTA 6 videos and live streams, picks the moments where chat explodes, cuts 1080 x 1920 clips with word-by-word captions, writes hooks and checks each clip against the campaign rules. It never posts anything by itself.

Install it in Claude Code with the two lines in README.md, then paste the "First run" prompt from the README.

You need Python 3.10+, ffmpeg and yt-dlp (the setup skill installs them). An NVIDIA graphics card makes the captions faster but is not required.

## A first day that works

1. Run the campaign finder and pick one campaign with budget left.
2. Read its rules and copy them into campaigns.md.
3. Find that streamer's latest GTA 6 stream, cut 3 clips of 7 to 30 seconds.
4. Check them with the rule checker, post, and submit the links.
5. Next day, look at which clip got the most views and make more like it.

No income is promised. Your result depends on speed, the moments you pick and your hooks.
