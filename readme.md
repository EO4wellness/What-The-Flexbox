# What The Flexbox?!

![Course Image](https://flexbox.io/images/WTF/share.png)

Exercises for the "What The Flexbox?!" video course. Videos available at <http://flexbox.io>

##  Original Course Creator:
My [gh-page](https://herminiotorres.github.io/whattheflexbox) by [@herminiotorres](https://twitter.com/herminiotorres)

## My Study 
https://courses.wesbos.com/account/access/606393ab75ff3a25a5c43252/view/197920688

* Day 0: 2021-03-30: discovered a link to this course, signed up, and forked the repo. Watched the first video, which outlined the Flexbox course of study. The videos and repo (fork) are easily to follow along with, while learning. 

* Day 1: 2021-03-31: [Introduction to Flexbox](https://github.com/EO4wellness/What-The-Flexbox/tree/eo4wellness/intro)
   - Today we start with a basic HTML and CSS template, of sorts. 
 
            <code> display: flex; </code>
            
   - This is where we start.  this establishes our container with its content. 
   - if we add a border say [code--> border:10px solid goldenrod;] as in our template, will add a border around our flex content so we can better visualize what a flex container is and where its edges lay on our page. 
   - another code evariation is 

                  <code> display: inline-flex; </code>
     which wraps around the content, only taking up the width that it needs. without the "inline" portion this code goes all the way across 
   - the divs on the page are children of the flex container as soon as we have the display flex code on the page. 
   - tomorrow, we look at axis and flex direction.  as a set up for tomorrow we going to add height.  
   - in real life, the height would come from the actual content 
   - we added 

                      <code> height: 100vh; </code>
   - V H is the code for viewport height.  it makes the container stretch the entire height which is available.  it is like height 100% 
   - Review: ON the HTML code, we have our FLEX container and our FLEX items (box 1-10)
  
* Day 2: 2021-04-01 [Working with Flexbox Flex-Direction](https://github.com/EO4wellness/What-The-Flexbox/tree/master/flex-direction)
  - This is super important to the rest of the study.  
  - Worth taking some time to learn, study out!
  - "flex direction"
  - default of any flex container is:   flex-direction:row: min-hight:100vh;
  - flex-direction:column; 
  - both of these codes use two axises 
  - main axis is left-to-right for row and the cross axis is top to bottom. 
  - main axis changes if you go to column.  the main axis for column is from top to bottom. 
  - another code is:  flex-direction:row-reverse: this has the main axis starting from right and going to left. 
  - another code is: flex-direction:column-reverse; to start at the bottom and go to the top. 

* Day 3: 2021-04-02 [Wrapping Elements with Flexbox]()
 - looking at widths 
 - container with display flex 
 - select the flex item and give it a width 
 - Example code:
      
        .box {
            width:300px
        }
      
 - it is going to try to deal with the width you gave it without scroll bars 
 - flex-wrap:nowrap; is the default 
 - flex-wrap:wrap; (gives you the width specified, exactly, and fit them with the space)
 - Axis-->left to right and then -->top to bottom  
 - flex-wrap:wrap-reverse; goes from left to right but from buttom to top instead of top to bottom (not used often but handy to know when it is needed)
 - if you want to fill everything use a fraction such as width:33.33333333%; 
 - flex-direction:column; 
 - flex-direction:row (this is the default) 

      .box{
        width:33.3333333%;
        padding:10px;
      }
margin is not part of the box structure so it will "break" 

* Day 4: 2021-04-03 [Flexbox Ordering](https://github.com/EO4wellness/What-The-Flexbox/tree/eo4wellness/ordering)
