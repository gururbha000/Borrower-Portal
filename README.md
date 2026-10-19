# LAHD Borrower Portal — GitHub Pages v122

Upload the four HTML files to the root of your GitHub Pages repository.

- `index.html` — borrower portal (v121 baseline)
- `staff-dashboard.html` — existing two-tab staff queue
- `lp-transaction-detail.html?requestId=LT-260322` — Change of Ownership (Sale) staff processing demo
- `reserve-withdrawal-detail.html?requestId=RW-260298` — Reserve Withdrawal staff processing demo

These are four standalone copies of the v121 mock-up with page-specific startup and routing. They intentionally retain the original embedded scripts and styles to minimize regressions. Request IDs are passed in the URL for future integration; the mock-up uses sample data and does not dynamically load records by ID. Other LP transaction types are not implemented as individual staff detail screens.

## Publish
1. In GitHub, open the existing repository and upload the four HTML files to the repository root.
2. In Settings → Pages, use Deploy from a branch and select the branch and root folder.
3. Visit `https://USERNAME.github.io/REPOSITORY/` and the three additional filenames above.
4. Hard-refresh and test the two dashboard tabs and request links.

Do not publish real borrower information on GitHub Pages; it is public static hosting.
