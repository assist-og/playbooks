# Caleb Elu — Complete Local SEO Playbook
## Extracted from 19 YouTube videos (March 2026)

---

# PART 1: THE PHILOSOPHY

## Core Belief: Local SEO ≠ Regular SEO
- Regular SEO = rank website URLs
- Local SEO = rank your **Google Business Profile** in the map pack
- 60–70% of clicks go to the top 3 map positions
- Position 4+ = invisible (you have to click "More businesses" which nobody does)
- **Every page on a local business website exists for ONE reason: to help the GBP rank higher**

## What Google Actually Rewards: Goal Completion
- Google's #1 priority: did the user get what they came for?
- If someone clicks your site and doesn't go back to Google = win
- If they click back and try the next result = very bad signal
- Google tracks this via Chrome browser data + Android
- **Stop optimizing for time-on-site. Optimize for "user stops searching."**
- For local: goal completion = user calls, gets directions, books appointment
- Google knows if you answered the phone (Chrome/Android data)

## The 3 Ranking Factors (Local Algorithm)
Caleb uses a "three glasses" analogy:
1. **Proximity** — how close the searcher is to your business (you can't control this)
2. **Relevance** — does Google believe you actually do the service searched? (topical depth)
3. **Authority/Trust** — do other entities vouch for you? (links, citations, consistency)

Your job: fill the relevance and authority glasses until they overflow enough to overcome the proximity penalty.

## Entity-Based Search (Post-2018)
- Google invented transformer technology in 2017 (same T in ChatGPT)
- Google no longer matches keywords — it matches **entities**
- An entity = a thing Google recognizes: business, location, service, person
- Google asks: "Is this business a real entity connected to this location and this service?"
- This is why keyword research is dead for local SEO
- This is also why optimizing for Google simultaneously optimizes for ChatGPT/AI

## What Doesn't Matter (According to Caleb)
- **Domain Authority / Domain Rating** — vanity metric for local. A DA-5 local plumber crushes a DA-80 national directory
- **Review count for ranking** — reviews drive CONVERSION, not RANKING. He shows examples of 488-review businesses outranking 19,000-review competitors repeatedly
- **Blog posts** — "5 ways to unclog a drain" builds zero local relevance. Stop paying agencies for this
- **Keyword research tools (Ahrefs, SEMrush)** — can't see click-through rates, phone calls, goal completion. Incomplete picture
- **High-volume keyword chasing** — Google matches entities, not keyword strings

## What Actually Matters
- GBP completeness and accuracy
- Website structure mirroring GBP exactly
- Dedicated pages for every service and category
- Internal linking following GBP hierarchy
- Local authority links (chambers of commerce)
- External links to every page (proving content isn't AI slop)
- Goal completion on every page
- Mobile-first design
- Schema markup
- Consistency between GBP and website

---

# PART 2: THE DIAGNOSTIC PHASE

## Step 1: Run a Local Rank Map
**Tool:** Lead Snap (or any grid search tool)
- Shows GBP ranking position at 169+ points across the city
- Green = top 3 (visible, getting calls)
- Yellow = positions 4–10 (invisible but close)
- Red = not found

**Key metric: Top 3%**
- What percentage of the map is green?
- This single number determines your entire strategy

### How to benchmark:
1. Run rank maps for the top 3–4 competitors dominating the keyword
2. Look at their top 3%
3. In competitive markets (Houston), top player might be 28%
4. In easy markets (Gary, IN), top player might be 94%
5. That number is your goal

### Decision threshold:
- Calculate 25–50% of the top player's score as your "topical relevance threshold"
- If top player = 80%, threshold = 30–40%
- If top player = 40%, threshold = 15–20%

**Below threshold → build topical content (prove expertise)**
**At/above threshold → build geographical content (expand coverage area)**

## Step 2: Size Up Competitors (Free Method)
Use Google's `site:` operator:
1. `site:competitor.com` → see total indexed pages
2. `site:competitor.com water heater` → see how much content they have on a specific topic
3. Compare your index count vs. top 3

**What this tells you:**
- If competitors have 175 pages and you have 4, you don't have a backlink problem — you have a relevance problem
- If they have 200 pages but most are blog posts ("5 ways to..."), those are fluff and can be ignored
- If they have 200 pages of specific services and locations, that's real topical authority

## Step 3: Check GBP Categories and Services
**Tool:** GMB Everywhere (Chrome extension)
- Shows every category competitors are using
- Shows how many GBPs use each category
- Shows related secondary categories

**What to check:**
- Is the primary category the best fit?
- How many secondary categories? (most businesses only have 1, should have 3–5+)
- How many services listed? (most have 0–5, should have 20–30+)

## Step 4: Entity Test
Verify if Google treats services as separate entities:
1. Open two tabs
2. Tab 1: search `plumber [city]` — note top 3
3. Tab 2: search `water heater installation [city]` — note top 3
4. If results are completely different → separate entities → needs its own page + strategy
5. If results are similar → Google sees them as same entity → don't need separate strategy

## Step 5: Audit Competitor Websites
For each top 3 competitor, check:
- **Title tag**: does it include primary category + city?
- **H1**: does it match?
- **Homepage content**: goal completion focus or fluff?
- **GBP embed**: present?
- **Google review embed**: present? Using Google's actual colors?
- **Schema markup**: use structured data testing tool
- **Menu/services**: HTML or PDF/images?
- **Mobile UX**: popups? animated heroes? usability?
- **Site size**: `site:domain.com`
- **Topic depth**: `site:domain.com [service keyword]`

## Step 6: Google Search Console Analysis
**Tool:** Search Analytics for Sheets (free Google Sheets extension)

### Page-Query Alignment Check:
1. Go to Performance → filter by Pages
2. For each page, check which queries trigger impressions
3. Healthy page = queries match intended service
4. Confused page = queries belong to a different page
5. **When Google is confused, it hedges. It doesn't rank you.**

### Bulk method:
1. Use Search Analytics for Sheets extension
2. Pull last 90 days
3. Dimensions: query + page
4. Export up to 25,000 rows
5. Feed to AI with prompt to check alignment across all pages

### Index Coverage Check:
1. Go to GSC → Pages
2. Check indexed vs not indexed
3. Two danger statuses:
   - "Discovered but not indexed" = Google found it, decided not worth crawling
   - "Crawled but not indexed" = Google looked at it and rejected it
4. Fix: improve content, add images/tables/callouts, internal links, one external link, outbound link to authority site
5. Then: URL Inspection → Request Indexing

### Modifier Mining:
1. From GSC export, look for modifier terms showing up in queries
2. Examples: "lead" pipe, "tankless" water heater, "emergency", "same day"
3. If modifier appears in queries but NOT on the page → add it
4. This is confirming what Google already suspects about your page
5. Use AI prompt to rewrite content naturally weaving modifiers in

---

# PART 3: GBP OPTIMIZATION

## Categories
- Most businesses have 1 category. Google allows up to 10.
- Target 2–4 minimum, more if relevant
- Use GMB Everywhere to see what competitors use
- Use AI prompt to suggest strategic categories
- **Caution:** AI hallucinate fake categories. Cross-reference against actual GBP category list

## Services
- List at least 20–30 services
- Organize services under the correct category
- Google checks semantic match between categories and services
- Use AI prompt to generate comprehensive service lists

## Fill Out Everything
- Business description: max 750 characters, use all of it
- Photos: at least 20, add new one weekly, geotag them
- Posts: weekly (automate with 52-post prompt, schedule in Lead Snap)
- Attributes: check every applicable box (veteran-owned, accepts credit cards, ADA, etc.)
- Q&A section
- Products section if applicable
- Special hours

## Automated GBP Management
1. **Weekly posts**: one prompt generates 52 posts (4 types: promotional, educational, engagement, seasonal). Schedule all at once. Repeat annually.
2. **Weekly geotagged photos**: upload weekly. Lead Snap auto-geotags.
3. **AI review responses**: set up once (25 seconds), handles all responses automatically
4. **Automated citations**: Apple Maps, Bing for Business, Yelp, major directories

---

# PART 4: WEBSITE STRUCTURE — THE CORE 30

## Architecture
```
Homepage (primary category + city)
├── Category Page 1 (secondary category + city)
│   ├── Service Page A (service + city)
│   ├── Service Page B (service + city)
│   └── Service Page C (service + city)
├── Category Page 2 (secondary category + city)
│   ├── Service Page D (service + city)
│   └── Service Page E (service + city)
├── Category Page 3 (secondary category + city)
│   ├── Service Page F (service + city)
│   └── ...
└── General Service Pages → link back to homepage
```

**This mirrors your GBP structure exactly.**

## Homepage Requirements (GBP Landing Page)
8 consistency signals:
1. **Title tag**: primary category + city + brand (e.g., "Houston Plumber | Same Day Service | Brand")
2. **H1**: primary category + city
3. **Google Maps embed** of GBP location
4. **Secondary categories** mentioned as H2 subheadings
5. **Google review widget** displaying GBP reviews
6. **Address** matching GBP character-for-character
7. **Phone number** matching GBP character-for-character
8. **Local business schema**

### Homepage content structure:
- First paragraph: immediately answer why the searcher should call. Service + city in first sentence. Phone number visible. Social proof above the fold.
- Each secondary category gets an H2 + 50–100 words + editorial link to category page
- Core services mentioned with links
- Google review embed (use Google's actual colors for trust)
- GBP map embed (lower on page — user already came from GBP)
- CTA

### What NOT to do on homepage:
- Start with "Welcome to ABC Plumbing, family-owned since 1985" → nobody cares
- Start with business history
- Use animated hero images (split-tested: causes bounces)
- Immediate popup (delay it — user hasn't decided if they're interested yet)
- Talk about yourself instead of the user

### Correct approach:
- "Houston plumber serving the Heights. Call us for same day service."
- Lead with what you do FOR them, not who you are

## Category Pages
- Target keyword: category name + city (e.g., "Drainage Service Houston")
- Title tag: category + city
- H1: category + city
- List relevant services as H2 subheadings
- 50–100 words per service
- Editorial link from each service section to its dedicated page
- 5–10 editorial links per category page

## Service Pages
- Target keyword: service + city (e.g., "Water Heater Replacement Houston")
- Title tag: service + city
- H1: service + city
- URL slug matches entity
- Detailed content: why customers need it, what it includes, how long it takes, what to expect
- Local specifics, not generic
- Schema markup (use AI to generate, validate with structured data testing tool)
- Internal links back to category page and homepage

## Core Services (High-Profit)
- Identify 2–4 "core services" the business really cares about (highest margin)
- For plumbers: usually water heater replacement + main drain line replacement
- Core services get child service pages underneath them for extra topical depth

## Internal Linking Rules
- **Editorial links pass authority. Navigation/footer links do not.**
- Homepage → category pages (editorial links in content)
- Category pages → service pages (editorial links in content)
- Service pages → back to relevant category page
- Geographic pages → relevant service pages
- Supporting content → core 30 pages
- **Link context matters**: Google reads the text surrounding the link

## Content Generation
- Use AI (Claude preferred over ChatGPT) with detailed prompts
- Feed AI: primary category, city, target keyword, secondary categories, all services, target length, words to avoid
- AI gets you 80–90% there
- **Human editor required**: add real business stories, local flavor, client anecdotes, personality
- Add images (client photos best, AI-generated acceptable)
- Add tables, callouts, bullet points, proper formatting
- Short paragraphs
- **Google renders pages in latest mobile Chrome** — if it looks like AI slop, Google treats it as AI slop

## What Makes Content Rank vs. Not Rank
- **Ranks**: locally specific, mentions neighborhoods, references local conditions, sounds like someone who actually works there
- **Doesn't rank**: generic service descriptions, "5 ways to..." blogs, platitudes ("we provide quality service"), walls of text with no formatting

## Accordion/Dropdown/Hidden Content
- **Avoid click-to-expand sections** (FAQ dropdowns, accordions)
- Google bot renders in mobile Chrome and **cannot click**
- Content hidden behind click events is heavily deprecated
- Solution: have all content visible on first page load

## Unique Content
- Check for duplicate content using exact-phrase Google searches
- Common with franchises/chains using template copy
- Use AI to rewrite to be unique while keeping same meaning

---

# PART 5: LINK BUILDING

## Type 1: "Not AI Slop" Links
- Medium-quality external links validating your content is worth reading
- Don't need to be local or from powerful domains
- Need one per page minimum (30 core pages = 30 links)
- Purpose: tell Google your content is legitimate, not just AI-generated filler
- Cost: ~$35/link at Caleb's service (Ice Cream Truck Shop)
- Without these, content "caps out around position 7"

## Type 2: Local Authority Links
**The most powerful links for local SEO.**

### #1: Chamber of Commerce (THE top link)
- Most cities charge $200–$300/year
- Google recognizes chambers as local authority sites
- **Join multiple chambers** — every chamber within 50–70 miles
- Caleb has had clients join 10+ chambers
- Chambers don't care if you're 30 miles away as long as you pay membership
- One client: joined local + every chamber within 50 miles → jumped from position 8 to position 3

### Other local links:
- Youth sports sponsorships
- Local charity donations/events
- Community events
- Local college events (one TEDx sponsorship for $250 moved a client 4 ranking positions)
- City preferred contractor directories
- Local festivals
- Any local org with a website that will link to you

### Finding local link opportunities:
- Use AI prompt to search for organizations, charities, sports leagues, events looking for sponsors
- Prompt finds opportunities instantly (used to require a dedicated employee)

## What Doesn't Work for Links Anymore
- VA-filled citations from 2017 (tiny white boxes on random directory sites)
- Guest post bio links (Google rolled out update largely ignoring these)
- Links from national blogs with no local relevance
- Cold email outreach for guest posts (race to the bottom)

## Citations That DO Work
- Platforms requiring **business verification**:
  - Apple Maps
  - Bing for Business
  - Better Business Bureau
  - Facebook Business
  - Navigation systems (BMW, Mercedes)
- These signal trust because they're hard to fake
- Also important for AI model recommendations (ChatGPT, etc.)

---

# PART 6: TOPICAL RELEVANCE (Below Threshold)

When your top 3% is below threshold, Google doesn't trust you're an expert. Build supporting content.

## Method: FAQ-Based Supporting Pages

### Source 1: People Also Ask (PAA)
1. Search target keyword (without city) on Google
2. Find "People Also Ask" section
3. Click questions to load more (20–30 questions easily)
4. **DO NOT copy questions word-for-word** — Google is wise to this abuse
5. Rephrase questions with different word order, same meaning
6. "How much does it cost to replace a water heater?" → "What's the typical price for water heater replacement?"

### Source 2: Reddit
- Use AI prompt with city + service to crawl Reddit for real local questions
- These are gold: actual questions from real people in the area
- More specific and local than PAA questions

### How to use FAQs:
1. Add brief answer (couple dozen words) to the relevant core 30 page
2. Include editorial link to a new supporting content page
3. On supporting page: answer the question comprehensively (hundreds of words)
4. Each supporting page needs one "not AI slop" external link
5. Keep building until you hit your top 3% threshold

### What this does:
- Adds value to main pages without bloating them
- Creates internal linking from core 30 to supporting pages
- Proves depth of expertise to Google

---

# PART 7: GEOGRAPHICAL RELEVANCE (At/Above Threshold)

When Google trusts your expertise, expand your coverage area.

## Method: Landmark-Based Geographic Pages

### How to identify targets:
1. Look at rank map for positions 4, 5, 6 (close to top 3)
2. Zoom into Google Maps overlay
3. Find geographic landmarks Google recognizes:
   - Neighborhoods
   - Subdivisions
   - Parks
   - Lakes
   - Major intersections
   - Shopping centers
   - Schools
   - City buildings
4. Only target areas where actual customers live (good demographics, residential)

### Why positions 4–6:
- Much easier to move from 4→3 than 19→3
- Moving from 19→4 gets you nothing (still invisible)
- Positions 4–6 mean you're close — just need geographic relevance push

### Target keyword format:
`[service] near [landmark] in [city]`
Example: "Water heater replacement near the intersection of 90 and 94 in Gary"

### Content requirements:
- NOT just swapping city names on generic content
- Write about the specific neighborhood
- Reference local landmarks
- Mention common issues in that area (older homes with cast iron pipes, newer construction with PEX, coastal weather, etc.)
- Reference local businesses nearby
- Mention driving routes technicians take to that area
- Local FAQ section specific to that neighborhood
- Each page needs one "not AI slop" external link

### Internal linking:
- Create a Locations page linking to all geographic pages
- Each geographic page links to relevant service page
- E.g., "Water Heater Replacement Memorial Heights" → links to "Water Heater Replacement Houston" main page

### Expansion loop:
- Run rank maps every couple weeks
- As authority grows, new areas appear at positions 4–6
- Target those new areas
- Green zone grows outward from address

---

# PART 8: AI SEO / AI VISIBILITY

## The Threat: AI Poisoning
- Anthropic study proved 250 malicious documents can corrupt even 13B-parameter models
- 0.000016% of training data = enough to create backdoor
- Defenses don't scale with model size
- Barrier to entry for attackers is very low (just post content online)
- AI companies are only ~3 years into building content quality filters (vs. Google's 20+ years)

## The Opportunity: Brand Presence in Training Data
- Same mechanism that allows poisoning can be used for legitimate brand building
- AI learns from patterns and consensus across sources
- If you don't actively build presence, you leave it to chance

## "250 Authority Content Protocol"
- Produce at least 250 pieces of high-quality, consistent content defining who you are and what you do
- **Distribution is critical**: same expertise expressed across different formats, platforms, angles
- NOT 250 identical articles (AI detects echo chambers)
- Types: LinkedIn articles, blog case studies, Reddit comments, guest posts, Medium articles
- Shift focus across different aspects of expertise
- Goal: build genuine content footprint representing expertise across the internet

## Monitoring AI Reputation
- Don't just monitor Google — monitor Reddit, forums, review sites, Medium
- These are data sources that feed AI models
- If ChatGPT starts claiming false things about your business, investigate
- Use "Model Training Data Risk Auditor" prompt to check what AI models know about your brand

## What Makes AI Recommend You
- Same entity signals Google uses
- Consistency: name, address, phone across all sources
- Corroboration: multiple independent sources confirming the same information
- Verified citations (Apple Maps, BBB, Bing) → AI trusts these more
- Mismatch in NAP across directories → AI stops trusting you

## Tracking AI Traffic
- Use Google Analytics to filter referral traffic by AI source
- Can see visits from ChatGPT, Gemini, Perplexity, Grok
- Volume will be much lower than Google
- But: AI traffic generates **80% more revenue per visit** (Adobe research)
- Lower bounce rates (23% lower for retail)
- AI pre-qualifies visitors → higher intent

## Princeton University Findings
Three tactics that produced 40% increase in AI visibility:
1. Citing authoritative sources
2. Adding direct quotations from recognized experts
3. Including specific statistics and data points

Caleb built a "local SEO content writer" prompt that forces AI to write using this framework.

---

# PART 9: WEBSITE BUILD PROCESS

## Building with AI Tools (Lovable Demo)
Caleb demonstrates building a 54-page local site in hours using Lovable (AI website builder):

### Process:
1. **Prompt 0 — Planning**: Give Claude the business info, secondary categories, core services, all services. Claude organizes the entire site architecture, internal linking map, page hierarchy.

2. **Prompt 1 — Skeleton**: Give Lovable the site architecture. It builds all 59 pages with no content — just structure, navigation, internal linking, image placeholders.

3. **Prompt 2 — Content**: Simultaneously, use Claude to write landing page content. Feed it the architecture plan, primary category, city, GBP data, writing instructions, words to avoid. Claude writes the homepage content optimized for goal completion.

4. **Prompt 3 — Landing Page Buildout**: Give Lovable the Claude-generated content to populate the homepage.

5. **Prompt 4–N**: Repeat for category pages and service pages. Claude writes content, Lovable implements.

### Content writing rules:
- First paragraph: talk to the USER, not about the business
- Include service + city immediately
- Social proof high on page
- Google review embeds using Google's colors
- GBP embed lower on page
- Secondary categories as H2s with 50-100 words each
- Links to category/service pages
- No platitudes ("we provide quality service" = meaningless)
- Specific: what you do, where, how fast, why you're different

## Caleb's Claude Code AI Agent
- Built an AI agent that automates the entire local SEO process:
  - Entity research
  - GBP audit
  - Gap analysis (comparing GBP services/categories to website pages)
  - Content production
  - Schema markup
  - Image generation
  - Video generation + YouTube upload + embed
  - WordPress deployment
- Reduces 60 hours of agency work to 15 minutes of active time
- Available in his pro community

---

# PART 10: SCHEMA MARKUP

## What Schema Does
- "Labels on moving boxes" — tells Google/AI exactly what your content represents
- Google can often infer without schema (25 years of crawling)
- AI tools struggle much more without schema
- Important for both Google and AI visibility

## Schema Stack for Local Businesses
- LocalBusiness (or specific subtype: Plumber, Dentist, etc.)
- Organization
- WebSite
- BreadcrumbList
- Review / AggregateRating
- Service (for each service page)
- FAQPage (where appropriate)
- Menu (for restaurants)
- Product (where relevant)

## Implementation:
1. Use AI to generate schema for each page
2. Validate with Google's Structured Data Testing Tool
3. Zero errors, zero warnings required
4. If errors: feed errors back to AI, fix, revalidate
5. Place on the specific page it describes

---

# PART 11: CONVERSION & TRUST ELEMENTS

## Reviews
- **Reviews DO NOT help rankings** (proven repeatedly with data)
- Reviews help CONVERSION — they get you the call once you're visible
- Optimal rating: 4.7–4.9 stars (perfect 5.0 looks suspicious, actually converts worse)
- **Review embeds must look like Google reviews** — use Google's colors, not custom styling
- Embed reviews HIGH on the page
- Don't manually paste review text (can be faked) — embed from Google

## Social Proof
- Google review embed (using Google's actual interface/colors)
- Awards, certifications, recognition
- Featured in / as seen in
- Specific numbers: "425 new customers" > "many satisfied clients"
- Testimonials with dates (recent dates = more convincing)

## Trust Signals on Page
- Google review widget above the fold
- GBP map embed (confirms location)
- Address/phone matching GBP exactly
- Real photos (client photos > stock photos > AI photos)
- Specific local references

## Review Generation (Not for Ranking — for Conversion)
- Simple text message to last 10 happy clients
- Script: "Hey, hope you're doing well. If you're happy with our services at [business name], would you mind leaving us a quick review here? [link]"
- Personal text from same number customer interacts with = 50%+ success rate
- No fancy automation needed

---

# PART 12: MOBILE-FIRST

## Why It Matters
- For restaurants: ~80% of visitors are on mobile
- For most local businesses: majority mobile
- Google bot crawls with latest version of mobile Chrome
- Everything Google sees is the mobile version
- **Design for mobile first, then check desktop**

## Common Mistakes
- Immediate popups before trust is established
- Animated/sliding hero images (split-tested: cause bounces)
- Hover-over content (Google bot can't hover)
- Click-to-expand accordions (Google bot can't click)
- Scrolling carousels (users hate them, tested)
- Content hidden behind interactions

## Mobile UX Checklist
- Static hero image
- No immediate popup (delay until user shows engagement)
- Core CTA visible immediately
- Phone number clickable
- Address/hours easy to find
- Page loads fast
- Content all visible on first render
- Short paragraphs
- Clear visual hierarchy

---

# PART 13: IMPLEMENTATION TIMELINE

## Week 1: Foundation
**Days 1–3:**
- Access GBP
- Audit and optimize GBP (categories, services, fill every box)
- Schedule 52 weekly posts
- Upload/schedule photos
- Should take < 1 hour with AI

**Days 4–7:**
- Audit and optimize GBP landing page (homepage)
- Title tag: primary category + city
- H1: primary category + city
- GBP embed
- Local business schema
- Secondary categories mentioned as H2s

## Week 2: Content + Links
**Days 8–10:**
- Use AI to generate content for all core 30 pages
- Review each page, add personal touches
- Optimize title tags, H1s, H2s
- Set up internal linking structure
- Add images to every page

**Days 11–12:**
- Join local chambers of commerce
- Set up citations (Apple Maps, Bing, etc.)
- Begin acquiring local links
- Submit sitemap to Google Search Console

**Days 13–14:**
- Add schema markup to all pages
- Optimize images
- Check mobile responsiveness
- Ensure site loads quickly
- Validate schema (zero errors, zero warnings)

## Expected Results
- Markets under 200–300K people: movement into top 3 within weeks
- Larger markets (400K+): significant movement within first 2 weeks, top 3 takes longer
- More competitive = more content + more links needed

## Ongoing Loop (Monthly)
1. Run rank map
2. Check top 3%
3. Below threshold → more topical content
4. At/above threshold → geographical content
5. Keep GBP active (automated posts, photos, review responses)
6. Monitor for competitor movement
7. Add new services as business evolves
8. Consider additional GBP locations

---

# PART 14: TOOLS USED

| Tool | Purpose | Cost |
|------|---------|------|
| Lead Snap | Rank maps, GBP management, citation automation, post scheduling | Paid (link for 50% off first 3 months) |
| GMB Everywhere | Chrome extension for GBP category/service research | Free/Paid |
| Search Analytics for Sheets | Google Sheets extension for GSC data export | Free |
| Screaming Frog | Technical SEO crawler (free for <500 URLs) | Free/Paid |
| Claude | AI content generation (preferred over ChatGPT) | Paid |
| Google Search Console | Index monitoring, query alignment | Free |
| Google Analytics | Track AI referral traffic | Free |
| Structured Data Testing Tool | Schema validation | Free |
| Index Me Now | Force indexing of stubborn pages | Paid |
| Lovable | AI website builder | Paid |
| Ice Cream Truck Shop | External link service (~$35/link) | Paid |

---

# PART 15: COMPLETE SOP CHECKLISTS

## GBP Optimization Checklist
- [ ] Primary category: best exact-fit category selected
- [ ] Secondary categories: 3–5+ relevant categories added
- [ ] Services: 20–30+ listed, organized under correct categories
- [ ] Business description: 750 characters (max), used all of it
- [ ] Photos: 20+ uploaded, geotagged
- [ ] Posts: 52 weekly posts scheduled
- [ ] Attributes: every applicable box checked
- [ ] Q&A section populated
- [ ] Products section (if applicable)
- [ ] Special hours set
- [ ] Photo upload: weekly schedule set up

## Homepage Checklist
- [ ] Title tag: primary category + city + brand
- [ ] H1: primary category + city (+ goal completion hook)
- [ ] First paragraph: service + city + why call now (talks to USER, not about business)
- [ ] Phone/CTA visible above the fold
- [ ] Social proof above the fold
- [ ] Each secondary category = H2 + 50–100 words + editorial link to category page
- [ ] Google review embed (using Google's colors)
- [ ] GBP map embed (lower on page)
- [ ] Address matching GBP exactly
- [ ] Phone matching GBP exactly
- [ ] Local business schema
- [ ] No immediate popup
- [ ] Static hero image (no animation/sliding)
- [ ] Mobile-first design

## Category Page Checklist
- [ ] Title tag: category + city
- [ ] H1: category + city
- [ ] Each relevant service = H2 + 50–100 words + editorial link to service page
- [ ] Internal links from homepage
- [ ] Schema markup

## Service Page Checklist
- [ ] Title tag: service + city
- [ ] H1: service + city
- [ ] URL slug matches entity
- [ ] Detailed content (specific, not generic)
- [ ] Local references
- [ ] FAQ section
- [ ] Schema markup (service-specific)
- [ ] Internal link from category page
- [ ] One external "not AI slop" link
- [ ] Images

## Link Building Checklist
- [ ] One "not AI slop" link per core 30 page (30 total)
- [ ] Local chamber of commerce joined (closest)
- [ ] Additional chambers within 70 miles joined
- [ ] Youth sports sponsorship sourced
- [ ] Local charity/event sponsorship sourced
- [ ] Apple Maps listing
- [ ] Bing for Business listing
- [ ] BBB listing
- [ ] Other verified directories

## Competitor Audit Checklist
- [ ] `site:competitor.com` — total indexed pages
- [ ] `site:competitor.com [target keyword]` — topic depth
- [ ] Title tag check
- [ ] H1 check
- [ ] GBP categories check (GMB Everywhere)
- [ ] Schema presence check
- [ ] Review count and rating
- [ ] Mobile UX quick scan
- [ ] Goal completion assessment (first impression of landing page)

## GSC Monthly Audit
- [ ] Page-query alignment check (export + AI analysis)
- [ ] Index coverage review (discovered not indexed, crawled not indexed)
- [ ] Modifier mining (find terms to add to existing pages)
- [ ] Request indexing for any stuck pages

## Content Quality Checklist
- [ ] AI-generated content reviewed by human
- [ ] Local specifics added (neighborhoods, landmarks, conditions)
- [ ] Real business stories/anecdotes included
- [ ] Images present (client photos preferred)
- [ ] Tables, callouts, bullet points used
- [ ] Short paragraphs
- [ ] No accordion/hidden content
- [ ] No duplicate content from other sites
- [ ] Passes mobile rendering check

---

# PART 16: KEY MENTAL MODELS & QUOTES

## Caleb's Frameworks
- **"Three glasses"** — proximity, relevance, authority. Fill relevance and authority until they overflow.
- **"Core 30"** — one page per GBP category and service. The foundation of everything.
- **"Goal completion"** — did the user stop searching? Google rewards sites that end the search.
- **"Not AI slop links"** — external links proving your content isn't generic AI filler.
- **"Entity fortress"** — comprehensive coverage of every service entity creates a moat.
- **"Labels on moving boxes"** — schema tells machines what your content is, like labels on moving boxes.
- **"Digital GPS coordinates"** — you're giving Google the GPS coordinates of a trustworthy local business.
- **"Check engine light"** — pages not being indexed is your check engine light. Fix before anything else.

## Key Quotes
- "Where's the best place to hide a dead body? Page two of Google search."
- "Reviews don't get you ranked. Reviews get you the call."
- "If 90% of your competitors have 'home' as their title tag, you just need to not be stupid."
- "You don't need to hack Google. You just need to give Google what it actually wants."
- "Google didn't build Chrome and Android out of the goodness of their heart. They track everything."
- "The strongest negative signal you can send Google is the back button."
- "Blogging like '5 ways to unclog a drain' is a waste of time for local SEO."
- "SEO agencies asking 'if we're not writing blog posts, what do we charge for?' tells you everything."
- "A 4.7–4.9 review score converts better than a perfect 5.0."
- "Position 4 in local search is the first position on page two."
- "Google doesn't care if content is written by AI. Google cares if content is helpful."

---

# PART 17: APPLYING TO SPECIFIC NICHES

## For Plumbers
- Core services: water heater replacement, main drain line replacement
- High-margin services to target: tankless water heater, sewer line, emergency plumbing
- Entity research example: "plumber" vs "water heater installation" vs "washing machine replacement" — all different entities
- Geographic expansion: neighborhoods with older homes (cast iron pipes), newer developments (PEX), specific intersections

## For Dentists
- Categories: dentist, cosmetic dentist, pediatric dentist, etc.
- Services: Invisalign, dental implants, emergency dental, teeth whitening, etc.
- Each service = separate page
- Geographic: neighborhoods, landmarks, malls near office

## For Mechanics/Auto
- Categories: auto repair shop, transmission shop, brake shop, etc.
- Services: oil change, brake repair, transmission repair, engine diagnostics, etc.
- Geographic: major intersections, car dealership rows, residential neighborhoods

## For Restaurants
- Use specific GBP categories (Cajun restaurant > restaurant)
- Fill out menu natively in GBP (individual items with prices and descriptions)
- Create pages for signature dishes (treat dishes like service pages)
- HTML menu on website (not PDF/images)
- Recipe pages build topical relevance for dish keywords
- Research: what dishes do visitors search for in your city? (Reddit, PAA)

## For Gyms
- Categories: gym, fitness center, CrossFit box, personal training, etc.
- Pages for each program type
- Class schedules visible (not hidden behind clicks)
- Membership pricing visible early
- Virtual tours if possible
- Equipment-specific pages for specialized searchers

---

# PART 18: AGENCY CLIENT ACQUISITION (Bonus)

## 5 Methods Caleb Uses

### 1. Facebook Ads → Sales Calls
- $500–$1,000 to test
- Can get qualified prospects on phone for $20 in ad spend
- AI writes copy, Go High Level landing page
- Requires sales ability
- Budget to test/optimize: $5K+ over 3 months

### 2. Facebook Ads → Low-Ticket Offers (No Calls)
- $147/month offers
- $380 in ads → 3 paying businesses ($441 MRR)
- Profitable day one
- No phone calls required
- Customer self-selects

### 3. Local Facebook Groups + Reddit ($0)
- Join 5–10 local business owner groups
- Answer questions with actual helpful advice
- Show prospects their rank map (red) vs competitor (green)
- Lead with value, never pitch
- Clients stick for years

### 4. Chamber of Commerce Events
- Works for extroverts
- Don't sell SEO — build relationships
- Offer to send a rank map comparison
- Frequency = familiarity = trust
- 3 agency owners Caleb knows built million-dollar businesses this way

### 5. Content Marketing (YouTube, LinkedIn)
- Longest timeline: 12+ months
- Highest quality clients
- Clients come pre-sold (been watching for months)
- 80%+ of Caleb's current clients come from YouTube
- They pay more, stay longer, never question expertise

## What Doesn't Work Anymore
- Cold email (too many barriers, high cost per reply)
- Cold calling (300 calls = 3 answers, 2 hang up)
- Upwork (race to the bottom, now charges for proposals)
- Ranking your own agency website (6+ months, tiny local search volume)

---

# PART 19: SPEED-TO-RANK COMPARISON

From slowest to fastest:

| Method | Timeline | Why |
|--------|----------|-----|
| Traditional content SEO (blogging) | 6–12 months | Competing against established domains, builds topical but not geographic relevance |
| Citation building (old style) | 1–3 months | Table stakes only, verifies existence but doesn't build service/geographic relevance |
| Quality link building (traditional) | 3–6 months | Manual outreach, low response rates, links often not locally relevant |
| GBP optimization | 2–6 weeks | Directly defines entity connections, most businesses have barely done this |
| Core 30 + local links | 2–4 weeks | Hyperlocal pages + verified local links = fastest ranking method |

---

# APPENDIX: PROMPTS REFERENCED

Caleb references these prompts across his videos (available in his School community):

1. **GBP Category & Service Generator** — multi-step: discovers categories from competitors, generates comprehensive service lists, organizes by semantic relevance
2. **Service Categorization Prompt** — sorts services under correct GBP categories
3. **Homepage/Category Content Writer** — generates locally relevant content with goal completion structure, words-to-avoid list
4. **Service Page Content Writer** — same structure for individual service pages
5. **52 GBP Posts Generator** — generates a full year of weekly posts (promotional, educational, engagement, seasonal)
6. **Local Link Finder** — finds chambers, sponsorships, charities, events, schools seeking sponsors
7. **Entity Research Prompt** — extracts entities from competitor content
8. **Reddit Question Finder** — crawls Reddit for local questions about your service
9. **GSC Page-Query Alignment Checker** — analyzes exported GSC data to find confused pages
10. **GSC Modifier Mining Prompt** — finds modifier terms to add to existing pages
11. **Content Rewrite Prompt** — weaves modifiers into existing content naturally
12. **Screaming Frog Gap Analysis** — compares crawl data against GBP services to find missing pages
13. **Goal Completion Rewrite Prompt** — rewrites page first paragraphs for immediate intent matching
14. **Model Training Data Risk Auditor** — checks what AI models say about your brand
15. **250 Authority Content Protocol** — generates diverse angles for brand authority content across platforms
16. **Ruthless Citation Hunter** — finds mismatched NAP data across directories
17. **Local SEO Content Writer (Princeton Framework)** — writes content citing authorities, expert quotes, statistics
18. **Geographic Content Prioritization** — takes rank map CSV data and prioritizes which neighborhoods to target
19. **Site Architecture Planning Prompt** — organizes all pages, categories, services into a complete site map with internal linking
20. **Competitor Analysis Tool** — takes homepage content + Screaming Frog data + GBP data and produces full competitive analysis

---

*Source: 19 videos by Caleb Elu (YouTube channel), transcripts extracted March 2026*
*Creator's background: SEO agency since 2016, scaled to seven figures, 200+ local businesses ranked*
*Preferred AI tool: Claude (over ChatGPT)*
*Preferred GBP management tool: Lead Snap*
*Community: School group with prompt library, 3,000+ members*
