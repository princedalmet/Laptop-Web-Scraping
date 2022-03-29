
## Introduction

What is Web Scraping?

It is the automated procedure of extracting the large amount of data from websites. The data available on the websites which is unstructured can be converted to structured data using Web Scrapping.

There are different ways to scrape websites such as Online Services, APIs or writing your own code.



## Why is Web Scraping Used?

Why does someone have to collect large data from websites?
To know about this, let’s look at the applications of web scraping:

Price Comparison:
To collect data from online shopping websites and use it to compare the prices of products.

Email address gathering:
To use email as a medium for marketing, use web scraping to collect email ID and then send bulk emails.

Social Media Scraping:
To collect data from Social Media websites such as Twitter to find out what’s trending.

Research and Development:
To collect a large set of data (Statistics, General Information, Temperature, etc.) from websites, which are analyzed and used to carry out Surveys or for R&D.

Job listings:
Details regarding job openings, interviews are collected from different websites and then listed in one place so that it is easily accessible to the user.

How Do You Scrape Data From A Website?

When you run the code for web scraping, a request is sent to the URL that you have mentioned. As a response to the request, the server sends the data and allows you to read the HTML or XML page. The code then, parses the HTML or XML page, finds the data and extracts it.


## To extract data using web scraping with python

you need to follow these basic steps:

1) Find the URL that you want to scrape.

2) Inspecting the Page.

3) Find the data you want to extract.

4) Write the code.

5) Run the code and extract the data.

6) Store the data in the required format.

Now let us see how to extract data from the Flipkart website using Python.


## Libraries used for Web Scraping:

As we know, Python is has various applications and there are different libraries for different purposes. In our further demonstration, we will be using the following libraries:


1) BeautifulSoup:
Beautiful Soup is a Python package for parsing HTML and XML documents. It creates parse trees that is helpful to extract the data easily.

2) Pandas:
Pandas is a library used for data manipulation and analysis. It is used to extract the data and store it in the desired format.

url = "https://www.flipkart.com/search?q=best%20laptops%20under%2080000&otracker=search&otracker1=search&marketplace=FLIPKART&as-show=on&as=off"


## Data Preparation

So, with this, we will get started with writing our own code for Laptops for gaming under 80000/- on Flipkart website

![1](https://user-images.githubusercontent.com/99526815/160583435-931a3e58-7751-40bf-800b-631e945a8123.PNG)

![11](https://user-images.githubusercontent.com/99526815/160583565-743ff7c9-371b-4434-a06c-d4e581cb3752.PNG)

Use urlopen to open the url and read the details in it.

![2](https://user-images.githubusercontent.com/99526815/160583613-88274185-d582-48be-acfe-d4746df67f97.PNG)

Get the Name of the produt:

![3](https://user-images.githubusercontent.com/99526815/160583662-b24e431d-3e50-4d13-a841-4d186d957aeb.PNG)

Get the Original Price of the product:

![4](https://user-images.githubusercontent.com/99526815/160583782-5711a8f2-0208-4791-98d4-8c7288594940.PNG)

Get the Discount Percentage on the product:

![5](https://user-images.githubusercontent.com/99526815/160583849-2aa1f7cb-4450-488c-9bc4-42e23d26417f.PNG)

Get the Discounted Price of the product:

![6](https://user-images.githubusercontent.com/99526815/160583890-995519ca-dc53-4b6a-ac46-d76a947c3397.PNG)

Get the Product Ratings:

![7](https://user-images.githubusercontent.com/99526815/160583938-6b346cdd-e703-40c4-9608-fb5b0bd23492.PNG)

Get the Number of Product Reviews:

![8](https://user-images.githubusercontent.com/99526815/160583965-2d3088a5-a801-438c-b456-8b952ae705e8.PNG)
![9](https://user-images.githubusercontent.com/99526815/160583978-200cc778-8c0c-494d-8097-5d935b73e33f.PNG)
![10](https://user-images.githubusercontent.com/99526815/160584017-fb8fb81f-080d-4cfa-80aa-d5c3dfb6cd92.PNG)


## Conclusion:

These are the first 5 laptops scrapped from the URL used.
