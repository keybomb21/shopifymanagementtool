# Shopify theme development workflow

Keep code work linked to GitHub Issues but separate from daily Shopify admin tasks.

1. Create a Theme Development or Bug & QA issue.
2. Create a short-lived feature branch, such as `fix/mobile-gallery`.
3. Make Liquid, CSS, JavaScript, or JSON template changes on that branch.
4. Open a pull request that references the issue.
5. Test using an **unpublished** Shopify theme or development environment.
6. Check relevant pages on desktop and mobile, including cart behavior where applicable.
7. Obtain peer review and merge only approved changes.
8. Publish using the team's agreed release process; verify production before marking the issue Done.

**Avoid committing credentials, Shopify access tokens, customer data, or production secrets.**

If you connect the repository to Shopify's GitHub theme integration, choose branch-to-theme mappings intentionally. Don't connect unreviewed feature branches to your live theme.

## Project statuses
- To Do: approved work not started
- In Progress: branch/work started
- For Review: PR or storefront QA pending
- Done: deployed and verified
