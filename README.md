<!-- Header banner -->
<p align="center">
  <img src="assets/img/header.svg" width="100%" />
</p>

<p align="center">
  <img src="assets/img/typing.svg" />
</p>

<p align="center">
  <a href="https://pann-resume-five.vercel.app/"><img src="assets/badges/Portfolio-000000-lg.svg" /></a>
  <a href="https://www.linkedin.com/in/pann-sreyoun-57ab011aa/"><img src="assets/badges/LinkedIn-0A66C2-lg.svg" /></a>
  <a href="https://t.me/pannmonster"><img src="assets/badges/Telegram-26A5E4-lg.svg" /></a>
  <a href="https://www.salesforce.com/trailblazer/koq7k3888ucievq8g0"><img src="assets/badges/Trailhead-00A1E0-lg.svg" /></a>
  <a href="mailto:pannsreyoun5@gmail.com"><img src="assets/badges/Email-EA4335-lg.svg" /></a>
</p>

---

<!-- About: text + GIF side by side -->
<table>
<tr>
<td width="58%" valign="top">

### ✳ About Me

I build full-stack web apps with **Rails, Laravel, Vue & Next.js** — and connect them to the systems businesses actually run on: **Shopify, Stripe, ERPs, CRMs and accounting tools**.

Hand me a project I've never touched and I'll research my way to a working solution — that's the part of the job I love.

- 💳 **Stripe** — subscriptions, one-time checkout, renewals, refunds
- 🛒 **Shopify** — B2B, Functions, App Extensions, Metaobjects
- 🔗 **Sync** — Brevo · HubSpot · M18 / RISE ERP · Xero · OData
- ⚙️ **Automation** — n8n · Sidekiq · webhooks
- 🤖 **AI** — agentic LLM loops, function-calling, AI-powered CRM features
- ☁️ **Salesforce** — Apex · LWC · Flow

</td>
<td width="42%" align="center">
  <img src="assets/img/coding.gif" width="100%" />
</td>
</tr>
</table>

```ruby
class PanSreyoun < Developer
  def initialize
    @role      = "Full-Stack E-Commerce Developer"
    @companies = %w[Techflow_Agency SyncMusic.Rocks Black_Durian]
    @based_in  = %w[Phnom_Penh Hong_Kong]
    @languages = %w[Khmer English]
    @stack     = %i[rails laravel nextjs vue shopify stripe postgres]
    @pair      = "Claude 🤖"
  end

  def motto
    "AI won't replace developers — but developers who use AI will replace those who don't."
  end
end
```

---

### 💼 Experience

> **🟠 Full-Stack Developer** · **Techflow Agency** · `Present`
> - Build and maintain a **Rails 7.2** membership platform for a Paris real-estate investors' club — tiered plans, duo memberships, renewals
> - Integrate **Stripe** (subscriptions & one-time checkout, webhooks, refunds) and **Brevo** CRM deal sync
> - Automate invoicing with **n8n → Pennylane**, background jobs with **Sidekiq**, features covered by **RSpec**
> - Ship with **Docker** to **DigitalOcean** — staging-first releases and end-to-end checkout testing

> **🟠 Full Stack Engineer** · **SyncMusic.Rocks** *(Black Durian group)* · `Jan 2026 – Present`
> - Own the **AI feature layer** of a metadata-driven music-licensing CRM (**Laravel + Vue SPA**): 40+ features across 12 families — natural-language CRM queries, scored prioritization, brief parsing, AI-drafted comms, meeting-summary-to-CRM updates, catalog insights
> - Shipped the **data-enrichment** family: an agentic LLM loop (function-calling + live web search) proposing sourced, confidence-graded updates in single, bulk and in-chat modes, with review panel, CRM-wide reconciliation and duplicate detection
> - Architected the **AI infrastructure**: provider-independent LLM integration, dedicated AI entities (result store, chat history, audit trail, job queue) on an async side-server — with cost controls, per-user limits and SSRF-guarded fetching

> **🟠 Full-Stack Developer · Shopify Consultant** · **Black Durian Co., Ltd** · `Apr 2025 – Present`
> - Co-built **RISE**, an in-house ERP (**Laravel + Vue.js, PostgreSQL**) for Hong Kong clients — inventory/stock, orders & invoicing, customer/CRM modules end to end
> - Architected **two-way Shopify ↔ ERP sync** (products, customers, sales orders, invoices, receipts) via webhooks and an OData async-job API; integrated **Xero**, payment gateways and shipping carriers
> - Built custom **Liquid** themes (OTP login, B2B-vs-personal segmentation), **Admin App UI Extensions** and metaobject/metafield architectures for credit terms, legal entities and production capacity
> - Designed a **metaobject-driven anti-oversell engine**: per-SKU daily caps synced from the ERP block over-limit orders in real time
> - Primary technical contact for merchants — demos, requirements, third-party apps (Zapiet, Stripe, Simple Bundle, Report Pundit)

> **⚪ Salesforce Developer** *(Triggdigital)* · **Gaeasys Co., Ltd** · `Feb 2025 – Mar 2025`
> - Automated document-generation pipeline (**Apex, Lightning Components, Documill Dynamo**) merging Salesforce + ADvendio campaign data into client-ready PowerPoint/Excel

