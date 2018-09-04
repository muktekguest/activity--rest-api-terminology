# REST API Terminology 

Fork and clone this repository. Then, push to github with all bad answers deleted and only the correct answers showing.

**1. What does it mean REST?**


**2. Who coined the REST term?**


**3. In which protocol REST is based?**


**4. What are the main building blocks of a REST Architecture?**


**5. Identifying a resource is easy; you know how to access it and you even know how to request for a specific format. Since REST is using HTTP protocol as a standing point, there are some actions related to resources: CRUD operations.**

Complete the below table:


|HTTP Verb|Proposed Action|
|---------|---------------|
|GET| Write it here. |
|POST| Write it here. |
|PUT| Write it here. |
|DELETE| Write it here. |

**6. Status Code**

Another interesting standard that REST can benefit from when based on HTTP is the usage of HTTP status codes.

+ What’s is a status code?

+ Explain with your own words, the meaning of next codes:

|Status Code|Description|
|-----------|-----------|
|404| Write it here. |
|200| Write it here. |
|500| Write it here. |

**7. Status Code are grouped in five sets.**

Write what are their meaning.

|Group|Description|
|-----|-----------|
|1XX| Write it here. |
|2XX| Write it here. |
|3XX| Write it here. |
|4XX| Write it here. |
|5XX| Write it here. |

**8. HTTP Status Codes and Their Related Interpretation**

There are the most common status codes in HTTP responses. Please, fill with the required description.

|Status Code|Meaning|
|-----------|-------|
|200| Write it here. |
|201| Write it here. |
|204| Write it here. |
|301| Write it here. |
|400| Write it here. |
|401| Write it here. |
|403| Write it here. |
|404| Write it here. |
|405| Write it here. |
|500| Write it here. |

###### [To see the full list of HTTP status codes and their meaning, please refer to the RFC of HTTP 1.1](http://tools.ietf.org/html/rfc7231#section-6)

**9. How are called the points of contact between all client apps and the API?**


**10. The following is a good example or bad example of a named access point? And why?**

_meant to list the books in a bookstore_

+ `GET /books/action1`

**11. Uniform Interface**

Easy-to-remember access points are important, but so is being consistent when defining them.

You have to “refactor” the next bad design of an API. **It’s not  a good practice to name the endpoints based on the actions taken instead of the resource handled.**

At a first glance, the might not seem that bad, but consider how poor the interface is going to become as new features and resources are added to the system. Each new addition to the system causes extra endpoints to the API’s interface.

To solve this problem, you can apply the REST style to the endpoints, and thanks to HTTP, you also have verbs to indicate actions.

|Old Style|REST Style|
|---------|----------|
|`/getAllBooks`| Write it here. |
|`/submitNewBook`| Write it here. |
|`/updateAuthor`| Write it here. |
|`/getBooksAuthors`| Write it here. |
|`/getNumberOfBooksOnStock`| Write it here. |
|`/addNewImageToBook`| Write it here. |
|`/getBooksImages`| Write it here. |
|`/addCoverImage`| Write it here. |
|`/listBookCovers`| Write it here. |

**12. What JSON does it mean?**

**13. Anatomy of a `REQUEST`**

Make a `curl` request to _GitHub API_

```sh
$ curl -X GET https://api.github.com
```

According to the responded request, answer what does it mean the next parts from the handler:

+ _`Content-Type`_. _Write it here_
+ _`Status`_. _Write it here_
+ _`Date`_. _Write it here_
+ _`Content-Length`_. _Write it here_


###### If response is not showing those parts, ask to google how to print them in console.

```sh
# Paste the response
```
