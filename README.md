
Create Your Own Portfolio Website
Creating your own portfolio website is a great way to showcase your work, skills, and
accomplishments to potential clients or employers.
1. Define Your Purpose and Goals:
Before you begin building your portfolio website, decide what you want to showcase and
who your target audience is. Determine the primary purpose of your website, whether it's to
display your design projects, photography, writing samples, or any other professional work.
2. Choose a Domain Name:
Select a unique and memorable domain name that reflects your name or profession. You
can register a domain through various domain registrars, and it's a good idea to choose a .com
domain if possible.
3. Choose a Website Building Platform:
There are several platforms that can help you build a portfolio website easily, even if you
have little or no coding knowledge. Some popular options include:
- WordPress: Offers a lot of flexibility and customization options.
-Wix: A user-friendly drag-and-drop website builder.
- Squarespace: Known for its visually appealing templates and ease of use.
- Webflow: Allows for more advanced design and customization.
4. Select a Template or Theme:
Once you've chosen a platform, browse through their templates or themes. Pick one that
aligns with your style and works well for showcasing your work. Many of these templates are
customizable, so you can add your own touch.
5. Create Your Pages:
Typical pages on a portfolio website include:
- Home/About: A brief introduction about yourself and your expertise.
- Portfolio: The main section showcasing your work. Organize it into relevant categories if
you have different types of work.
- Contact: A way for visitors to get in touch with you. You can include a contact form or
simply list your email address.
6. Add Your Content:
Populate your website with high-quality images, videos, or any other media that represents
your work. Write clear and concise descriptions for each project, providing context and
explaining your role if necessary.
7. Design and Layout:
Customize the template to match your branding and personal style. Use consistent colors,
fonts, and imagery throughout the website. Ensure the design is clean and easy to navigate.
8. Mobile Responsiveness:
Test your website on various devices to ensure it looks great and functions well on mobile
phones and tablets.
9. SEO Optimization:
Implement basic search engine optimization (SEO) techniques, such as using relevant
keywords in your content and meta tags. This can help your website rank better in search
engine results.
10. Test and Launch:
Before going live, thoroughly test your website for any issues, broken links, or errors. Once
everything checks out, launch your portfolio and make it live for the world to see.
11. Regular Updates:
Keep your portfolio up to date by adding new projects and removing older ones as you
progress in your career. Regularly check for broken links and update your contact
information if needed.

Source Code:

