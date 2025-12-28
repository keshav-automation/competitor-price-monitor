⚠️ Output Excel files are generated locally and not included in this repository.

competitors can be easily modified in the configuration section of the script:

CONFIG = {
    "products": [
        {
            "product_name": "A Light in the Attic",
            "competitors": [
                {
                    "name": "Amazon",
                    "url": "http://books.toscrape.com/catalogue/a-light-in-the-attic_1000/index.html"
                },
                {
                    "name": "Flipkart",
                    "url": "http://books.toscrape.com/catalogue/a-light-in-the-attic_1000/index.html"
                }
            ]
        }
    ]
}


This allows the project to scale to multiple products and competitors easily.


⚠️ Disclaimer

This project is for educational and portfolio purposes only.
Always check and respect a website’s robots.txt and terms of service before scraping.


👤 Author

Keshava Murthy P
Beginner Python Developer
Web Scraping & Excel Automation


✅ Project Status

✔ Portfolio-ready
✔ Beginner-friendly
✔ Client-understandable
✔ Freelance-ready foundation


🚀 Next Steps

Add support for real historical price storage (CSV / Database)

Schedule scraping using cron or Task Scheduler

Add logging instead of print statements


