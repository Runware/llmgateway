# Weekly Product Metrics — 2026-07-13

> **Period:** Jul 6–12, 2026 (this week) vs Jun 29–Jul 5, 2026 (last week)
> Note: `code.llmgateway.io` resolves in PostHog as `devpass.llmgateway.io` — reported under that name below.

---

## Overall Traffic (This Week vs Last Week)

| Product | PV (this) | PV (last) | WoW PV | Uniques (this) | Uniques (last) | WoW Uniques | Sessions (this) | Sessions (last) | WoW Sessions |
|---|---|---|---|---|---|---|---|---|---|
| llmgateway.io | 21,761 | 18,634 | **+16.8%** | 5,187 | 4,120 | **+25.9%** | 6,700 | 5,525 | **+21.3%** |
| devpass.llmgateway.io | 13,316 | 10,437 | **+27.6%** | 1,185 | 820 | **+44.5%** | 3,429 | 2,380 | **+44.1%** |
| docs.llmgateway.io | 2,192 | 1,792 | **+22.3%** | 732 | 555 | **+31.9%** | 839 | 672 | **+24.9%** |
| chat.llmgateway.io | 1,344 | 1,012 | **+32.8%** | 214 | 245 | **-12.7%** | 266 | 313 | **-15.0%** |

---

## llmgateway.io

### Headline Numbers
- **PV:** 21,761 (+16.8% WoW) | **Uniques:** 5,187 (+25.9%) | **Sessions:** 6,700 (+21.3%)
- **Bounce rate:** 57.7% vs 54.9% last week (+2.8pp, **+5.1% relative** — degrading)
- **Avg PV/session:** 3.25 vs 3.37 last week (-3.6%)

### Top 10 Pages (This Week)
| Page | Views | Uniques |
|---|---|---|
| / | 3,465 | 2,234 |
| /models | 1,921 | 717 |
| /signup | 813 | 654 |
| /pricing | 786 | 635 |
| /dashboard | 627 | 312 |
| /timeline/2026 | 539 | 472 |
| /timeline | 475 | 392 |
| /login | 392 | 266 |
| /blog/best-ai-coding-plans | 375 | 316 |
| /features/unified-api-interface | 274 | 204 |

Notable: `/blog/best-ai-coding-plans` is already the #9 page by volume. `/timeline/2026` is strong at #6.

### Top 10 Referrers (This Week)
| Referrer | Views | Uniques |
|---|---|---|
| (direct) | 9,342 | 2,386 |
| www.google.com | 7,591 | 2,239 |
| devpass.llmgateway.io | 1,254 | 171 |
| llmgateway.io (self) | 963 | 160 |
| www.bing.com | 403 | 107 |
| accounts.google.com | 235 | 50 |
| cn.bing.com | 204 | 89 |
| github.com | 204 | 56 |
| chatgpt.com | 134 | 29 |
| www.google.com.hk | 132 | 32 |

Notable: `trustmrr.com` sent 117 views from 37 uniques — worth monitoring as a new affiliate/review source. `t.co` (Twitter/X) at 127 views/69 uniques shows social traction.

### Top 10 Countries (This Week)
| Country | Views | Uniques |
|---|---|---|
| South Korea | 4,656 | 446 |
| United States | 3,125 | 1,290 |
| India | 1,166 | 312 |
| China | 1,027 | 492 |
| Germany | 829 | 152 |
| Singapore | 705 | 291 |
| Japan | 580 | 126 |
| Indonesia | 559 | 100 |
| Hungary | 470 | 37 |
| Spain | 447 | 65 |

⚠️ **South Korea** is #1 by views with 4,656 PV but only 446 uniques (10.4:1 ratio) vs US at 3,125 PV / 1,290 uniques (2.4:1). South Korea view-to-unique ratio is 4x higher than US — warrants a check on whether Korean users are power users, or if there's an automated referral/scraper.

### Device Breakdown
| Device | Views | Uniques |
|---|---|---|
| Desktop | 17,238 | 4,200 |
| Mobile | 4,428 | 1,026 |
| Tablet | 99 | 24 |

Mobile share: 20.4% of PV, 19.8% of uniques.

