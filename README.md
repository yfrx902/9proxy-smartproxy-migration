# smartproxy alternative: pay-per-IP pricing with unlimited bandwidth, all current 9Proxy plans, and how to migrate

If you searched this, you probably weren't shopping for a new proxy provider for fun. Something on your Smartproxy invoice stopped working for you. Maybe the monthly bandwidth reset swallowed the traffic you paid for. Maybe you crossed into a few hundred GB a month and the per-GB line item started competing with your actual hosting bill. Or maybe you just noticed that several comparison tables online still say "Smartproxy" while the site you land on says Decodo.

All three are real reasons to look for a smartproxy alternative, and they have different answers. So let's separate them before recommending anything.

## Smartproxy is Decodo now, and that's usually the actual question

Smartproxy rebranded to Decodo. The product lines, account system and pricing moved with the name, and decodo.com's own footer still reads "© 2018-2026 decodo.com (formerly smartproxy.com)" [1]. Some directories and blog posts kept the old URL structure, which is why searches like "smartproxy vs webshare" still return pages that describe Decodo the whole way through [2].

So if your question was "does Smartproxy still exist" — yes, under a new name, same company, same Lithuanian base, same residential pool.

That leaves the more useful question: if you're already on Decodo and something about it doesn't fit, what do you move to? That depends on which of these is true for you.

- You need mobile, ISP or datacenter proxies from one vendor → Decodo still covers that spread.
- You need the largest possible pool and deep targeting for hostile targets → Decodo, Oxylabs and Bright Data remain the names to benchmark.
- You need a lot of bandwidth without a per-GB meter running → that's where the model breaks, and that's what most of the rest of this page is about.

## When staying on Decodo still makes sense

No switch is universally correct, so here's the case against moving.

Decodo's residential network is advertised at 125M+ IPs across 195+ countries, and it sells residential, mobile, static ISP and datacenter proxies plus a web scraping API [2][3]. Its residential entry tier runs $3.75/GB on the 3GB plan, stepping down to $3.50 at 10GB, $3.25 at 25GB, $3.00 at 50GB and $2.75 at 100GB, with pay-as-you-go at $4/GB [4]. The "$2/GB" figure you'll see in headlines is the enterprise tier, not the self-serve one [4][5]. It also runs a 3-day trial with 100MB of traffic, and reviewers note that ID verification is required to reach popular target groups [6].

If your monthly volume is small, if you specifically need mobile or ISP proxies, or if the geographic spread of a 125M+ pool is the point of your project, there is no reason to move. Stay.

The pressure builds in two places: per-GB billing at volume, and bandwidth that expires if you don't spend it inside the billing window [4].

## What the alternative looks like: 9Proxy's pay-per-IP model

9Proxy is a residential proxy provider that sells the same kind of IPs on a different meter. Instead of charging per gigabyte, its core model charges per IP address with unlimited traffic on that IP [7][8].

That single change explains the price difference you'll see in a moment, because your cost stops scaling with how much data you pull. Scrape 100 pages through an IP or 10,000 pages through it — the price for that IP doesn't move [7].

The network is advertised at 20M+ residential IPs across 90+ countries, with targeting by country, state, city, ZIP code and ISP, and both HTTP/HTTPS and SOCKS5 support listed across its public product pages [7][9][10].

### Two products, two very different workflows

**Residential Proxy by IPs.** You buy a fixed number of IPs. An IP is deducted when you forward it to a local port, unused IPs sit in your balance indefinitely, and an activated proxy stays up for a few hours up to roughly 24 hours, varying naturally because these are real residential connections [8]. If one dies, you can replace it manually within a short free-replacement window or automate it with the app's Auto Refresh and Auto Rotation features [8][10]. The catch: this model runs through the 9Proxy desktop app for Windows, macOS or Linux, using `localhost:port` forwarding [8].

**Residential Proxy by GB.** Pay for traffic, generate unlimited endpoints, with rotating or sticky session modes, authenticated by username/password or IP whitelist, straight from the dashboard — no app needed [8]. Purchased traffic is valid for 180 days, or unlimited on Enterprise plans [8][11]. Targeting to city and ZIP level is the reason people pick this model when they need rotation breadth rather than session stability [7].

Bundles mix both, which is the practical option if part of your workflow needs sticky IPs and part needs high rotation.

> Worth knowing before you buy: the IP-based and bundle models are prepaid balances, not subscriptions. Nothing renews automatically, unused IPs never expire, and unused GB have a 180-day window (unlimited on Enterprise) [8][11].

## All current 9Proxy plans and prices

9Proxy raised prices for IP-based and bundle packages on June 1, 2026, and left GB-based pricing untouched [11]. That matters because a lot of third-party comparison pages are still quoting the pre-adjustment rates — you'll find $20 for 100 IPs on older articles, which is no longer the published price. The tables below use the post-adjustment figures [7][12].

