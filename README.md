Drip Store is a full-stack e-commerce web application built for dropshipping clothing. It supports a complete customer-facing storefront and an admin dashboard for managing the store.

Tech Stack

Backend: Node.js + Express, with SQLite (using Node's built-in SQLite module) for the database
Frontend: React
Auth: JWT-based authentication

Features
Storefront

Fashion-style homepage with hero banner, featured collections, best sellers, and new arrivals
Collection pages (Men, Women, Unisex, Streetwear, Formal, Casual, Accessories, Sale)
Filtering (size, color, price, category, fit, brand, availability) and sorting
Product pages with image gallery, variant picker, size guide, reviews, and related items
Cart with promo codes and save-for-later
Guest checkout with address and payment flow
Account area (order history, addresses, wishlist, tracking)
Search with autocomplete

Admin Dashboard

Full product management (variants, pricing, photos, SEO fields) with image upload, deletion, and cover-image selection
Inventory, orders, refunds, coupon, and customer management
Homepage banner and featured-product control
Sales analytics (totals, conversion rate, top products, abandoned carts)
Static page management (About, FAQ, Privacy Policy, etc.)
Full data export

Technical

Mobile-first responsive design
SEO-ready (sitemap.xml, robots.txt, product schema, clean URLs)
Secure input validation and sanitization (prevents SQLite type-binding errors on blank fields)
HTTPS-ready architecture

Status
Core backend API and full frontend UI are complete and functional. Payment gateway and hosting integration are planned next steps.
