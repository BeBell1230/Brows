# Brows By Clari — New Website

Modern, SEO-optimized site for Brows By Clari (Orlando, FL permanent makeup studio).
Open **index.html** in any browser to preview. Fully responsive (mobile + desktop).

## Pages & WordPress slug mapping
| Preview file | WordPress page | Slug |
|---|---|---|
| index.html | Home | `/` |
| microblading-orlando.html | Microblading | `/microblading-orlando/` |
| powder-brows-orlando.html | Powder Brows | `/powder-brows-orlando/` |
| nano-brows-orlando.html | NanoBrows | `/nano-brows-orlando/` |
| lip-blush-orlando.html | Lip Blush | `/lip-blush-orlando/` |
| about.html | About | `/about/` |
| contact.html | Contact | `/contact/` |

> Slugs include the city keyword ("-orlando") for **local SEO**. In WordPress, set each
> page's permalink to the slug above and keep the canonical/meta tags shown in each file.

## SEO meta (title / description) — already in each file's `<head>`
- **Home:** Brows By Clari | Microblading & Permanent Makeup in Orlando, FL
- **Microblading:** Microblading Orlando | Natural Hairstroke Brows | Brows By Clari
- **Powder Brows:** Powder Brows Orlando (Ombré Microshading) | Brows By Clari
- **NanoBrows:** NanoBrows Orlando | Premium Nano Hairstroke Brows | Brows By Clari
- **Lip Blush:** Lip Blush Orlando | Natural Lip Tint Permanent Makeup | Brows By Clari

## Structured data (local SEO)
- `BeautySalon` LocalBusiness schema (NAP, hours, geo, social) on every page
- `Service` + `BreadcrumbList` + `FAQPage` schema on each service page
- `sitemap.xml` and `robots.txt` included

## Business info used
- Address: 4401 East Colonial Dr, Suite 105, Orlando, FL 32803
- Phone: +1 (561) 672-4867
- Hours: Mon–Sat 9:00 AM – 5:00 PM
- Booking: existing Square Appointments link (all "Book Now" buttons)
- Social: Instagram, Facebook, Pinterest, Yelp

## To do before launch
1. Replace low-res thumbnails in `/assets/img/` with full-resolution photos (current
   images are pulled from existing web thumbnails — fine for layout, upgrade for production).
2. Connect the Contact form to email/CRM (currently a front-end demo).
3. Confirm/adjust pricing — copy intentionally avoids fixed prices ("free consultation").
4. Add Google Business Profile review widget + real Google Maps embed API key if desired.

## How to move into WordPress
- **Option A (fastest):** Recreate these 7 pages in Elementor using this copy/structure and the slugs above; paste the JSON-LD blocks into each page (e.g. via a Code/HTML widget or Yoast schema).
- **Option B:** Convert to a custom theme. Ask and I can generate an installable WordPress theme (.zip) from these files.
