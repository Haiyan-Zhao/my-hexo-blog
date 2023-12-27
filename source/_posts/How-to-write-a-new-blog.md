---
title: How to write a new blog
date: 2023-12-27 12:59:08
tags: study
---


To write a blog post on your Hexo blog, follow these steps:

1. Write Your Blog Post

a. Open Your Blog's Project: 
On your local machine, open the folder where your blog project is located. 

b. Create a New Post:

Use the command line to navigate to your blog's root directory and run the command to create a new post. For a Hexo blog, the command is:

![](/images/how-to-wirte-a-new-blog-images/command1.png)

Replace "Your Post Title" with the title of your blog post. This will create a new Markdown file in the source/_posts directory of your blog.

c. Edit the Post: Open the newly created Markdown file in your preferred text editor. Write your blog post using Markdown syntax. Save your changes once done.

2. Preview Your Post Locally

a. Start the Local Server: To preview your blog post locally, run the following command in your blog's root directory:

 ![](/images/how-to-wirte-a-new-blog-images/command1.png)

b. Open the Preview: Open a web browser and go to http://localhost:4000. You should see your blog with the new post.

3. Upload to GitHub

a. Stage Your Changes: In the terminal, use Git commands to stage your new blog post. Navigate to your blog's root directory and run 'git add .'

b. Commit Your Changes: Commit the staged changes with a message 'git commit -m "Add new blog post: Your Post Title"' (Replace "Your Post Title" with the actual title of your post)

c. Push to GitHub: Push your commit to your GitHub repository 'git push origin main'

4. Automatic Deployment to Netlify

a. Once your changes are pushed to GitHub, Netlify, which is connected to your GitHub repository, will automatically detect the changes.

b. Netlify will start building and deploying the new version of your blog, including your new post.

c. After the build process is complete, your updated blog will be live on your Netlify URL.