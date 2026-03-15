# XML Overview

## What is XML ?

**XML** → **e<span style="color:red">X</span>tensible <span style="color:red">M</span>arkup <span style="color:red">L</span>anguage**
XML is used to store and transport data in a structured format.  
It uses **tags (`<>`)** similar to HTML to organize and store information.

However, there is one important difference:

- **HTML is used to display data**
- **XML is used to store and exchange data**

XML was designed and standardized by the **W3C (World Wide Web Consortium)**, which is also responsible for maintaining HTML standards.

---

## Example

Suppose we are working with an **HRMS system**, and we need to send employee basic data in **XML format**.

```xml
<Employees>
    <employee>
        <name>Rounak</name>
        <userId>1234</userId>
        <dept>SAP</dept>
    </employee>

    <employee>
        <name>Rony</name>
        <userId>6789</userId>
        <dept>Java</dept>
    </employee>
</Employees>
```

In this example:

- `<Employees>` → Root element
- `<employee>` → Represents each employee record
- `<name>`, `<userId>`, `<dept>` → Store employee details

---

## XML Declaration

If we open an XML file in a browser, it usually shows an **XML declaration** at the top of the document.

Example:

```xml
<?xml version="1.0" encoding="UTF-8"?>
```

This line defines:

- XML version
- Character encoding used in the document

---

## Difference Between XML, XSLT, and XPath

XML, XSLT, and XPath are related technologies but they serve different purposes.

| Technology | Purpose             | What it Does                                                |
| ---------- | ------------------- | ----------------------------------------------------------- |
| XML        | Data Storage        | Stores structured data using tags                           |
| XPath      | Data Navigation     | Finds or selects specific elements inside an XML document   |
| XSLT       | Data Transformation | Converts XML into another format such as HTML, XML, or text |

---

## Example to Understand the Difference

### XML (Data Structure)

```xml
<employee>
    <name>Rounak</name>
    <dept>SAP</dept>
</employee>
```

XML stores the data in a structured format.

---

### XPath (Selecting Data)

XPath is used to **locate elements inside XML**.

Example XPath expression:

```
/employee/name
```

This expression selects the **name element** from the XML document.

---

### XSLT (Transforming Data)

XSLT is used to **transform XML data into another format**.

For example, converting XML data into a simple readable output.

Example transformation output:

```
Name : Rounak
Department : SAP
```

---

## Quick Understanding

| Technology | Think of it as                 |
| ---------- | ------------------------------ |
| XML        | The **data container**         |
| XPath      | The **tool to find data**      |
| XSLT       | The **tool to transform data** |

---

## Summary

- XML is used to store and exchange structured data.
- It uses tags to define elements and organize information.
- XPath is used to navigate through XML data.
- XSLT is used to transform XML data into another format.
- These technologies are widely used in **integration platforms such as SAP CPI**.
