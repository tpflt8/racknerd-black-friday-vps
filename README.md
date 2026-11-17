# RackNerd Black Friday: When Does the Sale Start, How Cheap Was It Last Year, and Should You Wait? (All Five Current VPS Plans Compared)

RackNerd hasn't published any Black Friday plans yet. The 2026 sale window is **27 November to 2 December**, Cyber Monday included, and last year RackNerd opened roughly a week early. Until then, the page the company uses for the event (racknerd.com/BlackFriday) sells the ordinary VPS Specials at **$21.99 to $119.99 per year**, and those prices renew at the same rate rather than jumping in year two.

That single fact decides most buying questions. If you need a server this week you're paying list price. If you can wait until the end of November, the same 1 GB tier cost $10.60 a year during the last Black Friday sale, about half of today's price.

> **Quick verdict:** need a box now, buy the **1 GB KVM at $21.99/year**. It runs a small site, n8n, Coolify or a Docker sandbox, and the rate doesn't change on renewal. Can you hold out two weeks? The identical tier was **$10.60/year** last Black Friday, and 4 GB and 8 GB plans saw the same ~50% cut. 👉 [Check the current VPS Specials and available datacenters](https://bit.ly/RacKnerd)

## Every plan RackNerd sells right now, with prices

These five are the full VPS Specials lineup on the official page today. Each one includes full root access, one IPv4, pure SSD storage, a 1 Gbps port, KVM virtualization and instant provisioning after payment.

