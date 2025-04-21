# Assignment - 3 (JSON)

## Answer the short questions:

Here are the answers to your short questions:

1. **What does JSON stand for?**  
    **JSON** stands for **JavaScript Object Notation**.
   <br>
2. **What data types does JSON support?**  
    JSON supports the following data types:

   - String
   - Number
   - Boolean (true/false)
   - Null
   - Object
   - Array
     <br>

3. **What is a JSON object?**  
    A **JSON object** is an unordered collection of key-value pairs enclosed in curly braces `{}`. Each key is a string, and each value can be any valid JSON data type.
   <br>

4. **How are key-value pairs represented in JSON?**  
    Key-value pairs are written as:  
    `"key": value`  
    Keys must be strings in double quotes, and the value can be any JSON type.
   <br>

5. **What is a JSON array?**  
    A **JSON array** is an ordered list of values, enclosed in square brackets `[]`. The values can be of any JSON data type, including objects and arrays.
   <br>

6. **How do you represent an array of strings in JSON?**  
   An array of strings in JSON is written like this:
   ```json
   ["apple", "banana", "cherry"]
   ```

---

### Resources:

- [JSON Official Website](https://www.json.org/json-en.html)
- [MDN Web Docs - JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)

---

## Answer the long questions:

### **1. Explain the concept of JSON and its key features**

**Concept:**

- JSON (JavaScript Object Notation) is a lightweight data-interchange format.
- It is used primarily to transmit data between a server and a web application or between systems.
- JSON is based on a subset of JavaScript but is language-independent and supported by most modern programming languages.

**Key Features:**

1. **Lightweight and Fast:** JSON is compact and easy to parse, making data exchange faster.
2. **Human-readable:** Its syntax is simple and easy to understand, resembling JavaScript objects.
3. **Language-independent:** JSON can be used with nearly all modern programming languages.
4. **Structured Data Representation:** Supports hierarchical (nested) data using objects and arrays.
5. **Text Format:** Data is stored in a plain text format, which makes it easy to debug and transmit.
6. **Interoperable:** Used widely in web APIs and configuration files.

---

### **2. What are JSON arrays, and how are they represented in different types?**

**Definition:**

- A JSON array is an **ordered list of values** enclosed in square brackets `[]`.
- Values inside an array can be of any valid JSON data type (strings, numbers, objects, arrays, etc.).

**Representation in Different Types:**

1. **Array of Strings:**

   ```json
   ["red", "green", "blue"]
   ```

2. **Array of Numbers:**

   ```json
   [10, 20, 30, 40]
   ```

3. **Array of Booleans:**

   ```json
   [true, false, true]
   ```

4. **Array of Objects:**

   ```json
   [
   	{ "name": "Alice", "age": 25 },
   	{ "name": "Bob", "age": 30 }
   ]
   ```

5. **Array of Arrays:**

   ```json
   [
   	[1, 2],
   	[3, 4],
   	[5, 6]
   ]
   ```

6. **Mixed Type Array:**
   ```json
   ["text", 123, true, null, { "key": "value" }]
   ```

---

### **3. Compare JSON and XML in terms of syntax, readability, and performance**

| **Aspect**      | **JSON**                                        | **XML**                                        |
| --------------- | ----------------------------------------------- | ---------------------------------------------- |
| **Syntax**      | Lightweight, concise, JavaScript-like           | Verbose, uses opening and closing tags         |
| **Readability** | Easy to read and write for humans               | More complex and harder to read                |
| **Data Format** | Key-value pairs, arrays, and nested objects     | Tag-based structure with attributes and values |
| **Parsing**     | Fast and easy to parse                          | Slower and requires more resources             |
| **Data Size**   | Compact and smaller in size                     | Larger due to extra tags                       |
| **Support**     | Widely used in web APIs and mobile apps         | Common in enterprise systems and old services  |
| **Schema**      | No built-in schema, but JSON Schema can be used | XML supports XSD for validation                |
| **Use Case**    | Best for web services (REST APIs)               | Still used in some legacy systems (SOAP APIs)  |

---

### Resources:

- [JSON.org](https://www.json.org/json-en.html)
- [MDN - JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)
- [W3Schools - JSON vs XML](https://www.w3schools.com/js/js_json_xml.asp)

---

<p align="right"><strong>- Aarsh Patel</strong></p>
