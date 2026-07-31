# Day 3 - Dynamic Rendering with React and TypeScript

## Objective

Continue building my AI Resume Analyzer while learning how professional React applications render dynamic data and organize reusable components.

---

# What I Built

Today I expanded the frontend of the Resume Analyzer by displaying resume information dynamically instead of hardcoding UI elements.

Current progress includes:

- Created a reusable Navbar component
- Rendered resume data from a constants file
- Connected React components with mock resume data
- Built the homepage structure
- Configured route metadata
- Continued styling with Tailwind CSS

---

# Concepts Learned

## React Components

React components allow sections of an application to be reused throughout the project.

Example:

```tsx
import Navbar from "~/components/navbar";
```

Instead of repeating navigation code, it is imported wherever needed.

---

## Rendering Arrays

Instead of manually creating each resume card, React's `.map()` method renders every resume object automatically.

```tsx
{resumes.map((resume) => (
    <div key={resume.id}>
        <h1>{resume.jobTitle}</h1>
    </div>
))}
```

This creates scalable applications because adding another object automatically updates the UI.

---

## React Keys

Every element rendered from an array needs a unique key.

```tsx
key={resume.id}
```

React uses these keys to efficiently update the DOM.

---

## TypeScript

Worked with typed Resume objects that include:

- Company Name
- Job Title
- Resume File
- Resume Image
- AI Feedback
- ATS Scores

Using interfaces makes the application safer and easier to maintain.

---

## React Router v7

Continued learning file-based routing.

Configured page metadata.

```tsx
export function meta() {
    return [
        { title: "Resulytic" }
    ];
}
```

---

## Debugging Experience

Today I solved multiple issues including:

- Missing imports
- JSX syntax errors
- Parser errors
- Understanding VS Code Inlay Hints
- Rendering arrays correctly
- Using React keys properly

One important lesson was understanding that editor hints are not actual code.

---

# Technologies Used

- React
- React Router v7
- TypeScript
- Tailwind CSS
- Vite
- Git
- GitHub

---

# Wins

✅ Better understanding of React rendering

✅ More comfortable reading compiler errors

✅ Improved TypeScript knowledge

✅ Continued building a production-level project
