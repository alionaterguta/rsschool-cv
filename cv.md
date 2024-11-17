# Aliona Terguta

### Junior Web Developer

**Location:** Frankfurt, Germany
**Email:** aliona.terguta@yahoo.com
**Personal Website:** [Portfolio](https://alionaterguta.github.io/portfolio/)
**GitHub:** [GitHub](https://github.com/alionaterguta/)

---

## Profile

Junior Full-Stack Developer with hands-on experience in coding digital products. Detail-oriented with a creative mindset, skilled in creating functional, aesthetically pleasing, and responsive designs. Eager to contribute to the development of high-quality digital products.

---

## Skills

### Programming Languages
- HTML, CSS, SCSS, JavaScript, TypeScript, Node.js, Express.js

### Libraries & Frameworks
- React, Angular, React Bootstrap, Angular Material

### Databases & ORM
- MongoDB, Mongoose

### Tools & Platforms
- GitHub, Postman, Figma, Firebase, AWS Lambda, WordPress

---

## Projects

### [Cine-Verse](https://cine-verse-app.netlify.app)
_Web App with React_ (Feb. – Mar. 2024)
A single-page web app to explore information on movies, directors, and genres.
- Architected and developed the entire application using React for the frontend.
- Enhanced the application's aesthetics and user interface with React-Bootstrap.
- Built and integrated a REST API to manage data interactions.

---

### [MeetAPP](https://alionaterguta.github.io/meet/)
_Progressive Web App with React_ (Mar. – Apr. 2024)
MeetAPP offers offline access to upcoming events in specific cities.
- Developed a serverless backend hosted on AWS Lambda.
- Wrote scenarios for each of the app’s features using Gherkin syntax.
- Conducted unit, integration, and acceptance tests following a TDD approach.

---

## Code Example

**Lucky Numbers** - from [Exercism](https://exercism.org/): Calculate the sum for the numbers on the slot machine (Task 1).

```javascript
/**
 * Calculates the sum of the two input arrays.
 *
 * @param {number[]} array1
 * @param {number[]} array2
 * @returns {number} sum of the two arrays
 */
export function twoSum(array1, array2) {
  const sum = Number(array1.join("")) + Number(array2.join(""));
  return sum;
}
