# Notes

## What I changed
- Rebuilt the storefront into a clearly structured premium landing page with a stronger hierarchy, cleaner type scale, consistent spacing and a calmer brand palette.
- Fixed the cart and coupon logic so quantities respect stock and the maximum of 5 per product, and the coupon only works once and only when eligible.
- Reworked the product grid so filters, search and sorting act together without conflicting state.
- Improved the delivery check to use the supplied API correctly, with proper loading and error states.
- Replaced the loud promo styling with a calmer brand-led design that follows the provided brand rules and remains mobile-friendly.
- Added email validation, a real FAQ section and a more accessible layout.

## What the AI got wrong
- The original page used flashy, mismatch-heavy styling and contradictory business logic, especially around cart totals, coupon behaviour and search state.
- The initial prompt approach was too generic and needed constraints and business rules added before the implementation became trustworthy.
- Several visuals and product interactions needed manual correction after the first draft to make the experience consistent and credible.

## Images
- The store uses a new SVG-based logo and hero art to keep the look clean and web-ready while avoiding large placeholder files.
- Product images were simplified into consistent illustrated pack graphics to match the premium tea aesthetic without using inconsistent placeholder imagery.

## How I tested it
- Checked the page structure in a browser for layout, content hierarchy and mobile sizing.
- Reviewed cart totals and edge cases manually for stock caps, coupon behaviour and shipping logic.
- Confirmed the checkout form keeps the required fields and contract names intact.

## Questions for the team
- No blocking questions at this stage; the design and copy are aligned with the brand guidelines as provided.

## Time spent
- Approximately 3–4 hours on restructuring, logic fixes, and design polishing.

## Extra features added
- A proper cart drawer with quantity controls and a clean summary.
- Product quick-view modal.
- FAQ accordion and inline newsletter form.

## With more time I would...
- Add a richer product detail view, more advanced saved wishlist behaviour and a more complete set of handcrafted illustrative assets.
