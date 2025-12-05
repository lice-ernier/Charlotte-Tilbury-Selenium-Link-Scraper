# Charlotte Tilbury Selenium Link Scraper
>The Charlotte Tilbury Selenium Link Scraper is a generic template-style scraper built with Selenium that fetches product links from shophouse pages of Charlotte Tilbury (or similar ecommerce sites). It collects URLs of product listings and outputs a structured list of links for further processing. Great for product discovery, catalog building, or feeding into more detailed scrapers down the line.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Charlotte Tilbury Selenium Link Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
This actor uses a headless browser (via Selenium) to load pages that may include dynamic content, render JavaScript, and navigate paginated collections. Its primary purpose is to extract all product URLs from provided start pages so downstream workflows can fetch full product data. It’s a useful building block for ecommerce crawls or catalog aggregation.

### What It Does
- Loads category or collection pages (or any start URL) in a browser context.  
- Handles dynamic loading or JS-rendered content (makes it more robust than static scrapers).  
- Extracts all product listing URLs from each page.  
- Outputs a structured JSON list of links, ready for use in other scraping steps.

---
## Features
| Feature | Description |
|---------|-------------|
| Selenium-Driven Scraping | Uses a headless browser to render JS-heavy pages accurately. |
| Link Extraction | Collects all product listing URLs from given start pages. |
| Pagination and Multi-Page Support | Able to traverse multiple pages if needed. |
| Proxy & Anti-Block Support | Compatible with proxy configuration to avoid IP blocking. |
| Structured Output | Returns clean JSON array of URLs for easy integration. |
| Ease of Integration | Acts as first step (link discovery) before deeper product scraping. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|------------------|
| url | A product listing URL found on the start pages. |

---
## Example Output
    
    [
      {
        "url": "https://www.charlottetilbury.com/us/product/example-lipstick"
      },
      {
        "url": "https://www.charlottetilbury.com/us/product/example-eye-shadow"
      }
    ]

---
## Directory Structure Tree
    
    charlotte-tilbury-selenium-link-scraper/
    ├── src/
    │   ├── main.js (or main.py depending on implementation)  
    │   ├── scraper/  
    │   │   ├── browser_launcher.js  
    │   │   ├── link_extractor.js  
    │   │   └── pagination_handler.js  
    │   └── config/  
    │       └── input_schema.json  
    ├── package.json (or requirements.txt)  
    └── README.md

---
## Use Cases
- **Catalog builders** gather all product links before feeding them into detailed scrapers.  
- **Market researchers** map product offerings by collecting URLs across categories.  
- **Ecommerce tools** assemble product link databases for price tracking or alerts.  
- **Scraper pipelines** use link output as input for a second-stage product data extractor.  

---
## FAQs

**Does this scraper fetch full product details?**  
No — this actor only extracts product URLs (links). Use a separate product scraper to get details like price, description, images.

**Is it suitable for JS-heavy websites?**  
Yes — since it uses Selenium (headless browser), it handles JavaScript and dynamic loading.

**Can it follow pagination?**  
Yes — it supports multi-page crawling if the site uses paginated collections.

**What output format does it use?**  
A JSON array of objects with a single `url` field per item, suitable for chaining into other scrapers or pipelines.  


---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>

