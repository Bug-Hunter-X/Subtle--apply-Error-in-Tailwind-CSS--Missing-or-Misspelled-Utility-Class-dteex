# Subtle @apply Error in Tailwind CSS

This repository demonstrates a subtle bug that can occur when using Tailwind CSS's `@apply` directive with an invalid or misspelled utility class. The error doesn't always result in a clear build error, making it difficult to debug.  The solution involves careful review of your Tailwind configuration and class names.

## Bug Description
The `@apply` directive in Tailwind CSS allows you to apply pre-defined utility classes to your components. If the applied class doesn't exist or is misspelled, the styles won't be applied. This error can be particularly frustrating as it often manifests as missing styles rather than a clear error message.

## How to reproduce
1. Clone the repository.
2. Open `bug.html` in your browser.
3. Observe that the text color is not correctly applied.

## Solution
The solution is to correct the misspelling within the `@apply` directive in `bugSolution.html`.