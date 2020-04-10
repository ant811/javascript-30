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

**Lessons Learned:** 
* querySelector / querySelectorAll are ancestors of jQuery basics
* keydown/keyup are handy event listeners
* The tutorial solution:
    * showcases how to listen for targeted transitions, and
    * explains how to restart sound clip immediately 

### **Project 2: JS and CSS Clock**
**Completed:** 04/07/20

**Lessons Learned:** 
* Fun ways to manipulate elements with CSS:
    * transform & transition properties 
    * animation with cubic-bezier function
* Pulling data from Date class

### **Project 3: CSS Variables**
**Completed:** 04/08/20

**Lessons Learned:** 
* document.querySelectorAll returns NodeList (looks like array), doesn't include all Array methods, but includes native forEach()
* `dataset` object contains all data of an element with `data-` in attribute name
* When using CSS variable, you can update that variable on any element/selector that references the variable
* Same cascade rules of CCS apply (variables can be scoped/nested for greater precedence)

### **Project 4: Array Cardio Day 1
**Completed:** 04/09/20

**Lessons Learned:** 
* Note that sort() mutates the array and does NOT return a shallow copy.  After sorting the array `inventors` twice, I kept getting false negatives in my console logs (I.e., result of 5 (Sort the inventors by years lived) kept overriding result of 3 (Sort the inventors by birthdate)).  For exercise 5, I sorted a shallow copy of `inventors` to showcase that both sorting functions log the correct results to the console.

### **Project 5: Flex Panel Gallery
**Completed:** 04/09/20

**Lessons Learned:** 
* For additional practice on flexbox, see Wes's course [What the Flexbox?](https://flexbox.io/)
* An element in CSS can be both a flex item and a flex container
* CSS Flex property makes it easy to position and size elements relative to sibling, children, and parent elements