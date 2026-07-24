# Database Design

## Database

PostgreSQL (Supabase)

---

## Tables

### projects

Purpose

Stores website projects.

Columns

- id
- name
- domain
- status
- created_at

---

### pages

Purpose

Stores crawled pages.

Columns

- id
- project_id
- url
- title
- meta_description
- canonical
- status_code
- word_count
- crawl_status
- created_at

---

### crawl_jobs

Purpose

Tracks crawling sessions.

Columns

- id
- project_id
- started_at
- finished_at
- pages_found
- status

---

### search_console

Stores

- page
- query
- clicks
- impressions
- ctr
- position
- date

---

### analytics

Stores

- page
- sessions
- users
- engagement
- conversions

---

### clarity

Stores

- page
- rage_clicks
- dead_clicks
- scroll_depth

---

### competitors

Stores competitor domains.

---

### competitor_pages

Stores competitor pages.

---

### keywords

Stores target keywords.

---

### entities

Stores detected entities.

---

### recommendations

Stores AI recommendations.

---

### tasks

Stores action items.

---

### reports

Stores generated reports.

---

## Relationships

Projects

↓

Pages

↓

Search Console

↓

Analytics

↓

Recommendations

↓

Tasks
