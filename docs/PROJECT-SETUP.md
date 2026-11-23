# GitHub Projects setup

Project: **Stan <> Romelie <> Mikey Workspace**

> Project settings must currently be configured in GitHub's web interface. Adding files to this repository does not create saved Project views, custom fields, or automations.

## 1. Privacy
Make the repository and Project private if they will hold internal planning, pricing, operations or unreleased campaign details.

## 2. Status field
Create these values in order: **Backlog, To Do, In Progress, For Review, Done**. Group the Team Board by Status.

## 3. Custom fields
- Category (single select): Products, Inventory, Marketing, SEO, Storefront, Theme Development, Bug & QA, Operations
- Priority (single select): Urgent, High, Medium, Low
- Store (single select): your store names
- Due Date (date)
- Publish Date (date)
- Marketing Channel (single select): Facebook, Instagram, TikTok, Email, Blog, Google Ads, Website
- Campaign (text)

Use the built-in Assignees field.

## 4. Saved views
1. **01 · Team Board** — Board grouped by Status, showing open work
2. **02 · My Tasks** — Table, filter `is:issue assignee:@me -status:Done`
3. **03 · Products & Inventory** — Board filtered to relevant Category values
4. **04 · Marketing & SEO** — Board filtered to relevant Category values
5. **05 · Marketing Schedule** — Roadmap, using Publish Date for start and end when available
6. **06 · Theme Development** — Board filtered to Theme Development and Bug & QA
7. **07 · Completed** — Table, filter `status:Done`

Filter syntax and field-value names should be verified in the Project's filter editor.

## 5. Issue flow
Create issues using the repository's New issue forms; add them to the shared Project; assign people, dates, categories and priority. Issue-form values are **not** automatically synchronized with Project custom fields.

## 6. Automation
Enable suitable built-in Project workflows, such as automatically adding matching issues and setting status on closure, but avoid prematurely marking work Done before QA.

## 7. Visual consistency
Keep only Category, Priority, Assignees, and Due Date visible on the Team Board. Use short titles, muted colors, and avoid overloading cards.
