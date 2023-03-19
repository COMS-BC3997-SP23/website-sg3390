---
title: "Project Update Presentation"
categories:
  - Presentation
---
#### This page contains a presentation of everything that has been completed in this project so far. 

## What is the project?

The goal of this project is to compare the reviews of three different products, produced from the same manufacturer 
and sold by different merchandisers. The manufacturer is Ulker (a leading food company in Turkey famous for its sweet
snacks). The products of Ulker can be found on the greatest e-commerce platform in Turkey: Trendyol. Similar to 
Amazon, you can get the same product from different sellers on Trendyol. We observed that the same product sold by 
different merchandisers have different concerns on the comments section. Therefore, we wanted to compare the comment 
section of three different products.

## Progress of the Project: 

- [x] Identify the products to be used in analysis
- [x] Implement a web scraper to obtain the comments from the website 
- [x] Clean and format the data, save and store in Excel files 
- [ ] Implement a Django Rest Framework API and post the data 
- [ ] Analyze the data 

1. Products Used in Analysis:


2. Codes Implemented for Web Scraping: 
   1. Utilized Selenium and BeautifulSoup 
   
    ``` 
     browser = webdriver.Chrome(ChromeDriverManager().install())
     browser.maximize_window()
     browser.get(url)
    ```
   
   ```
   time.sleep(10)
    while i < loop:
        browser.execute_script("window.scrollBy(0, 700);")
        time.sleep(0.8)
        i += 1
        django_logger.debug(f' Loop number: {i}')

    html = browser.page_source
    soup = BeautifulSoup(html, 'lxml')
   ```
## Complications and Problems:


## Next Steps: