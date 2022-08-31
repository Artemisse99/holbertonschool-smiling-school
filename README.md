# 0x0B. Implement a design with bootstrap
## Details
 By: Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School Weight: 3Ongoing second chance project - startedAug 21, 2022 12:00 AM, must end bySep 1, 2022 12:00 AMManual QA review must be done(request it when you are done with the project)In this project, you will implement 3 web pages with Bootstrap.You will use all HTML/CSS/Accessibility/Responsive design/Bootstrap knowledges that you learned previously. 
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have fully functional web pages that look the same as the designer file.
Here the final result:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3c71cc99d2fc1c12a3d3.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7e2cfefed6e89b815a5844776d3e70a697ba30a212a159796c47f7efcb9d5d7d) 

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
          mandatory         Progress vs Score  Task Body Create an account in  [Figma](https://intranet.hbtn.io/rltoken/0OS4ME4Kjnw0I82IVkkoSw) 
  and open these files:
* [Homepage](https://intranet.hbtn.io/rltoken/RLej4Ua6W3EmDh7UCwGTzQ) 
 - [fig file](https://intranet.hbtn.io/rltoken/1ZTxYF-usvxpIjj44YYcyw) 

* [Pricing](https://intranet.hbtn.io/rltoken/xQCL77_ePGWntUAe4T7ebQ) 
 - [fig file](https://intranet.hbtn.io/rltoken/AdJ6ZyZrG90gRNAI5bt_lA) 

* [Courses](https://intranet.hbtn.io/rltoken/__3w9ryapSUAwMaAYYS6ZA) 
 - [fig file](https://intranet.hbtn.io/rltoken/1JL-gCkfJ5Hqb0Sf2lmymw) 

And “Duplicate to your Drafts” to have access to all design details.
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ebb007df7537a51d984a403cbd78b72882267e2b10bd3f5d5119b6895a055928) 

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
          mandatory         Progress vs Score  Task Body Let’s start by the Homepage:  create the header/hero piece
Here an archive of all assets needed (for the entire project):
* [images_images.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/e62e701b6ce0374555e9.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=c5313f3237b2a6e0b9332d7ac6a28f894ccab3ee8d65ec5baf3e3b45c349c47d) 

* [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=ff0567294d4554802703b2555c2120a2c68facd7dca4b94f1ac6881184c0c780) 

Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/4/13572c3773e26651761e8b4a74b3383300ed9563.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=6fb6107e5616281163a68e41ad480e1590a2b95944ab70530ab42c4fd9d3a770) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/8854d68a957ef7dc2315.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c79684d4b0ac26081afd69a8e94a1707bbfc59b3265ade0b49f1f2098ed4266e) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 0-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 2. Carousel of quotes
          mandatory         Progress vs Score  Task Body Create the section “Carousel of quotes”
By using a Carousel component of Bootstrap, create this Carousel of quotes. 
You can have for the moment one quote or twice the same for testing (like example below)
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/8455560f9ac188658195.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=089f398166ea1d9719ce00115f52005d407f8b5b66e74f13c20cebff909efdff) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 1-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 3. Popular videos
          mandatory         Progress vs Score  Task Body Create the section “Most popular tutorials”
By using a Carousel component of Bootstrap, create this Carousel of video cards. 
Reminder:
* Desktop: 4 cards
* Tablet: 2 cards
* Mobile: 1 card
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/4b610dc2d2cc17ceb2f7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=70331bcfc7225e5d9b5a47f9c26396d1e83a11353ed43fe601b22f0b00cd2ab9) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 2-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 4. Row of smiles
          mandatory         Progress vs Score  Task Body Create the section “Free membership”
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/970efd54768b693bbfac.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3eb92a12c1a822b684a94b050a76588f02706c0b334ca0d51a156a89aa51632d) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 3-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 5. Latest videos
          mandatory         Progress vs Score  Task Body Create the section “Latest videos”
Copy the block “Most popular tutorials” to “Latest videos”
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 4-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 6. ... and the footer!
          mandatory         Progress vs Score  Task Body Create the footer
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/739d7cc60098e7ff8f25.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9362b33e41ad25febcc6f510a5d567c237cd1bc65cc123a05545e297254d9b56) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 7. Pricing - header
          mandatory         Progress vs Score  Task Body Now, let’s do the pricing page:  create the header/hero piece
The mobile version must be the same as the Homepage - it’s time to reuse code!
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/ccd30a4d80a990b96740.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=112d844fdb2ed05478aa912c0acb5ffd3827a001164721113e6e06f8cdeb876b) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 0-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 8. Prices grid
          mandatory         Progress vs Score  Task Body Create the prices grid
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/0ac3872946a0014e4f99.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9c8e708db7740b11c6c23e3d1336608a93fdcf1b5db21543d59e8fe40ad05ec1) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/edea8172b9cc0a867237.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=08fac90a9ed0ada2ceddda61cc87a324036931f335e5f1598092b3f954e2eca5) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 1-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 9. Quotes section
          mandatory         Progress vs Score  Task Body Same as the Homepage,  create the Carousel of quotes
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 2-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 10. FAQ
          mandatory         Progress vs Score  Task Body Create the FAQ grid
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/db8f90e37593a29c1ab6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=80b4b98e4fbdffb09f0934a37f0a5c21d9b705ac94d9073617a69ea862f3f198) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/eaeb117d40690a451c7b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ab85392d40f47f145a5ffd3de6435328c48c5ecf76fc6182702dba0228a5c76e) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 3-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 11. Close the page with a footer
          mandatory         Progress vs Score  Task Body Same as Homepage,  create the footer
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 12. Courses - header
          mandatory         Progress vs Score  Task Body Now, let’s do the courses page:  create the header/hero piece
The mobile version must be the same as the Homepage - it’s time to reuse code!
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/a5ba265af5dd643ad942.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c280b8487597b0bb59eacc5ed7344690a81e0ea683a42db17c8191435191afe5) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 0-courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 13. Search filters
          mandatory         Progress vs Score  Task Body Create the search filters section
Dropdown is a nice way to create filters.
For the selected/placeholder value of both dropdown, no need to have dynamic value - static content is totally ok.
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/98c0564e59ec5620990e.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=91f46d2615041f19330e8e02e17581cacfaefb12c3eaa03b59413a98c9f8cc9e) 

Tablet/Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3627550eccca7958d390.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=98b537cb5327bab882571e8e976e4f3fe18849c8314c94b92647cba13ae60ae5) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 1-courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 14. List of result
          mandatory         Progress vs Score  Task Body Create the result section of courses
You can reuse the same cell for testing. Don’t forget to test with odd and even number of cells.
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/76b2074f3f6bbd25cdb9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220831%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220831T150401Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2ed4858d4d52f5e8f2e21fb20f9c4b421d85a572971d042bd6861aa6844b27f2) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 2-courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 15. Close the page with a footer
          mandatory         Progress vs Score  Task Body Same as Homepage and Pricing page,  create the footer
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
Ready for a  manual review