### Flagged
- Bounce rate crept up 2.8pp WoW; not yet at 15% regression threshold but trending in wrong direction.
- `llmgateway.io` self-referral (963 views, 160 uniques) is SPA navigation noise — expected.

---

## devpass.llmgateway.io (code.llmgateway.io)

### Headline Numbers
- **PV:** 13,316 (+27.6% WoW) | **Uniques:** 1,185 (+44.5%) | **Sessions:** 3,429 (+44.1%)
- **Bounce rate:** 43.1% vs 39.4% last week (+3.7pp, **+9.4% relative** — degrading)
- **Avg PV/session:** 3.88 vs 4.39 last week (-11.6%)

### Top 10 Pages (This Week)
| Page | Views | Uniques |
|---|---|---|
| /dashboard | 6,704 | 443 |
| / | 2,345 | 997 |
| /dashboard/billing | 804 | 188 |
| /pricing | 644 | 449 |
| /login | 626 | 165 |
| /dashboard/settings | 482 | 137 |
| /coding-models | 429 | 227 |
| /profile | 390 | 133 |
| /signup | 377 | 247 |
| /guides | 141 | 96 |

Note: `/dashboard` has a 15.1:1 view-to-unique ratio (6,704/443) — below the 20:1 bot flag threshold but indicates heavy dashboard polling or page refreshes by active users.

### Top 10 Referrers (This Week)
| Referrer | Views | Uniques |
|---|---|---|
| (direct) | 10,358 | 802 |
| www.google.com | 1,175 | 246 |
| devpass.llmgateway.io (self) | 515 | 59 |
| accounts.google.com | 472 | 42 |
| llmgateway.io | 363 | 99 |
| checkout.stripe.com | 184 | 23 |
| t.co | 40 | 23 |
| www.bing.com | 29 | 7 |
| www.reddit.com | 27 | 13 |
| gemini.google.com | 22 | 3 |

`checkout.stripe.com` (184 views, 23 uniques) = post-purchase return traffic. `gemini.google.com` appearing as a referrer suggests AI assistant-driven discovery.

### Top 10 Countries (This Week)
| Country | Views | Uniques |
|---|---|---|
| South Korea | 9,198 | 448 |
| United States | 726 | 156 |
| Japan | 429 | 43 |
| Indonesia | 231 | 24 |
| France | 218 | 24 |
| India | 190 | 40 |
| Thailand | 180 | 15 |
| Germany | 173 | 30 |
| Türkiye | 170 | 6 |
| Canada | 125 | 25 |

⚠️ **South Korea concentration: 69% of all PV** (9,198/13,316) from 448 uniques (38% of total). This is a very skewed geographic distribution — likely a cohort of active Korean dev-plan subscribers driving most usage. Not necessarily problematic but worth monitoring.

### Device Breakdown
| Device | Views | Uniques |
|---|---|---|
| Desktop | 9,555 | 810 |
| Mobile | 3,732 | 426 |
| Tablet | 29 | 9 |

Mobile share is relatively high at 28% of PV — notable for a dev-tools dashboard product.

### Flagged
- Bounce rate up 3.7pp; avg PV/session down 11.6% — visitors are exploring less per session.
- South Korea dominates 69% of PV; single-country concentration is high.

### Funnel: Landing → Signup → dev_plan_subscribe_started
- `/signup` page: 377 views, 247 uniques this week
- `dev_plan_subscribe_started`: 235 events, 154 unique users
- Estimated landing-to-subscribe rate: 154/247 = **62%** of /signup unique visitors → this is healthy, though note the attribution is imperfect (subscribe intent may not come only from /signup).

---

## docs.llmgateway.io

### Headline Numbers
- **PV:** 2,192 (+22.3% WoW) | **Uniques:** 732 (+31.9%) | **Sessions:** 839 (+24.9%)
- **Bounce rate:** 62.3% vs 58.9% last week (+3.4pp, **+5.8% relative** — degrading)
- **Avg PV/session:** 2.61 vs 2.67 last week (-2.2%)

### Top 10 Pages (This Week)
| Page | Views | Uniques |
|---|---|---|
| / | 547 | 348 |
| /self-host | 135 | 93 |
| /guides/cursor | 125 | 110 |
| /quick-start | 123 | 95 |
| /overview | 84 | 67 |
| /features/routing | 76 | 61 |
| /self-host/docker | 61 | 39 |
| /v1_models | 55 | 44 |
| /self-host/docker-compose | 50 | 25 |
| /v1_chat_completions | 41 | 24 |

