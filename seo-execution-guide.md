# Local SEO Execution Guide
## Step-by-Step: How to Rank a Local Business (Caleb Elu Method)

> This is the "sit down and follow it" version. Open this, do what it says, move to the next step.
> The SEO Master Playbook is the reference encyclopedia. This is the recipe card.

---

# OVERVIEW: THE FULL PROCESS

```
PHASE 1: DIAGNOSTIC (Day 1) ............ Where are we? What's the competition?
PHASE 2: GBP SETUP (Days 1-3) .......... Optimize Google Business Profile
PHASE 3: WEBSITE BUILD (Days 4-10) ..... Build the Core 30 pages
PHASE 4: LINKS (Days 11-12) ............ Get external validation
PHASE 5: TECHNICAL (Days 13-14) ........ Schema, images, mobile, speed
PHASE 6: AI SEO (Parallel track) ....... Get recommended by AI models
PHASE 7: ONGOING (Monthly) ............. Monitor, expand, maintain
```

---

# PHASE 1: DIAGNOSTIC

## Step 1.1: Run a Local Rank Map

**Tool needed:** Lead Snap (paid) or any local rank tracking tool that does grid searches

1. Open Lead Snap → go to "New"
2. Type in the business name (e.g., "Green Piping Systems LLC")
3. Wait for it to find the business in Google's database
4. Set the grid size to cover the full service area (adjust the map view)
5. Enter the primary keyword (e.g., "plumber Gary" or "dentist San Juan")
6. Click "Run Scan"
7. Wait for results (few minutes)

**What you're looking at:**
- Green dots = top 3 (visible, getting calls)
- Yellow/orange dots = positions 4-10 (invisible but close)
- Red dots = position 11+ (completely invisible)

**The key number: Top 3%**
- Lead Snap calculates this automatically
- It's the percentage of the map that's green
- Write this number down: _____%

## Step 1.2: Run Rank Maps for Top 3 Competitors

1. In Lead Snap, run the same keyword for each of the top 3 businesses in the map pack
2. Write down each competitor's Top 3%:
   - Competitor 1: _____%
   - Competitor 2: _____%
   - Competitor 3: _____%
3. The highest number is your goal
4. Calculate your threshold: multiply the top player's % by 0.35
   - Example: top player = 80% → threshold = 28%
   - Example: top player = 40% → threshold = 14%

**This threshold determines your content strategy later (Phase 7).**

## Step 1.3: Size Up Competitor Websites

1. Open Google Chrome
2. For each of the top 3 competitors, type in the address bar:
   ```
   site:competitorwebsite.com
   ```
   (no space between `site:` and the domain)
3. Hit Enter
4. Click "Tools" below the search bar
5. Note the number of results — this is how many pages Google has indexed
6. Write it down:
   - Your site: _____ pages
   - Competitor 1: _____ pages
   - Competitor 2: _____ pages
   - Competitor 3: _____ pages

**Now check topic depth for key services:**

7. In the address bar, type:
   ```
   site:competitorwebsite.com water heater
   ```
   (replace "water heater" with whatever high-value service matters in your niche)
8. Note how many results mention that topic
9. Do the same for your own site
10. If competitors have 83 pages about water heaters and you have 1, you have a relevance gap — not a backlink gap

## Step 1.4: Check Competitor GBP Categories

**Tool needed:** GMB Everywhere (free Chrome extension)

1. Open Chrome Web Store: https://chrome.google.com/webstore
2. Search for "GMB Everywhere"
3. Click "Add to Chrome" → "Add Extension"
4. Open Google Maps: https://maps.google.com
5. Search for your primary keyword + city (e.g., "plumber Houston")
6. Click on one of the top 3 competitors in the results
7. You'll see GMB Everywhere data overlaid on the listing
8. Click "Find More" (or "Basic Audit" depending on version)
9. This shows you:
   - Their primary category
   - All their secondary categories
   - How many GBPs use each category
   - Related categories other businesses use
10. Click "Copy" to export their full category and service list
11. **Do this for all top 3 competitors**
12. Save this data — you'll use it in Phase 2

## Step 1.5: Run the Entity Test

This tells you which services Google treats as separate entities (needing their own pages).

1. Open two Chrome tabs side by side
2. In Tab 1, search: `plumber [city]` — note the top 3 businesses
3. In Tab 2, search: `water heater installation [city]` — note the top 3
4. **Compare the results:**
   - If results are completely different → **separate entity** → needs its own dedicated page
   - If results are mostly the same → Google sees them as the same thing → no separate page needed
5. Repeat for every service you think matters:
   - `drain cleaning [city]`
   - `emergency plumber [city]`
   - `sewer line repair [city]`
   - `washing machine replacement [city]`
   - etc.
