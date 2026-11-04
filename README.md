# PixelNest Studio

Public static website for PixelNest Studio.

## Publishing

GitHub Actions is configured to publish the website to GitHub Pages on every push to `main`. The repository owner must first enable Pages in repository settings and select GitHub Actions as the source.

The order form is currently a request preview only. Before accepting requests, set the `ORDER_EMAIL` value in `index.html` to the studio's real contact email. The form opens a prefilled email; it does not collect payment or check domain availability. Website prices are example estimates in INR.

## Website builder demo

Try the [public website builder demo](https://raw.githack.com/rexxy91/pixelnest-studio/main/ai-builder.html) or open [`ai-builder.html`](./ai-builder.html) in this repository. It runs in the browser without sign-in or an API key, uses built-in templates rather than a connected AI model, and downloads a standalone HTML preview. User-entered content stays in the browser unless the visitor chooses to download it.
