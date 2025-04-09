# SnipBit-Design-Token-System
Design Tokens & Multi-Platform Style Dictionary Setup

Overview
This project extends a design token system using Style Dictionary, ensuring consistent styling across web, iOS, and Android platforms. The goal is to create a scalable and reusable token structure that adheres to brand guidelines while being adaptable to multiple environments.

1. Extended Token Set
The design token system now includes:

Typography Tokens: Primary & secondary font families, sizes, line heights, and weights.
Spacing Tokens: A consistent scale for margins, paddings, and grid spacing.
Effects Tokens: Border radius values and shadows for UI consistency.
Typography (tokens/typography.json)
{
  "font": {
    "family": {
      "primary": { "value": "Inter, sans-serif" },
      "secondary": { "value": "Merriweather, serif" }
    },
    "size": {
      "small": { "value": "12px" },
      "body": { "value": "16px" },
      "large": { "value": "24px" },
      "title": { "value": "32px" }
    },
    "weight": {
      "regular": { "value": "400" },
      "bold": { "value": "700" }
    },
    "lineHeight": {
      "small": { "value": "16px" },
      "body": { "value": "24px" },
      "large": { "value": "32px" }
    }
  }
}
