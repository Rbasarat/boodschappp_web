# boodschappp
Boodschappen lijst app. 

# To run this scraper:
- Install chrome
- Download chromedriver to ./scraper/driver/
- `$ python AHScraper.py 1`

# TODO:
- Set up logging for python
- Figure out how to fix config
    - Same for passwords
- Fix error handling
    - Also error logging
    - (De)centralize error handling -> where are responsibilities
    - Basescraper error handler should be use every finally.
- Figure out how to deal with bonus products

- Ah specific:
    - Wijnen pagina is anders
    - drogisterij verzorging overslaan
    - logica bouwen page=? specific integer
