This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

This is a small project to create a page to display all recipes created by the 
Ingredients_service 

# Requirements 
Node version 16.0.0

#Local development 

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the main page. 


The app has just one view
The view has 3 main elements: 

Search input 
Ingredient button 
Recipes list 


The page loads an initial set of ingredients,
On page load, two main requests are done,
One for ingredients and one for recipes 
The initial set of ingredients is used when the search bar is empty
Otherwise a request is made to the backend for the filtered recipes 


