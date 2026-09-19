MUZAMILFIAZ.SITE - BLOG SYSTEM ADD-ON

IMPORTANT:
This package is designed to be added to your existing website.
It does NOT replace or modify your existing index.html, styles.css, app.js, images, or other files.

FILES:
- blog.html       Main blog listing page
- blogs.js        Blog list/database
- blog-style.css  Blog-specific styling
- blogs/          Individual articles
- images/         Put blog images here

HOW TO ADD THIS:
1. Upload blog.html, blogs.js and blog-style.css to your website root.
2. Upload the blogs folder and its HTML files.
3. Upload the images folder.
4. Add a link to blog.html from your existing navigation if you want:
   <a href="blog.html">Blog</a>

HOW TO ADD A NEW BLOG:
1. Create blogs/my-new-blog.html using the included template.
2. Add the article image to images/my-new-blog.jpg (optional).
3. Add one object to blogs.js:
   {
     title: "My New Blog",
     date: "20 September 2026",
     category: "Personal",
     image: "images/my-new-blog.jpg",
     description: "Short description.",
     link: "blogs/my-new-blog.html"
   }

Do not delete your existing website files.
