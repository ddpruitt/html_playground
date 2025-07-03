# html_playground

Playing around with HTML, CSS and some JavaScript.

Keeping it simple.

## Playgrounds Overview

This repository contains various HTML, CSS, and JavaScript playgrounds organized into two main categories: **Raw** (vanilla CSS/HTML) and **Tailwind** (using Tailwind CSS framework).

### Raw Playgrounds (`src/raw/`)

#### 1. MathML (`src/raw/MathML/`)
**Purpose**: Demonstrates mathematical notation rendering in HTML using MathML and LaTeX syntax.

**Files**:
- `simple.html` - Shows mathematical expressions using native MathML tags, TeXZilla for LaTeX rendering, and various math notation formats (ASCIIMath, jqMath)

#### 2. Semantic (`src/raw/Semantic/`)
**Purpose**: Showcases HTML5 semantic elements and proper document structure.

**Files**:
- `semantic01.html` - Complete example using semantic tags like `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<figure>`, `<details>`, `<time>`, and `<mark>`
- `image.jpg` - Sample image used in the semantic example

#### 3. CSS Menu (`src/raw/CSS Menu/`)
**Purpose**: Pure CSS collapsible navigation menus without JavaScript.

**Files**:
- `CssCollapsible.html` - Dropdown menu system using HTML `<details>` and `<summary>` elements with CSS styling
- `DisplayContentFlexGrow.html` - Additional menu layout exploration with flexbox properties

#### 4. Content (`src/raw/Content/`)
**Purpose**: Static assets and favicon files.

**Files**:
- `favicon.ico` - Standard favicon file
- `favicon-16x16.png` - 16x16 pixel favicon
- `favicon-32x32.png` - 32x32 pixel favicon

#### 5. CSS Scroll (`src/raw/CSS Scroll/`)
**Purpose**: CSS-only infinite scrolling animations and effects.

**Files**:
- **01 - simple/**
  - `infinitscroll01.html` - Single-line infinite horizontal scroll animation using CSS keyframes
  - `infinitscroll02.html` - Enhanced version of the infinite scroll with additional features

#### 6. Layout (`src/raw/Layout/`)
**Purpose**: Various CSS layout techniques and methodologies.

**Subdirectories**:

- **Masonry/**
  - `example01.html` - CSS-only masonry layout using column-count
  - `example02.html` - Advanced masonry implementation with responsive design

- **Flexbox/**
  - `index.html` - Flexbox layout demonstrations with different justification methods
  - `index.css` - Accompanying CSS styles for flexbox examples
  - `index.js` - JavaScript file (currently empty)

- **Grid/**
  - **Centering in Grids/**
    - `index.html` - Grid centering techniques
    - `index.css` - CSS for grid centering examples
    - `index.js` - JavaScript file (currently empty)
  
  - **grid-areas/**
    - `grid-areas-02.html` - Named grid areas implementation
    - **01 - Simple/**
      - `index.html` - Basic grid areas example
      - `index.css` - CSS for basic grid areas
      - `index.js` - JavaScript file (currently empty)
  
  - **grid-column grid-row/**
    - `simple-01.html` - Grid column and row positioning basics
    - `simple-02.html` - Advanced grid positioning techniques
    - `simple-03.html` - Complex grid layout examples

#### 7. Templates (`src/raw/Templates/`)
**Purpose**: Basic HTML page templates and starting points.

**Files**:
- **01 - Basic/**
  - `index.html` - Minimal HTML template
  - `index.css` - Basic CSS styling
  - `index.js` - JavaScript file (currently empty)

- **02 - Basic/**
  - `index.html` - Alternative basic HTML template

### Tailwind Playgrounds (`src/tailwind/`)

#### 1. CSSCollapsible.html (`src/tailwind/`)
**Purpose**: Tailwind CSS version of the collapsible menu system.

**File**:
- `CSSCollapsible.html` - Same functionality as the raw version but implemented using Tailwind utility classes

#### 2. Content (`src/tailwind/Content/`)
**Purpose**: Static assets for Tailwind examples.

**Files**:
- `favicon-16x16.png` - 16x16 pixel favicon for Tailwind examples
- `favicon-32x32.png` - 32x32 pixel favicon for Tailwind examples

#### 3. Flexbox (`src/tailwind/Flexbox/`)
**Purpose**: Flexbox layouts implemented with Tailwind CSS utilities.

**Files**:
- `flex-tw01.html` - Flexbox justification examples (center, between, around) using Tailwind classes
- `flex-tw02.html` - Additional flexbox layout patterns with Tailwind

#### 4. Grid Layouts (`src/tailwind/Grid Layouts/`)
**Purpose**: CSS Grid implementations using Tailwind CSS.

**Files**:
- `grid-areas-02.html` - Grid areas implementation with Tailwind utilities
- `index-tw01.html` - Basic grid layout with Tailwind
- `index-tw02.html` - Advanced grid layout patterns with Tailwind

## Getting Started

Each playground is self-contained and can be opened directly in a web browser. For Tailwind examples, the Tailwind CSS is loaded via CDN, so no build process is required.

Simply navigate to any `.html` file and open it in your browser to see the demonstration in action.

