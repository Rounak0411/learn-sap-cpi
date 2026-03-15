## What is JSON ?

JSON stands for **JavaScript Object Notation**.

JSON is a lightweight data format used to **store and exchange data between systems and applications**.  
It represents data using **key-value pairs**, which makes it simple to read and easy for machines to parse.

JSON is widely used in **modern APIs and web services** because it is lightweight compared to formats like XML.

JSON was originally derived from **JavaScript**, but today it is supported by almost all programming languages.

---

### Example

Suppose we are working with an **HRMS system**, and we need to send employee basic data in **JSON format**.

```json
{
  "Employees": [
    {
      "name": "Rounak",
      "userId": 1234,
      "dept": "SAP"
    },
    {
      "name": "Rony",
      "userId": 6789,
      "dept": "Java"
    }
  ]
}
```

In this example:

- `{ }` → Represents a JSON object
- `[ ]` → Represents an array or list
- `"name"`, `"userId"`, `"dept"` → Keys
- `"Rounak"`, `1234`, `"SAP"` → Values

---

### Note

Unlike XML, JSON **does not use tags**.  
Instead, it uses **key-value pairs** to represent data.

Because of its simple structure, JSON is **faster to parse and easier to work with in APIs**.

---

## Characteristics of JSON

| Feature              | Description                                |
| -------------------- | ------------------------------------------ |
| Lightweight          | JSON is smaller in size compared to XML    |
| Human Readable       | Easy for developers to read and understand |
| Language Independent | Supported by most programming languages    |
| API Friendly         | Widely used in REST APIs                   |

---

## Example Structure Breakdown

| Symbol | Meaning                 |
| ------ | ----------------------- |
| `{ }`  | JSON Object             |
| `[ ]`  | JSON Array              |
| `:`    | Separates key and value |
| `,`    | Separates data elements |

---

## Quick Understanding

| Technology | Think of it as                                         |
| ---------- | ------------------------------------------------------ |
| XML        | Structured data using tags                             |
| JSON       | Structured data using key-value pairs                  |
| APIs       | Systems exchanging data using formats like JSON or XML |

---

💡 **Tip:**  
In modern **REST APIs**, JSON is the most commonly used data format because it is lightweight, easy to parse, and works efficiently with web applications and integration platforms like **SAP CPI**.
