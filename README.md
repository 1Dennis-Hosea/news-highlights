# [News Highlights Application](https://ppolle-news-highlights.herokuapp.com/)

## By Dennis Hosea

## Description

We have tis page where users are able to view to news headlines and sites eg bbc cnn etc.
with the proceedure provided you can see your page.
With the application, a user will be able to:



## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display news sources | **On page load** | List of various news sources is displayed per category |
| Display articles from a news source | **Click a news source** | Redirected to a page with a list of articles from the source |
| Display the preview of an article | **On page load** | Each article displays an image, title, description and publication date |
| Read an entire article | **Click an article** | Redirected to the news source's site to read the entire article |

### Prerequisites

have the following with you

* A computer running on either Windows, MacOS or Ubuntu operating system installed with the following:

```
-Python version 3.6
-Flask
-Pip
-virtualenv
-A text  Editor
```

## Getting Started

* Clone this repository to your local computer.
* Ensure you have python3.6 installed in your computer.
* From the terminal navigate to the cloned project folder.
* Create a virtual environment and access the folder via your virtual amchine.
* Visit https://newsapi.org/ and register for an API key.
* Create start.sh file and in it write the following lines:
```
 export NEWS_API_KEY='<Your-Api-Key>'
 python3.6 manage.py server
```
* Run ```chmod +x start.sh``` follwoed by ``` ./start.sh ``` while in the project folder to start the project.
* Once started, the project can be accessed on your localhost using the address: ``` localhost:5000 ```.
* 

## Technologies Used

* Python v3.6
* Boostrap
* Flask
