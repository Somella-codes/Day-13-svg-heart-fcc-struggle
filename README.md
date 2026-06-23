# Day-13-svg-heart-fcc-struggle

**Challenge:** Draw a heart using SVG `path` element.

**What happened:**
- Wrote the exact code FCC provided
- Error: "You should have a `d` attribute on your path element"
- Reality: The `d` attribute was there the whole time

**The real bug:** 
FCC’s test is strict about 3 things:
1. No line breaks inside `d="..."`
2. No `xmlns` attribute on `<svg>`
3. `fill="red"` must be on `<path>` not `<svg>`

## Failed Attempt Screenshot
This is what FCC kept showing me:
![FCC Error Screenshot](Screenshot_20260623_193243_Samsung%20Internet.jpg)
![FCC Error Screenshot]()

**Lesson learned:** 
Coding is 20% writing logic, 80% debugging invisible syntax.

Computers don’t care about effort. They care about precision.


#LearnToCode #WebDev
