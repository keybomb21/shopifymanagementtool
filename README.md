# Shopify Store Operations

A shared workflow for Shopify store administration, marketing, and theme development.

## Start here

- **GitHub Projects** is the team's Kanban/roadmap workspace. Configure its views and fields in the Project's web interface.
- **Issues** are individual tasks. Use the **New issue** button and choose the relevant form.
- **Pull requests** track changes to Shopify theme code. Keep them linked to the relevant issue.

> **Privacy:** This repository is currently public. Do not publish passwords, API tokens, customer information, unpublished campaign details, supplier prices, or internal inventory data here. Make the repository and Project private before adding confidential business work.

## Recommended Project views

| View | Layout | Filter / purpose |
| --- | --- | --- |
| 01 · Team Board | Board | Active issues, grouped by Status |
| 02 · My Tasks | Table | `is:issue assignee:@me -status:Done` |
| 03 · Products & Inventory | Board | Category: Products or Inventory |
| 04 · Marketing & SEO | Board | Category: Marketing or SEO |
| 05 · Marketing Schedule | Roadmap | Marketing work by Publish Date |
| 06 · Theme Development | Board | Category: Theme Development or Bug & QA |
| 07 · Completed | Table | Status: Done |

GitHub Projects does **not** currently provide a built-in monthly calendar grid. The Roadmap is the native date-based option. A separate calendar tool can provide the month-grid interface.

## Recommended Project fields

| Field | Type | Options |
| --- | --- | --- |
| Status | Single select | Backlog, To Do, In Progress, For Review, Done |
| Category | Single select | Products, Inventory, Marketing, SEO, Storefront, Theme Development, Bug & QA, Operations |
| Priority | Single select | Urgent, High, Medium, Low |
| Store | Single select | Add your store names |
| Due Date | Date | Task deadline |
| Publish Date | Date | Marketing publication date |
| Marketing Channel | Single select | Facebook, Instagram, TikTok, Email, Blog, Google Ads, Website |
| Campaign | Text | Optional campaign name |

The issue forms in `.github/ISSUE_TEMPLATE/` collect task details. **They do not automatically populate GitHub Projects custom fields.** Assign those fields in the Project until automation is set up.

## Daily workflow

1. Create a new issue from the appropriate template.
2. Add the issue to the shared GitHub Project.
3. Assign an owner, category, priority, and any relevant dates.
4. Move it through **Backlog → To Do → In Progress → For Review → Done**.
5. For theme changes, open a pull request and test in an unpublished Shopify theme before publishing.

## Guides

- [Project setup checklist](docs/PROJECT-SETUP.md)
- [Marketing calendar workflow](docs/MARKETING-CALENDAR.md)
- [Theme development workflow](docs/THEME-DEVELOPMENT.md)
