Green Browse Extension 🍃

This repository is the public showcase for my capstone project for the INCO Academy Green Digital Certificate (GDC 2025).

It demonstrates the "Green Browse" Chrome extension, a tool I developed to help users browse more sustainably by reducing their digital carbon footprint.

Status: Coming soon to the Chrome Web Store!

The Problem & Solution

The modern web is data-heavy, downloading megabytes of images and fonts on every page load. "Green Browse" intercepts these requests to save bandwidth and energy, giving you control over what you load.

Before: Normal Website (e.g., BBC.com)

The page automatically loads all high-resolution images, consuming significant data.

After: With "Green Browse" Active

Images and custom fonts are blocked. Lightweight, size-matched placeholders are injected, allowing you to load any image with a single click.

Key Features

Network-Level Blocking: Uses the declarativeNetRequest API to efficiently block all image and font resource types before they are downloaded.

On-Demand Content: Injects lightweight, interactive placeholders that show the image's alt text and a "Load" button.

Intelligent Sizing: Placeholders read the original image's intended CSS styles to match its size, preserving the page layout without distortion.

System Font Override: Replaces all custom web fonts with your computer's native system font, eliminating font downloads and improving page speed.

Smart Whitelist: A built-in whitelist allows you to easily disable the extension on specific domains where a full visual experience is required.

See Your Impact

The popup dashboard gives you tangible feedback on your positive environmental impact by tracking the number of resources you've avoided downloading.

Full Control

The whitelist feature is simple. If you trust a site or need its full content, just add it to the list. The extension will then disable all blocking and script injection for that domain.