Notable: `/guides/cursor` is #3 with a strong 110/125 unique ratio — nearly all visitors are new/organic. Self-hosting pages dominate bottom half, indicating healthy self-hosted user base.

### Top 10 Referrers (This Week)
| Referrer | Views | Uniques |
|---|---|---|
| (direct) | 1,525 | 439 |
| www.google.com | 349 | 221 |
| llmgateway.io | 128 | 40 |
| docs.llmgateway.io (self) | 67 | 17 |
| devpass.llmgateway.io | 18 | 5 |
| llmgw-1.docker.01.servidorpro.com | 18 | 1 |
| chatgpt.com | 15 | 7 |
| www.bing.com | 12 | 5 |
| teams.public.onecdn.static.microsoft | 11 | 5 |
| statics.teams.cdn.office.net | 7 | 6 |

Notable:
- `llmgw-1.docker.01.servidorpro.com` (18 views, 1 unique) — a specific self-hosted instance referencing the docs. Likely an internal deployment with docs embedded.
- `teams.public.onecdn.static.microsoft` + `statics.teams.cdn.office.net` (18 combined views) — Microsoft Teams users reading LLM Gateway docs, indicating enterprise interest.
- `chatgpt.com` as referrer (15 views, 7 uniques) — ChatGPT users being sent to docs.

### Top 10 Countries (This Week)
| Country | Views | Uniques |
|---|---|---|
| United States | 549 | 236 |
| South Korea | 246 | 77 |
| Germany | 138 | 33 |
| Spain | 116 | 8 |
| China | 113 | 31 |
| India | 109 | 45 |
| Singapore | 98 | 37 |
| Hungary | 81 | 10 |
| Indonesia | 62 | 10 |
| United Kingdom | 46 | 21 |

⚠️ Spain: 116 views from only 8 uniques (14.5:1 ratio) — unusually high. Could be a scraper or a small team hammering the docs. Worth a spot check.

### Device Breakdown
| Device | Views | Uniques |
|---|---|---|
| Desktop | 1,968 | 651 |
| Mobile | 223 | 83 |
| Tablet | 1 | 1 |

### Flagged
- Bounce rate up 3.4pp; docs bounce is structurally high (readers often find what they need on one page) but the trend is worth watching.
- Spain docs traffic: 116 views / 8 uniques = 14.5:1. Below 20:1 bot threshold but notable.

---

## chat.llmgateway.io

### Headline Numbers
- **PV:** 1,344 (+32.8% WoW) | **Uniques:** 214 (-12.7%) | **Sessions:** 266 (-15.0%)
- **Bounce rate:** 42.1% vs 45.4% last week (-3.3pp, **-7.3% relative** — improving)
- **Avg PV/session:** 5.05 vs 3.23 last week (+56.3%)

⚠️ **Anomaly:** PV is up 33% but sessions and uniques are both down ~13–15%. The remaining users are far more engaged (avg 5 pages/session vs 3.2 last week), but the top-of-funnel is contracting. This could reflect a shift from broad discovery to a retained power-user base, or reduced acquisition.

### Top 10 Pages (This Week)
| Page | Views | Uniques |
|---|---|---|
| / | 728 | 205 |
| /pricing | 209 | 83 |
| /projects | 96 | 13 |
| /skills | 75 | 4 |
| /signup | 56 | 39 |
| /image | 50 | 15 |
| /video | 39 | 15 |
| /group | 22 | 13 |
| /login | 22 | 6 |
| /canvas | 20 | 12 |

`/pricing` is #2 by views (209) with 83 uniques — strong monetization intent. `/skills` has 75 views from only 4 uniques (18.75:1) — nearing the bot threshold, but likely a small set of heavy users exploring skills.

### Top 5 Referrers (This Week)
| Referrer | Views | Uniques |
|---|---|---|
| (direct) | 811 | 199 |
| chat.llmgateway.io (self) | 475 | 1 |
| www.google.com | 31 | 6 |
| llmgateway.io | 13 | 3 |
| chatgpt.com | 6 | 1 |

