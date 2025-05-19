# 🕸 Web Scraping Portfolio – Retail Store Locator Projects

This portfolio showcases a collection of web scraping projects focused on extracting and transforming store locator data from various retail websites across Belgium and the Netherlands. These projects demonstrate proficiency in HTML parsing, API sniffing, React/JS scraping, recursive JSON extraction, and geolocation enrichment using the Google Maps API.

## 🧩 Projects Included

| Website              | Technique Used                        | Coordinates | Notes |
|----------------------|----------------------------------------|-------------|-------|
| Le ROI du Matelas    | API sniffing + JSON parsing            | ✅          | Clean internal API |
| Handy Home           | API sniffing + JSON parsing            | ✅          | Similar to above |
| Plum’Art             | Selenium + regex on JS var             | ✅          | `var stores = [...]` |
| JYSK                 | Selenium + React JSON attribute        | ✅          | `data-jysk-react-properties` |
| Albert Heijn         | ID enumeration + HTML parsing          | ✅          | Dynamic pages |
| Medi-Market          | Static HTML + BeautifulSoup + Geocode  | ✅          | Unstructured HTML |
| Jumbo Netherlands    | Deeply nested JSON (recursive parsing) | ✅          | No visible API |

## 📦 Output Format

Each project results in a structured `DataFrame` or `.csv` file with:
- Store Name
- Full Address
- Contact Info
- Latitude & Longitude (if applicable)
- Additional metadata (e.g., services, URL path)

## 🧠 Highlights

- ✅ Efficient use of Selenium only when necessary
- ✅ Clean error handling and retry logic
- ✅ Integrated Google Maps Geocoding API
- ✅ Recursive parsing and JS-unfriendly solutions
- ✅ Production-ready and scalable scraping patterns

## 📘 Notebook

Open the main notebook under `notebooks/scraping_project_summary.ipynb` to view all projects, documented professionally in Markdown for portfolio or client showcase.

---

© Built by [Your Name]. Contact via [LinkedIn] or [Upwork Profile].
