# javascript-30

> This vanilla JavaScript course was created by [Wes Bos](https://github.com/wesbos).  
> Sign up at [JavaScript30](https://javascript30.com/account).

<h1 align="center">
  <img src="https://javascript30.com/images/JS3-social-share.png" style="max-width:100%" alt="JavaScript30" />
</h1>

Greetings!

This repository tracks my progress and lessons learned on the JavaScript 30 Day challenge by Wes Bos.

---

## **Project Logs**

### **Project 1: JavaScript Drum Kit**

**Completed:** 04/06/20

**Lessons Learned/Notes:**

- querySelector / querySelectorAll are ancestors of jQuery basics
- keydown/keyup are handy event listeners
- The tutorial solution:
  - showcases how to listen for targeted transitions, and
  - explains how to restart sound clip immediately

### **Project 2: JS and CSS Clock**

**Completed:** 04/07/20

**Lessons Learned/Notes:**

- Fun ways to manipulate elements with CSS:
  - transform & transition properties
  - animation with cubic-bezier function
- Pulling data from Date class

### **Project 3: CSS Variables**

**Completed:** 04/08/20

**Lessons Learned/Notes:**

- document.querySelectorAll returns NodeList (looks like array), doesn't include all Array methods, but includes native forEach()
- `dataset` object contains all data of an element with `data-` in attribute name
- When using CSS variable, you can update that variable on any element/selector that references the variable
- Same cascade rules of CCS apply (variables can be scoped/nested for greater precedence)

### **Project 4: Array Cardio Day 1**

**Completed:** 04/09/20

**Lessons Learned/Notes:**

- Note that sort() mutates the array and does NOT return a shallow copy. After sorting the array `inventors` twice, I kept getting false negatives in my console logs (I.e., result of 5 (Sort the inventors by years lived) kept overriding result of 3 (Sort the inventors by birthdate)). For exercise 5, I sorted a shallow copy of `inventors` to showcase that both sorting functions log the correct results to the console.

### **Project 5: Flex Panel Gallery**

**Completed:** 04/09/20

**Lessons Learned/Notes:**

- For additional practice on flexbox, see Wes's course [What the Flexbox?](https://flexbox.io/)
- An element in CSS can be both a flex item and a flex container
- CSS Flex property makes it easy to position and size elements relative to sibling, children, and parent elements

### **Project 6: Type Ahead**

**Completed:** 04/10/20

**Lessons Learned/Notes:**

- `fetch` used for API calls, easy GET requests, promisified
- Regular expressions can be used to modify data, and not just confirm patterns in data

### **Project 7: Array Cardio Day 2**

**Completed:** 04/11/20

**Lessons Learned/Notes:**

- `find` and `findIndex` methods only return the _first match_, subsequent matches are not returned.

### **Project 8: Fun with HTML5 Canvas**

**Completed:** 04/12/20

**Lessons Learned/Notes:**

- You don't draw on HTML `canvas` element, you draw on context
- Content `ctx` properties `lineJoin` and `lineCap` have value `round` to round out digit paintbrush
- Drawing in Canvas - need a starting and ending 'x' and 'y'
- HSL reference: [Mother-Effing HSL](https://mothereffinghsl.com/)
- HSL:
  - Color representation
  - Hue, Saturation, Lightness
  - Hue (color), red to red
  - Saturation (brightness)
  - Lightness (white to black)
  - Representation of rainbow pallette w/ all colors and shades, which we can programmatically select, and return to red

### **Project 9: Dev Tools Domination**

**Completed:** 04/15/20

**Lessons Learned/Notes:**

- Interpolated isn't much needed as template literals can be used instead
- Can add all the CSS you want to a console log
- Console.assert for testing, only logs when an assertion is false
- Console.group saves real estate in console.logs
- Can re-size and sort tables produced by console.table

### **Project 10: Hold Shift and Check Checkboxes**

**Completed:** 05/05/20
**Lessons Learned/Notes:**

- Check shift key's use on the event object
- Store references to the previous checked box and the currently checked box (previous `this` and current `this`) - check all elements between
- NOTE: handleCheck function _cannot_ be an arrow function. It is not a method within a class and thus does not receive context of a parent object. The context it receives is the global window object.

### **Project 11: Custom Video Player**

**Completed:** 05/07/20
**Lessons Learned/Notes:**

- Discover names and events of `video` element by console-logging properties, titles are often intuitively names
- `mousedown`, `mousemove`, `mouseup` are handy event listeners
- `mousemove` event - using short-circuiting in `&&` statement to decide whether to dispatch event
