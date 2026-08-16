
# Day 4 – RESULYTIC, AI Resume Analyzer 🚀

## Today's Goal
Continue building the Resume Card component for my AI Resume Analyzer (Resulytic) using React, TypeScript, and React Router.

## What I Worked On
- Built the `ResumeCard` component
- Worked on dynamic routing with React Router
- Passed resume data through component props
- Improved TypeScript interfaces for resume and feedback data
- Debugged component imports and routing

## Current Challenge 🐛
I'm currently stuck trying to display the `ResumeCard` component.

The main issue started with a TypeScript error stating that the module had **no default export**, which led me down a rabbit hole of debugging.

Along the way I discovered:
- A Git filename casing issue (`Navbar.tsx` vs `navbar.tsx`)
- TypeScript wasn't recognizing my `Resume` interface because it wasn't exported
- My React Router `Link` template string was written incorrectly
- I'm still working through why the component isn't rendering correctly

## What I Learned
Today's biggest lesson wasn't about writing code—it was about debugging.

I learned that:
- Git and macOS can have issues with filename casing.
- TypeScript errors can sometimes point to a symptom instead of the actual problem.
- Breaking problems into smaller pieces is much more effective than changing random code hoping it works.

## Next Steps
- Fix the ResumeCard rendering issue
- Display uploaded resumes on the dashboard
- Continue building the AI feedback UI
- Push through the bug instead of starting over

---
**Progress:** Day 3 / 100 ✅

Some days are spent building features.
Some days are spent learning how to debug like a software engineer.

Today was definitely the second one.
