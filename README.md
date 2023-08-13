# **Book-Recommendation-system**
---
## ***Project Type : Unsupervised Machine Learning***
---

## ***Project summary :***
---

### During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys. In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries). Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create recommendation system for users.

## ***Data Description :***
---

### The Book-Crossing dataset comprises of 3 files.
### ***1. Users :***
### Contains the users. The user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.
### ***2. Books :***
### Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book_Title, Book_Author, Year_Of_Publication, Publisher), obtained from Amazon Web Services. In the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image_URL_S, Image_URL_M, Image_URL_L), i.e., small, medium, large. These URLs point to the Amazon website.
### ***3. Ratings :***
### Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

## **Data Description of each column in our dataset:**
---

1. **User_ID** ⇒ Unique anonymized Id for each user.
2. **Age** ⇒ Age of the user.
3. **Location** ⇒ Location of the user.
4. **ISBN** ⇒ The International Standard Book Number (ISBN) is a 13-digit number that uniquely identifies books and book-like products published internationally.
5. **Book_Title** ⇒ Title of the book.
6. **Book_Author** ⇒ Name of the Author of the book.
7. **Year_Of_Publication** ⇒ Year, the book got published.
8. **Publisher** ⇒ Name of the Publisher
9. **Book_Rating** ⇒ Ratings that the book got.
10. **Image_URL_S** ⇒ Link for the image(small) of the book.
11. **Image_URL_M** ⇒ Link for the image(medium) of the book.
12. **Image_URL_L** ⇒ Link for the image(large) of the book.
