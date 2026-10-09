# Affiliate intro page — Weblate PO keys

English source strings for the Airpaz Affiliate onboarding page (`airpaz-web-frontend`).
Import-ready file: [`en.po`](./en.po) (monolingual gettext: `msgid` = key, `msgstr` = English).

## Placeholders

| Placeholder | Value | Note |
|---|---|---|
| `{rate}` | `2%` | Keeps the rate out of the translations, so changing it needs no re-translation |
| `{year}` | `2011` | Founding year |
| `{highlight}` | text of the matching `*_highlight` key | The page wraps it in `<em>` / `<strong>` |

Not translated: currency amounts (`USD 500`, `USD 10`, table amounts) come from the currency formatter; SVG icons and JSON-LD are skipped.

## Keys (82)


### meta

| Key | English |
|---|---|
| `affiliate_intro.meta.title` | Welcome to Airpaz Affiliate — Earn {rate} on every booking |
| `affiliate_intro.meta.description` | Introduction page for the Airpaz Affiliate Dashboard: what the program is, the benefits of joining, and how the {rate} commission on every transaction works. |

### hero

| Key | English |
|---|---|
| `affiliate_intro.hero.kicker` | Airpaz Affiliate Program |
| `affiliate_intro.hero.title` | Turn your audience into {highlight} |
| `affiliate_intro.hero.title_highlight` | travel earnings |
| `affiliate_intro.hero.subtitle` | Welcome to the Airpaz Affiliate Program. Share flights, hotels, activities and transport from Airpaz with your audience and earn a {highlight} your customers make. |
| `affiliate_intro.hero.subtitle_highlight` | {rate} commission on every transaction |
| `affiliate_intro.hero.cta_primary` | Get my affiliate link |
| `affiliate_intro.hero.cta_secondary` | See how it works |

### commission_card

| Key | English |
|---|---|
| `affiliate_intro.commission_card.aria_label` | Commission summary |
| `affiliate_intro.commission_card.label` | Your commission rate |
| `affiliate_intro.commission_card.rate_suffix` | on every transaction |
| `affiliate_intro.commission_card.note` | Applies to every completed booking made by customers you refer — flights, hotels, activities and transport. |
| `affiliate_intro.commission_card.example_customer_books` | Customer books |
| `affiliate_intro.commission_card.example_you_earn` | You earn |

### highlights

| Key | English |
|---|---|
| `affiliate_intro.highlights.aria_label` | Program highlights |
| `affiliate_intro.highlights.free_title` | Free to join |
| `affiliate_intro.highlights.free_desc` | No fees, no minimum traffic |
| `affiliate_intro.highlights.inventory_title` | Global inventory |
| `affiliate_intro.highlights.inventory_desc` | Flights, hotels, activities, transport |
| `affiliate_intro.highlights.tracking_title` | Real-time tracking |
| `affiliate_intro.highlights.tracking_desc` | Clicks, bookings and earnings |
| `affiliate_intro.highlights.trusted_title` | Trusted since {year} |
| `affiliate_intro.highlights.trusted_desc` | Travelers already know Airpaz |

### about

| Key | English |
|---|---|
| `affiliate_intro.about.kicker` | What is Airpaz Affiliate? |
| `affiliate_intro.about.title` | A partnership that pays you for every traveler you send our way |
| `affiliate_intro.about.paragraph_1` | Airpaz is an online travel agent that has helped travelers book flights, hotels, activities and ground transport since {year}. The Airpaz Affiliate Program lets you share that inventory with your own audience — on a blog, a social channel, a newsletter, a travel community or a business website. |
| `affiliate_intro.about.paragraph_2` | You get a personal tracking link and ready-made creative assets. Whenever someone clicks your link and completes a booking on Airpaz, the transaction is attributed to you and a {rate} commission is credited to your affiliate account. You can follow every click, booking and payout right here in your dashboard. |
| `affiliate_intro.about.paragraph_3` | There is nothing to build, stock or support. Airpaz handles search, payment, ticketing and customer service — you simply bring the travelers. |

### products

| Key | English |
|---|---|
| `affiliate_intro.products.aria_label` | What you can promote |
| `affiliate_intro.products.flights_title` | Flights |
| `affiliate_intro.products.flights_desc` | Hundreds of airlines worldwide |
| `affiliate_intro.products.hotels_title` | Hotels |
| `affiliate_intro.products.hotels_desc` | Stays for every budget |
| `affiliate_intro.products.activities_title` | Activities |
| `affiliate_intro.products.activities_desc` | Attractions, tours and tickets |
| `affiliate_intro.products.transport_title` | Transport |
| `affiliate_intro.products.transport_desc` | Trains, buses, ferries and cars |

