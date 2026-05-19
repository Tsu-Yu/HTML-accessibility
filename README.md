# Accessibility Improvements for home.html

Course: SWE263P User Experience & Interaction  
Name: Yu-Tsu Chang  
Date: 05/15/2026  
Scope: WCAG 2.2 Level A and AA review of [home.html](home.html).

## Summary

This project improves the accessibility of the original Matt's Mats homepage while keeping the overall look and layout close to the source design. The main focus was keyboard access, semantic structure, readable link text, and alternative text for images.

## What Was Improved

- Added `lang="en"` to the page.
- Added a skip link so keyboard users can jump to the main content.
- Replaced image-only navigation with real text links.
- Removed focus-killing behavior and added visible focus styles.
- Added labels and a separate action button for the QuickNav dropdown.
- Rebuilt the page structure with semantic elements like `<header>`, `<nav>`, `<main>`, and `<aside>`.
- Replaced vague links such as “Click here” with descriptive link text.
- Added meaningful alternative text to product and sidebar images.
- Kept decorative images hidden from screen readers.
- Improved contrast and text readability.
- Replaced the phone number image with real text.
- Made the layout more flexible for zooming and smaller screens.

## Main Accessibility Results

- Keyboard navigation is clearer and easier to use.
- Screen readers can understand the page structure more reliably.
- Links explain their purpose without extra context.
- Decorative content is no longer announced as meaningful content.
- The page keeps the original visual style but is much easier to use with assistive technology.

## Files

- [home.html](home.html) contains the accessible version of the page.
- [README.md](README.md) summarizes the accessibility work for GitHub.