# API

## What is an API?

- API stands for - Application Programming Interface
- A set of protocols that allow different applications to communicate and exchange data.

## Why do we use it?

- API helps to integrate the existing functionality with a new application.
- Avoid code to be written from scratch
- Helps in sharing data

## How it works?

An API explains the `WHAT` part, and not the `HOW` part to the users of the API. What do I mean by this?

There is a famous analogy of a `Customer` visiting a restaurant and getting the food ordered from a `Waiter`. The `waiter` takes that request to a `Chef`. And when the food is ready, the `waiter` collects that order food from the `Chef` and delivered to the `Customer`.

Here waiter acts as an API, and the customer and Chef act as Client and Server respectively. The Customer can ask for customized food by asking the waiter but is not necessarily aware of the making of that dish. Similarly, when we request some resources from the server through a Client, the client can ask what it wants but is not aware of how the API works.

One more example, when you hit any keyword for a search on google.com. What exactly happens? `You and your pc` act as a `Client`, and the keyword that you hit, act as a GET request to the google server. And the results that is being displayed on the page act as a response. Here, you are only aware of WHAT part, means you're searching for something and get the result accordingly; but you don't neeed to know exactly how the search engine works.

<iframe frameborder="100" style="width:900px;height:200px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=#R7VnbbuM2EP0avxokdX%2BML9kWaIGgWaCPAS0xMhFZVCn6knx9h7rYEqnY3qzcFnADx5YOyRF5znBIjibOfHP4Jmmx%2Fl0kLJsQlBwmzmJCiItD%2BNbAewN4fg2kkic1hE7AM%2F9gNYhbdMsTVjZYDSkhMsWLPhiLPGex6mFUSrHvV3sVWdIDCpoyC3iOaWajf%2FJErWs09NAJ%2F4XxdN0%2BGaOmZEXjt1SKbd48Lxc5q0s2tDXTVC3XNBH7DuQsJ85cCqHqq81hzjLNap%2Bxx09Kj12WLFdXNWj7od7bYbMEWGhuq547s7XaZHCH4fI1E%2FuHnMNAuMhbjGfZXGRCVgYcvKKYwUhmpZLijXVKEPKXD9CVmd3Npuf64R2g6fQ3JjZMyXeoIFkGj971JaKN0umx3rHpk%2BDwCIIap3TcqG7S%2BCT2nb6JUmxlzJpWXeIMQ%2BDN5w0pKlOmLENw0RnPCap0GdaI1IZ3NNs2w7Y06wiU0HLNdEsEN%2Fs1V6wsaKzr7WGW2mqRMPCWg2q9Vn9QUuhBVMPyZvBBU4Rg8HM01WOeo4kHtedVAa5gYqDRIFqZMGtGnxgOqtZQPmAEGxgJjbrwcWY7JhWHyf0bXbHsSZS8ceCVUEpsoALNeKqBGHySyU6Lh6ZACU0fzNhCs7k5pDrqTd%2B2KyZzBjRPeawtzgr5a3WxoAU%2F5%2BvaPjuc9fbWawPcdzbcONv%2BFJe8oIbWnZDkh5%2FPj55DnvE%2B57L30bKo4%2B8rP2jXmxVMcniQZnEB1iBgs6cT1A0nFunHgIhMX9ZuzPP0u1Zh4QAAQUgHi%2FZ3wTcpDCbjK%2FimsQ4SLwmX0DOhR%2Fy4LZmclrt0HEkCp69IS0tHERxOPVuTdvn4GU38y5q0bppQRUtggLXR4LkfDTpajMGKiwxHtWnx0YCjjkBKNP5K5iMa4WAoNpJF4CP0b65kxFzJnOhrK5nj4fOGxlvJgst%2BezFMdxQcDtB2SOmJ1ziCoTRCs%2BUjGQjv9GMr2TSjRW28WgqZXO5YvSKONG%2BOAf04byJr3kT%2BbYJJeFmUNtJ2uB8KujFE%2Bhcqlb4Um2ILRJVw%2FcwkMPHyXezhG5PwAP%2FTIh8pEHuOuTb6FnXhQMgJR6AOe%2BPHnP%2Fy7tlrj3THTa9B4rUxx3WC84bGizmtO9zLuuC6Zjj3v6aRh80Fxr%2BZRsF9zaMAG4dHL%2FyaRj7G5w2NqFF4X%2FPINzVy3K9pFODgvKERNYqstfwP9teWlcrSDlZXdeEoZm6vNjxJdPOZZCX%2FoKvKFLLyA%2FqwTbcKtm5VQg9fswNroBG2A8Q3dlLI3g60VbrbAeJ%2F7iDXbgfapN4d0%2B%2BapxJkZypuRj%2B%2Be%2Fp9xzh%2F%2F5PeTwboLwuRl%2Bx%2B%2BG%2BJPO5r7fxHQG7Ev52puzv%2BXdc8V9j%2BfzP%2BPYt%2Fi%2FeL2Y3hlEZHJzM%2FsaIlj6eyyr%2BeSCUnVmv22xdYVSK1loboa54nNdse3AidYVWauuDs1usH5kP%2FvBgFlhp4KG8djZC3Ju7%2F08HaDPl2Wulm0%2BGKJPW9TQeP9MPTwHwg4cDyfHyz%2FAOCwO3pNXJ9lji9pXeWfwM%3D"></iframe>

## Types of APIs

API exchanges data based on cearly defined `protocols` and `architectures` - the rules, structures,and constraints that govern an API's operation.

There are 3 main categories of API `protocols` or `architectures`:

??? note " REST or RESTful API"

      - stands for REpresentational State Rransfer (REST)
        - is a way for two machines to transfer the state of a resource via representations
        - possibly multiple representations such as - json, html, and text etc.
      - this is the most popular API
      - 6 constraints followed by RESTful APIs

          1. client/server
              - Client is someone who is requesting resources and are not concerned with data storage
              - server is someone who holds the resources and are not concerned with the user interface or user state
          2. stateless
              - The server will not store anything about the latest HTTP request the client made
              - every request is treated as new
              - No session, no history
          3. Uniform Interface
             - A resource in the system should have only one logical URI, like naming conventions, link formats, or data format (XML or/and JSON)
             - Naming conventions Example:
                 - [x] good example: `/api/users`
                 - [ ] bad example: `/api?type=users`
          4. caching
             - caching of data and responses is of utmost importance wherever they are applicable/possible.
             - The webpage you are reading here is also a cached version of the HTML page.
             - Caching brings performance improvement for the client side
             - Caching can be implemented on the server or client side.
          5. Layered
             - architecture where you deploy the APIs on server A, and store data on server B and authenticate requests in Server C.
             - for example. A client cannot ordinarily tell whether it is connected directly to the end server or an intermediary along the way
          6. Code on Demand (optional)
             - Most of the time, you will be sending the static representations of resources in the form of XML or JSON
             - But when you need to, you are free to return executable code to support a part of your application, e.g., clients may call your API to get a UI widget rendering code

??? note " SOAP API"

      - simple object access protocol

??? note " RPC API"

      - remote procedural call
