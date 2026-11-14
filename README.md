# akile aff: what the referral code changes, what Akile Cloud costs now, and which plans are actually in stock

Akile Cloud is a London-registered VPS seller (AKILE LTD, 71-75 Shelton Street, Covent Garden, WC2H 9JQ) running nodes in Hong Kong, Singapore, the US, the UK, Japan, Korea, Taiwan and a few European markets. An `akile aff` link is a referral tag: the `aff_code` parameter records who sent you and does not change your price, your plan or your refund rights. What does move your bill is tier and stock. The live order pages currently show Hong Kong HKPro from ¥114.99/month with all four tiers marked Sold Out, and Singapore SGBase from ¥35/month, where only the two unlimited-traffic plans (¥235 and ¥360) are actually buyable.

Below are the prices that load on the shop today, the 2023-2024 review prices that still circulate and no longer match, the per-plan traffic-reset fee that decides your real monthly cost, the refund window, and the cases where you should buy somewhere else.

> **Short version.** If you need a box today: SGBase-UNLIMITED-500M, ¥235/month, 1 core / 2GB / 10GB, 500Mbps, unlimited traffic, 4 in stock. If you need Hong Kong or a China-optimised US line specifically, wait for a restock instead of buying a Singapore box that carries no mainland routing guarantee. 👉 [Check current stock and prices on the Akile order page](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## What is in stock right now, and at what price

Two node families returned live plan pricing: Hong Kong HKPro and Singapore SGBase. Prices are in CNY as displayed, monthly, and stock is as shown on the order page.

| Plan | Core specs | Traffic / port | Price and stock | Order |
| --- | --- | --- | --- | --- |
| HKPRO-Starter | 1 core, 1024M, 20GB | 500G/month, 100M | ¥114.99/mo, Sold Out | [View HKPro plans](https://akile.io/shop/server?type=traffic&areaId=3&nodeId=3&planId=818&aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKPRO-Standard | 1 core, 1024M, 20GB | 1000G/month, 100M | ¥214.49/mo, Sold Out | [View HKPro plans](https://akile.io/shop/server?type=traffic&areaId=3&nodeId=3&planId=818&aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKPRO-Pro | 2 cores, 2048M, 20GB | 2000G/month, 150M | ¥429.99/mo, Sold Out | [View HKPro plans](https://akile.io/shop/server?type=traffic&areaId=3&nodeId=3&planId=818&aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| HKPRO-Max | 4 cores, 4096M, 20GB | 4000G/month, 200M | ¥849.99/mo, Sold Out | [View HKPro plans](https://akile.io/shop/server?type=traffic&areaId=3&nodeId=3&planId=818&aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGBase-Lite | 1 core, 1024M, 10GB | 3000G/month, 2000M | ¥35.00/mo, Sold Out | [View SGBase plans](https://akile.io/shop/server?type=traffic&areaId=7&nodeId=20&planId=901&aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGBase-Standard | 1 core, 2048M, 10GB | 6000G/month, 2000M | ¥70.00/mo, Sold Out | [View SGBase plans](https://akile.io/shop/server?type=traffic&areaId=7&nodeId=20&planId=901&aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGBase-UNLIMITED-500M | 1 core, 2048M, 10GB | Unlimited, 500M | ¥235.00/mo, 4 in stock | [View SGBase plans](https://akile.io/shop/server?type=traffic&areaId=7&nodeId=20&planId=901&aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |
| SGBase-UNLIMITED-1000M | 1 core, 3072M, 20GB | Unlimited, 1000M | ¥360.00/mo, 6 in stock | [View SGBase plans](https://akile.io/shop/server?type=traffic&areaId=7&nodeId=20&planId=901&aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811) |

Second-order details worth knowing before you pick:

- Every HKPro and SGBase plan ships 1 IPv4. The Singapore plans add 1 IPv6; HKPro lists 0 IPv6.
- Traffic over the monthly cap is throttled to 10Mbps rather than billed, and the shop sells a separate traffic reset per plan (more on the fees below).
- HKPro is described on the order page as three-network optimised with a native IP. The Singapore node carries an explicit disclaimer: no guarantee for China direct routes, with private DNS intended for streaming unlocks.
- The Hong Kong region selector still lists HK-OPT, HKLite, 香港家宽, HKS, HKPro and HKPlus as separate nodes. HKPlus exists as a node but did not return a current plan price on the pages that loaded HKPro, so any HKPlus figure you see elsewhere is unconfirmed.

## The 2023-2024 prices you'll still find in reviews

Older write-ups quote much lower numbers because they cover different product lines, different currencies and, in one case, a discount code that was live at the time. They are useful as a record of what each line is, not as a quote.

| Line / plan | Config as reviewed | Price then | When listed |
| --- | --- | --- | --- |
| HKPlus-Starter | 1 core EPYC 7402, 1GB, 20GB NVMe, 500GB, 200M | $5.92/mo after a 20% recurring code | June 2024 |
| HKPlus-Standard | 1 core EPYC 7402, 1GB, 20GB NVMe, 1000GB, 250M | $12.40/mo after the same code | June 2024 |
| LAXPremium-M1 | 1 core, 1024M, 20GB SSD, 500GB, 100M, 1 IPv4 + 1 IPv6, US native IP, 20Gbps DDoS | $4.13/mo after the same code | June 2024 |
| UK Lite2 | 1 vCPU Ryzen 9 7900, 1GB, 10GB, 1TB at 500Mbps | ¥19.99/mo, extra 1TB at ¥14 | November 2024 |
| UK Lite2 (2-core) | 2 vCPU, 2GB, 1000Mbps | ¥87.49/mo | November 2024 |
| US Premium (unnamed tier) | 500GB, 9929 / CMIN2 / CN2 GIA routes, 20Gbps DDoS | ¥30/mo | March 2024 |

A separate community table from September 2025 lists "akile" at ¥39/month with 1000M port and 500G bidirectional traffic, but that table was written from memory by its author and explicitly says so. No ¥39 plan appears on the order pages today, which is the practical argument for checking the shop rather than a comparison post.

## What the aff_code does, and where discounts come from

The `aff_code` in the URL is an account identifier. Landing on `akile.io/register?aff_code=...` pre-fills that identifier at signup, and from then on the referrer gets credited for the account. It does not reduce the plan price, it does not unlock a hidden tier, and it does not affect your refund eligibility. Anyone telling you an affiliate link is where the discount lives has the mechanism backwards: the discount field sits at checkout, separate from the referral parameter.

On codes themselves, the honest position: the only widely circulated Akile code traces back to a June 2024 618 promotion that ran as a 20% recurring discount across the catalogue. There is no current official promotion page in what the shop surfaces, and a 2026 third-party deal roundup floating sitewide and LAX-scoped percentages could not be matched against anything Akile publishes. Test whatever code you have in the redemption field on the product page before you pay. If the total does not drop, close the tab and buy at list price.

Also note the checkout currency. The order pages above quote CNY. Older English reviews quote USD for Hong Kong and Los Angeles lines. Do not convert one into the other to compare plans across years.

## Traffic resets are the real cost line

Nearly every plan throttles to 10Mbps once the monthly allowance is gone. That is survivable for a backup node and miserable for anything interactive, so most heavy users end up buying a reset instead. The reset price scales with the plan and it is where a cheap-looking tier stops being cheap:

- HKPRO-Starter: ¥100 per reset for 500G
- HKPRO-Standard: ¥200 for 1000G
- HKPRO-Pro: ¥400 for 2000G
- HKPRO-Max: ¥800 for 4000G
- SGBase-Lite: ¥30 for 3000G
- SGBase-Standard: ¥60 for 6000G
- Both SGBase unlimited plans: ¥10, listed as a reset fee despite the unlimited allowance

Run the arithmetic on HKPRO-Starter: ¥114.99 monthly plus one reset is ¥214.99, which is Standard money for Starter specs. If you expect to hit the cap most months, buy the tier with the bigger allowance instead of resetting. On the September 2024-era UK line the equivalent add-on was ¥14 per extra 1TB, roughly a seventh of the Hong Kong reset cost for twice the data, which tells you the reset fee is a per-node pricing decision rather than a bandwidth cost.

## Refunds: 24 hours, 5GB, three per month

The published policy is narrow and specific. A full refund is available within 24 hours of activation while usage stays under 5GB. Each account may refund at most three times in a calendar month, and the same node can only be refunded once per month. That structure suits someone testing latency from their own connection and bailing if the route is bad. It does not suit someone who wants a 30-day money-back window after migrating a live site.

The 24-hour clock starts at activation, not at order, so do not buy on Friday and provision on Monday. 👉 [Create the account and check plan availability](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)

## Network reality: what third-party tests found, and when

Latency claims age badly, so here is what was measured and when. None of this comes from Akile's own marketing.

The US Premium line tested in March 2024 ran 130-170ms from most Chinese nodes, with Telecom outbound on CN2 (59.43.x), Unicom on AS9929/AS10099 and Mobile on CMIN2 (AS58807). Individual results included Shanghai Telecom 128.10ms, Beijing Unicom 150.58ms and Chengdu CERNET 193.85ms. Streaming checks on that box returned US-region yes for Netflix, Disney+, YouTube Premium, Amazon Prime, HBO Max and Hulu, and yes for ChatGPT. The reviewer's main complaint was port size, not routing.

The UK Lite2 tested in November 2024 averaged 249.3ms across the three Chinese networks, fastest at 185ms from Guizhou Unicom. Shanghai Telecom outbound detoured through the US, Germany and Belgium, while Guangdong Chaozhou Unicom connected directly. Speedtest peaked at 475.79Mbps down and 499.09Mbps up on a 500Mbps port.

The Hong Kong HKT NAT box tested in September 2023 pulled 206.46Mbps down and 200.69Mbps up locally at 1.92ms, but Netflix returned Originals only. A Hong Kong IP is not the same thing as the full Hong Kong catalogue, and that distinction has not been re-tested since.

## Who shouldn't buy Akile, and what the alternatives cost

Three cases where the answer is a different provider.

You need selectable egress routes. In a five-provider comparison posted in September 2025, the author marked Akile as having a dedicated egress IP but no choice of egress route, against a competitor that offers both. That table was written from memory, so treat the classification as a lead, not a spec sheet. If route choice matters, ask support before paying.

You need guaranteed mainland direct connectivity on a non-China node. The Singapore order page says outright that direct routes to China are not guaranteed. Cheap Asia bandwidth and China-optimised routing are different products, and Akile sells both under one shop.

You need a small backup node at minimum spend. The cheapest in-stock item today is ¥235/month. The sub-¥50 tiers exist in the catalogue but sit sold out.

For context, the same September 2025 community table priced the alternatives it covered at ¥25 to ¥128/month for 130-yuan-class machines: tap at ¥25 (200M port, 1024G bidirectional), hepta at an effective ¥48/month on annual billing (1000M, 500G one-way, dedicated IX IP, selectable egress), bgp at ¥99 before discount (500M, 750G bidirectional), 肥仔 at ¥128 (500M, 2000G) and MK at ¥126 (2000G bidirectional). The author ranked them hepta > bgp > tap > akile > 肥仔 on "playability" and said he kept only hepta. One user's ranking of one price band, worth exactly that much.

## FAQ

**Does buying through an aff link cost me more?** No. The parameter identifies the referrer; the price on the order page is the price you pay.

**Where do I enter a discount code?** On the product detail page, in the redemption field, before checkout. The referral parameter and the discount field are separate inputs.

**What happens when I exceed my traffic?** Speed drops to 10Mbps until the allowance resets or you buy a traffic reset (¥30-¥800 depending on plan).

**Can I get a refund?** Within 24 hours of activation and under 5GB used, full refund. Maximum three refunds per account per calendar month, one per node per month.

**Hong Kong or Los Angeles?** Hong Kong for mainland latency, historically on AS10099 outbound and CMI for Mobile. Los Angeles for a US native IP and streaming unlocks, with 9929/CMIN2/CN2 GIA routing as tested in March 2024. Neither matters if the tier you want is sold out, so check stock first.

## The choice, in one paragraph

Need a box today and don't care about China routing? SGBase-UNLIMITED-500M at ¥235/month, or the 1000M version at ¥360 if the extra 500Mbps is worth ¥125 to you. Need China-optimised Hong Kong? Wait for HKPro stock and budget for the reset fee at your expected usage, because ¥114.99 plus one ¥100 reset is Standard-tier money. Need a US native IP for streaming? The LAX lines are the ones with the documented 9929/CMIN2/CN2 GIA routing, at prices last verified in mid-2024, so confirm the current listing rather than the review. Need a cheap European presence? The UK Lite2 at ¥19.99/month as listed in November 2024, with ¥14 per extra 1TB, is the value line if it is still sold at that figure.

Two things to confirm on the order page before you pay: the plan is not marked Sold Out with a price you assumed from a blog post, and the total survived your discount code attempt. Then check the refund clock starts at activation, not payment.

👉 [Start with the Akile order page and confirm today's stock](https://akile.io/register?aff_code=24a6f6bd-f995-4158-a9fd-f4b6aef27811)
