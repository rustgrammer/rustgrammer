```javascript
const info = {
  name: "Muhammad Umer",
  age: 19,
  role: "Full stack developer",
  isCriticalThinker: true,
  isProblemSolver: true,
  skills: ["Javascript", "Django", "Figma", "Python", "CSS", "React"],
  status: "unemployed",
  canBeHired() {
    return status == "unemployed" ? true : false;
  },
};
```