⚠️ `chat.llmgateway.io` as self-referrer: 475 views, **1 unique visitor**. This is almost certainly SPA navigation being recorded as a referring domain rather than true external referral — but the extreme concentration (1 user) is unusual. Could be a single automated session or a stuck PostHog referrer property.

### Top 10 Countries (This Week)
| Country | Views | Uniques |
|---|---|---|
| United States | 615 | 42 |
| Hungary | 87 | 9 |
| South Korea | 67 | 18 |
| India | 54 | 18 |
| Vietnam | 44 | 8 |
| Indonesia | 38 | 10 |
| Japan | 35 | 8 |
| Türkiye | 35 | 8 |
| Hong Kong | 35 | 6 |
| Jordan | 27 | 2 |

⚠️ United States: 615 views from only 42 uniques (14.6:1 ratio) — the highest ratio in the list. A small US cohort is driving most of the PV. Jordan: 27 views from 2 uniques (13.5:1) — worth noting.

### Device Breakdown
| Device | Views | Uniques |
|---|---|---|
| Desktop | 1,164 | 170 |
| Mobile | 174 | 43 |
| Tablet | 6 | 1 |

### Flagged
- Sessions and uniques both down >12% WoW — acquisition is shrinking even as engagement deepens. Need to watch whether this is a seasonal dip or a structural decline.

---

## Product Events — This Week vs Last Week

| Event | Count (this) | Count (last) | WoW Count | Users (this) | Users (last) | WoW Users |
|---|---|---|---|---|---|---|
| pricing_plan_clicked | 800 | 102 | **+684.3%** ⚠️ | 97 | 74 | +31.1% |
| cta_clicked | 768 | 748 | +2.7% | 403 | 347 | +16.1% |
| dev_plan_subscribe_started | 235 | 134 | **+75.4%** | 154 | 91 | +69.2% |
| api_key_created | 230 | 238 | **-3.4%** | 167 | 203 | **-17.7%** |
| dev_plan_started | 156 | 94 | +66.0% | 1 | 1 | — |
| credits_purchased | 147 | 127 | +15.7% | 1 | 1 | — |
| provider_key_added | 113 | 34 | **+232.4%** ⚠️ | 10 | 16 | -37.5% |
| user_signed_up | 96 | 100 | **-4.0%** | 96 | 100 | -4.0% |
| playground_chat_sent | 73 | 133 | **-45.1%** ⚠️ | 19 | 17 | +11.8% |
| topup_completed | 67 | 35 | **+91.4%** | 20 | 10 | +100% |
| onboarding_completed | 66 | 58 | +13.8% | 63 | 55 | +14.5% |
| user_logged_in | 48 | 41 | +17.1% | 38 | 32 | +18.8% |
| onboarding_try_success | 31 | 22 | +40.9% | 18 | 17 | +5.9% |
| dev_plan_tier_changed | 23 | 21 | +9.5% | 21 | 18 | +16.7% |
| dev_plan_renewed | 17 | 32 | **-46.9%** ⚠️ | 1 | 1 | — |
| playground_image_generated | 15 | 16 | -6.3% | 5 | 5 | 0% |
| playground_video_generated | 8 | 4 | +100% | 5 | 3 | +66.7% |
| subscription_created | 0 | 1 | **-100%** | 0 | 1 | -100% |
| playground_group_chat_started | 0 | 4 | **-100%** | 0 | 4 | -100% |

### Key observations:
- **Positive:** `dev_plan_subscribe_started` (+75%), `topup_completed` (+91%), `dev_plan_started` (+66%), `onboarding_completed` (+14%) — strong activation and monetization signals.
- **Negative:** `playground_chat_sent` (-45%), `dev_plan_renewed` (-47%), `api_key_created` unique users (-18%), `user_signed_up` (-4%).
- `dev_plan_started` and `credits_purchased` show 1 unique user each — these are system/automation events; count changes may reflect infrastructure behavior rather than user actions.

### Signup Funnel (llmgateway.io)
- `/signup` page visitors (unique): **653**
- `user_signed_up` events: **96** (96 unique users)
- Conversion rate: **14.7%**
- This is below the ~19% implied last week (100 signups / ~520 estimated /signup uniques). Worth tracking as a proper funnel over time.

---

