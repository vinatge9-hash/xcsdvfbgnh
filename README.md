# NIyantri Coffee - Web Project

This repository contains a simple, Tailwind CSS driven, multi-page static site for NIyantri Coffee. It supports online ordering with a client-side cart and a mock PayPal checkout flow.

Files generated:

- index.html (Home) - includes a hero, a small menu, and testimonials
- about.html (About Us)
- contact.html (Contact Us)
- cart.html (Cart) - shows items added to cart from the home page
- checkout.html (Checkout) - mock PayPal payment flow
- README.md (this file)

How to run:

1. Open the HTML files directly in a browser (no server required).
2. Use the Home page to add items to the cart. Items are stored in localStorage.
3. Visit Cart to view and adjust quantities, then proceed to Checkout.
4. On Checkout, click Pay with PayPal to simulate a payment. The cart will be cleared on success.

Notes:
- All styling uses Tailwind CSS classes loaded via CDN.
- All images use placeholder syntax as required: src="https://images.unsplash.com/photo-1643270676135-ee67127e2895?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw2fHxhJTIwcmljaGx5JTIwZGV0YWlsZWQlMjBjb2ZmZWUlMjBzaG9wJTIwaW50ZXJpb3IlMjB3aXRoJTIwd2FybSUyMGxpZ2h0aW5nfGVufDB8MHx8fDE3NTg0NjA1OTB8MA&ixlib=rb-4.1.0&q=80&w=1080".
- The site uses a responsive header with a mobile hamburger menu.
- The footer contains three columns and a centered 2025 copyright, plus NADARGUL location.
- Accessibility: semantic HTML, proper heading order, alt text on images.
- Animations: page fade-in, scroll reveal, hover effects, and interactive cards.

Copyright 2025 NIyantri Coffee