### how

| Key | English |
|---|---|
| `affiliate_intro.how.title` | How it works |
| `affiliate_intro.how.subtitle` | Four simple steps from sign-up to your first commission. |
| `affiliate_intro.how.step_1_title` | Join for free |
| `affiliate_intro.how.step_1_desc` | Create your affiliate account and get instant access to this dashboard. |
| `affiliate_intro.how.step_2_title` | Share your link |
| `affiliate_intro.how.step_2_desc` | Use your tracking link, banners and widgets anywhere your audience is. |
| `affiliate_intro.how.step_3_title` | Customers book |
| `affiliate_intro.how.step_3_desc` | Travelers click through and complete their booking on Airpaz as usual. |
| `affiliate_intro.how.step_4_title` | Earn {rate} per transaction |
| `affiliate_intro.how.step_4_desc` | Every completed transaction credits {rate} to your account, ready for payout. |

### benefits

| Key | English |
|---|---|
| `affiliate_intro.benefits.title` | Why affiliates love the program |
| `affiliate_intro.benefits.subtitle` | Everything you need to earn is already set up for you. |
| `affiliate_intro.benefits.core_tag` | Core benefit |
| `affiliate_intro.benefits.commission_title` | {rate} commission on every transaction |
| `affiliate_intro.benefits.commission_desc` | Not just the first purchase — every transaction your customers make earns you {rate}, across all Airpaz products. |
| `affiliate_intro.benefits.products_title` | One link, four products |
| `affiliate_intro.benefits.products_desc` | Promote flights, hotels, activities and transport in one program — more ways for the same traveler to book through you. |
| `affiliate_intro.benefits.reports_title` | Transparent real-time reports |
| `affiliate_intro.benefits.reports_desc` | Track clicks, conversions, bookings and earnings as they happen, and export reports whenever you need them. |
| `affiliate_intro.benefits.assets_title` | Ready-made creative assets |
| `affiliate_intro.benefits.assets_desc` | Banners, widgets, deep links and seasonal campaign materials — download and publish in minutes. |
| `affiliate_intro.benefits.payouts_title` | Reliable payouts |
| `affiliate_intro.benefits.payouts_desc` | Commissions are credited to your account automatically and paid out on a regular schedule you can follow in the dashboard. |
| `affiliate_intro.benefits.support_title` | Dedicated partner support |
| `affiliate_intro.benefits.support_desc` | A partner team to help with integration, campaigns and questions, plus guides right inside the dashboard. |

### explainer

| Key | English |
|---|---|
| `affiliate_intro.explainer.title` | Simple, flat {rate} on every transaction |
| `affiliate_intro.explainer.desc` | No tiers to decode and no fine print on product type. Whatever your customer books, you receive {rate} of the transaction value. |
| `affiliate_intro.explainer.point_1` | Earned on every completed transaction, not just the first one |
| `affiliate_intro.explainer.point_2` | Same rate for flights, hotels, activities and transport |
| `affiliate_intro.explainer.point_3` | Credited to your account automatically — see it in Earnings |
| `affiliate_intro.explainer.table_title` | What {rate} looks like |
| `affiliate_intro.explainer.table_col_booking` | Your customer books |
| `affiliate_intro.explainer.table_col_transaction` | Transaction |
| `affiliate_intro.explainer.table_col_earn` | You earn |
| `affiliate_intro.explainer.example_domestic_flight` | A domestic flight |
| `affiliate_intro.explainer.example_hotel_stay` | A 3-night hotel stay |
| `affiliate_intro.explainer.example_international_trip` | An international round trip |
| `affiliate_intro.explainer.example_full_trip` | A full trip (flight + hotel + activities) |
| `affiliate_intro.explainer.fine_print` | Amounts are illustrative examples of the {rate} calculation. Commission is credited on completed transactions and shown in your Earnings report. |

### final_cta

| Key | English |
|---|---|
| `affiliate_intro.final_cta.title` | Ready to start earning? |
| `affiliate_intro.final_cta.desc` | Grab your affiliate link, pick a banner from Creative Assets, and your first {rate} commission could be one booking away. |
| `affiliate_intro.final_cta.cta_primary` | Get my affiliate link |
| `affiliate_intro.final_cta.cta_secondary` | Browse creative assets |

### footer

| Key | English |
|---|---|
| `affiliate_intro.footer.note` | Commission rate: {rate} per completed transaction. Example amounts on this page are illustrative. Full program terms are available in the Help section of your dashboard. |