## Top 3 Things to Investigate This Week

### 1. `pricing_plan_clicked` event firing bug — Jul 11 spike (708 events, 24 users)

Daily breakdown of `pricing_plan_clicked`:
- Jun 29–Jul 10: 9–31 events/day (9–26 users/day) — normal
- **Jul 11: 708 events from only 24 users = 29.5 avg clicks/user**
- Jul 12: 20 events, 18 users — back to normal

This is a data quality issue, not real user behavior. Something changed on Jul 11 that caused the event to fire ~30x per user session (vs ~1x normally). Check for: scroll-triggered event bindings, a pricing section rendered multiple times, observer-based tracking that misfired, or a re-render loop. The total weekly count of 800 looks like massive growth but is inflated by this one-day bug — actual organic pricing interest is ~97 users which is a real +31% growth WoW.

### 2. `playground_chat_sent` dropped 45% (133→73) — engagement collapse in chat

Despite unique users being flat (17→19), total chats sent dropped from 133 to 73, meaning avg chats/user fell from 7.8 to 3.8. Simultaneously, chat.llmgateway.io sessions dropped 15% and uniques dropped 13%. This is a compound signal: fewer users are visiting and those who do are chatting significantly less. Check for: rate-limit changes, a broken model or provider in the playground, UX friction added, or reduced discoverability. The `/skills` page shows 4 unique users generating 75 PV (18.75:1) — a small power-user cohort is inflating engagement stats.

### 3. `dev_plan_renewed` dropped 47% (32→17) — renewal pipeline regression

Renewals halved WoW. Given that both periods show only 1 unique user (i.e., this is likely a system/cron-driven event), the drop in count from 32 to 17 may indicate a subscription renewal job running less frequently, timing out, or erroring silently. Separately, `subscription_created` went from 1→0. Investigate the renewal cron/webhook handler for failures in the last 7 days.

---

## Bot / Data-Quality Flags

### Pages with >20:1 view-to-unique ratio (≥50 pageviews)

| Host | Page | Views | Uniques | Ratio |
|---|---|---|---|---|
| llmgateway.io | /dashboard/DjH5omDnqm3tjxAD5f2D/... | 72 | 1 | 72:1 |
| llmgateway.io | /dashboard/ebvz8Qb2itvfRPqxPzeK/... | 64 | 1 | 64:1 |
| llmgateway.io | /dashboard/t9phefwLHI39QljN55VU/.../activity | 55 | 1 | 55:1 |
| llmgateway.io | /dashboard/2reEnMZhpmLI31pufG9H/... | 52 | 1 | 52:1 |

These are individual power users (1 unique each) who heavily refreshed their personal dashboards. Not bot traffic — but these sessions inflate the overall PV count for llmgateway.io. Combined ~243 views from 4 users are included in the headline 21,761 PV.

### Self-referrer flag: chat.llmgateway.io
- `chat.llmgateway.io` appears as its own referrer for 475 views from **1 unique visitor**.
- Likely a PostHog SPA tracking issue where in-app navigation retains the same domain as referrer. The 1-user concentration is unusual though — could be a single automated testing session. Does not materially inflate traffic numbers but skews referrer attribution.

### `pricing_plan_clicked` event inflation (Jul 11)
- 708 out of 800 total weekly `pricing_plan_clicked` events occurred on a single day from 24 users.
- Weekly count of 800 is **not** representative of actual pricing intent — true signal is ~92 events on other days of the week.
- Do not use this week's `pricing_plan_clicked` count for conversion rate calculations until the root cause is confirmed and fixed.

### `provider_key_added` concentration
- 113 events from 10 unique users = **11.3 keys/user** this week vs 2.1 keys/user last week.
- High but potentially legitimate if users are bulk-adding provider integrations (e.g., after a UI feature release). Confirm no automated test accounts are included.

### South Korea + Hungary concentration
- South Korea drives 21.4% of llmgateway.io PV and 69% of devpass PV from a small unique base.
- Hungary appears in top-10 for llmgateway.io (470 PV, 37 uniques = 12.7:1), docs (81 PV, 10 uniques), and chat (87 PV, 9 uniques).
- Neither exceeds 20:1 thresholds but the multi-product concentration pattern is worth a geo-IP spot check.
