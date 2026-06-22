# Netherlands Travel Plan Site

This repository hosts the generated static HTML site for the Netherlands travel plan.

Published site: https://personaltravelplan.github.io/Netherlands-site/

## Repository Role

- `personaltravelplan/Netherlands` is the private source-of-truth repository.
- `personaltravelplan/Netherlands-site` is the public generated-site repository.
- This repo should contain only generated HTML and public-facing assets.

## Update Flow

Do not edit generated site files here directly. Update the Markdown source in the private `Netherlands` repository, then run the publish workflow there. That workflow regenerates `site-dist/` and publishes the generated output to this repository.

## Privacy Note

The source repository remains private, but this published site is public. Anyone with the link can access the generated page and assets. The generated site includes `robots.txt` and `noindex,nofollow` metadata to reduce search indexing, but those are not access controls.

Do not publish passport details, ticket numbers, hotel confirmation numbers, personal IDs, private addresses, or other sensitive travel documents here.
