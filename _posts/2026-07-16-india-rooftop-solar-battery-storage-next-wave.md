---
layout: post
title: "India Is Putting Solar on 10 Million Rooftops. Battery Storage Is the Next Wave, and We Are Not Ready to Launch It Safely. (Part 1 of 2)"
date: 2026-07-16
author: Sumit Mahato
categories: [residential-storage]
tags: [BESS, rooftop-solar, PM-Surya-Ghar, net-metering, lithium, lead-acid, India]
topics: [energy-system-design, energy-policy]
description: "PM Surya Ghar put solar on millions of Indian roofs and left the battery out on purpose. India's two-decade home-backup habit, shifting solar economics, and an ageing lead-acid base all point to the same lithium upgrade."
published: true
---

<figure>
  <img src="/assets/img/post1.webp" alt="Rooftop solar panels on homes in a village in India">
  <figcaption>Rooftop solar on village homes in India — increasingly ordinary, thanks to PM Surya Ghar.</figcaption>
</figure>

Earlier this year, I went back to my village in Jharkhand. What amazed me were the rooftops. Not long ago, these homes ran on lead-acid batteries for backup power; now they carried solar panels. When I asked what had changed, the answer was the same everywhere: PM Surya Ghar. A subsidy had done in a couple of years what awareness campaigns hadn't managed in a decade, put rooftop solar within reach of an ordinary family.

The village isn't an exception; it's the leading edge of the largest residential solar rooftop programme in the world. Under PM Surya Ghar: Muft Bijli Yojana, roughly 40 lakh (4 million) homes had rooftop solar by mid-2026, with cumulative capacity above 11,300 MW, on the way to one crore (10 million) households by March 2027 (SolarQuarter; PIB). The scheme puts up to ₹78,000 (about $780) of subsidy and 300 free electricity units a month within reach of a middle-class household.

I spent over a decade in the renewable energy sector, including seven years at Tesla, where I was involved in the global launch of Powerwall across North America, EMEA and APAC. Residential storage is the hardest energy product to launch well, because the moment you ship it, you don't have a project, you have a fleet living in people's homes. India is about to run that learning curve at ten-million-roof scale.

This first piece makes the case that a battery-storage wave is coming: why India's two-decade home-backup habit, its shifting solar economics, and its ageing lead-acid base all point to the same lithium upgrade. A second piece will turn to the harder question: how that storage gets launched, the honest pros and cons of a home storage battery, the deployment landmines, and why, done carelessly, a home-battery boom could go wrong.

## Why Lithium Battery Storage Will Follow

India already stores energy at home. Just badly. The mistake most people make is treating residential storage as a new behaviour India has to be taught. It isn't. India has had a home-backup culture for two decades. The inverter-and-battery in the living room is a normal middle-class purchase, because the power goes out frequently. The Central Electricity Authority (CEA) notes that daily outages of two to four hours are common in many regions, and longer in rural areas, and the inverter-battery market was worth around USD 1.02 billion in 2025 (Research and Markets).

The catch: almost all of that installed base is lead-acid. Lead-acid holds roughly 65% of the home-UPS battery market, favoured purely for its low upfront cost in a price-sensitive market (Astute Analytica).

So India's residential storage story is not "adopt a new behaviour." It's an upgrade path: a large lead-acid base, ripe for replacement by lithium, now colliding with ten million new solar roofs.

### Surya Ghar covers the solar, not the storage, and "net metering" isn't what most people think

Here's the policy design that matters. PM Surya Ghar subsidises grid-connected rooftop solar only. The battery is explicitly not covered by the subsidy, and off-grid or battery-only systems are ineligible for the central assistance (Business Today). A hybrid inverter and battery can still sit in the home, but the subsidy applies only to a grid-connected system built with ALMM-listed modules and commissioned with a net meter (Qbits Energy); the battery itself earns nothing.

(ALMM, the Approved List of Models and Manufacturers, is the government's whitelist of solar modules and manufacturers eligible for subsidised and government-backed projects. If the panel isn't on the list, the system doesn't qualify for support. It's how the government steers demand toward quality-verified, largely domestic equipment.)