6. Make a list of all unique entities (services that show different results)

## Step 1.6: Audit Competitor Websites

For each top 3 competitor, open their website and check:

### Title Tag
1. Look at the browser tab — that's the title tag
2. Or right-click → "View Page Source" → search for `<title>`
3. ✅ Good: includes primary category + city name
4. ❌ Bad: just says "Home" or just the business name

### H1 (Primary Heading)
1. Right-click the main heading on the page → "Inspect"
2. Look for `<h1>` in the HTML
3. ✅ Good: includes primary category + city
4. ❌ Bad: says "Welcome to..." or a platitude

### Goal Completion Check
1. Land on the homepage as if you're a customer
2. Within 5 seconds, can you tell:
   - What they do?
   - Where they do it?
   - Why you should call them?
   - How to contact them?
3. If not → they're failing goal completion → you can beat them here

### Review Embed
1. Scroll the homepage looking for reviews
2. ✅ Good: Google review widget with Google's colors (blue, red, yellow, green stars)
3. ❌ Bad: manually pasted review text (can be faked)
4. ❌ Bad: no reviews on the website at all

### GBP Map Embed
1. Look for an embedded Google Map on the page
2. ✅ Good: present somewhere on the homepage
3. ❌ Bad: missing entirely

### Schema Check
1. Go to: https://search.google.com/test/rich-results
2. Paste the competitor's URL
3. Click "Test URL"
4. See what schema types are detected
5. Note: LocalBusiness, Organization, Review, etc.
6. No results = they have no schema = easy win for you

### Site Size (already done in Step 1.3)

---

# PHASE 2: GBP OPTIMIZATION

## Step 2.1: Access and Audit the GBP

1. Go to https://business.google.com
2. Sign in with the Google account that owns the business
3. Select the business location
4. You're now in the GBP dashboard

## Step 2.2: Set Primary and Secondary Categories

1. In the GBP dashboard, go to "Edit Profile" → "Business category"
2. Your **primary category** should be the most specific category that matches what you do:
   - ❌ "Contractor" (too vague)
   - ✅ "Plumber" or "Dentist" or "Cajun Restaurant"
3. Click "Add another category" to add secondary categories
4. Use the data from Step 1.4 (GMB Everywhere competitor research)
5. Add 3-5 secondary categories that are relevant:
   - For a plumber: Drainage Service, Gas Installation Service, Heating Contractor, Septic Tank Service
   - For a dentist: Cosmetic Dentist, Pediatric Dentist, Emergency Dental Service
   - For a restaurant: use the most specific cuisine type available
6. **Don't add irrelevant categories** — fewer relevant categories beats many irrelevant ones

### Using AI to suggest categories:
1. Open Claude.ai (or ChatGPT)
2. Paste this prompt structure:
   ```
   I have a [business type] in [city]. My primary GBP category is [category].
   My top 3 competitors use these categories:
   [paste the GMB Everywhere data you copied in Step 1.4]

   Based on what my competitors use and what's available in Google Business Profile,
   suggest the best 3-5 secondary categories for my business.
   Only suggest real GBP categories that actually exist.
   ```
3. **Important:** AI sometimes invents fake categories. Cross-check every suggestion by typing it into the GBP category field to see if Google accepts it.

## Step 2.3: Add 20-30 Services

1. In GBP dashboard, go to "Edit Profile" → "Services" (or "Products" depending on business type)
2. For each category you selected, add 5-10 specific services under it
3. Example for "Plumber" category:
   - Water Heater Replacement
   - Water Heater Installation
   - Tankless Water Heater Repair
   - Pipe Repair
   - Leak Detection
   - Emergency Plumbing
   - etc.

### Using AI to generate services:
1. Open Claude.ai
2. Paste this prompt structure:
   ```
   I have a [business type] in [city].
   My GBP categories are: [list primary + secondary categories]

   Generate 30 specific services that I should list on my Google Business Profile.
   Organize each service under the most relevant category.
   Make sure services are semantically connected to their parent category.
   Only suggest services that a real [business type] would actually offer.
   ```
3. Review the output — remove anything you don't actually offer
4. Go back to GBP → Services → add each one under its category

## Step 2.4: Fill Out Every Single Field

Go through the entire GBP profile and fill in:

