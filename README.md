# -IA-API-Data-Mashup



1. Project Description
(Commtech) This is a simple storefront that displays free games, with all data gathered via an API. There are filters to change the genre, platform and sort the information. A link to the game in question is also included. 

2. APIs Used
https://www.freetogame.com/api-doc

This API returns information on various free-to-play games. Including title, genre, platform, release date and a short description. It has no fees and is completely free to use.

3. Setup Instructions
To run properly this file needs to be launched while in localhost. Which can be done by running python -m http.server in the console, Python is required.  


4. Data Integration Explanation
Information is taken from the API, via a JavaScript fetch request.
This request runs through a proxy server in order to bypass CORS restrictions that prevent parsing of JSON files directly
from API links. Once passed, it is fed into the code which handles all the displaying of content. Including the filters. 


5. Known Limitations
Missing features:
The function can only render 30 pages at a time. Also, there is no pagination or infinite scroll. Making browsing difficult. 

API constraints:
The API does not discriminate truly free and freemium monetization models. 

Edge cases:
I did not identify any edge cases. 

6. AI Usage Disclosure

AI was utilized for the styling and bugfixing. I didn't have the time to do a proper manual implementation.

The parts I implemented myself are the API requests and data filtering, the more backend side of front-end programming. 