The policy design leans on net metering: export your midday surplus, draw it back in the evening. But here's the part that quietly changes the storage calculus, and it's widely misunderstood: in most of India, "net metering" no longer means you buy and sell at the same price. What DISCOMs now label net metering typically credits exported units at a defined export tariff of roughly ₹2–₹3.5/unit, well below the ₹5–₹9/unit retail rate you pay to import (Heaven Green Energy). Karnataka makes the gap concrete. Your solar serves the home first; only the surplus you inject after that real-time self-consumption is paid the KERC export tariff, while your imports are billed separately at retail (Mercom India). So a unit of your solar is worth about ₹6.7–₹7 if you self-consume it (the retail price you avoid paying) but only around ₹3.86/unit if you export it from a non-subsidised domestic rooftop, and just ₹2.30–₹2.93/unit from a PM Surya Ghar system (Energetica India). The export price is already roughly half the import price, and less than half for the subsidised mass-market home the scheme is creating. (Separately, MNRE, the Ministry of New and Renewable Energy, has signalled that future scheme revisions may add a partial battery subsidy, but as of now that's a stated possibility, not policy.)

So why will the storage wave come anyway? Three forces are converging:

- **The export-vs-import gap already exists, and it's widening.** Because exports are already credited below retail, storing a unit to self-consume later is worth roughly ₹3–₹4 more than exporting it today, for any solar you'd otherwise send to the grid. (How big the prize is depends on how much your home exports rather than self-consumes in real time: a house that's empty 9-to-6 exports most of its midday peak, so the gap bites hardest there.) And it's deepening: in mid-2026 KERC proposed cutting Karnataka's future rooftop export tariff further to as low as about ₹2.37/unit, with the industry's own suggested antidote being battery storage, time-of-day tariffs and self-consumption (EQ Magazine; Saur Energy).
- **The outages never went away.** The core Indian value, to keep the lights, fan, and router alive through a cut, is permanent, solar or no solar. Solar just makes the battery more useful.
- **The lead-acid base is due for a lithium upgrade.** Tens of millions of homes already own storage; the question is which chemistry they buy next.

## Why Lithium-Ion Beats Lead-Acid for a Solar Home

For a battery that cycles daily on solar, lithium (specifically LFP) outperforms lead-acid on nearly every axis that matters:

- **Usable depth of discharge:** over 95% (lithium) vs about 50% (lead-acid)
- **Cycle life:** 5,000–6,000+ cycles vs about 1,400–1,500
- **Calendar life:** 7–12 years vs 3–5 years
- **Charge time:** about 3× faster, full in 3–4 hours vs slow
- **Maintenance:** effectively zero vs water top-ups, corrosion and fumes
- **Size and weight:** compact and light vs bulky and heavy
- **Lifetime cost per usable kWh:** lower despite the higher sticker price

(Sources: Vigood Solartek; Heaven Green Energy; Lento.)

Two of those advantages matter most for a solar home. First, usable capacity: because you can safely draw down almost all of a lithium pack but only about half of lead-acid, a 100Ah LFP delivers around 5.12 kWh usable and you'd need a roughly 200Ah lead-acid battery to match it. Second, that cycle-life gap widens in practice, because solar imposes exactly the partial-state-of-charge, deep-cycling duty that ages lead-acid fastest. Put those together and the economics follow: even though lithium costs more upfront, it works out cheaper per usable kWh over its life. You use more of each charge, get several times the cycles, and replace the pack far less often, where a lead-acid bank might need swapping two or three times over a single lithium battery's life. The honest counterargument is the higher upfront cost, and the thermal-management demands of lithium in Indian heat are a central theme of the next piece.

The demand is already here, the economics are turning, and the incumbent lead-acid base is ready to be replaced. A battery-storage wave will follow India's rooftop-solar wave the way it has in every market before it. The only real question is how well or how badly we launch it.

That's the subject of Part 2: the honest pros and cons of a home battery, the deployment landmines that could derail the category, and what a responsible, safe launch actually looks like in Indian conditions.

---

*Check out Part 2 of this article.*

## Sources

- SolarQuarter, PM Surya Ghar: 40 lakh homes, 11,300+ MW. <https://solarquarter.com/2026/05/30/pm-surya-ghar-scheme-solarises-40-lakh-households-accelerating-indias-rooftop-solar-growth/>
- PIB, PM Surya Ghar. <https://www.pib.gov.in/PressReleaseIframePage.aspx?PRID=2081250&reg=3&lang=2>
- Research and Markets, India inverter-battery market; CEA outage data. <https://www.researchandmarkets.com/report/india-inverter-battery-market>
- Astute Analytica, India home-UPS market; lead-acid share. <https://www.astuteanalytica.com/industry-report/india-home-ups-market>
- Business Today, battery not subsidised under PM Surya Ghar. <https://www.businesstoday.in/latest/trends/story/can-rooftop-solar-provide-uninterrupted-electricity-learn-why-grid-connection-is-essential-534712-2026-06-04>
- Qbits Energy, PM Surya Ghar eligibility, ALMM, net meter. <https://qbitsenergy.com/blog/pm-surya-ghar-yojana-complete-guide/>
- Heaven Green Energy, net metering export tariffs; lithium vs lead-acid. <https://www.heavengreenenergy.com/blog/what-is-net-metering-india>
- Mercom India, Karnataka net-metering settlement. <https://www.mercomindia.com/karnataka-regulator-clarifies-rooftop-solar-net-metering-arrangements>
- Energetica India, Karnataka DSPV tariffs. <https://www.energetica-india.net/news/karnataka-overhauls-rooftop-solar-policy-with-dspv-reforms-and-flexible-net-metering>
- EQ Magazine, KERC proposed tariff cut. <https://www.eqmagpro.com/karnataka-electricity-regulator-proposes-sharp-reduction-in-rooftop-solar-tariffs-potentially-lowering-future-consumer-returns-eq/>
- Saur Energy, KERC FY27–FY29 tariff proposal. <https://www.saurenergy.com/solar-energy-news/kerc-proposes-265unit-solar-tariff-for-fy27-fy29-seeks-stakeholder-views-12052818>
- Vigood Solartek, lithium batteries for solar, India. <https://vigoodsolartek.com/blogs/news/top-10-best-lithium-batteries-for-solar-system-in-india-2026-utl-luminous-exide-more>
- Lento, lithium inverter batteries for home. <https://www.lentoindia.com/blog/lithium-battery-inverter-for-home-in-india.html>
- Heaven Green Energy, Exide lithium vs tubular payback. <https://www.heavengreenenergy.com/blog/exide-vs-luminous-solar-battery>

*Figures as reported mid-2026; market-share and household-penetration figures vary by source and definition.*
