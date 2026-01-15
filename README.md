# Styfi

Styfi is an AI-powered marketplace that helps small businesses sell directly to buyers while helping buyers discover, style, and trust products more easily. It removes unnecessary middlemen, reduces friction in discovery and styling, and improves conversion and confidence using AI-powered tools.

---
---

## Repository Workflow

This repository follows a structured branch and contribution workflow to ensure stability, clarity, and clean collaboration.

### Branches

- **main**
  - Production-ready branch
  - Always stable and deployable
  - No direct commits allowed

- **dev**
  - Integration branch for all completed features
  - Tested and reviewed before merging into `main`

- **feature branches**
  - One branch per feature or task
  - Created from `dev`
  - Merged back into `dev` after review

---

## Branch Rules

- No one commits directly to `main`
- All changes must go through:
  feature branch → dev → main
- Each feature must have its own branch
- Only reviewed and tested code is merged into `dev`
- Only stable, release-ready code is merged into `main`

---

## Working Rules

### General
- Keep commits small and meaningful
- Write clear commit messages
- Do not push broken or unfinished code to `dev`
- Test your changes before requesting merge

### Feature Development
- Each feature must be developed in its own branch
- Do not mix multiple features in one branch
- Follow naming pattern: feature/feature-name

### Reviews
- All merges into `dev` require at least one review
- Fix all review comments before merging

### Frontend, Backend, AI Work
- Frontend, backend, and AI teams all follow the same workflow
- Each team creates feature branches for their tasks
- Large changes should be discussed before implementation


## Product Vision

Styfi aims to become a demand-aware commerce layer where:
- Sellers know what to list and how to present it.
- Buyers find what they want faster and with more confidence.
- AI is used to reduce search friction, styling friction, and trust friction.

---

## Core Features

### Buyer Features
- Smart product discovery using filters like category, budget, location, and style
- Natural language search for products
- Outfit composition suggestions and add-on recommendations
- Virtual try-on to preview products on the user
- Trend discovery showing what is currently popular
- Wishlist and saved items
- Seller trust indicators and reviews

### Seller Features
- Seller onboarding and profile management
- Product listing and inventory management
- AI-powered image enhancement for product photos
- Trend detection to guide what to list
- Outfit compatibility suggestions to increase order value
- Order management and communication
- Basic analytics on views and conversions

### Marketplace Core
- Smart matching between buyer intent and seller listings
- Ranking system based on relevance, trust, and performance
- Commission and subscription model support
- Ratings and review system

### AI Systems
- Outfit composer
- Trend detection engine
- Virtual try-on engine
- Image enhancement engine
- Recommendation and ranking engine

### Trust and Safety
- Seller verification
- Duplicate and fake listing detection
- Abuse and content moderation

---

## Target Users

- Small and medium businesses who want better visibility and conversion
- Buyers looking for personalized, trusted, and style-aware shopping
- Brands wanting trend insights and demand forecasting

---

## Business Model

- Commission on successful transactions
- Premium tools and analytics for sellers
- Sponsored product placement


---

## Status

Styfi is under active development.

Architecture, scope, and features may evolve rapidly as the product matures.