**IP-based packages** (unlimited bandwidth per IP, one-off purchase, unused IPs never expire)

| Plan | What you get | Price (USD) | Effective rate | Buy |
| --- | --- | --- | --- | --- |
| Entry | 100 IPs | $24 | $0.24/IP | [Start with the 100-IP package](https://bit.ly/9-Proxy) |
| Small team | 500 IPs | $72 | $0.144/IP | [Get the 500-IP package](https://bit.ly/9-Proxy) |
| Scale-up | 1,000 IPs + 500 bonus IPs | $126 | $0.084/IP | [Buy 1,000 IPs with 500 bonus](https://bit.ly/9-Proxy) |
| Mid | 2,500 IPs | $210 | $0.084/IP | [Check the 2,500-IP tier](https://bit.ly/9-Proxy) |
| Growth | 5,000 IPs | $360 | $0.072/IP | [See the 5,000-IP package](https://bit.ly/9-Proxy) |
| High volume | 15,000 IPs | $720 | $0.048/IP | [View the 15,000-IP package](https://bit.ly/9-Proxy) |
| Bulk | 25,000 IPs | $863 | $0.035/IP | [Get the 25,000-IP package](https://bit.ly/9-Proxy) |
| Bulk+ | 50,000 IPs | $1,438 | $0.029/IP | [Buy the 50,000-IP package](https://bit.ly/9-Proxy) |
| Business | 100,000 IPs | $2,300 | $0.023/IP | [Request business-tier pricing](https://bit.ly/9-Proxy) |
| Business | 200,000 IPs | $4,140 | $0.021/IP | [See the 200,000-IP business package](https://bit.ly/9-Proxy) |
| Business | 500,000 IPs | $8,625 | $0.018/IP | [Check the 500,000-IP business package](https://bit.ly/9-Proxy) |

**GB-based packages** (pay per GB, unlimited endpoints, dashboard access)

| Plan | Price (USD) | Effective rate | Validity | Buy |
| --- | --- | --- | --- | --- |
| 5 GB | $15 | $3.00/GB | 180 days | [Grab the 5 GB starter pack](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | $105 | $2.10/GB | 180 days | [Get 50 GB plus 5 GB free](https://bit.ly/9-Proxy) |
| 100 GB | $150 | $1.50/GB | 180 days | [Buy the 100 GB package](https://bit.ly/9-Proxy) |
| 200 GB | $200 | $1.00/GB | 180 days | [See the 200 GB package](https://bit.ly/9-Proxy) |
| 1,000 GB | $800 | $0.80/GB | 180 days | [Check the 1,000 GB package](https://bit.ly/9-Proxy) |
| 2,000 GB | $1,500 | $0.75/GB | 180 days | [Get the 2,000 GB package](https://bit.ly/9-Proxy) |
| 3,000 GB (Enterprise) | $2,160 | $0.72/GB | Unlimited | [Ask about the 3,000 GB Enterprise plan](https://bit.ly/9-Proxy) |
| 6,000 GB (Enterprise) | $4,200 | $0.70/GB | Unlimited | [Ask about the 6,000 GB Enterprise plan](https://bit.ly/9-Proxy) |
| 10,000 GB (Enterprise) | $6,800 | $0.68/GB | Unlimited | [Ask about the 10,000 GB Enterprise plan](https://bit.ly/9-Proxy) |

**Bundle packages** (IPs plus traffic in one purchase)

| Plan | What you get | Price (USD) | Buy |
| --- | --- | --- | --- |
| Starter bundle | 100 IPs + 5 GB | $30 | [Start with the bundle package](https://bit.ly/9-Proxy) |
| Popular bundle | 1,500 IPs + 50 GB | $180 | [Get the popular bundle](https://bit.ly/9-Proxy) |
| Pro bundle | 5,000 IPs + 500 GB | $720 | [Check the Pro bundle](https://bit.ly/9-Proxy) |

All figures are USD, prepaid, and reflect 9Proxy's published pricing after the June 2026 update [11][12]. Payments are accepted by credit card, cryptocurrency, local payment methods, Google Pay, Alipay and the 9Proxy Wallet [8].

## The 100GB test: where per-GB pricing actually hurts

Numbers make the argument faster than adjectives.

Take a project that moves 100GB of residential traffic a month. On Decodo's 100GB residential tier that's $2.75/GB, or about $275 — and any unused portion of that bandwidth expires monthly rather than carrying over [4]. On 9Proxy's GB-based 100GB package the same 100GB costs $150 at $1.50/GB, and it stays usable for 180 days [7].

Now the part that changes the conversation entirely. If your workflow tolerates IPs that live hours rather than months, 100 IPs with unlimited bandwidth is $24 on 9Proxy [12]. That's not a 20% saving; it's a different category of cost, and it's the specific reason people start hunting for a smartproxy alternative in the first place.

The honest counterweight: unlimited bandwidth only helps if your automation can live with the app's forwarding model, and IPs that rotate out every few hours are useless for workflows that need a fixed address for weeks. Sticky residential sessions up to 24 hours are a real feature in some pipelines. So run this test before switching — take one month of your actual usage and ask two questions: how many gigabytes did I move, and how long did each session need to survive? If the answers are "a lot" and "not long", per-GB billing is the wrong model for you.

## How to migrate without rebuilding your stack

Switching proxy providers sounds heavier than it is. In most stacks it's three lines of configuration. The real work is picking the right 9Proxy model.

1. **Register through the invite link and confirm the code applied.** 👉 [Open your 9Proxy account with the invite code pre-filled](https://bit.ly/9-Proxy). Google sign-in is supported, and the process takes under a minute [8].
2. **Choose your model based on session behaviour, not on price.** Need the same IP for hours of work, account sessions or a checkout flow? Take IP-based. Need thousands of rotating endpoints across cities for SERP checks or price collection? Take GB-based and skip the app entirely.
3. **Install the app only if you went IP-based.** Windows, macOS and Linux builds are available; the GB-based model runs from the dashboard alone [8].
4. **Set your targeting and authentication.** Country, state, city, ZIP and ISP filters apply in both models. GB-based accepts username/password or IP whitelisting; IP-based uses local port forwarding with optional proxy authentication [8].
5. **Wire it into your tooling.** Existing HTTP/HTTPS and SOCKS5 clients mostly need a host:port swap. For IP-based, that host is `localhost` with the forwarded port; for GB-based, it's the endpoint from the proxy generator.
6. **Turn on Auto Refresh for IP-based workloads** so dead IPs get swapped without you watching the dashboard [8].

Keep the Decodo account open for a month while you compare success rates on your own targets. Your targets are the only benchmark that matters, and no provider's marketing page can substitute for that.

## What you give up with 9Proxy

Being straight about this is more useful than another comparison matrix.

The IP-based model requires the desktop app. If you run everything from containers or a remote server, that's friction you don't have with a pure API provider, and at least one review flagged the app requirement as a complication for multi-device setups [8][13]. The same review noted detection on some streaming services, though it rated the network well for e-commerce and automation work [13]. IP lifetime is genuinely variable — a few hours to about a day — and that's inherent to residential sourcing rather than a bug [8].

There's also no documented mobile, ISP or datacenter line yet; 9Proxy's own documentation lists two residential models and nothing else [8]. If your project needs mobile IPs, this is not your vendor. And if you need the biggest advertised pool in the market, 20M+ IPs against Decodo's 125M+ is a real difference, not a rounding error [2][7].

## Discounts and signup credit

Two things are worth checking rather than assuming.

Signing up through the link above attaches invite code **12345** to your account. 9Proxy's affiliate program documentation states that referred users receive a 5% discount, so it's worth confirming that discount shows on your first purchase rather than trusting it silently [14]. Separately, the 1,000 IP tier already bundles 500 bonus IPs for $126, and paying with cryptocurrency has been listed as adding a 5% IP bonus [10][12]. Package bonuses at 9Proxy change more often than base prices do, so check the billing page before you pay rather than relying on any coupon list, including this one.

## FAQ

**Is Smartproxy shutting down?**
No. Smartproxy rebranded to Decodo and the business continues under that name, with the old brand still referenced in its own site footer and in legacy URLs [1][2].

**Is 9Proxy cheaper than Decodo for residential proxies?**
On published rates, yes at most volumes — $1.50/GB against $2.75/GB at the 100GB tier, and $24 per 100 IPs with unlimited bandwidth as an entirely separate option [4][7][12]. The comparison only holds if the workload fits the model; session requirements matter more than the rate.

**Can I use 9Proxy without installing the desktop app?**
Yes, on GB-based packages. The dashboard handles endpoint generation, targeting and authentication. The IP-based model requires the app for local port forwarding [8].

**Does 9Proxy support rotating and sticky sessions?**
Both, on GB-based plans, with rotation per request or sessions that switch when the configured session time ends [8].

**Do unused 9Proxy balances expire?**
Purchased IPs never expire. GB-based traffic is valid for 180 days, and Enterprise GB plans have unlimited validity [8][11].

## Who should actually switch

If your monthly traffic is low, you need mobile or ISP proxies, or the size of a 125M+ pool is doing real work for you, stay on Decodo and ignore this whole category of search results.

If your logs show steady gigabyte growth with sessions measured in minutes or hours, per-GB billing is charging you for a resource you're not rationing. That's the case 9Proxy was built for: 👉 [start with a $24 100-IP package](https://bit.ly/9-Proxy) or a 👉 [100GB traffic package at $1.50/GB](https://bit.ly/9-Proxy), then compare success rates against your current provider on your own targets. Whichever model you pick, the decision should come from your bandwidth graph and your session durations — not from a table on someone's blog, this one included.
