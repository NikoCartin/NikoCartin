<h1 align="center">Hey, I'm Nícolas Cartín Reyes</h1>

<p align="center">
Entrepreneur · Full Stack Developer · Shopify Plus Engineer · Digital Strategist
</p>

<p align="center">
  Valedictorian in Web Design &amp; Full Stack Development from <strong>Universidad Fidélitas</strong> and Business Administration at <strong>TEC</strong><br/>
  AI Product Management Specialization from <strong>Duke University</strong><br/>
  Building commerce systems, digital products, and growth experiences that connect technology with business results
</p>

<p align="center">
  Founder of <strong>Hablemos de MMA</strong>, a content and commerce platform for the martial arts community
</p>

<p align="center">
  <a href="https://nikocartin.github.io/"><strong>View my portfolio</strong></a>
  ·
  <a href="https://www.linkedin.com/in/n%C3%ADcolas-cart%C3%ADn-reyes-6382852a/"><strong>LinkedIn</strong></a>
</p>

---

### Featured Experience

### Primal Strength US - Shopify Theme Customizations

[us.primalstrength.com](https://us.primalstrength.com) · [primal-strength-us-shopify](https://github.com/NikoCartin/primal-strength-us-shopify)

Production-level Shopify theme development for Primal Strength US, a premium fitness equipment brand. Work included resolving critical storefront availability bugs, adapting UK-specific features for the US market, integrating financing and product-video systems, protecting quote-only commerce flows, improving collection merchandising, and customizing transactional email templates.

<p align="center">
  <a href="https://us.primalstrength.com">
    <img src="https://raw.githubusercontent.com/NikoCartin/primal-strength-us-shopify/main/banner.jpg" alt="Primal Strength US" width="800"/>
  </a>
</p>

- [View repository](https://github.com/NikoCartin/primal-strength-us-shopify)
- [Live Store](https://us.primalstrength.com)
- [Dynamic product video documentation](https://github.com/NikoCartin/primal-strength-us-shopify/blob/main/docs/TECHNICAL-PRODUCT-VIDEO-METAFIELDS.md)
- [Product video setup SOP](https://github.com/NikoCartin/primal-strength-us-shopify/blob/main/docs/SOP-PRODUCT-VIDEO-METAFIELDS.md)
- [Split Echelon and PRIMAL logo implementation](https://github.com/NikoCartin/primal-strength-us-shopify/blob/main/docs/TECHNICAL-SPLIT-ECHELON-PRIMAL-LOGO-LINKS.md)
- [General Shopify SOP repository](https://github.com/NikoCartin/shopify-sops)
- Tech used: `Shopify` · `Liquid` · `JavaScript` · `HTML` · `CSS` · `ChargeAfter` · `Metafields` · `Shopify CLI`

---

### Featured Open-Source Contribution: DomainPass

[DomainPass - Domain-Verified Partner Benefits Starter](https://github.com/NikoCartin/shopify-domain-verified-partner-benefits-starter)

<p align="center">
  <a href="https://github.com/NikoCartin/shopify-domain-verified-partner-benefits-starter">
    <img src="https://raw.githubusercontent.com/NikoCartin/NikoCartin/main/assets/domain-verified-partner-benefits-banner.png" alt="DomainPass, a Domain-Verified Partner Benefits Starter for Shopify" width="900"/>
  </a>
</p>

DomainPass is a reusable public Shopify starter for granting an individual, single-use benefit only after the email domain on an authenticated customer account matches an approved organization. The architecture is designed for employee, alumni, membership, corporate, association, and partner programs where a generic public discount code is not enough.

- [View repository and installation guide](https://github.com/NikoCartin/shopify-domain-verified-partner-benefits-starter)
- [Portfolio case study](https://nikocartin.github.io/#shopify-work)
- Tech used: `Node.js` · `Shopify Customer Account API` · `OAuth 2.0 + PKCE` · `MySQL` · `App Proxy` · `Admin GraphQL` · `Liquid` · `Shopify Discount Codes`

---

### Featured Open-Source Contribution: Shopify Membership Shipping Discount Starter

[shopify-membership-shipping-discount-starter](https://github.com/NikoCartin/shopify-membership-shipping-discount-starter)

<p align="center">
  <a href="https://github.com/NikoCartin/shopify-membership-shipping-discount-starter">
    <img src="https://raw.githubusercontent.com/NikoCartin/NikoCartin/main/assets/shopify-membership-shipping-banner.png" alt="Membership Shipping Discount, Shopify Function and App Home Configurator" width="900"/>
  </a>
</p>

A reusable, open-source Shopify starter for building a membership-gated free-shipping rule directly in Shopify checkout. The project uses a Rust/WASM Shopify Function and a Shopify-hosted App Home configurator so developers can implement and manage a configured automatic shipping discount without maintaining an external backend.

**Key capabilities:**
- Configures eligible and explicitly excluded membership Product or ProductVariant GIDs from Shopify Admin
- Applies a 100% shipping discount across all delivery groups only when an eligible cart line is present
- Fails closed when configuration is missing or malformed, with exclusions taking precedence over inclusions
- Includes a Shopify-hosted App Home configurator with Direct API Access, duplicate protection, resource validation, and controlled automatic-discount creation
- Includes Rust, JavaScript, and CI validation, plus replication, testing, security, and contribution guidance

- [View repository and replication guide](https://github.com/NikoCartin/shopify-membership-shipping-discount-starter)
- [Safety and testing guidance](https://github.com/NikoCartin/shopify-membership-shipping-discount-starter/blob/main/docs/SAFETY_AND_TESTING.md)
- Tech used: `Shopify Functions` · `Rust` · `WASM` · `Shopify Admin GraphQL API` · `App Home UI Extensions` · `Preact` · `Polaris Web Components` · `GitHub Actions`

---

### Shopify Storefront Development & E-commerce Operations - Echelon US, UK & CA

<p align="center">
  <a href="https://echelonfit.com/">
    <img src="https://github.com/NikoCartin/NikoCartin/blob/main/echelonfit.jpg" alt="Echelon Shopify Storefront" width="900"/>
  </a>
</p>

Lead Shopify development, maintenance, and e-commerce operations across Echelon Fitness regional storefronts and related sites. The public portfolio highlights Echelon US, UK, and Canada, while the broader operating scope includes regional experiences and geo-routing support for France, Germany, and Ireland.

The work combines Liquid theme engineering, product and variant data, metafields, collection merchandising, app integrations, checkout rules, shipping logic, promotional experiences, SEO, responsive UX, production QA, and stakeholder support across multiple storefronts.

**Key contributions:**
- Edited Shopify Liquid themes, templates, sections, snippets, JavaScript assets, and storefront code
- Managed product pages, collection pages, product media, metafields, merchandising content, and regional catalog updates
- Built and maintained reusable product architecture instead of relying only on hardcoded SKU-specific templates
- Architected a UK dynamic equipment template with 17 sections and 10 supporting snippets for galleries, memberships, financing, accessories, reviews, video, responsive UX, and cart behavior
- Built and validated custom Shopify Functions and app-extension workflows for membership shipping and promotional gift logic
- Implemented and tested geo-location storefront routing across US, UK, Canada, France, Germany, and Ireland
- Improved collection UX, navigation, content structure, imagery, product-card behavior, and regional customer journeys
- Supported technical SEO audits, JSON-LD, semantic headings, metadata, controlled theme releases, post-deployment crawls, and Lighthouse benchmarking
- Troubleshot upload, display, layout, inventory, cart, shipping, app-integration, and content issues
- Documented development, QA, deployment, rollback, and operational procedures for developers and Shopify administrators

**Storefronts and pages:**
- [Echelon US](https://echelonfit.com/)
- [Echelon UK](https://echelonfit.uk/)
- [Echelon Canada](https://echelonfit.ca/)
- [Echelon France](https://echelonfit.fr/)
- [Echelon Germany](https://echelonfit.de/)
- [Echelon Coach](https://echeloncoach.com/virtualpt/)

**Related repositories and documentation:**
- [Echelon Shopify Development SOPs](https://github.com/NikoCartin/echelon-sops)
- [Geo-fencing storefront routing](https://github.com/NikoCartin/geo-fencing)
- [Dynamic Shopify PDP Playbook](https://github.com/NikoCartin/shopify-dynamic-pdp-playbook)
- [Echelon US SEO technical case study](https://github.com/NikoCartin/echelon-sops/blob/main/SEO-CASE-STUDY-echelon-fit-us-2026-10.md)
- [SEO audit and controlled theme release SOP](https://github.com/NikoCartin/echelon-sops/blob/main/SOP-016-seo-audit-controlled-theme-release.md)
- [ThermaChill chair-gift SOP](https://github.com/NikoCartin/echelon-sops/blob/main/SOP-015-thermachill-chair-gift.md)
- [UK two-part equipment and screen cart SOP](https://github.com/NikoCartin/echelon-sops/blob/main/SOP-011-uk-two-part-screen-line-cart-flow.md)
- Tech used: `Shopify Plus` · `Liquid` · `HTML` · `CSS` · `JavaScript` · `TypeScript` · `Ruby` · `Rust/WASM` · `GraphQL` · `Shopify Functions` · `App Extensions` · `Shopify CLI` · `Metafields` · `UX/UI` · `E-commerce Operations`

---

### Echelon Commercial Site Contribution

[echeloncommercial.com](https://echeloncommercial.com/) · [echelon-commercial-portfolio](https://github.com/NikoCartin/echelon-commercial-portfolio)

Led ongoing development and optimization of the Echelon Commercial fitness e-commerce experience on Shopify. Work included React-powered product-detail experiences, product information updates, commercial category organization, specification-sheet downloads, quote-flow improvements, Formspree to HubSpot market routing, navigation and link auditing, technical SEO, runtime recovery, and production deployment validation.

**Core development areas:**
- React-powered Shopify storefront architecture, product-detail experiences, catalog UX, and responsive presentation
- Product data, specifications, warranty content, category organization, and direct specification-sheet downloads
- Formspree forms that redirect to the correct owner emails and create HubSpot contacts
- HubSpot workflow routing based on market segment so leads reach the correct sales team owner
- Commercial quote flows, technical audits, link validation, runtime recovery, and controlled production releases
- Product content, merchandising, navigation, and customer-facing improvements for commercial buyers

<p align="center">
  <a href="https://echeloncommercial.com/">
    <img src="https://raw.githubusercontent.com/NikoCartin/NikoCartin/main/assets/echelon-commercial-banner.png" alt="Echelon Commercial equipment catalog" width="900"/>
  </a>
</p>

- [Live Site](https://echeloncommercial.com/)
- [Contribution portfolio](https://github.com/NikoCartin/echelon-commercial-portfolio)
- [Portfolio case study](https://nikocartin.github.io/#echelon)
- Tech used: `Shopify` · `Liquid` · `React` · `JavaScript` · `TypeScript` · `JSX` · `HTML` · `CSS` · `Formspree` · `HubSpot` · `Python` · `Node.js` · `Git` · `Shopify CLI`

---

### Echelon Coach API HTTPS Recovery

[echeloncoach.com/virtualpt](https://echeloncoach.com/virtualpt/) · [echelon-coach-ssl-recovery](https://github.com/NikoCartin/echelon-coach-ssl-recovery)

Public technical case study documenting the recovery of an AWS-hosted Echelon Coach API after an expired SSL certificate interrupted the secure HTTPS path. The work covered Linux and Nginx diagnosis, Certbot and Let’s Encrypt certificate installation, HTTPS validation, and automated renewal verification.

- [Live platform](https://echeloncoach.com/virtualpt/)
- [Technical case study repository](https://github.com/NikoCartin/echelon-coach-ssl-recovery)
- [Portfolio case study](https://nikocartin.github.io/#shopify-work)
- Tech used: `AWS` · `Linux/Ubuntu` · `Nginx` · `SSL/TLS` · `Let’s Encrypt` · `Certbot` · `Systemd` · `SSH`

---

### Echelon Partners Program

[Echelon Partners page](https://echelonfit.com/pages/partners)

<p align="center">
  <a href="https://echelonfit.com/pages/partners">
    <img src="https://raw.githubusercontent.com/NikoCartin/NikoCartin/main/assets/echelon-partners-program-banner.png" alt="Echelon Partners Program domain verification and partner benefits experience" width="900"/>
  </a>
</p>

Built a custom Echelon partner-verification experience that combines Shopify Customer Accounts, OAuth 2.0 with PKCE, approved corporate-domain validation, MySQL benefit state, App Proxy security, and single-use discount issuance.

- [Live partner experience](https://echelonfit.com/pages/partners)
- [Portfolio case study](https://nikocartin.github.io/#shopify-work)
- Tech used: `Node.js` · `Shopify Customer Account API` · `OAuth 2.0 + PKCE` · `MySQL` · `App Proxy` · `Admin GraphQL` · `Liquid`

---

### Echelon US Technical SEO Improvements

[Echelon Fit US](https://echelonfit.com/) · [SEO case study](https://github.com/NikoCartin/echelon-sops/blob/main/SEO-CASE-STUDY-echelon-fit-us-2026-10.md)

Audited metadata, canonical tags, social markup, Product JSON-LD, semantic H1 coverage, product-card rendering, and site-wide crawl health. Delivered a narrow five-file Liquid release through duplicate-theme QA, controlled production deployment, pull-back verification, post-deployment crawl analysis, and mobile Lighthouse benchmarking.

- [Live storefront](https://echelonfit.com/)
- [Public technical case study](https://github.com/NikoCartin/echelon-sops/blob/main/SEO-CASE-STUDY-echelon-fit-us-2026-10.md)
- [Controlled release SOP](https://github.com/NikoCartin/echelon-sops/blob/main/SOP-016-seo-audit-controlled-theme-release.md)
- [Portfolio case study](https://nikocartin.github.io/#seo)
- Tech used: `Shopify Liquid` · `JSON-LD` · `Technical SEO` · `Lighthouse` · `Core Web Vitals` · `Crawling` · `Release Engineering`

---

### Projects & Experiments

### NossoCR E-commerce Platform

[nossocr.com](https://nossocr.com/) · [nossocr-wordpress](https://github.com/NikoCartin/nossocr-wordpress)

Full WordPress and WooCommerce storefront for NossoCR, a Costa Rican multi-brand fashion retailer specializing in imported Brazilian clothing and official Melissa Shoes. I developed the customer-facing experience as Lead Developer using Elementor, WordPress theme selection and customization, and custom PHP, HTML, and CSS. The site includes women’s, men’s, and children’s shopping sections, a Melissa Shoes catalog, product variants, newsletter integration, a WhatsApp catalog, SEO, visual merchandising, and promotional content.

<p align="center">
  <a href="https://nossocr.com/">
    <img src="https://raw.githubusercontent.com/NikoCartin/NikoCartin/main/nosso_banner.png" alt="NossoCR WordPress and WooCommerce storefront" width="800"/>
  </a>
</p>

- [Live Site](https://nossocr.com/)
- [Public project record and repository](https://github.com/NikoCartin/nossocr-wordpress)
- [Portfolio case study](https://nikocartin.github.io/#woocommerce)
- Tech used: `WordPress` · `WooCommerce` · `Elementor` · `PHP` · `HTML` · `CSS` · `SEO` · `WhatsApp Commerce`

---

### Hablemos de MMA - E-commerce & Content Platform

[hablemosdemma.com](https://hablemosdemma.com/)

Founder and developer of a content and commerce platform for the martial arts community in Costa Rica. Built with Hostinger’s website builder, the platform combines a product catalog for martial arts equipment, an integrated blog, social media content, promotional email campaigns, and community engagement through interviews, tutorials, and fight analysis.

<p align="center">
  <a href="https://hablemosdemma.com/">
    <img src="https://raw.githubusercontent.com/NikoCartin/NikoCartin/main/hmma_banner.webp" alt="Hablemos de MMA" width="800"/>
  </a>
</p>

- [Live Site](https://hablemosdemma.com/)
- [YouTube Channel](https://youtube.com/@HablemosdeMMA)
- [Email marketing portfolio section](https://nikocartin.github.io/#email)
- Tech used: `E-commerce` · `Content Management` · `Social Media Integration` · `SEO` · `Digital Marketing` · `Email Marketing`

---

### MarbellaCR E-commerce Platform

[marbellacr.com](https://www.marbellacr.com/)

Recreated MarbellaCR’s customer-facing e-commerce site after the original development agency did not provide the WooCommerce backups. Built a practical no-code solution with Hostinger’s AI Website Builder, custom styling, layout design, graphic editing, product catalog organization, promotions, WhatsApp catalog integration, social content, and SEO.

<p align="center">
  <a href="https://www.marbellacr.com/">
    <img src="https://raw.githubusercontent.com/NikoCartin/NikoCartin/main/marbella_banner.png" alt="MarbellaCR Hostinger AI Website Builder storefront" width="800"/>
  </a>
</p>

- [Live Site](https://www.marbellacr.com/)
- [Portfolio case study](https://nikocartin.github.io/#archive)
- Tech used: `Hostinger AI Website Builder` · `E-commerce` · `CSS` · `SEO` · `Social Media Integration` · `WhatsApp Catalog` · `Digital Marketing`

---

### Grupo Inmarca Landing Page

[grupoinmarca.com](https://grupoinmarca.com/) · [landing-page-grupo-inmarca](https://github.com/NikoCartin/landing-page-grupo-inmarca)

Professional React and PHP landing page for Grupo Inmarca, the official distributor and representative of Brazilian clothing brands in Costa Rica. Features institutional information, commercial details, contact routing, WhatsApp, and company policies.

<p align="center">
  <a href="https://github.com/NikoCartin/landing-page-grupo-inmarca">
    <img src="https://raw.githubusercontent.com/NikoCartin/landing-page-grupo-inmarca/main/docs/screenshot.png" alt="Grupo Inmarca Landing Page Screenshot" width="800"/>
  </a>
</p>

- [Live Site](https://grupoinmarca.com/)
- [View code on GitHub](https://github.com/NikoCartin/landing-page-grupo-inmarca)
- [Portfolio archive](https://nikocartin.github.io/#archive)
- Tech used: `React` · `PHP` · `EmailJS` · `CSS` · `HTML` · `Responsive UX`

---

### Laravel Inventory Management System

[InventarioRapidoLaravel](https://github.com/NikoCartin/InventarioRapidoLaravel)

Complete inventory management system developed with Laravel. Features product, supplier, and category management, CRUD operations, responsive interface, Blade templates, Eloquent ORM, and a professional MVC architecture.

<p align="center">
  <a href="https://github.com/NikoCartin/InventarioRapidoLaravel">
    <img src="https://raw.githubusercontent.com/NikoCartin/InventarioRapidoLaravel/main/public/PortadaInventario.PNG" alt="Inventory management system cover" width="800"/>
  </a>
</p>

- [View repository](https://github.com/NikoCartin/InventarioRapidoLaravel)
- [Portfolio archive](https://nikocartin.github.io/#archive)
- Tech used: `Laravel` · `PHP` · `MySQL` · `Blade Templates` · `Eloquent ORM` · `MVC Architecture`

---

### AJAX Shopping Cart System

[carrito-compras-ajax](https://github.com/NikoCartin/carrito-compras-ajax)

Complete shopping cart system developed with native web technologies using AJAX for asynchronous communication and PHP sessions for state management. The project includes dynamic product management, real-time cart updates, and purchase-history functionality.

<p align="center">
  <a href="https://github.com/NikoCartin/carrito-compras-ajax">
    <img src="https://raw.githubusercontent.com/NikoCartin/carrito-compras-ajax/main/Portada.png" alt="AJAX and PHP shopping cart system" width="800"/>
  </a>
</p>

- [View repository](https://github.com/NikoCartin/carrito-compras-ajax)
- [Portfolio archive](https://nikocartin.github.io/#archive)
- Tech used: `PHP` · `JavaScript` · `AJAX` · `HTML` · `CSS` · `Sessions`

---

### E-commerce Platform - PHP & MySQL

[ecommerce-php](https://github.com/NikoCartin/ecommerce-php)

Complete e-commerce system built with vanilla PHP and MySQL. Features a product catalog, shopping cart management, customer inquiry system, checkout process, responsive Bootstrap 5 design, session management, and database persistence.

<p align="center">
  <a href="https://github.com/NikoCartin/ecommerce-php">
    <img src="https://raw.githubusercontent.com/NikoCartin/ecommerce-php/main/assets/images/PortadaGithub.PNG" alt="PHP and MySQL e-commerce platform" width="800"/>
  </a>
</p>

- [View repository](https://github.com/NikoCartin/ecommerce-php)
- [Portfolio archive](https://nikocartin.github.io/#archive)
- Tech used: `PHP` · `MySQL` · `HTML` · `CSS` · `Bootstrap 5` · `JavaScript` · `Apache`

---

### Demo: jQuery Interactive Web

[HMMADemoJquery](https://github.com/NikoCartin/HMMADemoJquery)

Demonstration project implementing interactive functionality with jQuery for DOM manipulation, event handling, effects, animations, and dynamic browser-side behavior.

- [View repository](https://github.com/NikoCartin/HMMADemoJquery)
- [Portfolio archive](https://nikocartin.github.io/#archive)
- Tech used: `jQuery` · `JavaScript` · `HTML` · `CSS` · `DOM Manipulation`

---

### Demo: React vs Vanilla JavaScript

[react-vs-vanilla-demo](https://github.com/NikoCartin/react-vs-vanilla-demo)

Comparative demo exploring the differences between building interactive interfaces with pure Vanilla JavaScript and React, including state management, DOM handling, and maintainability considerations.

- [View repository](https://github.com/NikoCartin/react-vs-vanilla-demo)
- [CodeSandbox live preview](https://codesandbox.io/p/github/NikoCartin/react-vs-vanilla-demo)
- [Portfolio archive](https://nikocartin.github.io/#archive)
- Tech used: `React` · `JavaScript` · `HTML` · `CSS`

---

### Demo: React Essentials

[react-essentials-start](https://github.com/NikoCartin/react-essentials-start)

React starter project covering components, props, state, and dynamic rendering.

- [View repository](https://github.com/NikoCartin/react-essentials-start)
- [Live Site](https://vzmfs3.csb.app/)
- [Portfolio archive](https://nikocartin.github.io/#archive)
- Tech used: `React` · `JavaScript` · `HTML` · `CSS`

---

### Tech I'm Into

`HTML` · `CSS` · `JavaScript` · `TypeScript` · `React` · `Vue.js` · `Node.js`

`PHP` · `Laravel` · `Python` · `Ruby` · `MySQL` · `REST` · `GraphQL` · `AJAX`

`Shopify Plus` · `Liquid` · `Shopify Functions` · `Rust/WASM` · `WooCommerce` · `WordPress`

`AWS` · `Linux/Ubuntu` · `Nginx` · `SSL/TLS` · `Certbot` · `Git` · `GitHub` · `Shopify CLI`

`SEO` · `CRO` · `Email Marketing` · `Klaviyo` · `Formspree` · `HubSpot` · `Digital Strategy`

- [Full portfolio and selected case studies](https://nikocartin.github.io/)
- [Public Shopify SOPs](https://github.com/NikoCartin/echelon-sops)
- [Public technical projects](https://github.com/NikoCartin?tab=repositories)

---

### Want to connect?

- [LinkedIn](https://www.linkedin.com/in/n%C3%ADcolas-cart%C3%ADn-reyes-6382852a/)
- [Portfolio](https://nikocartin.github.io/)
- [GitHub repositories](https://github.com/NikoCartin?tab=repositories)
- nicolascartinreyes@gmail.com

---

<p align="center"><em>Building commerce systems with technical depth, product judgment, and practical execution. Based in Costa Rica.</em></p>
