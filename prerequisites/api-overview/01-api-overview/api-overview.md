## What is an API?

API stands for **Application Programming Interface**.

In simple words, an API is an interface that helps different applications or systems communicate with each other.

Through an API, one application can request data or services from another application without understanding its internal working.

APIs help automate tasks, integrate multiple systems, and allow applications to exchange information in a smooth and efficient way.

---

## Understanding the Term API

| Letter | Word        | Meaning                                                              |
| ------ | ----------- | -------------------------------------------------------------------- |
| A      | Application | Software or system designed to perform specific tasks                |
| P      | Programming | The logic or code that enables applications to perform operations    |
| I      | Interface   | A communication bridge where applications interact and exchange data |

## How API Works?

In an API transaction, three main steps happen:

1. A request is sent to perform an operation.
2. The program processes the request.
3. The program sends back a response.

---

### Example

When we search **SAP CPI** on Google or any search engine, we are actually sending a request to Google. Google then processes that request, runs its program, and sends back the search results as a response.

Now the question is — **Where is the program that we are calling?**

The answer is in the **URL**.

Example: https://www.google.com/search?q=SAP%20CPI

---

### Understanding the URL

This URL contains different parts:

- `www.google.com` → The server or application where the request is sent
- `/search` → The operation or service we want to perform
- `?q=SAP CPI` → The parameter sent with the request

Here, the parameter `q` represents the search query, and the value `SAP CPI` tells Google what we want to search for.

---

This is how APIs work behind the scenes. A request is sent using a URL, the application processes it, and a response is returned to the user.

## What Makes API the Hero? 🦸‍♂️

APIs play a very important role in modern application development and system integration. They make development faster, simpler, and more flexible.

Here are some reasons why APIs are considered the hero:

1. You don’t have to write the full program — you can simply use existing services through APIs.

2. APIs are platform independent. You can call an API from different platforms such as web applications, mobile apps, or other systems.

3. APIs are easy to upgrade and expand, which helps increase functionality and future scope.

4. APIs help different systems communicate with each other smoothly.

5. APIs save development time because developers can reuse existing services instead of building everything from scratch.

6. APIs help automate processes and reduce manual work.

7. APIs provide secure data exchange using authentication and authorization mechanisms.

## Types of APIs

APIs can be classified in different ways based on **how they communicate** and **how they are designed**.  
Understanding this classification helps avoid confusion and makes it easier to choose the right API approach while building integrations.

Broadly, APIs can be grouped into two main categories:

1. API Protocols
2. API Architectural Styles

---

## API Protocols

API protocols define **how data is transmitted** between applications.  
They focus on communication rules, message formats, and transport mechanisms.

Common API protocols include:

- **HTTP / HTTPS**  
  Used for web-based communication and data exchange between systems.

- **SOAP**  
  A protocol that uses structured XML messages and strict communication standards.

- **OData**  
  A standardized protocol built on HTTP that is widely used in enterprise and SAP systems for data access.

---

## API Architectural Styles

API architectural styles define **how APIs are designed and structured**.  
They focus on how requests and responses are organized and how operations are performed.

Common API styles include:

- **REST (Representational State Transfer)**  
  A lightweight and widely used architectural style that works on top of HTTP.

- **GraphQL**  
  A flexible query-based API style that allows clients to request exactly the data they need.

---

## Important Note

REST APIs usually **use HTTP or HTTPS protocols** for communication.  
SOAP APIs come with their **own protocol and strict message structure**.  
OData APIs are built on **HTTP and REST principles**, with additional standards for querying data.

---

### In a Nutshell

- **Protocols** define _how communication happens_.
- **Architectural styles** define _how APIs are designed_.

Both are important to understand when working with APIs and integration platforms like SAP CPI.
