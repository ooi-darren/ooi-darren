# Darren Ooi

Deep-dive market research and analytics case studies, distilled into one answer: how should a business decide?

## What this is

A collection of rigorous market research case studies. Each one starts from a real business question, investigates it in depth against public data (government statistics, industry reports, primary-source filings) with every figure traced to its source and every assumption labeled, and ends in a specific recommendation. Not a dashboard, not a chart deck: real research, distilled into a decision.

I'm a Business Analytics student at Sunway University, aiming for a career in strategy and management consulting, with a longer-term goal of leading my family's business.

**Reading on a schedule?**
- **20 minutes:** [006](https://github.com/ooi-darren/malaysia-graduate-underemployment) for depth (8 notebooks, one country funneled from national headline down to individual districts) or [008](https://github.com/ooi-darren/project-008-global-supply-chain-intelligence) for the most complete single system (a 59-country trade network, a critical-minerals concentration index, a supply chain risk index, and a validated 2030 forecast, all in one project).
- **The full portfolio:** everything below, roughly in the order it was built.

## Case Studies

### 🇲🇾 001: [Malaysia E-Commerce Market Intelligence Report (2020–2024)](https://github.com/ooi-darren/malaysia-ecommerce-market-intelligence)

<img src="./assets/001-ecommerce.png" width="640" alt="Online shopping cart icon representing Malaysia e-commerce">

**Question:** How has Malaysia's e-commerce competitive landscape evolved since 2020, and what should a business weigh when deciding where to invest?

Sourced from Department of Statistics Malaysia, Bank Negara Malaysia, and platform market intelligence, with every figure traced to its source and labeled public, derived, or estimated.

`Python` `SQL`; **Complete**

### 📦 002: [Malaysia's Semiconductor Shortage: Manufacturing Under Pressure (2021–2023)](https://github.com/ooi-darren/malaysia-semiconductor-shortage-impact)

<img src="./assets/002-semiconductor.png" width="640" alt="Microchip icon representing Malaysia's semiconductor industry">

**Question:** How did the global chip shortage affect Malaysia's electronics manufacturing and export performance, and what does it reveal about supply chain resilience?

`Python` `SQL`; **Complete**

### 🌱 003: [Malaysia Grid Decarbonization: On Track or Overstated? (2017–2024)](https://github.com/ooi-darren/malaysia-grid-decarbonization)

<img src="./assets/003-grid.png" width="640" alt="Power pylon and sun icon representing Malaysia's grid energy transition">

**Question:** Is Malaysia's electricity grid decarbonizing fast enough to meet its own climate commitments, and what does that pace mean for a business deciding whether to wait on the grid vs. invest in its own renewable capacity to hit its emissions targets?

`Python`; **Complete**

### ♻️ 004: [Malaysia's E-Waste Opportunity: Recoverable Value vs. Formal Capture (2019–2021 Data, 2026 Pricing)](https://github.com/ooi-darren/malaysia-ewaste-opportunity)

<img src="./assets/004-ewaste.png" width="640" alt="Electronic device and recycling loop icon representing Malaysia's e-waste opportunity">

**Question:** How much economic value in recoverable metals sits inside Malaysia's e-waste stream, how much is the formal recycling system actually capturing, and does that gap represent a real business opportunity or something else?

`Python`; **Complete**

### 🌐 005: [Is Capital Really Leaving China? Global → Regional → Local (2019–2026)](https://github.com/ooi-darren/is-capital-leaving-china)

<img src="./assets/005-global.png" width="640" alt="Globe with expanding rings icon representing the global to regional to local funnel">

**Question:** Does the "China+1" narrative (that capital is diversifying away from China toward alternative manufacturing destinations) actually show up in the data, at the global level, the ASEAN regional level, and specifically in Malaysia?

`Python`; **Complete**

### 🎓 006: [Malaysia's Graduate (Un)employment: National, State, and District (2016–2026)](https://github.com/ooi-darren/malaysia-graduate-underemployment)

<img src="./assets/006-graduate.png" width="640" alt="Graduation cap and briefcase with a question mark, representing graduate job search uncertainty">

**Question:** Does Malaysia have a graduate unemployment crisis, or an underemployment one, and does that answer hold at the national level, across every state, and down to individual districts?

Eight notebooks, the deepest funnel in this portfolio: national headline → age cohort → job quality → every state → structural explanation → every district → wage penalty → field-of-study mismatch. Includes a real data-quality bug found and corrected in a government dataset, and two notebooks where the first-draft finding was rewritten after the chart contradicted it.

`Python`; **Complete**

### 🌍 007: [Global Consumer Spending Intelligence](https://github.com/ooi-darren/project-007-global-consumer-spending)

<img src="./assets/007-global-spending.png" width="640" alt="Globe with an ascending bar chart, representing a global consumer spending market attractiveness index">

**Question:** How does consumer spending behaviour differ across global regions, and what economic, demographic, and technological factors help explain those differences?

The first case study in this portfolio to go fully global: a 182-country, 11-year panel built from World Bank, OECD, and World Bank Governance Indicators data. Data-driven K-Means market segmentation, a transparent, sensitivity-tested 5-pillar market attractiveness index, and a real solved-in-the-open technical story (the OECD SDMX category-spending API was initially descoped, then genuinely fixed by discovering the correct query structure rather than guessing).

`Python`; **Complete**

### 🌐 008: [Global Supply Chain Intelligence](https://github.com/ooi-darren/project-008-global-supply-chain-intelligence)

<img src="./assets/008-supply-chain.png" width="640" alt="Network graph with a central accented hub node, representing trade network centrality analysis">

**Question:** How has the global supply-chain system changed over the past decade, where are the major dependencies and vulnerabilities right now, what could happen over the next 5-10 years under different scenarios, and what does all of this mean for Malaysia specifically?

The most complete system in this portfolio: a genuinely complete 59-country bilateral trade network (UN Comtrade, backfilled with OECD data for the four countries Comtrade's free tier excludes entirely) with betweenness/eigenvector/PageRank centrality analysis, a 13-material critical-minerals concentration index (HHI/CR3/CR5) built from real USGS production data, a transparent, sensitivity-tested Supply Chain Risk Index, a Malaysia export forecast to 2030 validated by a genuine 5-year rolling backtest, a 10,000-path Monte Carlo simulation on nickel prices, and a dedicated Malaysia 2030+ Vulnerability Index and evidence-graded Opportunity Radar.

`Python`; **Complete**

### 🌴 009: [Malaysia's Palm Oil: Value Chain, Crisis, and What's Next](https://github.com/ooi-darren/malaysia-palm-oil)

<img src="./assets/009-palmoil.png" width="640" alt="Palm tree with a fruit bunch and trunk, representing Malaysia's palm oil industry">

**Question:** Where does the money actually go in Malaysia's palm oil value chain, and is the country's push beyond raw production, into certification, downstream processing, and now entirely new products, actually paying off?

The first case study in this portfolio built primarily on company financial disclosures (SD Guthrie, IOI, KLK, Genting Plantations FY2025 segment results) rather than government statistics alone. Traces the industry from its 1917 origin through Indonesia's 2007 overtake, a real margin-capture finding (upstream earned 5x what downstream did in FY2025), an honestly-disclosed data-licensing issue found and corrected mid-project, the 2026 Iran war's effect on palm oil's price link to crude oil, and closes on Sawit EcoTherm, Malaysia's genuinely new bet on palm oil as an AI data centre coolant.

`Python`; **Complete**

### ✈️ 010: [AirAsia / Capital A: The Whole Ecosystem (History, the Business Empire, and the 2026 Crisis)](https://github.com/ooi-darren/airasia-capital-a)

<img src="./assets/010-airasia.png" width="640" alt="Stylised climbing airplane icon representing AirAsia Group and Capital A">

**Question:** "AirAsia" today is actually two separate companies with five other businesses between them, logistics, aircraft maintenance, a travel app, a fintech brand, and a catering arm. Is the September 2026 crisis a symptom of a broadly struggling ecosystem, or is it concentrated in one piece of it?

An 18-notebook segment-first structure covering both companies that emerged from a January 2026 reverse acquisition (Capital A Berhad and AirAsia Group Berhad) and all six businesses between them, the first case study in this portfolio built around one company's own financial statements as its core structure. Includes a direct balance-sheet reconciliation (a widely-cited RM18.4 billion liabilities figure vs RM2.76 billion in lease liabilities vs the real RM14.5 billion working-capital deficit neither side's framing stated), and a same-quarter portfolio scorecard showing the airline is the only one of the six businesses examined that shrank in 2Q2026.

`Python` `SQL`; **Complete**

Ten case studies, chosen for range across industries and depth over volume. New case studies are added one at a time, each only once it's genuinely done, not before.

## How I work

Business problem → objectives → data acquisition → cleaning → analysis → visualization → insight → recommendation. Every notebook opens with the question and the answer, then shows the reasoning between them, including what the data didn't support.

Every repo includes a `requirements.txt` and a "Reproducing This Analysis" section: clone it, `pip install -r requirements.txt`, and the notebooks run against the data already checked into `data/processed/`.

## Toolkit

Python · SQL · Git

## Contact

[LinkedIn](https://www.linkedin.com/in/darrenooizhixian)
