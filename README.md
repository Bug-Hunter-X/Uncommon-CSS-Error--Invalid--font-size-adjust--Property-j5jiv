# Uncommon CSS Error: Invalid 'font-size-adjust' Property

This repository demonstrates a subtle but impactful error in CSS involving the use of the non-standard `font-size-adjust` property.  The issue lies in the reliance on a feature that lacks widespread browser support, causing inconsistent rendering across different browsers and potentially unexpected visual outcomes.

## Problem

The `font-size-adjust` property, while conceptually useful for maintaining x-height consistency, isn't widely adopted.  Using it leads to unpredictable behavior in many browsers, resulting in rendering differences and unexpected visual discrepancies.  Browsers often ignore or handle this property differently, causing inconsistencies in typography.

## Solution

A robust solution is to avoid using `font-size-adjust` altogether and instead rely on more reliable methods for managing text scaling and appearance.

## Usage

1.  Clone this repository.
2.  Examine `bug.css` to see the problematic code.
3.  Refer to `bugSolution.css` for a corrected implementation.
