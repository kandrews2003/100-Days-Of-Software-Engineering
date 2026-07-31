## Notes

Today was focused on understanding how React renders data dynamically and how modern frontend applications organize reusable code. One of the biggest concepts I learned was that data and UI should remain separate. Instead of creating multiple HTML elements manually, React allows components to generate the interface from structured data using methods like `.map()`. This makes applications significantly easier to maintain because adding new data automatically updates the interface without changing the component itself.

I also learned more about React Router's file-based routing and how pages are organized within a project. Rather than having one large application file, each route represents a specific page, making navigation and project structure much cleaner as an application grows.

Another important lesson was becoming more familiar with TypeScript. Instead of treating data as generic JavaScript objects, TypeScript uses interfaces to define exactly what information each object should contain. In this project, each resume object contains structured information such as company name, job title, resume location, image path, and AI feedback scores. This improves code readability, catches mistakes earlier, and makes the project easier to scale.

I gained a better understanding of React list rendering by using the `.map()` function to dynamically display resume information. I also learned why every rendered element should have a unique `key` prop. While it may seem like a small detail, React relies on keys to efficiently identify and update elements during re-renders.

Finally, I learned more about debugging. Compiler errors can initially appear intimidating, but today's experience reinforced that error messages often point directly toward the problem when read carefully. Taking the time to understand what the compiler is communicating is often faster than randomly changing code.
