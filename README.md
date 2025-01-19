# Tailwind CSS @apply Directive Failure with Relative Imports

This repository demonstrates a bug where Tailwind CSS's `@apply` directive fails to work correctly when used with relative import paths. The issue arises when the relative path to the stylesheet containing the `@apply` directive is incorrect, causing Tailwind to not properly resolve and apply the referenced styles.

## Bug Description

When importing a CSS file containing `@apply` directives using a relative path that points to an incorrect location or if the file is not correctly included in the build process, Tailwind CSS fails to apply the expected styles. This results in elements not receiving the intended styling, potentially leading to visual inconsistencies or layout problems.

## Solution

The solution involves ensuring that the relative path in the import statement is accurate and that the relevant CSS file is correctly included in your project's build process.  Double-check your import path and build configuration to correctly include the necessary files.