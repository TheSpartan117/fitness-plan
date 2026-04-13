# Fitness Plan

This repository currently hosts a single static page used as a personal gym reference.

## Privacy Notes

- The published page is intended for personal use, not as a reusable coaching plan.
- `index.html` has been trimmed to avoid exposing personal stats in visible metadata.
- The page now includes `noindex` crawler directives and a restrictive in-page content security policy.
- A `robots.txt` file should be published alongside the page to discourage indexing.

## Important Limitation

If this page is deployed publicly through GitHub Pages or another public static host, it is still publicly reachable by anyone with the URL. Client-side HTML cannot provide real access control.

For actual privacy, use one of these:

- Put the site behind hosting-level authentication.
- Keep the repository and deployment private.
- Stop publishing it publicly and open the file locally on your own devices.

## Repo Contents

- `index.html` - the personal dashboard page
- `robots.txt` - crawler exclusion request for static hosting
