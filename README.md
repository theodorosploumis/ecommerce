# e-Commerce development

A simple guide, tips and resources to help you create a (Drupal 9.x) e-commerce website.

**Table of Contents**
- [Structure](#structure)
- [Blocks](#blocks)
- [Simple Pages](#simple-pages)
- [Commerce Pages (Customer)](#commerce-pages-customer)
- [Commerce Pages (Admin)](#commerce-pages-admin)
- [Emails](#emails)
- [Search](#search)
- [Other](#other)

---

## Structure

- **Product Display** (node)
  - Text Fields
  - Taxonomies (brand, category, display taxonomy, season etc)
  - Translations
  - Images
  - Share on social networks buttons
  - Metatag (schema.org)
  - Product reviews
 
- **Product Variation**
  - Price
  - List price
  - Shippable/Non-shippable
  - Name pattern
  - Stock (inventory)
  - Attributes (size, color, etc)
  - Weight
  - Ask for this Product link
  - Out of Stock message
  - See also list (related Products)
  - Product bundles (packages of Products sold as a single item)
  - Product gifts (free Products when you buy other Products)
 
- **Payment types**
  - Cash on delivery
  - Cash on store
  - Bank transfer (deposit)
  - Paypal
  - Credit/debit card payment (bank APIs, Stripe etc)

- **Shipping methods**
  - Store pickup
  - Courier (get rates API or set flat rates)
  - Free shipping
  - Custom (by arrangement)

- **Order**
  - Notes/Comments
  - Shipping tracking key/ID
  - PDF attachment (order or invoice attachment)
  - Guest checkout
  - Taxes setup
  - Allowed Countries for shipping

- **Customer Profile**
  - Shipping
  - Billing

---

## Blocks
- Breadcrumbs
- System messages
- Search form (text input)
- Search facets
- Cart
- Login/Register
- Checkout step indicator
- Free shipping banner
- Info about Shipping costs and time
- Info about Payment methods
- Info about Discounts
- Info about Quarantee
- Info about Secure transactions
- Info about Store physical address
- Contact info
- Social profiles info and links
- Dynamic: Latest Products
- Dynamic: Popular Products
- Dynamic: Editor picks Products
- Dynamic: Promoted Products
- Dynamic: Related Products (by reference or search query)
- Dynamic: Recently viewed Products

---

## Simple Pages
- Shipping
- Payments
- Returns
- Our Store/Company
- FAQs
- Terms of use and legal contents
- Measuring, sizes etc
- Contact form and info

---

## Commerce Pages (Customer)
- Checkout pages (with steps)
- My Order(s)
- My Account
- My Addresses (Billing, Shipping)
- Return a Product form (or pdf application)
- Create Account
- Complete Order Thank-you landing page

---

## Commerce Pages (Admin)
- Shop overview/dashboard
- Orders
- Products
- Product Varations
- Customer profiles
- Discounts/Promotions
- Coupons, Gift cards, Loyality points

---

## Emails
Emails as also as SMS and Mobile App messages (eg WhatsApp)

- New Order created (Customer)
- New Order created (Admin)
- Order sent with courier with tracking info (Customer)
- Order canceled (Customer)
- Product Variation is out of stock (Admin)

---

## Search
- External service (SOLR, Elastic, Algolia, core Views)
- Autocomplete (ajax)
- Suggestions for keywords
- Suggestions for wrong (eg misspelling) input
- No results message
- Search API: stemmer
- Search API: partial search (tokenizer)
- Search API: greeklish
- Search API: smallcase
- Search API: weight by tag
- Facets: Taxonomy
- Facets: Price
- Facets: Attributes
- Voice search input

---

## Other
- SSL
- sitemap.xml
- metatags
- (google) analytics for commerce orders
- gdpr cookies banner
- cron setup for search index and sitemap
- Product: path aliases
- Product: tell a friend
- dynamic product displays (eg taxonomy or search api view)
- SMS on complete payment transaction (for e-payments)
- Export data (orders, customers etc)
- Integration with 3rd party services (marketing, newsletters, user tracking, analytics etc)
- Customer reviews
- Customer comments per Product
- Wholesame customers
- Repeat an Order
- Favorite Products
- Online Invoices
- Skroutz API status and xml
- Translations
- Currencies
- CRM/Logistics external integration (2 way sync)
- CDN and fast hosting
- Login with social profile (Google, FB, Apple etc)
- Instant messaging and support widget
- Chatbot

---

## Drupal Modules
Interesting Drupal modules for e-commerce websites