.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="https://fonts.googleapis.com/css2?family=Merienda+One&display=swap"
rel="stylesheet">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-
awesome/4.7.0/css/font-awesome.min.css"
integrity="sha384-
wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN"
crossorigin="anonymous">
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
<title>Portfolio website</title>
</head>
<body>
<!---main section-->
<section class="sec1" id="home">
<i class="fa fa-arrow-up" aria-hidden="true" onclick = "scrollToTop();"></i>
<div class="bg">
<div class="navigation">
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#services">services</a></li>
<li><a href="#work">works</a></li>
<li><a href="#testimonials">testimonials</a></li>
<li><a href="#contact">contact</a></li>
</ul>
</div>
</div>
<div class="nav">
<h2>Portfolio</h2>
<div class="navBar">
<ul>
<li>
<a href="#home">Home</a>
</li>
<li>
<a href="#about">About</a>
</li>
<li>
<a href="#services">Services</a>
</li>
<li>
<a href="#work">Work</a>
</li>
<li>
<a href="#testimonials">Testimonial</a>
</li>
<li>
<a href="#contact">Contact</a>
</li>
</ul>
</div>
<div class="menu">
</div>
</div>
<div class="context">
<h2>Hello, I'm</h2>
<h1>Maheswari</h1>
<h4>I'm a Front End Web Developer</h4>
</div>
</section>
<!---!main section-->
<!--about us section-->
<section class="sec2" id="about">
<h2 class="head">about Me</h2>
<div class="container">
<div class="content one" data-aos="fade-right" data-aos-offset="250" data-aos-
duration="1000">
<h2>I'm a Front End Web Developer</h2>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis debitis sint nihil
saepe veritatis
minima aliquid? Unde eos, non pariatur nulla illo placeat modi dolorem
repudiandae maxime neque,
labore aperiam corrupti consequuntur iste illum eaque adipisci quis!
Reprehenderit, animi
repudiandae!</p>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam non quae
provident ex, maxime libero in
ad nihil aperiam veniam.</p>
</div>
</div>
</section>
<!--!about us section-->
<!---our services section----->
<section class="sec3" id="services">
<h2 class="head">My services</h2>
<p class="info">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam,
adipisci.</p>
<div class="container">
<div class="box" data-aos="flip-left" data-aos-offset="250" data-aos-
duration="1000">
<div class="content">
<img src="https://img.icons8.com/wired/64/000000/web-laptop.png"/>
<h2>Web Design</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo, quo. Sequi
corporis laudantium
facilis fugit quos ut provident ex tempora atque placeat veritatis consequatur
porro, impedit
blanditiis molestias excepturi culpa.</p>
</div>
</div>
<div class="box" data-aos="flip-right" data-aos-offset="250" data-aos-
duration="1000">
<div class="content">
<img src="https://img.icons8.com/ios-filled/50/000000/web.png"/>
<h2>Web Develpoment</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo, quo. Sequi
corporis laudantium
facilis fugit quos ut provident ex tempora atque placeat veritatis consequatur
porro, impedit
blanditiis molestias excepturi culpa.</p>
</div>
</div>
<div class="box" data-aos="flip-up" data-aos-offset="250" data-aos-
duration="1000">
<div class="content">
<img src="https://img.icons8.com/wired/64/000000/android.png"/>
<h2>Android App</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo, quo. Sequi
corporis laudantium
facilis fugit quos ut provident ex tempora atque placeat veritatis consequatur
porro, impedit
blanditiis molestias excepturi culpa.</p>
</div>
</div>
<div class="box" data-aos="flip-down" data-aos-offset="250" data-aos-
duration="1000">
<div class="content">
<img src="https://img.icons8.com/wired/64/000000/portrait-mode-
female.png"/>
<h2>Photography</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo, quo. Sequi
corporis laudantium
facilis fugit quos ut provident ex tempora atque placeat veritatis consequatur
porro, impedit
blanditiis molestias excepturi culpa.</p>
</div>
</div>
<div class="box" data-aos="fade-right" data-aos-offset="250" data-aos-
duration="1000">
<div class="content" >
<img src="https://img.icons8.com/ios-filled/50/000000/content.png"/>
<h2>Content Writing</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo, quo. Sequi
corporis laudantium
facilis fugit quos ut provident ex tempora atque placeat veritatis consequatur
porro, impedit
blanditiis molestias excepturi culpa.</p>
</div>
</div>
<div class="box" data-aos="fade-left" data-aos-offset="250" data-aos-
duration="1000">
<div class="content">
<img src="https://img.icons8.com/wired/64/000000/video.png"/>
<h2>Video Editing</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo, quo. Sequi
corporis laudantium
facilis fugit quos ut provident ex tempora atque placeat veritatis consequatur
porro, impedit
blanditiis molestias excepturi culpa.</p>
</div>
</div>
</div>
</section>
<!---!our services section----->
<!----our latest work section------->
<section class="sec4" id="work">
<h2 class="head">
My latest Work
</h2>
<p class="info">Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem,
eligendi.</p>
<div class="container">
<div class="box" data-aos="fade-right" data-aos-offset="250" data-aos-
duration="1000">
<img src="https://images.unsplash.com/photo-1554415707-6e8cfc93fe23?ixlib=rb-
1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80">
</div>
<div class="box" data-aos="fade-left" data-aos-offset="250" data-aos-
duration="1000">
<img src="https://images.unsplash.com/photo-1502945015378-
0e284ca1a5be?ixlib=rb-
1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80">
</div>
<div class="box" data-aos="zoom-in-down" data-aos-offset="250" data-aos-
duration="1000">
<img src="https://images.unsplash.com/photo-1472289065668-
ce650ac443d2?ixlib=rb-
1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80">
</div>
<div class="box" data-aos="zoom-in-left" data-aos-offset="250" data-aos-
duration="1000">
<img src="https://images.unsplash.com/photo-1489844097929-
c8d5b91c456e?ixlib=rb-
1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1052&q=80">
</div>
</div>
</section>
<!----!our latest work section------->
<!----our testimonial section------->
<section class="sec5" id="testimonials">
<h2 class="head">Testimonial</h2>
<p class="info">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi,
voluptates.</p>
<div class="container">
<div class="box" data-aos="flip-left" data-aos-offset="250" data-aos-
duration="1000">
<div class="upper">
Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore, voluptates iure
dolorem soluta
nesciunt provident, in ea dignissimos suscipit rerum excepturi exercitationem
officiis, vitae quia
aspernatur corporis itaque eius nemo. Maiores, reiciendis illo odit saepe
similique minima illum
vero explicabo.
</div>
<div class="lower">
<h2>Someone Famous</h2>
<h4>Creative Designer</h4>
</div>
</div>
<div class="box" data-aos="flip-right" data-aos-offset="250" data-aos-
duration="1000">
<div class="upper">
Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore, voluptates iure
dolorem soluta
nesciunt provident, in ea dignissimos suscipit rerum excepturi exercitationem
officiis, vitae quia
aspernatur corporis itaque eius nemo. Maiores, reiciendis illo odit saepe
similique minima illum
vero explicabo.
</div>
<div class="lower">
<h2>Someone Famous</h2>
<h4>Creative Designer</h4>
</div>
</div>
</div>
</section>
<!----!our testimonial section------->
<!------contact us section--------->
<section class="sec6" data-aos="fade-right" data-aos-offset="250" data-aos-
duration="1000" id="contact">
<h2 class="head">Contact Me</h2>
<p class="info">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime,
consectetur.</p>
<div class="container">
<div class="box1 box" data-aos="flip-left" data-aos-offset="250" data-aos-
duration="1000">
<h2>Contact Info</h2>
<div class="book">
<div class="page1">
<i class="fa fa-map-marker" aria-hidden="true"></i><span>Address</span>
</div>
<div class="page2">
near government school,Ponnur Road <br>
Kakumanu(v)(m),Guntur(d) <br>
522112
</div>
</div>
<div class="book">
<div class="page1">
<i class="fa fa-envelope-o" aria-hidden="true"></i><span>Email</span>
</div>
<div class="page2">
pinnetimaheswari@gmail.com
</div>
</div>
<div class="book">
<div class="page1">
<i class="fa fa-phone" aria-hidden="true"></i><span>Phone</span>
</div>
<div class="page2">
+91-9704979858
</div>
</div>
</div>
<div class="box2 box">
<form >
<h2>Message me</h2>
<input type="text" class="name" placeholder="Full Name">
<input type="email" class="email" placeholder="Email">
<input type="text" class="message" placeholder="Your Messsage">
<button type="submit" class="btn">Send</button>
</form>
</div>
</div>
</section>
<!------!contact us section--------->
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
AOS.init();
</script>
<script>
var menu = document.querySelector('.menu');
var bg = document.querySelector('.bg');
menu.addEventListener('click',function(){
bg.classList.toggle('active');
menu.classList.toggle('active');
})
</script>
<script>
var nav = document.querySelector('.nav');
window.addEventListener('scroll',function(){
nav.classList.toggle('sticky',window.scrollY>0);
})
</script>
<script>
window.addEventListener('scroll',function(){
var scroll = document.querySelector('.fa');
scroll.classList.toggle("active",window.scrollY>500)
})
function scrollToTop(){
window.scrollTo({
top:0,
behavior:'smooth'
})
}
</script>
</body>
</html>

