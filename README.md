# 0x0B. Implement a design with bootstrap
## Details
 By: Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School Weight: 3Project over - took place fromJan 8, 2023 12:00 AMto Jan 16, 2023 12:00 AMManual QA review was done by onJan 26, 2023 3:16 AM#### In a nutshell…
* Manual QA review:          0.0/366 mandatory      
* Altogether:         0.0%* Mandatory: 0.0%
* Optional: no optional tasks

In this project, you will implement 3 web pages with Bootstrap.You will use all HTML/CSS/Accessibility/Responsive design/Bootstrap knowledges that you learned previously. 
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have fully functional web pages that look the same as the designer file.
Here the final result:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/3c71cc99d2fc1c12a3d3.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1b800a9634562062aa86ea4593f12255c9c451c63121e98d93954f43e317ce75) 

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/623/Archive.zip) 

### Requirements
* You have to use Bootstrap
* Your  ` styles.css `  must be as small as you can - you must use as much as you can Bootstrap classes
### Imports
For this project, you will need: fonts from Google, JQuery, Bootstrap CSS/JS
```bash
<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Coiny&display=swap" rel="stylesheet">

<script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

```
## Tasks
### 0. Read and be familiar with Figma
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create an account in  [Figma](https://intranet.hbtn.io/rltoken/0OS4ME4Kjnw0I82IVkkoSw) 
  and open these files:
* [Homepage](https://intranet.hbtn.io/rltoken/ffh_BUBdjRAoU6BNqtck0g) 
 - [fig file](https://intranet.hbtn.io/rltoken/1ZTxYF-usvxpIjj44YYcyw) 

* [Pricing](https://intranet.hbtn.io/rltoken/02VGWn3xysq05XbGLiR44g) 
 - [fig file](https://intranet.hbtn.io/rltoken/AdJ6ZyZrG90gRNAI5bt_lA) 

* [Courses](https://intranet.hbtn.io/rltoken/5eo9AKurCwVfj1-Hb8m59g) 
 - [fig file](https://intranet.hbtn.io/rltoken/1JL-gCkfJ5Hqb0Sf2lmymw) 

And “Duplicate to your Drafts” to have access to all design details.
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b2f4bd0a0299bfa813327b12afe536a496848ab0c2c6fe6ab3e3cbb492860a07) 

Important notes with Figma:
* if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/4uQkoVbAjr7lRVqSVCWBcw) 
 and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/5HnXzrMbtVKLCScrdy4CIg) 

* some values are in float - feel free to round them
* “Be pixel perfect” - yes! but mainly make sure colors, size and position are correct. #C271FF is not purple.
For this task, please write an amazing   ` README.md ` 
Interactions note:
* Web pages must switch to the tablet version when the screen width is 768px
* Web pages must switch to the mobile version when the screen width is 576px
* button hover/active:  ` opacity: 0.9 ` 
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` README.md ` 
 Self-paced manual review  Panel footer - Controls 
### 1. Header first
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Let’s start by the Homepage:  create the header/hero piece
Here an archive of all assets needed (for the entire project):
* [images_images.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/e62e701b6ce0374555e9.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=b4fc1e531e4c6c11ce349b40d82f98bbdcd1c2cd2f86cf37eb2ed6dd725c7359) 

* [holberton_school-icon.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=394ca74dfde3841b47e310b5b6dccb69ffa742a98e4b3e2deca46a0c615f45b2) 

Desktop:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/4/13572c3773e26651761e8b4a74b3383300ed9563.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=73c780020e512520eed721792b5a14f6ad86d2c83959dd80958201408661a77c) 

Mobile:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/8854d68a957ef7dc2315.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=758f925fd9f81e698873eda2be9102d6af71422dcfb7af2e5b5c8562aae26b92) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 0-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 2. Carousel of quotes
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create the section “Carousel of quotes”
By using a Carousel component of Bootstrap, create this Carousel of quotes. 
You can have for the moment one quote or twice the same for testing (like example below)
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/8455560f9ac188658195.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=bf00d1f9960b406c38c878bd9876b3f453a8dd5e89cbc69785b955fd9cc9a7a0) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 1-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 3. Popular videos
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create the section “Most popular tutorials”
By using a Carousel component of Bootstrap, create this Carousel of video cards. 
Reminder:
* Desktop: 4 cards
* Tablet: 2 cards
* Mobile: 1 card
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/4b610dc2d2cc17ceb2f7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=775d8e0e6823c2829de2e90831cf3de43679351d7dbc337008f4664892717b93) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 2-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 4. Row of smiles
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create the section “Free membership”
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/970efd54768b693bbfac.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8b7c731c3a465575ed42e6d81dd80e32d91ef313a462e8d818e63cac18967382) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 3-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 5. Latest videos
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create the section “Latest videos”
Copy the block “Most popular tutorials” to “Latest videos”
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 4-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 6. ... and the footer!
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create the footer
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/739d7cc60098e7ff8f25.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192527Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a1542701455fa315e7f25b8985043755819bb4464157a8dcd9dac3d7971495f6) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 7. Pricing - header
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Now, let’s do the pricing page:  create the header/hero piece
The mobile version must be the same as the Homepage - it’s time to reuse code!
Desktop:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/ccd30a4d80a990b96740.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2b4438ec98b093a0c9dd659df9d7dae799eb3d92aeb0839d2336e7d1256b50ca) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 0-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 8. Prices grid
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create the prices grid
Desktop:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/0ac3872946a0014e4f99.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=29bd2166e0e502daf58968f0573d0999a6408607eaf5c41b03c7592e686a5642) 

Mobile:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/edea8172b9cc0a867237.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c20c617d71aeb06c5699873bc2552d8f86128358d63cd659ffecf20bc55b6975) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 1-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 9. Quotes section
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Same as the Homepage,  create the Carousel of quotes
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 2-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 10. FAQ
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create the FAQ grid
Desktop:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/db8f90e37593a29c1ab6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5ad19ae71a98bc8963ff82953707a8eed8683fc8c7b7b0e39fa6791af815f605) 

Mobile:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/eaeb117d40690a451c7b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d0994f9962b710e37f16b104b049224d4ebdd4c5fc1300c376d0b1745b39bd8e) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 3-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 11. Close the page with a footer
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Same as Homepage,  create the footer
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 12. Courses - header
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Now, let’s do the courses page:  create the header/hero piece
The mobile version must be the same as the Homepage - it’s time to reuse code!
Desktop:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/a5ba265af5dd643ad942.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c4ad4c7573e79be76f572dfc18b26638a5ead04326f571c9295625edcd6bb2a7) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 0-courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 13. Search filters
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create the search filters section
Dropdown is a nice way to create filters.
For the selected/placeholder value of both dropdown, no need to have dynamic value - static content is totally ok.
Desktop:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/98c0564e59ec5620990e.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=25be90225dc0a3d6acad171448f37356a95db21cd21e26bccaa159945560ca6a) 

Tablet/Mobile:
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/3627550eccca7958d390.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=cd22a5eaf6f6cd94816e28016501e1b57563a21a734e6d0ebe86376892f448ec) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 1-courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 14. List of result
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Create the result section of courses
You can reuse the same cell for testing. Don’t forget to test with odd and even number of cells.
 ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/76b2074f3f6bbd25cdb9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230215%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230215T192528Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0a7cf5795f56d2c73ef44b67f353e4ac3fab3b19c20820b203a3b31f19db7646) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 2-courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 15. Close the page with a footer
          mandatory         Progress vs Score           Score: 0.00% (Checks completed: 0.00%)         Task Body Same as Homepage and Pricing page,  create the footer
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
Ready for a new manual review