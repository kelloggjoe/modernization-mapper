---
name: Modernization Mapper
description: A polished enterprise decision surface for application portfolio strategy.
colors:
  canvas: "#f8fafc"
  surface: "#ffffff"
  ink: "#0f172a"
  muted: "#5b687d"
  line: "#dbe3ef"
  indigo: "#4f46e5"
  indigo-dark: "#3730a3"
  violet: "#7c3aed"
  emerald: "#059669"
  amber: "#d97706"
  rose: "#e11d48"
typography:
  display:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "clamp(3rem, 6vw, 5.7rem)"
    fontWeight: 800
    lineHeight: 0.96
    letterSpacing: "-0.04em"
  body:
    fontFamily: "Plus Jakarta Sans, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 500
    lineHeight: 1.6
rounded:
  control: "10px"
  card: "14px"
  pill: "999px"
spacing:
  sm: "8px"
  md: "16px"
  lg: "24px"
components:
  button-primary:
    backgroundColor: "{colors.indigo}"
    textColor: "#ffffff"
    rounded: "{rounded.control}"
    padding: "10px 17px"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "24px"
---

# Design System: Modernization Mapper

## Overview

**Creative North Star: "The Executive Control Plane"**

Modernization Mapper is the most explicitly digital of the three tools: cool, precise, and enterprise-ready. Indigo establishes authority, white work surfaces maintain clarity, and subtle dimensional moments make the portfolio model feel sophisticated rather than bureaucratic.

**Key Characteristics:** cool slate canvas; indigo-violet actions; restrained dimensional metrics; precise 12–14px surfaces; crisp data visualization.

## Colors

Indigo and violet identify primary action and strategic attention. Emerald, amber, and rose encode recommendations; cool slate neutrals carry all inactive structure.

**The Strategic Color Rule.** Accent color explains action or recommendation. Decorative color never competes with the matrix.

## Typography

**Display and Body Font:** Plus Jakarta Sans (system sans fallback)

A single geometric sans family keeps the operating surface consistent. Hierarchy comes from weight, scale, and spacing rather than a second decorative face.

## Layout

The desktop workspace pairs a flexible matrix with a 290px insight rail, followed by a full-width queue. At 850px both stack; at 600px inventory rows become two-column cards. The matrix remains a true four-quadrant plane at every width, with points absolutely layered over it.

## Elevation & Depth

Panels use cool tinted ambient shadows. Summary metrics introduce restrained perspective on wide screens and return to a flat shared plane on mobile.

## Shapes

Cards use 12–14px radii, controls use 10px, and recommendation tags are pills. Circular points are reserved for plotted applications and remain distinct from rectangular controls.

## Components

- **Buttons:** indigo-to-violet primary, white bordered secondary, 44px minimum height.
- **Matrix:** four equal quadrants with semantic pastel fields and overlaid circular markers.
- **Insight rail:** high-contrast indigo field for priority narrative and cost exposure.
- **Recommendation tags:** semantic tinted pills with explicit text labels.

## Do's and Don'ts

### Do:
- **Do** keep every application marker inside the four-quadrant matrix.
- **Do** reserve dimensional treatment for summary and priority surfaces.
- **Do** preserve recommendation labels alongside color.

### Don't:
- **Don't** reuse the portfolio's playful geometric borders or hard shadows.
- **Don't** add editorial serif typography or organic silhouettes.
- **Don't** let atmospheric color reduce data contrast.
