# Assignment #5: JavaScript Basics (DOM Manipulation & Events)

**Student Name:** Yermek Tuzelkhan  
**Group:** IT-2513  
**GitHub Pages Link: https://ytuzelkhan.github.io/Assignment_5_web/** 

---

## Assignment Parts & Tasks

### Part 1: Profile Object, Data Types & Arithmetic
* **Task 1: Personal Info Object:** Created a `userProfile` constant object containing `string` (name), `number` (birthYear), `boolean` (isDeveloper), and an `array` (hobbies).
* **Task 2: Arithmetic Calculations:** Dynamically calculated the user's age using arithmetic operators (`currentYear - birthYear`), computed age in months (`age * 12`), and tracked total hobbies count. Outputted these values to both the page and the browser console.

#### Screenshot - Part 1
<img width="983" height="713" alt="изображение" src="https://github.com/user-attachments/assets/e1a2d7f9-3e11-4a39-884c-42273fb6a744" />


---

### Part 2: Form Input & Event Responses
* **Task 3: HTML Form Setup:** Built form input fields for Username and Birth Year with an update button.
* **Task 4: Event Listener:** Added a `submit` event listener to handle input values, prevent default form submission (`e.preventDefault()`), update the `userProfile` object properties, and refresh the DOM elements dynamically.

#### Screenshot - Part 2
<img width="1045" height="457" alt="изображение" src="https://github.com/user-attachments/assets/435df764-6ada-494c-b8c1-d383533d8301" />
<img width="1064" height="717" alt="изображение" src="https://github.com/user-attachments/assets/a1f80222-408d-4b1d-8a03-ba058e7211ad" />


---

### Part 3: DOM List Manipulation
* **Task 5: Creating & Removing Elements:** Created an unordered list (`<ul>`) displaying hobbies. Added an "Add" button that creates new `<li>` elements using `document.createElement()` and `appendChild()`, and a "Remove" button that deletes the last item using `removeChild()`.

#### Screenshot - Part 3
<img width="703" height="154" alt="изображение" src="https://github.com/user-attachments/assets/3c03bd9a-38a6-4c2f-adec-caa57a2832d5" />
<img width="1088" height="761" alt="изображение" src="https://github.com/user-attachments/assets/1b4d22b7-cb66-4780-aa15-5130c8bf5eb3" />
<img width="1121" height="494" alt="изображение" src="https://github.com/user-attachments/assets/bfd6a6dd-2bba-4257-bf97-fbb45e714250" />


---

## Summary of Work Process

1. **Markup Structure:** Created `index.html` divided into three sections corresponding to Parts 1, 2, and 3 of the assignment.
2. **Data Model:** Declared the initial `userProfile` object in JavaScript storing data types as required.
3. **Event & DOM Manipulation:** Implemented dynamic UI update functions (`updateUI()` and `renderHobbies()`) driven by form submission and click events.
4. **Testing & Deployment:** Tested input validation, age arithmetic, element creation/removal and console log. Pushed the project to a public GitHub repository and enabled GitHub Pages.