portfolio.css

transition: .5s;
}
.sec4 .container .box:hover img{
transform: scale(1);
}
/*----!our latest work section-----*/
/*-------our testimonial section---------*/
.sec5{
position: relative;
height: auto;
width: 100%;
padding: 8rem;
display: flex;
justify-content:space-evenly;
align-items: center;
flex-direction: column;
background: rgb(238, 238, 238);
overflow:hidden ;
}
.sec5 .container{
position: relative;
width: 90%;
display: flex;
justify-content: space-evenly;
align-items: center;
margin-top: 5rem;
flex-wrap: wrap;
}
.sec5 .head{
font-size: 5rem;
text-transform: uppercase;
color: rgb(72, 117, 241);
}
.sec5 .info{
font-size: 1.5rem;
}
.sec5 .container .box{
max-width: 45%;
margin: 2rem;
padding: 3rem 2rem;
background:rgb(72, 117, 241) ;
font-size: 1.6rem;
color: #fff;
}
.sec5 .container .box .lower{
width: 100%;
text-align: right;
margin-top: 3rem;
}
/*-------our testimonial section---------*/
/*------contact Me section-----------*/
.sec6{
position: relative;
height: auto;
width: 100%;
padding: 5rem;
display: flex;
justify-content: center;
align-items: center;
flex-direction: column;
background: #000;
}
.sec6 .head{
color: #fff;
font-size: 5rem;
}
.sec6 .info{
color: #fff;
font-size: 1.4rem;
}
.sec6 .container{
display: flex;
width: 90%;
justify-content: space-evenly;
align-items: center;
flex-wrap: wrap;
}
.sec6 .container .box{
max-width: 50%;
margin: 2rem;
color: #fff;
}
.sec6 .container .box1 h2{
font-size: 2rem;
}
.sec6 .container .box1 .book{
margin: 2rem 0;
}
.sec6 .container .box1 .book .page1 i{
color: rgb(126, 158, 247);
font-size: 2rem;
margin-right: 1rem;
}
.sec6 .container .box1 .book .page1 span{
font-size: 2rem;
}
.sec6 .container .box1 .book .page2{
text-align:center;
}
.sec6 .container .box2{
width: 60rem;
}
.sec6 .container .box2 form{
display: flex;
justify-content: space-evenly;
flex-direction: column;
align-items: center;
width: 100%;
}
.sec6 .container .box2 form input{
width: 100%;
height: 3rem;
border: none;
outline: none;
background: none;
background: #333;
margin: 1rem;
text-align: center;
color: #777;
}
.sec6 .container .box2 form .message{
height: 10rem;
}
.sec6 .container .box2 form button{
background: none;
outline: none;
border: none;
background:rgb(95, 121, 238);
color: #fff;
padding: 2rem 3rem;
}
.sec6 .container .box2 form h2{
font-size: 2rem;
}
/*------!contact Me section-----------*/
/*-----media query works here------*/
@media(max-width:991px){
html{
font-size: 55%;
}
.sec2 .container .content {
max-width: 80%;
}
.sec2 .container .image1 {
max-width: 100%;
}
.sec5 .container .box {
max-width: 80%;
}
.sec3 .container{
grid-template-columns: repeat(auto-fill,minmax(50%,1fr));
grid-template-rows: minmax(auto,auto);
}
.sec4 .container{
grid-template-columns: repeat(auto-fill,minmax(50%,1fr));
grid-template-rows: minmax(auto,auto);
}
.sec2 .container .content {
margin: 2rem 0;
max-width: 50%;
}
}
@media(max-width:768px){
html{
font-size: 45%;
}
}
@media(max-width:650px){
html{
font-size: 45%;
}
.nav .menu{
display: inline-block;
}
.nav .navBar ul {
display: none;
}
.sec6 .container {
flex-direction: column;
}
.sec6 .container .box {
max-width: 100%;
}
.sec2 .container .content {
max-width: 100%;
}
.sec5 .container {
width: 100%;
}
.sec4 .head {
font-size: 4rem;
}
.sec2 .container {
width: 100%;
}
.sec2 .container .content {
margin: 2rem 0;
}
.sec5 {
padding: 2rem;
}
.sec4 .head {
font-size: 3.5rem;
}
.nav.sticky {
width: 95%;
}
.sec3 {
padding: 1rem;
}
}


