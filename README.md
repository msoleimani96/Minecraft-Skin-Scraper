
# Minecraft Skin Scraper

This is a scraper project to extract skins of [NameMC](https://namemc.com) and https://www.minecraftskins.net websites.

One of the challenges I faced was the [NameMC](nameMC.com) website that used JavaScript rendering, and I solved it using Selenium.
The other challenge was some skins that had no title or tag, so I generated titles or tags for them using NLP (Natural language processing).

## Technologies:
- Python
- Selenium (For Javascript rendering websites)
- Requests
- Beautiful Soup
- [TextRazor](https://www.textrazor.com) (NLP API for generating tags and titles based on details of skin)

## Getting Started
1. Clone or download the project.
   
2. Create a virtual environment.
   ```
   python3 -m venv virtual_env_name
   ```

3. Activate the environment.
   ```
   source virtual_env_name/bin/activate
   ```
   
4. Install packages.
   ```
   pip install -r requirements.txt
   ```

5. Use scrapers. (I write comments to guide you in using the code)
