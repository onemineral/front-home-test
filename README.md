Your task is to implement the included design (`design.fig`, a [Figma](https://www.figma.com/) file) and build it using any technology you are comfortable with and the [TV Maze API](https://www.tvmaze.com/api).

Use the [show index endpoint](https://www.tvmaze.com/api#show-index) to select three random shows from the first page and then query the episodes to show the first three in the image gallery, preselecting the first episode.

### What we're looking for

- **Make it interactive.** Users should be able to choose from the different episodes and see the details change (title, description, airdate, season number and episode number).
- **The implementation should be responsive.** We want our users to have a great experience across all their devices. We have provided the design for multiple breakpoints, please make sure the implementation matches the design at each point.
- **Build your components from scratch.** Don't use any existing javascript libraries for the image gallery (CSS frameworks/libraries can and are encouraged to be used, Tailwind is a plus).
- **Make custom components as general and reusable as possible.** Because we're looking to build a component library we would like to see your approach to designing a component API design. Don't spend a lot of time making it completely universal or bullet-proof.


### What we're not looking for
- **You don't need to go crazy in terms of componentization.** Extract components when it helps you maintain what would otherwise be annoying duplication, but don't break things apart needlessly. We just want to see that you can implement the design in a robust way with good HTML semantics, and that you can get all of the interactive pieces working properly. Aside from the custom interactive controls, build it as if it's literally a one-page website, not part of a bigger, more complex application where many of the components would be re-used. For example it's fine for the headline to be hard-coded into the template instead of imagining this as a page that could show any arbitrary product.
- **You don't need to write tests.** If they help you then sure go for it, but don't prioritize them over getting the requirements implemented.


### Nice to haves
- **Use typescript to build it.** We are heavy typescript users and it would be nice to see how you use it in this simple project.
- **Server side rendering.** You can try your hand at implementing this in a server side rendered manner. We would prefer you use [nextjs](https://nextjs.org/) if you do implement it this way, and if you decide to use tailwind together with nextjs we recommend taking a look at their examples https://github.com/vercel/next.js/tree/canary/examples/with-tailwindcss-emotion or https://github.com/vercel/next.js/tree/canary/examples/with-tailwindcss .
- **Loading progress.** Currently there would be two external api calls that might make the page janky when it loads the information. You could consider implementing a loading page to show progress to the user without affecting the layout (or use a skeleton loading approach).
