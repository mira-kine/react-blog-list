- blog card information will be received from supabase

* need blogs.js in services directory

  - exports `getBlogs` function which calls supabase
  - similar to getRestaurants function in demo

* App.js
  - need to add `blogs` state
  - need useEffect to call `getBlogs` when the page initially renders
  - console.log to make sure my supabase call is working
  - once supabase call is working, loop through the `blogs` state variable and render a `<BlogCard>` component for each item in blogs (like what we did last week to render)
