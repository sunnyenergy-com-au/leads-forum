# Forum for Sales Leads Platform

This repository hosts the GitHub Discussions used by Giscus to power the comment system on the **Forum** page of Sales Leads Platform.

## How It Works

- The forum page of our website integrates the [Giscus](https://giscus.app) widget.
- This repository must have the **Discussions** feature enabled.
- Visitors' comments on the forum page are posted as discussions in this repo.
- The comment section on the website is a live mirror of these discussions.

## Setup & Configuration (For Maintainers)

1.  **Enable Discussions:** In this repository, go to **Settings > General**, scroll to the "Features" section, and enable **Discussions**.

2.  **Install & Configure Giscus:**
    *   Visit [giscus.app](https://giscus.app).
    *   Enter this repository's URL (e.g., `https://github.com/sunnyenergy-com-au/leads-forum`).
    *   Follow the steps to generate your configuration script.
    *   The key configuration used on our site is:
        - **Mapping:** `Discussion title contains page title`
        - **Discussion Category:** Choose or create a dedicated category (e.g., "Website Forum").
        - **Features:** Enable reactions, strict title matching, etc., as preferred.

3.  **Embed on Website:** The generated script from Giscus is embedded only on the `forum` page of our website.

## Notes

- Comments are publicly visible both here on GitHub and on the website forum.
- Please keep discussions respectful and on-topic.
- The comment system is active **only** on the `/forum` page. Other pages do not use Giscus.

## Troubleshooting

If comments are not loading on the forum page:
1.  Ensure Discussions are enabled in this repo's Settings.
2.  Verify the Giscus script configuration matches this repository.
3.  Check if the page title matches the discussion title exactly (if using strict mapping).

---
*Powered by [Giscus](https://giscus.app).*