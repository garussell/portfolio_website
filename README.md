# Portfolio Website
Deployment Link: [Allen Russell CV](https://portfolio-website-5ls8.onrender.com/)

# Lessons Learned
This is a funny project.  When I was a back-end student at Turing School for Software and Design, I created the MVP of this project during a "hackathon" challenge.  What is "funny" is that I created a Rails app and only used the views 😂

Over time this taught me some useful things.
1. Ruby and Ruby on Rails for Startups: Ruby on Rails is indeed known for its ability to enable rapid development, which can be particularly beneficial for startups that need to get a product to market quickly. The framework's convention-over-configuration philosophy allows for fast prototyping and deployment without the need for an extensive upfront plan.
2. Full Stack Framework: Rails is indeed a full-stack framework, which means it provides tools and libraries for handling both the front-end and back-end aspects of web development. The use of embedded Ruby (html.erb) syntax is a feature of Rails that allows for dynamic content generation within HTML templates.
3. Resource Overkill: Deploying a Rails application does require some resources, such as a database, but it's not necessarily "overkill" for a simple application. Rails' "magic" and MVC architecture can streamline development, but they also introduce complexity that might not be necessary for a very simple application.
4. Performance Overkill: While Rails does have some overhead due to its framework features, the impact on performance for a static page might not be significant. However, for more complex applications or under heavy load, the overhead can become more noticeable.
5. Scalability Overkill: Rails is designed to handle a wide range of traffic and can scale to support large applications. However, for a simple static page, the scalability features might not be utilized.
6. Complexity Overkill: The MVC architecture and embedded Ruby can indeed be overkill for a single static HTML page. However, the complexity can be justified if the application is expected to grow or if the developer prefers the structure and conventions provided by Rails.
7. Performance Comparison: The comparison of Ruby's performance to other languages like Java, Python, C++, Go, etc., is a valid point. While Rails might introduce some overhead, the difference in load times for a static page might not be noticeable unless the application is very large or the server is under heavy load.

"Choose the right tool for the right job."  In this case I think React would have been better.  That way I could separate each section ("About Me," "Projects," "Resume," "Tech Stack," "Coding Music," "Watch Me Drum," etc.) into individual React components.

That being said, the learning gained from this code challenge was straight forward, and if I wanted to make this a multipage application in the future the architecture support sit.  However there is one other lesson learned that is notable.  I copied many files from a bootstrap website that are also inert in this project.  In the future, I will strive to only import files I need for the project as it has become cluttered.  

I also did not know enough about how the local files would be used versus the imported files in the main `Application.html.erb` as well as with include tags in the `index.html.erb` file.  There was additional learning around utilizing the asset pipeline leading to discussions around how Ruby and JavaScript are interpreted, not compliled.  

## Overview
This is a personal portfolio website that showcases my software development credentials, projects, and skills. The website is designed to provide visitors with information about my work, skills, and projects, serving as a professional online presence for potential employers and collaborators.

## Features
- About Me: An introduction to who I am and my background in software development.

- Projects: A collection of my most notable projects, complete with descriptions, screenshots, and links to the project repositories.

- Skills: An overview of the programming languages, frameworks, and tools I am proficient in.

- Contact: A way for visitors to get in touch with me for potential collaboration or job opportunities.

## Built With
- Ruby on Rails: Backend framework for the website.

- HTML and CSS: Frontend design and structure.

- JavaScript: Enhancing user experience and interactivity.

- Bootstrap: Styling and responsive design.

## Credits
### Used bootstrap template designed by Xiaoying Riley [More Info](https://github.com/xriley/Developer-Theme)

## Author
### Allen Russell
[GitHub:](https://github.com/garussell) - @garussell
