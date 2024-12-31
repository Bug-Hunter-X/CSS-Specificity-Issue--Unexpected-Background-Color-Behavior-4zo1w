# CSS Specificity Bug Report

This repository demonstrates an uncommon bug related to CSS selector specificity.  The issue involves unexpected behavior of background color application based on screen size and selector precedence. The bug occurs on screen sizes less than 768px where the expected background color is not applied due to a more specific CSS rule overriding the general rule.  The solution provides a corrected CSS rule set to address this issue.

## Bug Description:

An element with the class "container" fails to apply the expected background color at screen widths less than 768px. This is due to a specificity conflict between CSS rules.  The more specific rule, applied later in the stylesheet, overrides the desired behavior, resulting in the incorrect background color.