> **⚪ Frontend Developer** · **Gaeasys Co., Ltd** · `May 2024 – Feb 2025`
> - Responsive **Next.js / TypeScript** apps across e-commerce and media — dynamic routing, optimized data fetching, **next-intl** localization
> - Full-stack where needed: **Laravel Backpack** admin panels with role-based access (Troke eLibrary, B2E store)

> **⚪ Full-Stack Developer (Internship)** · **Chhoun Yerng** · `Jan 2024 – May 2024`
> - Lottery website and web app with **Vue.js / Nuxt.js**, alongside a 3-person design team

---

### 🧰 Tech Stack

<p align="center">
  <img src="assets/img/skills-1.svg" /><br/><br/>
  <img src="assets/img/skills-2.svg" /><br/><br/>
  <img src="assets/img/skills-3.svg" />
</p>

<p align="center">
  <img src="assets/badges/Stripe-635BFF-lg.svg" />
  <img src="assets/badges/Shopify-7AB55C-lg.svg" />
  <img src="assets/badges/Sidekiq-B1003E-lg.svg" />
  <img src="assets/badges/n8n-EA4B71-lg.svg" />
  <img src="assets/badges/Brevo-0B996E-lg.svg" />
  <img src="assets/badges/HubSpot-FF7A59-lg.svg" />
  <img src="assets/badges/Salesforce-00A1E0-lg.svg" />
  <img src="assets/badges/Xero-13B5EA-lg.svg" />
  <img src="assets/badges/GraphQL-E10098-lg.svg" />
  <img src="assets/badges/DigitalOcean-0080FF-lg.svg" />
  <img src="assets/badges/RSpec-CC342D-lg.svg" />
  <img src="assets/badges/AI_-_LLM_Agents-F97316-lg.svg" />
</p>

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🛒 Waves Pacific Wholesale · `2026`
B2B Shopify store for a HK food distributor — **M18 ERP + HubSpot** customer approval and two-way order sync.<br/>
<img src="assets/badges/Shopify-7AB55C-sm.svg" /> <img src="assets/badges/HubSpot-FF7A59-sm.svg" /> <img src="assets/badges/B2B-334155-sm.svg" />

</td>
<td width="50%" valign="top">

#### 🍰 Bakehouse Occasions · `2025`
Custom Shopify storefront for a HK bakery with one- and two-way **RISE ERP** sync via webhooks & OData.<br/>
<img src="assets/badges/Shopify-7AB55C-sm.svg" /> <img src="assets/badges/Laravel-FF2D20-sm.svg" /> <img src="assets/badges/OData-334155-sm.svg" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📄 Salesforce Document Automation · `2025`
Pipeline merging **Salesforce + ADvendio** campaign data into client-ready PowerPoint/Excel via Documill.<br/>
<img src="assets/badges/Salesforce-00A1E0-sm.svg" /> <img src="assets/badges/Apex-334155-sm.svg" />

</td>
<td width="50%" valign="top">

#### 🎨 Custom Shopify Themes & Apps · `2025`
Bespoke **Liquid** themes plus app setup & consulting for Hong Kong enterprise merchants.<br/>
<img src="assets/badges/Liquid-004999-sm.svg" /> <img src="assets/badges/Metafields-334155-sm.svg" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏛️ Troke eLibrary · `2024`
Public digital archive for **Cambodia's Ministry of Land Management**, with role-based access to sensitive documents.<br/>
<img src="assets/badges/Laravel-FF2D20-sm.svg" /> <img src="assets/badges/Backpack-334155-sm.svg" />

</td>
<td width="50%" valign="top">

#### ⚡ B2E E-Commerce Store · `2024`
B2B electrical & engineering supplies store — **Next.js** storefront, Laravel admin.<br/>
<img src="assets/badges/Next-js-000000-sm.svg" /> <img src="assets/badges/Laravel-FF2D20-sm.svg" />

</td>
</tr>
</table>

<p align="center"><a href="https://pann-resume-five.vercel.app/"><img src="assets/badges/See_all_case_studies_--F97316-lg.svg" /></a></p>

---

### 📊 GitHub Analytics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=PannTechFlow&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&title_color=f97316&icon_color=f97316" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PannTechFlow&layout=compact&theme=tokyonight&hide_border=true&title_color=f97316" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=PannTechFlow&theme=tokyonight&hide_border=true&ring=f97316&fire=f97316&currStreakLabel=f97316" />
</p>
<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=PannTechFlow&theme=tokyonight" />
</p>
<p align="center">
  <img src="https://github-trophies.vercel.app/?username=PannTechFlow&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&row=1" />
</p>

### 🐍 Contribution Snake
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PannTechFlow/PannTechFlow/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/PannTechFlow/PannTechFlow/output/github-snake.svg" />
  </picture>
</p>

---

### 🎓 Education
**International Diploma in Software Development** · IT STEP Academy Institute · `Jan 2022 – Apr 2025`<br/>
<sub>2.5-year internationally certified program — OOP (C++, C#/.NET, Java), web (Angular, React, PHP/MySQL), databases (SQL Server, Oracle), mobile & game dev (Android, Unity)</sub>

<p align="center">
  <b>Got a Shopify build, an integration headache, or a full-stack idea? Let's build something <i>loud</i>.</b><br/><br/>
  <a href="https://t.me/pannmonster"><img src="assets/badges/Let-s_talk-F97316-lg.svg" /></a>
</p>

<!-- Footer banner -->
<img src="assets/img/footer.svg" width="100%" />
