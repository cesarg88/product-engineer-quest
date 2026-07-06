# Week 01 Product Analysis: Fever Favorites

## Feature

Fever Favorites.

## 1. User problem

Users may discover plans they like while browsing Fever, but they are not always ready to buy immediately.

Without a way to save interesting plans, they need to search or browse again later. That creates friction and may reduce the chance of purchase.

Favorites solves this by giving users direct access to plans they already expressed interest in.

## 2. User

A person browsing the Fever catalog who finds plans they may want to visit, compare, share, or buy later.

This user may be exploring without immediate purchase intent, or may need more time before deciding.

## 3. Product hypothesis

If users can save plans they like and access them later from a dedicated place, they will be more likely to return to those plans and complete a purchase.

The feature may reduce the friction of rediscovery and increase conversion from previously expressed interest.

## 4. Success metrics

Primary metric:

- `purchase_success` with source `favorites`

Supporting metrics:

- `plan_view` with source `favorites`
- number of plans added to favorites
- number of users with at least one favorite
- revisit rate from favorites list
- conversion rate from favorite plan view to purchase

The primary business question is not only whether users save plans, but whether saving plans helps them come back and buy.

## 5. Simplest useful version

The simplest useful version has two parts:

1. Users can add or remove a plan as favorite with one tap.
2. Users have an easy-to-find place in the app where all favorited plans are listed.

This version is enough to validate whether saving plans creates return visits and purchases.

## 6. Main trade-offs

### Discoverability

Users may not notice the favorite action or may not understand what it does.

### Access

Users may save plans but fail to find the favorites list later.

### Product complexity

Adding favorite state introduces UI states, empty states, synchronization, analytics, and edge cases.

### Expectation management

A favorited plan may later become unavailable, sold out, changed, or no longer relevant.

### Opportunity cost

Engineering and design effort spent on favorites cannot be spent on other discovery or conversion improvements.

## 7. Questions for PM and Design

### Questions for PM

- Which metric defines success for Favorites?
- Are we optimizing for more plan views, more purchases, higher retention, or better user convenience?
- What is the expected behavior after a user saves a plan?
- Should favorites influence recommendations, notifications, or personalization later?
- Do we have evidence that users currently fail to buy because they cannot rediscover plans?

### Questions for Design

- Where should the favorite action appear so users notice it without adding visual noise?
- How should the favorite state be represented?
- Where should the favorites list live in the app?
- What should the empty state communicate?
- How should unavailable, expired, or sold-out plans appear in favorites?

## Learning note

The initial reasoning was implementation-adjacent: add/remove favorite and list saved plans.

The Product Thinking improvement is connecting the feature to a broader product hypothesis:

> Favorites is not only a convenience feature. It is a rediscovery and conversion feature.
