```javascript
const info = {
  name: "Muhammad Umer",
  age: 19,
  role: "Full stack developer",
  isCriticalThinker: true,
  isProblemSolver: true,
  skills: ["Javascript", "Django", "Figma", "Python", "CSS", "React"],

  isHireable() {
    return (
      this.skills.length >= 5 && this.isProblemSolver && this.isCriticalThinker
    );
  },
};
```
