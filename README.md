# 0x09. Implement a design from scratch

### Concepts

_For this project, we expect you to look at this concept:_

- [Implement a design](https://intranet.hbtn.io/concepts/220)

In this project, you will implement from scratch, without any library, a web page. You will use all HTML/CSS/Accessibility/Responsive design knowledges that you learned previously.

You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have a fully functional web page that looks the same as the designer file.

Here the final result:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/2/60df485eb772ecbad54a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T152623Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=83fe3c60a3e8d6207033d35c5c68f74230baff569af1e443a637c3a6f645ce89)

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/622/Archive.zip 'here')

### Requirements

- you are not allowed to import external CSS framework (like Bootstrap)
- you are not to use Javascript

## Tasks

### 0. Read and be familiar with Figma

mandatory

Score: 0.00% (Checks completed: 0.00%)

Create an account in [Figma](https://intranet.hbtn.io/rltoken/eumOUW-eMS4X9ZDZg9KPLg 'Figma') and open this [project](https://intranet.hbtn.io/rltoken/2ED3P1a2wnbQqRLi8aXJKw 'project') and “Duplicate to your Drafts” to have access to all design details.

If you can’t access to it, please find here the [Figma file](https://intranet.hbtn.io/rltoken/NxsDNicWs5KSlsR94kt52A 'Figma file')

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T152623Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1197c7b5be9976df58fb2ebaf377157654d3cf9c902b1c46e6d1253a66ad4f24)

Important notes with Figma:

- if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/wltHny-KZP3B8JFRvpmVjA 'source-sans-pro') and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/Qb96K4nTPQJO1paP_OBELw 'Spin-Cycle-OT')
- some values are in float - feel free to round them

For this task, please write an amazing `README.md`

**Interactions note:**

- the web page must switch to the mobile version when the screen width is 480px or less
- links hover/active: `#FF6565`
- button hover/active: `opacity: 0.9`
- max width of the content: 1000px centered in the page

**Repo:**

- GitHub repository: `holbertonschool-headphones`
- File: `README.md`

Done? Help QA Review

### 1. Header

mandatory

Score: 0.00% (Checks completed: 0.00%)

Building a web page the right way, is not easy - expect if you put in place strong foundations:

- reset CSS styling
- use variables
- simple/“as generic as you can” CSS selectors
- avoid using super specific CSS selectors as much as possible
- simple HTML structure - `div` containers are your friend!

Last advice: Personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.

Now, your turn!

For this first task: **create the header/hero piece**

Here an archive of all assets needed: [images_0x09.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T152623Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=43833eb64c1ae767e12bb8963167d666bcd91b702260c157bddb821a5b476ef1 'images_0x09.zip')

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/4a93441c93989ad7ea72.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T152623Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=650d5ff3973ad377b52678d2dedc6c84877b294ed87bcb6d28d7dd9273400365)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/75a582f98640445a2dbf.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T152623Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f4fc4d2f0fa418c293e5c8123eff44ff91e203f2a77c8e638c1a0175f99c08a8)

**Repo:**

- GitHub repository: `holbertonschool-headphones`
- File: `0-index.html, 0-styles.css`

Done? Help QA Review

### 2. "What we do..." section

mandatory

Score: 0.00% (Checks completed: 0.00%)

Copy files from the previous task.

For this second task: **create the “What we do…” section**

In this section, you will need custom font icons. Here the archive of it: [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T152623Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=9f2fa8f4eb30389b78c563c3b21cb1b6b8ee27fe5f0c81065e1e69f294ee1137 'holberton_school-icon.zip') Inside you will find demo page of how to use it.

**Important:** try to build as generic as you can… you will probably need some components in next section.

**Repo:**

- GitHub repository: `holbertonschool-headphones`
- File: `1-index.html, 1-styles.css`

Done? Help QA Review

### 3. "Our results" section

mandatory

Score: 0.00% (Checks completed: 0.00%)

Copy files from the previous task.

For this third task: **create the “Our results” section**

Now you can reuse components form the previous task!

**Repo:**

- GitHub repository: `holbertonschool-headphones`
- File: `2-index.html, 2-styles.css`

Done? Help QA Review

### 4. Contact us

mandatory

Score: 0.00% (Checks completed: 0.00%)

Copy files from the previous task.

A good landing page has always a contact form.

You are free to add any animations and/or constraints on fields.

**Repo:**

- GitHub repository: `holbertonschool-headphones`
- File: `3-index.html, 3-styles.css`

Done? Help QA Review

### 5. Footer

mandatory

Score: 0.00% (Checks completed: 0.00%)

Copy files from the previous task.

Last piece of the page… the Footer!

When you are done, here the result:

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3b5a9f7948a58d58bd43.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T152623Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=960f13d17253ba5419493cd412252ccb7aa02d5cb57c077f2183776b9e287bb8)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/83d6311e87d4775ca4b3.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220718T152623Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a64db33c64fd27fde60a47d6efff31436b1d2555a5f5e974825231e028a06a94)

And you are done!

**Good job!**

**Repo:**

- GitHub repository: `holbertonschool-headphones`
- File: `4-index.html, 4-styles.css`

### 6. Replace background image with... code!

#advanced

Score: 0.00% (Checks completed: 0.00%)

In the section “Our results”; without the use of an image file, draw each pentagon using HTML and CSS.

**Repo:**

- GitHub repository: `holbertonschool-headphones`
- File: `100-index.html, 100-styles.css`

Done? Help QA Review

### 7. Let's animate items

#advanced

Score: 0.00% (Checks completed: 0.00%)

From `4-index.html` and `4-styles.css`, add fun animations to “What we do…” and “Our results” sections items row. Either all the time, either when hover.

Scaling, opacity, rotation, bouncing… many options!

**Repo:**

- GitHub repository: `holbertonschool-headphones`
- File: `101-index.html, 101-styles.css`

Done? Help QA Review

### 8. And SASS??

#advanced

Score: 0.00% (Checks completed: 0.00%)

Take your `101-styles.css` file and create a `102-styles.scss` that will be the SASS version of it.

```
$ sass 102-styles.scss > 101-styles.css
```
