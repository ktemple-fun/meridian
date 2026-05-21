# meridian

═══════════════════════════════════════════════════════
  HOW TO CLONE THIS SITE FOR A NEW CITY
  Garage Door Repair — Lead Gen Site Template
═══════════════════════════════════════════════════════

STEP 1 — DUPLICATE THE FOLDER
  Copy this entire folder and rename it to the new city.
  Example: garagedoorrepairnatchezms

STEP 2 — BUY THE DOMAIN
  Buy [city]garagedoor.com or garagedoorrepair[city].com
  Namecheap or Porkbun — ~$10-12/yr

STEP 3 — FIND & REPLACE THESE PLACEHOLDERS
  Open each .html file and replace all instances of:

  [PHONE]          → full digits, no formatting  e.g. 6015550100
  [AREA]           → area code only              e.g. 601
  [PHONE-DISPLAY]  → formatted display number   e.g. 500-0100
  [WEB3FORMS_KEY]  → your key from web3forms.com (free)

STEP 4 — SWAP CITY REFERENCES
  In every .html file, find and replace:

  "Meridian"           → New City Name
  "Lauderdale County"  → New County Name
  "39301"              → New ZIP code
  "MS"                 → New state (if different)
  "Mississippi"        → New state full name (if different)
  "garagedoorrepairmeridian.com" → New domain

STEP 5 — UPDATE THE SCHEMA (index.html <head>)
  In the JSON-LD block, update:
  - "addressLocality"     → new city
  - "addressRegion"       → new state abbreviation
  - "postalCode"          → new zip
  - "geo" lat/longitude   → new city coordinates (Google "city name coordinates")
  - "areaServed" list     → nearby cities/towns for the new market
  - "url"                 → new domain
  - "telephone"           → new tracking number

STEP 6 — UPDATE SERVICE AREA TAGS (index.html)
  Find the .area-grid section and replace the city tags
  with cities/towns near your new market.

STEP 7 — UPDATE SITEMAP.XML
  Replace all instances of garagedoorrepairmeridian.com
  with your new domain.

STEP 8 — UPDATE ROBOTS.TXT
  Replace the sitemap URL with your new domain.

STEP 9 — DEPLOY TO VERCEL
  - Push the folder to a GitHub repo
  - Connect repo to Vercel (vercel.com — free)
  - Add your custom domain in Vercel settings
  - Point your domain's DNS to Vercel (they give you the records)
  - Done — live in minutes

STEP 10 — SUBMIT TO GOOGLE
  - Go to search.google.com/search-console
  - Add your new domain as a property
  - Submit your sitemap: yourdomain.com/sitemap.xml
  - Tells Google to come index your site immediately

STEP 11 — SET UP FORM BACKEND (free)
  - Go to web3forms.com
  - Create free account, get access key
  - Paste key into contact.html where it says [WEB3FORMS_KEY]
  - Form submissions will email you directly — no backend needed

═══════════════════════════════════════════════════════
  FILES IN THIS TEMPLATE
═══════════════════════════════════════════════════════

  index.html          Homepage (most important for SEO)
  services.html       Services detail page
  about.html          About page (builds trust)
  contact.html        Contact + lead form
  css/style.css       All styles — shared across pages
  sitemap.xml         Tells Google what pages exist
  robots.txt          Tells crawlers they're welcome
  CLONE-INSTRUCTIONS.txt  This file

═══════════════════════════════════════════════════════
  TRACKING NUMBER RECOMMENDATION
═══════════════════════════════════════════════════════

  Use a call tracking number so you can see exactly how
  many calls each site generates — essential for proving
  value when you go to rent or sell the site.

  Options:
  - CallRail ($45/mo, professional, best for multiple sites)
  - CallTrackingMetrics (similar pricing)
  - Google Voice (free, basic — ok for starting out)

  Replace [PHONE] placeholders with your tracking number.
  When you rent to a contractor, either forward the number
  to them or transfer it to their CallRail account.

═══════════════════════════════════════════════════════
  QUICK DEPLOYMENT CHECKLIST
═══════════════════════════════════════════════════════

  [ ] Folder duplicated and renamed
  [ ] All [PHONE], [AREA], [PHONE-DISPLAY] replaced
  [ ] All city/county/state references replaced
  [ ] Schema JSON-LD updated (index.html <head>)
  [ ] Service area tags updated (index.html)
  [ ] Sitemap.xml domain updated
  [ ] Robots.txt sitemap URL updated
  [ ] Web3Forms key added to contact.html
  [ ] Deployed to Vercel
  [ ] Custom domain connected in Vercel
  [ ] Submitted to Google Search Console

═══════════════════════════════════════════════════════