| Plan | vCPU / RAM / SSD | Monthly transfer | Price per year | Order |
| --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 core / 1 GB / 20 GB | 3 TB | **$21.99** | [Order the 1 GB plan](https://bit.ly/RacKnerd) |
| 2 GB KVM VPS (listed as most popular) | 2 cores / 2 GB / 35 GB | 5 TB | **$35.99** | [Order the 2 GB plan](https://bit.ly/RacKnerd) |
| 4 GB KVM VPS | 3 cores / 4 GB / 60 GB | 7 TB | **$59.99** | [Order the 4 GB plan](https://bit.ly/RacKnerd) |
| 6 GB KVM VPS | 6 cores / 6 GB / 100 GB | 12 TB | **$89.99** | [Order the 6 GB plan](https://bit.ly/RacKnerd) |
| 8 GB KVM VPS | 7 cores / 8 GB / 150 GB | 20 TB | **$119.99** | [Order the 8 GB plan](https://bit.ly/RacKnerd) |

Those are regular list prices, not Black Friday prices. Anyone quoting "$21.99 Black Friday deal" is describing the everyday store page.

## How much cheaper was Black Friday, in real numbers

RackNerd's 2025 Black Friday batch had five VPS plans, and they map almost one to one onto the five plans above. Every tier came in at roughly half price.

| Tier | Black Friday 2025 price | Current regular price | Difference |
| --- | --- | --- | --- |
| 1 GB KVM | $10.60/yr | $21.99/yr | 52% cheaper |
| 2.5 GB KVM | $18.66/yr | $35.99/yr (2 GB) | 48% cheaper |
| 4 GB KVM | $29.98/yr | $59.99/yr | 50% cheaper |
| 6 GB KVM | $44.98/yr | $89.99/yr | 50% cheaper |
| 8 GB KVM | $62.49/yr | $119.99/yr | 48% cheaper |

Two footnotes matter. The sale plans weren't identical SKUs: last year's 1 GB came with 25 GB of disk against 20 GB now, and the second tier was 2.5 GB rather than 2 GB. The 8 GB discount also gets quoted two ways. One tracker lists it as 31% cheaper because it measures against the $89.99 six-gig plan; measured against the $119.99 eight-gig plan on sale today, it's about 48%. Same deal, different yardstick.

The starting price has drifted upward over four years: **$8.50**, then **$10.18** (2023), **$10.99** (2024), **$10.60** (2025). Nothing in that series suggests this year's entry point will fall below $10 or climb past $12, but that's an inference from history, not an announced price. Treat any figure you see before the sale opens as a guess.

## Two things the price tables leave out

**The cheap tiers came with fewer datacenter choices.** The 2025 Black Friday batch of five plans was deployable in a single location. In 2024 those five plans covered five datacenters, and 2023 had nine. If you specifically need Los Angeles or Amsterdam or a low-latency box for a particular audience, waiting for a $10 plan that may only exist in one city is a bad trade. Check what's actually offered on the order page before you commit.

**The Black Friday URL is live but isn't a sale.** racknerd.com/BlackFriday resolves and shows VPS Specials with prices, which reads like a sale until you compare the numbers to the regular store and find they're identical. There's no countdown and no promo language on it right now. When the real event starts, that page is where it will land.

## Which tier you actually need

RackNerd's own documentation gives memory floors for the one-click apps in its ctrl panel, and they're a better buying guide than the specs table.

- **OpenClaw wants at least 8 GB of RAM.** That's the $119.99 plan today, or $62.49 at last year's Black Friday price. Nothing smaller will do.
- **Hermes Agent, AnythingLLM, Ollama and LibreChat want at least 4 GB.** The $59.99 plan, or $29.98 last year.
- **n8n and Coolify are comfortable from 2 GB.** Add a static site, a small WordPress install or a personal blog and 2 GB covers it.
- **A single small site, a VPN endpoint, a monitoring node or a Docker playground** fits in 1 GB without drama.

Most people reading a Black Friday post want the cheapest box on the page, and most of them are running n8n, a blog or a WireGuard node. The 1 GB or 2 GB plan handles that. The 8 GB plan exists for a different customer, and paying $119.99 for it to host a static site is wasted money. 👉 [Compare all five Specials and their datacenters](https://bit.ly/RacKnerd)

## Renewal, panel, and the refund rule

**Renewal:** the official FAQ on the Specials page says it plainly: "These RackNerd VPS specials are lifetime recurring. You can renew at the same rate for as long as you decide to keep the service." A Black Friday price is therefore not a first-year teaser. The annual plans have historically been sold the same way, though the renewal terms for this year's unannounced plans can only be confirmed once they're posted.

**Panel:** every plan ships with **ctrl**, RackNerd's own control panel. From there you reboot, reinstall the OS, open an HTML5 VNC console, reset the root password, set inbound firewall rules, upgrade the plan and install one-click apps. Custom ISO installs require a support ticket. OS templates cover CentOS, Rocky Linux, AlmaLinux, Fedora, Debian and Ubuntu.

**Support model:** these are unmanaged KVM VPS. You get root and a ticket queue that runs 24/7, not a managed service that logs in for you.

**Refunds:** RackNerd's knowledge base states that they do not offer refunds or a money-back guarantee. That changes the risk calculation. Test throughput from your connection before ordering, confirm the datacenter you want is selectable on the order page, and keep your own backups from day one. If you want to try the platform with less exposure, RackNerd's standard KVM line is also sold on monthly billing, which is a lower-stakes way in than a prepaid year. 👉 [Start with the plan that matches your workload](https://bit.ly/RacKnerd)

## Shared hosting, reseller accounts, and dedicated servers

Black Friday at RackNerd has covered more than VPS. The numbers below are prices listed during the 2025 Black Friday promotion and on the regular store, not 2026 sale prices.

| Product | Spec | Price per year |
| --- | --- | --- |
| Shared 30 GB | cPanel, 3 TB transfer, 3 hosted domains | $10.49 |
| Shared 85 GB | cPanel, 10 TB transfer, 11 hosted domains | $24.99 |
| Shared 200 GB | cPanel, 30 TB transfer, unlimited domains | $59.00 |
| Reseller 75 GB | cPanel/WHM, 2.5 TB, 3 cPanel accounts | $34.88 |
| Reseller 110 GB | cPanel/WHM, 5 TB, 7 cPanel accounts | $64.88 |
| Reseller 180 GB | cPanel/WHM, 9 TB, 12 cPanel accounts | $94.88 |

Shared and reseller plans run on Ryzen 7950X hardware with Gen4 NVMe, CloudLinux 9, LiteSpeed, JetBackup daily offsite backups, free SSL and a free Clientexec license. Singapore adds roughly $8/year. Dedicated servers start around **$49/month**, for example a Xeon E3-1240 V2 with 32 GB RAM, 240 GB SSD, 30 TB at 1 Gbps and a /29 IPv4 block, provisioned manually in 24 to 72 hours.

## FAQ

**When exactly does the sale start?**
The window is 27 November to 2 December, Cyber Monday included. RackNerd picks its own start date each year, and last year it opened about a week before the holiday. Flash sales can appear with no notice at any point.

**Can I buy the Black Friday price today?**
No. No 2026 Black Friday plan or price exists yet. What's purchasable right now is the regular VPS Specials at $21.99 to $119.99 per year.

**Will the renewal price go up after year one?**
The Specials page states that specials renew at the same rate for as long as you keep the service. That has been the pattern for annual specials generally.

**Is the cheapest plan enough?**
For n8n, Coolify, a static site, a small blog or a VPN endpoint, yes. For Ollama, LibreChat, AnythingLLM or Hermes Agent you need 4 GB, and OpenClaw needs 8 GB.

**Do the good plans sell out?**
Flash sales arrive without warning and the best plans can sell out within minutes. Datacenter availability also shifts during the event, with locations added or temporarily out of stock.

## What to do with this

If the server has to be online this week, take the **1 GB KVM at $21.99/year**, or the 2 GB at $35.99 if you're running n8n or a couple of small sites. You're paying roughly double the November price for two weeks of uptime, which is a fair trade when something is already waiting to launch.

If nothing is on fire and you're after 4 GB or more, wait for 27 November and watch the Black Friday page. Last year the four-gig plan landed at $29.98 against $59.99 today, and that gap is worth two weeks of patience. If you need one specific city rather than the lowest price, don't wait blindly, since the cheapest tiers have come with a shrinking list of locations.

Before you pay, confirm two things on the order screen: that your preferred datacenter is selectable for that plan, and that your OS template is on the list. Then keep your own backups, because there is no refund waiting on the other side.

👉 [See what's available on RackNerd right now](https://bit.ly/RacKnerd)