- [ ] **Business description**: Write 750 characters (that's the max). Include primary category, city name, key services, what makes you different. Use all 750 characters.
- [ ] **Address**: Make sure it's exact and matches your website character-for-character
- [ ] **Phone number**: Same — must match website exactly
- [ ] **Website URL**: Set to your homepage
- [ ] **Hours**: Set accurate hours including special hours for holidays
- [ ] **Attributes**: Go to "More" → check every applicable attribute:
  - Veteran-owned? Check yes or no.
  - Woman-owned? Check yes or no.
  - Accepts credit cards? Check.
  - Free estimates? Check.
  - ADA compliant? Check.
  - Has restroom? Check.
  - **Check every single attribute** — even checking "No" is better than leaving it blank
- [ ] **Q&A section**: Add 5-10 common questions and answer them yourself
- [ ] **Products/Menu**: If applicable, add individual items with prices and descriptions

## Step 2.5: Upload 20+ Photos

1. In GBP → "Photos"
2. Upload at least 20 photos:
   - Exterior of building (multiple angles)
   - Interior shots
   - Team/staff photos
   - Work-in-progress photos
   - Equipment/tools
   - Completed work examples
   - Logo
3. **Take photos with your phone** — they'll be automatically geotagged with GPS coordinates
4. Set up a recurring reminder to upload 1 new photo per week

## Step 2.6: Generate and Schedule 52 Weekly Posts

1. Open Claude.ai
2. Paste this prompt structure:
   ```
   Generate 52 Google Business Profile posts for a [business type] in [city].
   One post per week for the entire year.
   
   Mix these 4 types evenly across the year:
   - Promotional (sales, offers, seasonal specials)
   - Educational (tips, advice, industry knowledge)
   - Engagement (questions, community involvement, local events)
   - Seasonal (holiday-related, weather-related, local events)
   
   Each post should be 150-300 words.
   Include a call to action in each post.
   Reference the local area, neighborhoods, and city-specific details.
   Do NOT use the following words: [your words-to-avoid list]
   
   Business details:
   - Business name: [name]
   - Primary category: [category]
   - City: [city]
   - Key services: [list top 5-10 services]
   ```
3. Review the 52 posts — edit for accuracy and local flavor
4. Open Lead Snap (or your GBP management tool)
5. Go to the post scheduler
6. Paste each post in, set date for consecutive weeks
7. Schedule all 52 to auto-post weekly
8. Set to repeat annually

## Step 2.7: Set Up Automated Review Responses

1. In Lead Snap (or your GBP management tool)
2. Go to review management / auto-respond settings
3. Enable AI-powered review responses
4. Set the tone (professional, friendly, grateful)
5. This takes ~25 seconds to configure
6. It will automatically respond to every new review

---

# PHASE 3: BUILD THE CORE 30 WEBSITE

## Step 3.1: Plan the Site Architecture

Before building anything, create the map of your entire site.

1. Open Claude.ai
2. Paste this prompt:
   ```
   Create a complete site architecture for a [business type] website in [city].
   
   Primary category: [category]
   Secondary categories: [list them]
   Core services (highest margin, most important): [list 2-4]
   All services: [paste your full service list from Step 2.3]
   
   Organize this into:
   1. Homepage (targets primary category + city)
   2. Secondary category pages (one per secondary category)
   3. Core service pages (one per core service, with child services underneath)
   4. Individual service pages (grouped under their parent category or core service)
   5. General service pages that link back to homepage
   
   Show the complete hierarchy with internal linking structure.
   Show which pages link to which other pages.
   Total should be approximately 30 pages.
   ```
3. Review the output — this is your site map
4. Save it — you'll reference this for every page you build

## Step 3.2: Build the Homepage

### Title Tag
Open your website builder. Find the homepage title tag setting (often in SEO settings).

Set it to: `[Primary Category] [City] | [Differentiator] | [Brand Name]`

Examples:
- `Houston Plumber | Same Day Service | Smith Plumbing`
- `Dentist in San Juan | Emergency & Family Dental | Smile PR`
- `Auto Repair Bayamón | ASE Certified Mechanics | Island Auto`

**The primary category and city MUST be in the title tag. This is the single most important text on your entire website.**

### H1 (Primary Heading)
Set the main heading on the page to include primary category + city:
- `Houston Plumber Serving the Heights & Beyond`
- `Your Trusted San Juan Dentist`

**Do NOT use:** "Welcome to [business]" or "Experience the best" or any platitude.

### First Paragraph (Critical for Goal Completion)
Write the first paragraph to immediately tell the user:
- What you do
- Where you do it
- Why they should call NOW

**Example:**
> "Need a plumber in Houston right now? Smith Plumbing provides same-day emergency plumbing, water heater replacement, and drain cleaning across Houston, the Heights, River Oaks, and Montrose. Call (713) 555-1234 for immediate service."

**NOT this:**
> "Welcome to Smith Plumbing! We're a family-owned business that has been serving the Houston area since 1985. Our team of certified professionals..."

Nobody cares about your history. They care about getting their problem solved.

### Secondary Category Sections
For each secondary category (3-5 of them):

1. Add an H2 heading: `[Secondary Category] in [City]`
   - Example: `Drainage Service in Houston`
2. Write 50-100 words about that category — what it covers, why customers need it
3. Add an editorial link (in the text, NOT in navigation) to the dedicated category page:
   - Example: "For comprehensive drain solutions, see our [drainage service page →](/drainage-service-houston)"

### Trust Elements (Above the Fold)
Add these as high on the page as possible:
- [ ] Google review embed widget (using Google's actual colors — blue, red, yellow, green)
- [ ] Phone number (clickable on mobile)
- [ ] Key differentiators (24/7 service, licensed/insured, years in business)
- [ ] Awards or certifications if any

### Lower on the Page
- [ ] Google Maps embed of your business location
- [ ] Address (matching GBP character-for-character)
- [ ] Phone (matching GBP character-for-character)
- [ ] Service areas mentioned
- [ ] CTA (call to action) button

### Technical
- [ ] Add Local Business schema (use AI to generate — see Step 5.1)
- [ ] No popup on first page load (delay at least 30 seconds if you must have one)
- [ ] Static hero image (NO animated/sliding hero)
- [ ] All content visible on first load (NO accordion dropdowns — Google bot can't click them)

## Step 3.3: Build Category Pages

**Create one page for each secondary category.**

For each page:
1. **Title tag:** `[Category] [City] | [Brand]`
   - Example: `Drainage Service Houston | Smith Plumbing`
2. **H1:** `[Category] in [City]`
3. **First paragraph:** Immediately state what this category covers and where you serve
4. **Service sections:** For each service under this category:
   - Add an H2: `[Service Name] in [City]`
   - Write 50-100 words about that service
   - Add an editorial link to the dedicated service page
5. **Internal link** from homepage → this category page (already done in Step 3.2)

### Using AI to Generate Category Page Content:
1. Open Claude.ai
2. Paste this prompt:
   ```
   Write a category page for a [business type] website.
   
   Primary category: [category]
   This page's target: [secondary category] in [city]
   Services under this category: [list the 5-10 services]
   All GBP categories: [list them]
   All GBP services: [full list]
   
   Requirements:
   - Title tag: [secondary category] [city] | [brand]
   - H1: [secondary category] in [city]
   - First paragraph must mention the category + city + why call now
   - Each service gets an H2, 50-100 words, and a note where an editorial link should go
   - Include local neighborhood mentions
   - Write for goal completion: answer the searcher's question immediately
   - Target length: 800-1200 words
   - Do NOT use these words: leverage, utilize, comprehensive, solutions, cutting-edge, 
     state-of-the-art, second to none, look no further, nestled
   ```
3. Review the output, add local flavor and real business details
4. Copy into your website builder
5. Make sure internal links are properly connected

## Step 3.4: Build Service Pages

**Create one page for every single service on your GBP.**

If you have 20 services listed, you need 20 service pages.

For each page:
1. **Title tag:** `[Service] [City] | [Brand]`
   - Example: `Water Heater Replacement Houston | Smith Plumbing`
2. **H1:** `[Service] in [City]`
3. **URL slug:** `/water-heater-replacement-houston` (matches the entity)
4. **First paragraph:** What this service is, where you do it, why call now
5. **Detailed content:** 
   - Why customers need this service
   - What's included / what to expect
   - How long it takes
   - Price range (if appropriate)
   - Local specifics (common issues in your area)
6. **FAQ section:** 3-5 questions specific to this service
7. **Internal links:**
   - Link FROM the parent category page TO this service page (already set up)
   - Link FROM this page BACK to the category page
   - Link to related service pages where natural

### Using AI to Generate Service Pages:
1. Open Claude.ai
2. Paste this prompt (run it once per service, changing inputs each time):
   ```
   Write a service page for a [business type] website.
   
   Primary category: [category]
   City: [city]
   Target service: [specific service]
   Parent category for this service: [which category it falls under]
   All GBP categories: [list]
   All GBP services: [full list]
   
   Requirements:
   - Title tag: [service] [city] | [brand]
   - H1: [service] in [city]
   - First paragraph must answer: what is this service, where do you offer it, why call now
   - Include: what's involved, typical timeline, what to expect, local considerations
   - Add 3-5 FAQs specific to this service in [city]
   - Mention nearby neighborhoods and local conditions
   - Reference local landmarks, building types, weather patterns that affect this service
   - Target length: 600-1000 words
   - Do NOT use: leverage, utilize, comprehensive, solutions, cutting-edge,
     state-of-the-art, second to none, look no further, nestled
   ```
3. **Run this 20+ times** — once per service, changing the inputs each time
4. Each prompt takes ~2 minutes to set up, AI generates in ~1 minute
5. Spend 10-15 minutes editing each one: add real business stories, local details, personality
6. Copy into website builder

**Time estimate: ~20 minutes per page × 20 pages = ~5-7 hours total for all service pages**

## Step 3.5: Add Images to Every Page

Every single page needs at least one image. Google will largely ignore pages without images.

**Preferred (in order):**
1. Real client/project photos (best)
2. AI-generated images (acceptable)
3. Stock photos (last resort)

For each page:
1. Add at least 1 relevant image
2. Set the alt text to include the service + city (e.g., "water heater replacement in Houston")
3. Compress images for fast loading (use TinyPNG or similar)

## Step 3.6: Verify Internal Linking Structure

Before moving on, verify the linking matches your site architecture:

- [ ] Homepage links to every category page (editorial links in content, not just navigation)
- [ ] Each category page links to its child service pages (editorial links in content)
- [ ] Each service page links back to its parent category page
- [ ] Core service pages link to their child service pages
- [ ] No orphan pages (every page has at least one editorial link pointing to it)

**Test:** Can you click from the homepage → category → service → back to category → back to homepage? The path should be clear and logical.

---

# PHASE 4: LINK BUILDING

## Step 4.1: Join Your Local Chamber of Commerce

**This is the #1 most important link you can get.**

1. Google: `[city] chamber of commerce`
2. Go to their website
3. Look for "Join" or "Membership"
4. Most chambers cost $200-$300/year (based on employee count)
5. Sign up, pay the membership fee
6. They will add your business to their online directory with a link back to your website
7. **Make sure the link points to your homepage**
8. **Make sure your business name, address, and phone match your GBP exactly**

### Join MULTIPLE Chambers
1. Google: `chamber of commerce near [city]`
2. Look for every chamber within 50-70 miles
3. Join as many as you can afford
4. Each one is a massive local trust signal
5. Caleb has had clients join 10+ chambers

**Real example from the videos:** A personal injury attorney in New Orleans joined the local chamber + every chamber within 50 miles + sponsored a local event called the "Bayou Bash." The day after the event link went live, he jumped from position 8 to position 3. His first call the next morning was a $14,000 case.

## Step 4.2: Find Local Sponsorship Opportunities

1. Open Claude.ai
2. Paste this prompt:
   ```
   Find local organizations in [city] and within 50 miles that offer
   sponsorship opportunities where I would receive a link on their website.
   
   Look for:
   - Youth sports leagues (baseball, soccer, basketball, football)
   - Local charities and nonprofits
   - Community events and festivals
   - Local college events (TEDx, career fairs, etc.)
   - Local business directories
   - City preferred contractor directories
   - School PTA/booster clubs
   - Church directories
   - Local awards programs
   
   For each opportunity, tell me:
   - Organization name
   - Estimated cost
   - Type of link I would receive
   - How to contact them
   ```
3. Review the list
4. Start with the cheapest/easiest opportunities
5. Target 5-10 local links total

**Real example:** A $250 sponsorship of a local college TEDx event got a .edu link that moved a client 4 ranking positions.

## Step 4.3: Get "Not AI Slop" Links (One Per Page)

Every page on your site needs at least one external link pointing to it. This proves to Google that the content isn't just AI-generated filler.

**Options:**
1. **DIY:** Reach out to relevant blogs, local news sites, industry directories
2. **Paid service:** Caleb's service is Ice Cream Truck Shop (~$35/link)
3. **Guest contributions:** Write for local publications, industry sites

**You need approximately 30 links for 30 pages.**

This doesn't have to happen all at once. Start with links to the homepage and most important service pages, then gradually cover all pages.

## Step 4.4: Set Up Verified Citations

These are directory listings that require business verification:

1. **Apple Maps:**
   - Go to: https://mapsconnect.apple.com
   - Sign in with Apple ID
   - Claim or add your business
   - Complete verification process

2. **Bing Places for Business:**
   - Go to: https://www.bingplaces.com
   - Sign in with Microsoft account
   - Claim or add your business
   - Complete verification (phone or mail)

3. **Better Business Bureau:**
   - Go to: https://www.bbb.org
   - Search for your business
   - If not listed, apply for accreditation
   - Cost varies by business size

4. **Facebook Business:**
   - Create/claim your Facebook Business page
   - Ensure name, address, phone match GBP exactly

5. **Yelp:**
   - Go to: https://biz.yelp.com
   - Claim your business
   - Fill out complete profile

**Why these matter:** These platforms verify you're a real business. Google AND AI models (ChatGPT, Perplexity, Gemini) treat verified citations as high-trust signals.

**Critical rule:** Your name, address, and phone number MUST be identical across every single platform. One wrong digit or abbreviation difference (St vs Street) can hurt you.

---

# PHASE 5: TECHNICAL SEO

## Step 5.1: Add Schema Markup to Every Page

Schema is code that tells Google and AI models exactly what your content represents.

### For the Homepage (Local Business Schema):
1. Open Claude.ai
2. Paste:
   ```
   Generate LocalBusiness schema markup in JSON-LD format for:
   
   Business name: [name]
   Business type: [primary category]
   Address: [full address]
   Phone: [phone]
   Website: [URL]
   Description: [your business description]
   Hours: [operating hours]
   Geo coordinates: [latitude, longitude]
   Rating: [your Google rating]
   Review count: [number of reviews]
   Services: [list top services]
   Price range: [$ to $$$$]
   ```
3. Copy the generated JSON-LD code
4. Go to: https://search.google.com/test/rich-results
5. Click "Code" tab
6. Paste the schema
7. Click "Test Code"
8. **Must show: 0 errors, 0 warnings**
9. If there are errors: copy the error messages, paste them back into Claude, ask it to fix them
10. Repeat until 0 errors, 0 warnings
11. Add the schema to your homepage's `<head>` section (or use your website builder's custom code injection)

### For Service Pages:
1. Generate Service schema for each service page using the same process
2. Validate each one
3. Add to each page

## Step 5.2: Check Mobile Responsiveness

1. Open your website on your phone
2. Check every page:
   - [ ] Text is readable without zooming
   - [ ] Buttons are tappable (not too small)
   - [ ] Phone number is clickable
   - [ ] No horizontal scrolling
   - [ ] Images aren't broken or oversized
   - [ ] No content is cut off
3. Also test using: https://search.google.com/test/mobile-friendly

## Step 5.3: Check Page Speed

1. Go to: https://pagespeed.web.dev
2. Enter your homepage URL
3. Run the test
4. Focus on mobile score
5. Common fixes:
   - Compress images (TinyPNG)
   - Enable browser caching
   - Minimize CSS/JavaScript
   - Use a CDN if available
6. Target: 70+ mobile score is acceptable, 90+ is great

## Step 5.4: Submit Sitemap to Google Search Console

1. Go to: https://search.google.com/search-console
2. Add your website property if not already added
3. Go to "Sitemaps" in the left sidebar
4. Enter your sitemap URL (usually `yoursite.com/sitemap.xml`)
5. Click "Submit"
6. This tells Google about all your new pages so it can crawl them faster

---

# PHASE 6: AI SEO (Parallel Track)

This runs alongside the main process. It's about making sure AI models (ChatGPT, Perplexity, Gemini, etc.) recommend your business.

## Step 6.1: Check What AI Models Say About Your Business

1. Open ChatGPT (or Claude, Perplexity, etc.)
2. Ask: "Who is the best [your service] in [your city]?"
3. Ask: "Can you recommend a [your service] in [your city]?"
4. Note: Are you mentioned? Are competitors? Is the information accurate?

### Run the Brand Audit:
1. Open Claude.ai
2. Paste this prompt:
   ```
   Act as a brand reputation forensic analyst.
   
   Business: [name]
   Service: [what they do]
   City: [city]
   Website: [URL]
   
   Search for real conversations about this business across:
   - Reddit threads
   - Local forums
   - Medium articles
   - Review sites (Google, Yelp, BBB)
   - Industry forums
   
   Report:
   1. What are people actually saying?
   2. What complaints keep coming up?
   3. What's accurate vs exaggerated vs completely wrong?
   4. What patterns would AI models pick up from this data?
   5. Action items to fix any issues
   ```
3. Review the findings
4. Address any inaccuracies you find on Reddit, forums, etc.

## Step 6.2: Track AI Referral Traffic

1. Open Google Analytics for your website
2. Go to Acquisition → Traffic Acquisition
3. Filter by referral source
4. Look for traffic from:
   - `chat.openai.com` (ChatGPT)
   - `gemini.google.com` (Gemini)
   - `perplexity.ai` (Perplexity)
   - `grok.x.ai` (Grok)
5. Set up a custom report to track this monthly
6. Note: Volume will be much lower than Google, but conversion rate is typically much higher (80% more revenue per visit according to Adobe research)

## Step 6.3: Build AI-Friendly Content

Use the Princeton University findings. Three things increase AI visibility by 40%:

For every page on your site, make sure content includes:
1. **Citations of authoritative sources** — reference industry standards, local building codes, manufacturer specs
2. **Direct quotations from recognized experts** — quote industry leaders, cite research
3. **Specific statistics and data points** — actual numbers, not vague claims

### Use this AI content prompt that implements these findings:
```
Write content for a [service] page in [city] that will perform well in both 
Google search and AI model recommendations.

Requirements:
- Include at least 2 citations of authoritative sources (industry standards, 
  local regulations, manufacturer guidelines)
- Include at least 1 direct quote from a recognized expert or study
- Include at least 3 specific statistics or data points
- Write from a local expert perspective
- Mention specific neighborhoods, local conditions, building types
- Target keyword: [service] [city]
```

## Step 6.4: Ensure Citation Consistency for AI

AI models cross-reference your business information across multiple sources. Inconsistencies kill trust.

1. Search for your business name on Google
2. Check every listing that appears:
   - Google Business Profile
   - Yelp
   - Facebook
   - Apple Maps
   - Bing
   - BBB
   - Any other directories
3. **Every single one must have identical:**
   - Business name (exact spelling, same abbreviations)
   - Address (same format: "Street" vs "St" matters)
   - Phone number (same format)
4. Fix any mismatches immediately

---

# PHASE 7: ONGOING OPERATIONS

## Monthly Rank Map Check

1. Run rank map in Lead Snap for your primary keyword
2. Check your Top 3%
3. Compare to your threshold (calculated in Step 1.2)

### BRANCH A: Below Threshold → Build Topical Content

You need to prove to Google that you're an expert. Build FAQ-based supporting content.

**Step 1: Find Questions from People Also Ask**
1. Open Google
2. Search for your service (WITHOUT city name): e.g., just "water heater replacement"
3. Scroll to "People Also Ask" section
4. Click on any question → more questions appear
5. Keep clicking until you have 20-30 questions
6. **DO NOT copy these word-for-word** (Google is wise to this)
7. Rephrase each question in different words with same meaning:
   - Original: "How much does it cost to replace a water heater?"
   - Rephrased: "What's the typical price for water heater replacement?"

**Step 2: Find Questions from Reddit**
1. Open Claude.ai
2. Paste:
   ```
   Search Reddit for questions people in [city] are asking about [service].
   Look in subreddits related to:
   - r/[city name]
   - r/HomeImprovement
   - r/plumbing (or relevant industry subreddit)
   - r/askreddit
   
   Find 10-15 real questions with the actual Reddit thread context.
   These should be questions that a [business type] in [city] could answer.
   ```
3. Save these questions

**Step 3: Add FAQ Content**
For each question:
1. Add a brief answer (2-3 sentences) to the relevant core 30 page
2. Include an editorial link: "For a detailed breakdown, see our [guide to water heater replacement costs →](/water-heater-cost-guide)"
3. Create a new supporting page that answers the question in depth (300-500 words)
4. Get one external "not AI slop" link to each new supporting page

**Keep building until your Top 3% reaches your threshold.**

### BRANCH B: At/Above Threshold → Build Geographical Content

Google trusts your expertise. Now expand how far from your address you rank.

**Step 1: Identify Target Areas**
1. Open your rank map
2. Look for dots showing positions 4, 5, 6 (close to top 3 but not there yet)
3. Zoom into Google Maps in those areas
4. Find geographic landmarks Google recognizes:
   - Neighborhood names
   - Park names
   - Major intersections
   - Shopping centers
   - Schools
   - Lakes, rivers
   - Subdivisions

**Step 2: Build Neighborhood Pages**
For each target area:
1. **Target keyword:** `[service] near [landmark] in [city]`
   - Example: "Water heater replacement near Memorial Park in Houston"
2. **Title tag:** `[Service] [Landmark] [City] | [Brand]`
3. **Content requirements:**
   - NOT just the same page with a different city name
   - Write about that specific neighborhood
   - Mention common issues in that area (older homes? newer construction? specific pipe types?)
   - Reference local landmarks, businesses, streets
   - Include driving routes your technicians take to get there
   - Add a local FAQ section specific to that neighborhood
4. **Internal links:**
   - Create a "Service Areas" or "Locations" page linking to all neighborhood pages
   - Each neighborhood page links to the relevant service page
5. **External link:** Get one "not AI slop" link to each new page

**Keep running rank maps every 2 weeks. Target new areas as they appear at positions 4-6.**

## Monthly Google Search Console Check

### Page-Query Alignment (Monthly)
1. Open Google Search Console → Performance
2. Click "Pages" tab
3. For each important page, click on it to see its queries
4. Check: are the queries matching what you want this page to rank for?
5. If a page is getting impressions for the wrong queries → content needs updating to differentiate it from other pages

### Bulk Check with Search Analytics for Sheets:
1. Open Google Sheets
2. Go to Extensions → Add-ons → Get Add-ons
3. Search for "Search Analytics for Sheets" → Install it
4. Open the sidebar (Extensions → Search Analytics for Sheets → Open Sidebar)
5. Connect your Google Search Console account
6. Select your website property
7. Set date range to "Last 90 days"
8. Set dimensions to: "Query" and "Page"
9. Click "Request Data"
10. Wait for export (up to 25,000 rows)
11. Now you can see every page + every query Google associates with it
12. Feed this data to Claude with the alignment-checking prompt to find confused pages

### Index Coverage (Monthly)
1. In GSC → go to "Pages" section
2. Check "Not indexed" reasons
3. Look specifically for:
   - "Discovered – currently not indexed" (Google found it, decided not to crawl it)
   - "Crawled – currently not indexed" (Google looked at it and rejected it)
4. For any pages with these issues:
   - Improve the content quality
   - Add images, tables, callouts
   - Make sure internal links point to the page
   - Get one external link pointing to it
   - Then: URL Inspection → paste the URL → click "Request Indexing"
5. Wait 1-2 weeks. If still not indexed, content needs more work.

### Modifier Mining (Monthly)
1. From your GSC export, look for modifier terms in queries that don't appear on the page
2. Examples: "lead" pipe repair, "tankless" water heater, "emergency" drain, "same day"
3. For each modifier:
   - Go to the page it's associated with
   - Ctrl+F to search for the modifier word
   - If it's not there → add it naturally to the content
4. Use Claude to rewrite sections adding modifiers naturally:
   ```
   Here is the current content of my [service] page:
   [paste current content]
   
   I need to naturally add these modifier terms that Google is already associating with this page:
   [list modifiers]
   
   Rewrite the content keeping it as close to the original as possible,
   but weaving these terms in naturally. Bold every new term you add.
   ```

## GBP Maintenance (Automated)
- [ ] Weekly posts firing automatically (set up in Phase 2)
- [ ] Weekly photo uploads (set a calendar reminder)
- [ ] Review responses running automatically (set up in Phase 2)
- [ ] Respond personally to any negative reviews

---

# QUICK REFERENCE: TOOL LIST

| When You Need To... | Use This Tool |
|---|---|
| See where you rank across the city | Lead Snap (rank maps) |
| Check competitor GBP categories | GMB Everywhere (Chrome extension) |
| Generate AI content | Claude.ai (preferred) or ChatGPT |
| Check what Google thinks your pages are about | Google Search Console + Search Analytics for Sheets |
| Validate schema markup | Google Rich Results Test |
| Check mobile friendliness | Google Mobile-Friendly Test |
| Check page speed | PageSpeed Insights |
| Crawl your site for technical issues | Screaming Frog (free for <500 URLs) |
| Manage GBP posts/photos/reviews | Lead Snap |
| Build the website structure | Lovable (AI builder) or WordPress or any builder |
| Get external links | Ice Cream Truck Shop or manual outreach |
| Track AI traffic | Google Analytics (referral filter) |
| Find local link opportunities | Claude.ai with link finder prompt |

---

# QUICK REFERENCE: COMMON MISTAKES TO AVOID

| Mistake | Why It's Bad | Fix |
|---|---|---|
| Title tag says "Home" or just business name | Google doesn't know what to rank you for | Add primary category + city |
| Homepage starts with "Welcome to..." | Fails goal completion | Start with service + city + why call now |
| Only 1 GBP category | Missing searches for other categories | Add 3-5 relevant categories |
| 0-5 services on GBP | Google doesn't know what you do | List 20-30 services |
| Writing blog posts | Doesn't build local relevance | Build service pages instead |
| Animated/sliding hero image | Increases bounce rate (split-tested) | Use static hero image |
| Accordion/dropdown FAQs | Google bot can't click to expand | Show all content on first load |
| Manually pasted review text | Not trustworthy (could be faked) | Embed Google reviews with Google's colors |
| Inconsistent NAP across directories | Confuses Google and AI models | Make name/address/phone identical everywhere |
| Popup on first page load | User hasn't decided to engage yet | Delay popup 30+ seconds |
| Hover-over content | Google bot can't hover | Make content visible by default |
| Chasing domain authority | Vanity metric for local SEO | Focus on GBP relevance and local links |
| Thinking reviews drive rankings | Reviews drive conversion, not ranking | Focus on relevance and authority for ranking |

---

*Based on 19 videos by Caleb Elu. Companion document to the SEO Master Playbook.*
