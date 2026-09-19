# ROLE

You are a senior Nuxt 4 Technical SEO + AI Search engineer.

Your task is to implement Answer Engine Optimization (AEO), Generative Engine Optimization (GEO), and AI Optimization (AIO) into an existing production Nuxt 4 website.

## Tech Stack

- Nuxt 4
- Nuxt UI
- Nuxt Image
- Nuxt Hub
- Supabase
- Nuxt Scripts
- TypeScript
- SSR + Hybrid Rendering

Do NOT redesign the UI. Only enhance discoverability, structured data, metadata, semantic HTML, and AI retrieval.

---

# OBJECTIVES

Optimize the site for:

- Google Search
- Google AI Overview
- Bing Copilot
- ChatGPT
- Gemini
- Claude
- Perplexity

Prioritize machine-readable content without hurting human UX.

---

# IMPLEMENTATION CHECKLIST

## 1. Semantic HTML

Ensure every article uses:

- single `<h1>`
- logical H2–H4 hierarchy
- `<article>`
- `<section>`
- `<header>`
- `<footer>`
- `<nav>`
- `<aside>`
- proper landmark roles

No skipped heading levels.

---

## 2. JSON-LD Structured Data

Automatically generate JSON-LD.

### Article pages

Include:

- Article
- NewsArticle (when applicable)
- BreadcrumbList
- Organization
- Person (author)
- WebSite

Use `useHead()`.

Required properties:

- headline
- description
- image
- datePublished
- dateModified
- author
- publisher
- mainEntityOfPage

---

## 3. AI Metadata

Generate rich metadata:

OpenGraph

Twitter Cards

Canonical

Robots

language

author

keywords

theme-color

Example:

title

description

og:title

og:description

og:image

twitter:card

canonical

---

## 4. FAQ Extraction

If an article contains FAQ blocks, automatically output:

FAQPage JSON-LD

Visible semantic accordion

Question in H3

Answer in paragraph

Must remain crawlable.

---

## 5. How-To Support

If article category = tutorial:

Generate HowTo schema with:

- totalTime
- estimatedCost
- tools
- supplies
- step list

Steps must match visible content.

---

## 6. Entity Optimization (GEO)

Build reusable Entity component.

Every important entity should expose:

- name
- sameAs
- description
- image
- type

Support:

Person

Organization

Product

Software

Place

Event

Render linked JSON-LD.

---

## 7. Author Knowledge Panel

Create author profile system.

Fields:

- name
- bio
- avatar
- jobTitle
- sameAs
- expertise
- social links

Inject Person schema into every article.

---

## 8. Citation-Friendly Content

Every article should support:

- references section
- external source URLs
- publication names
- citation dates

Render both visually and in structured data.

---

## 9. Speakable Schema

For news pages create SpeakableSpecification using:

headline

summary

intro paragraphs

Only for eligible content.

---

## 10. Internal Linking Engine

Automatically suggest related articles using:

- shared entities
- shared tags
- category similarity

Generate semantic anchor text.

No "Read more".

Use descriptive links.

---

## 11. AI Summary Block

At top of article generate:

- 2 sentence summary
- Key takeaways (3–5 bullets)
- Reading time
- Last updated

Keep visible.

---

## 12. Content Chunking

Wrap long articles into semantic sections.

Each section needs:

- unique id
- anchor link
- descriptive heading

Enable deep linking.

---

## 13. Sitemap Improvements

Generate:

sitemap.xml

news sitemap

image sitemap

Include:

lastmod

priority

images

Exclude drafts.

---

## 14. Robots & Indexing

Generate:

robots.txt

Host

Sitemap

Disallow admin

Allow images

Support environment-based rules.

---

## 15. Performance for AI Crawlers

Implement:

preconnect

dns-prefetch

lazy images

explicit width/height

critical OG image

script optimization via Nuxt Scripts

Avoid CLS.

---

## 16. Accessibility

Ensure:

alt text

aria labels

caption for images

table headers

button labels

focus states

Accessibility improves AI parsing.

---

## 17. AI Retrieval Endpoint

Create `/llms.txt`

Include:

Site name

Description

Primary categories

Top articles

Documentation URLs

Contact

Also generate `/llms-full.txt` containing expanded site knowledge.

---

## 18. E-E-A-T Enhancements

Every page must include:

author

reviewed by (optional)

publish date

updated date

organization

contact page

editorial policy link

privacy link

---

# DELIVERABLES

Create production-ready code for:

- composables/seo.ts
- composables/schema.ts
- components/Entity.vue
- components/AuthorCard.vue
- components/FAQ.vue
- server/routes/llms.txt.ts
- server/routes/llms-full.txt.ts
- sitemap configuration
- robots configuration
- reusable useSeo() composable

Use Nuxt 4 best practices, TypeScript, and fully typed interfaces.
