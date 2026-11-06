# greencloud vps sale: What's Actually on Discount Right Now, Which Plans Are Worth It, and the No-Refund Fine Print Before You Pay

GreenCloud runs its VPS discounts through a rotating sale store rather than a permanent price list, so what "greencloud vps sale" gets you depends heavily on the week you search. Here's the state of play as of early November 2026: the 13th Birthday Sale (October 26–31) has just ended, GreenCloud has said publicly there will be **no Black Friday sale this year**, and the standing sale categories — Premium KVM, Budget KVM, and the Windows VPS Sale — continue to restock and sell out in rotation on the same store.

That last sentence is the part most deal posts skip. Articles about GreenCloud promotions are usually written around one event and go stale the moment it ends. This one covers what's still buyable, what the restrictions actually say, and how the math works past the first invoice.

> **Quick pick**
> If you want the cheapest usable Linux plan right now, the **Premium KVM entry tier at $25/year** (1 core, 2GB RAM, 25GB NVMe, 750GB monthly traffic) in Tokyo, Hong Kong, or Singapore is the recurring workhorse deal — or the same price with **3TB of traffic** if you take the UK location instead. Need Windows Server? The WinPromo sale tiers start at 4GB RAM with a licensed image included. Stock rotates and sells out, so check what's live before deciding: 👉 [check GreenCloud's current sale stock and prices](https://greencloudvps.com/billing/aff.php?aff=6679)

## What the 13th Birthday Sale left behind

The event itself is over, but two things from it still matter — one of them urgently.

**First, a deadline.** During the sale, GreenCloud offered 13% cashback as account credit on invoices paid between October 26 and October 30, 11:59 PM UTC, with a minimum of $500 in paid invoices. Account top-ups didn't count toward the $500, and purchases paid with existing account balance were excluded. The step people forget: the cashback had to be requested **via support ticket by November 5, 2026**. It doesn't happen automatically. If you spent over $500 during the event and haven't filed the ticket yet, that's the single most time-sensitive thing in this article.

**Second, a pricing commitment worth knowing about.** GreenCloud stated that despite rising hardware, RAM, and datacenter costs, promo plans renew at the price they were sold at. The company explicitly encouraged customers to keep and renew their old promotional plans rather than expecting a sudden increase. This changes how you should evaluate their deals — more on that in the cost section below.

The birthday plan itself was $123 for three years: 13GB RAM, 113GB NVMe 4.0 storage in RAID-10, 6 fair-share EPYC Milan cores, a 10Gbps port, one free backup/snapshot, and VirtFusion as the control panel, across APAC, US, and EU locations. That's roughly **$3.42 per month**, Linux only. It sold out, but the pricing sets the benchmark for what to expect at the next flash event — and GreenCloud has run several of these, including an April 2026 flash sale with special plan IDs and double resources on three-year KVM orders.

## The sale plans you can actually buy today

GreenCloud's discount store is organized into sale categories that restock at unpredictable intervals. Everything currently displayed on the sale pages is below, with last verified configurations and prices.

### Premium KVM Sale — restocked October 19

This is the category with the most recent confirmed stock. All plans share the same foundation: AMD EPYC Milan, NVMe RAID-10 storage, 10Gbps port, VirtFusion control panel, Linux, 1 IPv4 with IPv6, and 1 free backup/snapshot. No coupon is needed — the sale price is printed on the plan itself.

| Plan tier | Locations | Configuration | Traffic | Price & billing | Order |
| --- | --- | --- | --- | --- | --- |
| Entry | Tokyo (IIJ / Softbank), Hong Kong DC1, Singapore DC2 | 1 core, 2GB RAM, 25GB NVMe | 750GB/mo | **$25/year** | [ order the entry plan](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Mid | Tokyo (IIJ / Softbank), Hong Kong, Singapore | 2 cores, 3GB RAM, 35GB NVMe | 1TB/mo | **$35/year** | [ order the mid-tier plan](https://greencloudvps.com/billing/aff.php?aff=6679) |
| 8GB Tokyo | Tokyo IIJ / Softbank | 4 cores, 8GB RAM, 60GB NVMe | 2TB/mo | **$68/year** | [ see the 8GB Tokyo plan](https://greencloudvps.com/billing/aff.php?aff=6679) |
| 8GB HK/SG | Hong Kong DC1, Singapore DC2 | 4 cores, 8GB RAM, 60GB NVMe | 2TB/mo | **$20/quarter** | [ check HK/SG stock](https://greencloudvps.com/billing/aff.php?aff=6679) |
| UK Coventry | Coventry, UK | 2GB / 3GB / 8GB tiers | 3TB / 5TB / 8TB per month | **$25/yr, $35/yr, $20/quarter** | [ see UK plan pricing](https://greencloudvps.com/billing/aff.php?aff=6679) |

The UK row is the one most people scroll past too fast. At the same $25/year, Coventry gets you 3TB of monthly traffic versus 750GB at the Asian locations — four times the allowance for identical money. If your use case doesn't need low latency to East Asia (a backup node, a bot, a self-hosted app for Western audiences), the UK plan is simply better value at that tier. If you're routing through Japan on purpose — gaming, streaming, latency-sensitive proxy work — the Asian locations are the entire point, and 750GB still covers a single user comfortably.

Two hardware-level details worth knowing before picking between Tokyo plans. Softbank and IIJ are different upstream lines, not two names for the same thing, and which one performs better depends on your ISP and route. And IPv6 allocation varies by location: Tokyo and Hong Kong DC1 give /64, while Singapore DC2 gives /112. Most users won't care; anyone running IPv6-dependent tooling will.

### Windows VPS Sale

Four tiers, all including a licensed Windows Server 2019/2022 image, Hyper-V virtualization, and unmetered bandwidth on a 10Gbps port:

- **WinPromo-1**: 4GB RAM, 2 cores, 40GB SSD
- **WinPromo-2**: 6GB RAM, 3 cores, 60GB SSD
- **WinPromo-3**: 8GB RAM, 4 cores, 80GB SSD
- **WinPromo-4**: 16GB RAM, 8 cores, 120GB SSD

Pricing isn't displayed in a static table — it shows on the plan's order page and varies by billing cycle, so treat the configurations as fixed and confirm the current price there. The licensed Windows image is the real reason this category exists: self-installing Windows on a cheap KVM box means an unlicensed mess or paying separately for licensing, and this bundles it. During the birthday event, standard Windows VPS purchases and renewals of 12 months also got 6 extra months free (18 months for the price of 12), promotional plans excluded — a reasonable pattern to expect again at the next event. Current pricing and availability: 👉 [open the Windows VPS sale page](https://greencloudvps.com/billing/aff.php?aff=6679)

### Budget KVM Sale

The Budget KVM category rotates fastest. A New York plan (4GB RAM, 35GB NVMe RAID-10) was listed at zero availability when last checked, which is typical for this category — it appears briefly and disappears. If it's in stock when you look, it tends to be the lowest price-per-GB option in the store.

## The fine print that decides whether a deal is actually good

Three restrictions live only on the plan pages and checkout flow, and they're the ones roundup articles tend to omit.

**1. No refunds on sale plans.** Every promo category — Premium KVM, Budget KVM, Windows VPS Sale, and the birthday plans — is marked "No refund / Money back on this plan." This isn't a hidden trap so much as the mechanism that makes the prices possible, but it changes your pre-purchase checklist. GreenCloud publishes test IPs for every datacenter, and the sensible move is to ping and route-test the specific location from your own network before paying — especially for Tokyo, where the IIJ and Softbank lines behave differently depending on your carrier. Unpaid orders auto-cancel after 30 minutes, so browsing costs nothing.

**2. Bandwidth is not uniform.** The marketing says 10Gbps everywhere, but monthly traffic allowances vary enormously by region: 12TB at US/EU locations on event plans, 3333GB at APAC locations on the same plans, 750GB on the $25 Asian KVM entry tiers. And 10Gbps is the port specification, not a guaranteed throughput — fair-share CPU and shared uplinks mean sustained real-world speed depends on the moment. Nobody should buy a sale VPS expecting to pull a dedicated 10Gbps around the clock.

**3. Stock rotation replaces a fixed price list.** There's nothing permanent to compare against. Deals appear, sell out, and reappear, sometimes with different billing cycles for identical hardware depending on location — that 8GB tier is $68/year in Tokyo but $20/quarter in Hong Kong and Singapore, which works out to roughly $80/year, so Tokyo wins on price there. Waiting for the next restock is the normal play, and these categories restock repeatedly through the year.

## What it costs over time, not just on day one

This is where GreenCloud's model diverges from most budget hosts, and it's worth running the actual numbers.

A $25/year Premium KVM plan costs $50 over two years and $75 over three — flat, because of the renewal price guarantee. Compare that to the common competitor pattern of a cheap first year followed by a renewal spike, where a lower first invoice can end up more expensive by year two. On the birthday plan, $123 across three years came to $41/year for a 13GB RAM machine, and it renews at $123, not at some undisclosed standard rate. For context on how GreenCloud has priced bigger flash events: last year's Black Friday lineup included special-edition plans from $22/year for a 2GB/2-core/22GB NVMe box up to $120/year for 32GB/8-core/250GB, with percentage-off coupon discounts on regular Ryzen KVM, Budget KVM, and Windows lines.

The flip side of locked-in renewals plus no refunds: a bad location choice is a mistake you live with for the whole billing period. That's an argument for the shorter cycles when you're unsure — the $20/quarter options in Hong Kong and Singapore exist precisely so you can test a location for three months before committing to a year.

## FAQ

**Does GreenCloud have a Black Friday sale?**
Not in 2026. The company announced in advance that the October 13th Birthday Sale would be its only major promotion of the season, deliberately early, so buyers wouldn't wait for a Black Friday discount that isn't coming. Guides promising a current GreenCloud Black Friday coupon are describing past years.

**Do I need a coupon code for the sale prices?**
No, not for the current sale categories. Premium KVM, Windows VPS, and Budget KVM sale plans are priced directly in the store — the discount is already on the plan. Coupon codes have appeared only during specific past events, like last year's Black Friday percentage-off promotions.

**Are the cheap plans Linux-only?**
The KVM sale plans ship with Linux. Windows is available through the Windows VPS Sale tiers, which bundle a licensed Windows Server 2019/2022 image on Hyper-V.

**Can I pay with account credit and still get promo rewards?**
Pricing yes, but purchases paid with account balance didn't count toward cashback or wheel-spin thresholds during the birthday event. If a future promotion ties rewards to real payments, paying by card or another direct method keeps you eligible.

**What happens if my plan sells out before renewal?**
Sold-out plans stop being purchasable by new customers, but existing services keep running and renewing, with renewal pricing locked per the company's stated guarantee.

## Which plan should you actually get

Sorted by use case, from the verified options:

- **Cheap Linux box, location flexible** → UK Coventry 2GB at $25/year with 3TB monthly traffic. Best raw value in the current store.
- **Need East Asia latency** → Tokyo IIJ or Softbank at $25/year, but test both lines from your network first; with no refunds, there are no do-overs.
- **Want more headroom without committing a year** → the $20/quarter Hong Kong or Singapore 8GB plan. Real hardware, three months, low risk.
- **Windows Server requirement** → whichever WinPromo tier fits your RAM needs; WinPromo-1 (4GB) covers light admin work, WinPromo-3 and up if you're running actual services. Confirm the current price on the order page since it isn't published in a static table.
- **Waiting for a bigger machine** → watch the store instead of settling. Flash event plans in the 1313 class have come back in some form repeatedly, and the store updates frequently.

One last practical note: when a restock lands, the popular Asian locations can sell out within hours, and there's no waitlist. GreenCloud has been operating since October 2013 under 365 Group LLC and serves customers in more than 150 countries, so the company itself isn't the risk here — timing is. If you've already settled on a plan, the fastest path from decision to running server is 👉 [grab your GreenCloud sale plan while stock lasts](https://greencloudvps.com/billing/aff.php?aff=6679) — and ping those test IPs before you click pay.
