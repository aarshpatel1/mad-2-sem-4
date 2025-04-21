# Assignment - 1 (jQuery)

### **Short Questions:**

1. **What is jQuery?**  
    jQuery is a fast, lightweight, and feature-rich JavaScript library designed to simplify HTML document traversal, event handling, animations, and AJAX interactions. It provides an easy-to-use API that works across multiple browsers.
   <br>
2. **What does the $ symbol represent in jQuery?**  
    The `$` symbol in jQuery is an alias for the `jQuery` function. It is used to select elements, manipulate the DOM, handle events, and perform AJAX operations.
   <br>
3. **What are jQuery selectors?**  
    jQuery selectors are used to find and select HTML elements based on their attributes, IDs, classes, types, and more. They simplify DOM traversal and manipulation.
   <br>
4. **What is the difference between \$("#id") and \$(".class")?**
   - `$("#id")`: Selects an element with a specific `id`. It returns a single element because IDs are unique.
   - `$(".class")`: Selects all elements that have the specified `class`. It returns multiple elements if more than one element has the class.
     <br>
5. **Which jQuery selector is used to select all form inputs?**  
   The `:input` selector is used to select all form inputs, including `<input>`, `<textarea>`, `<select>`, and `<button>` elements.

---

### **Long Questions:**

1. **Describe different types of jQuery selectors and their significance in DOM manipulation.**  
    jQuery provides various selectors for efficiently selecting and manipulating DOM elements:
   <br>

   - **Basic Selectors**:

     - `$("#id")` – Selects an element by ID
     - `$(".class")` – Selects elements by class
     - `$("element")` – Selects elements by tag name
       <br>

   - **Attribute Selectors**:

     - `$("[attribute]")` – Selects elements with the specified attribute
     - `$("[attribute='value']")` – Selects elements with a specific attribute value
       <br>

   - **Hierarchy Selectors**:
     - `$("parent child")` – Selects direct child elements
     - `$("parent > child")` – Selects immediate child elements
       <br>
   - **Filter Selectors**:
     - `:first`, `:last`, `:eq(index)`, `:odd`, `:even` – Filters elements based on position
       <br>
   - **Form Selectors**:
     - `:input`, `:text`, `:checkbox`, `:radio`, `:submit` – Selects form elements
       <br>

   These selectors are crucial for efficient DOM manipulation, event handling, and applying styles dynamically.
   <br>

2. **How does jQuery handle events? Explain various event handling methods with examples.**  
   jQuery provides multiple ways to handle events:

   - **Using `.on()`** (Recommended for dynamic elements)

     ```javascript
     $(document).on("click", "#buttonId", function () {
     	alert("Button clicked!");
     });
     ```

   - **Using `.click()`, `.hover()`, `.dblclick()`**
     ```javascript
     $("#buttonId").click(function () {
     	alert("Button Clicked!");
     });
     ```
   - **Using `.bind()` and `.live()`** (Deprecated, replaced by `.on()`)
   - **Event delegation** (for dynamically added elements)
     ```javascript
     $(document).on("click", ".dynamicClass", function () {
     	alert("Dynamically added element clicked!");
     });
     ```
     <br>

3. **What are jQuery effects and animations? Explain different types with examples.**  
   jQuery provides built-in effects and animations to enhance user interaction:
   - **Hide/Show**
     ```javascript
     $("#btn").click(function () {
     	$("#element").hide(1000); // Hides in 1 second
     });
     ```
   - **Fade Effects** (`fadeIn()`, `fadeOut()`, `fadeToggle()`, `fadeTo()`)
     ```javascript
     $("#btn").click(function () {
     	$("#element").fadeOut(500);
     });
     ```
   - **Slide Effects** (`slideUp()`, `slideDown()`, `slideToggle()`)
     ```javascript
     $("#btn").click(function () {
     	$("#element").slideToggle();
     });
     ```
   - **Animate** (Custom animations)
     ```javascript
     $("#btn").click(function () {
     	$("#box").animate({ left: "250px", opacity: "0.5" }, 1000);
     });
     ```

These effects improve UI interaction by making elements more visually appealing.

---

<p align="right"><strong>- Aarsh Patel</strong></p>
