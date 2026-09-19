# ROLE

You are a senior Nuxt 4 Ecommerce Technical SEO + AI Commerce engineer.

Implement AEO, GEO, and AIO for an existing production ecommerce website.

## Stack

- Nuxt 4
- Nuxt UI
- Nuxt Image
- Nuxt Hub
- Supabase
- Nuxt Scripts
- TypeScript
- SSR

Do NOT change UI. Improve discoverability, structured commerce data, AI shopping visibility, and semantic architecture.

---

# GOALS

Optimize products for:

- Google Shopping
- Google AI Overview
- Bing Copilot
- ChatGPT Shopping
- Gemini
- Perplexity
- AI product retrieval systems

---

# IMPLEMENTATION

## 1. Product Schema

Generate Product JSON-LD.

Required:

- name
- brand
- sku
- gtin (optional)
- mpn
- description
- image
- category
- color
- material
- size
- audience

Nested:

Offer

AggregateRating

Review

MerchantReturnPolicy

ShippingDetails

Inventory status

Update dynamically from Supabase.

---

## 2. Offer Schema

Include:

price

currency

availability

priceValidUntil

seller

itemCondition

url

Reflect live inventory.

---

## 3. Breadcrumb Schema

Generate:

Home

Category

Subcategory

Product

Using BreadcrumbList.

---

## 4. Organization Schema

Include:

logo

sameAs

contactPoint

customer support

email

address

social profiles

---

## 5. Collection Pages

For category pages implement:

CollectionPage schema

ItemList schema

Sorted product positions

Pagination metadata

Canonical URLs

---

## 6. AI Product Summary

Above product description render:

- AI Summary
- Best for
- Key features
- Materials
- Warranty
- Shipping
- Return window

Machine-readable.

---

## 7. Specification Table

Create semantic spec table using:

<table>

<thead>

<tbody>

No div tables.

Generate ProductGroup attributes.

---

## 8. FAQ System

Product FAQ should generate:

FAQPage JSON-LD

Questions from database

Semantic accordion

---

## 9. Review Schema

Implement:

Review

AggregateRating

author

ratingValue

reviewBody

datePublished

Do not fabricate reviews.

Only use real Supabase data.

---

## 10. Entity Modeling

Create reusable entities for:

Brand

Product

Category

Material

Use sameAs where available.

---

## 11. Image Optimization

Every product image:

descriptive filename

alt text

width

height

OG image

Image sitemap

Use Nuxt Image.

---

## 12. Metadata

Generate unique:

title

description

canonical

OpenGraph

Twitter

Product rich tags

No duplicated metadata.

---

## 13. Internal Linking

Automatically link:

Related products

Frequently bought together

Same brand

Same category

Recently viewed

Use descriptive anchors.

---

## 14. Merchant Policies

Generate structured data for:

Return policy

Shipping policy

Payment methods

Store availability

---

## 15. AI Commerce Endpoint

Create:

/llms.txt

/llms-full.txt

Include:

Brand

Categories

Featured products

Buying guides

Return policy

Shipping

Support

---

## 16. Search Optimization

Implement semantic search preparation:

Normalize product attributes

Synonym support

Brand aliases

Color aliases

Material aliases

Useful for AI retrieval.

---

## 17. Accessibility

Ensure:

alt text

form labels

aria

keyboard navigation

price announced correctly

rating accessible

---

## 18. Performance

Optimize:

Nuxt Scripts

Lazy hydration

Critical images

Preload hero

Font optimization

Minimal JS

Excellent Core Web Vitals.

---

# FILES TO CREATE

- composables/useProductSeo.ts
- composables/useSchema.ts
- components/ProductSchema.vue
- components/ProductFAQ.vue
- components/SpecificationTable.vue
- components/AISummary.vue
- server/routes/llms.txt.ts
- server/routes/llms-full.txt.ts
- typed schema interfaces
- reusable metadata utilities

Use production-quality Nuxt 4 + TypeScript architecture with reusable composables and zero hardcoded business data.
