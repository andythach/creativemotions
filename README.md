#Planning our application
1.	Answer Questions
a.	What are we building?
b.	Who are we building it for?
c.	What features do we need to have?
2.	User Stories
3.	Model out data
4.	Think through the pages we need in our app
#Questions
1.	What are we building? We are building a personal site. A place where we can blog, share examples of our work, and have people contact us.
2.	Who are we building it for? We are building it for ourselves, but also the community. Sharing what we are learning by blogging is a great way to learn for ourselves, but we teach others in the process. Show potential employers that we know what we are doing.
3.	What features do we want to have?
a.	Posts
i.	Create / Edit / Destroy
ii.	Markdown
iii.	Syntax highlighting
iv.	Comments (Disqus)
b.	Projects
i.	Create / Edit / Destroy
c.	Contact
i.	Contact form
ii.	Sendgrid
d.	User (Devise)
#User stories
As a black, I want to be able to blank, so that blank.
	As a user, I want to be able to create posts so that I can share what I am learning on my blog.
	As a user, I want to be able to edit & destroy posts, so that I can manage my blog.
As a user, I want to be able to write posts in markdown format so that it’s easy for me to writes posts.
As a user, I want to be able to highlight the various syntax of code blocks that I share on my blog.
As a user, I want to show the visitors and potential employers examples of my work, or stuff I’ve built.
As a user, I want to be able to have visitors contact me through a form on my site.
As a user, I want visitors to be able to leave comments on my posts.
 
# Modeling our data
	Post
		Title:string
		Content:string
	Project
		Title:string
		Description:text
		Link:string
	User
# Think through the pages we need in our app
	Home
	Posts#index
Posts#show
	Projects#index
	Project#show
	Contact


