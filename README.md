# Admin Dashboard    

Site Link: https://blue0206.github.io/admin-dashboard/    

This is the final project of the Intermediate HTML/CSS course of The Odin Project
and this one focused on one of the most important and the most powerful layout mode
of CSS - `display: grid`.      

I found myself reading a lot of articles on CSS while working on this project and this helped
me grasp literally all the topics I had been struggling with. Let's dig into the most important
aspects of my journey with this project! 


#### CSS Units

I was always confused about when should I use which CSS unit and decided to read some articles
and understand what others have to say on this topic and came up with my own criteria for using
these units.

In this project I decided to set different use-case for each unit:

1.  **rem:** I decided to use `rem` for all the text content in my project.      
   
2. **px:** I decided to use `px` for everything that I did not want to scale alongside my 
    text content (for example: padding, margin, border, etc.)

3. **em:** I decided to use `em` for everything that I wanted to scale alongside my text 
   content like icons, images, etc. I realized that `em` is an excellent unit for this purpose 
   and makes scaling so easy without depending on `calc()` (something I was doing prior to this project.)

Up until this project, I had been hesitating a LOT when it came to using the `px` unit. For some reason, I
had this stigma in my head that `rem` and `em` are the ideal units for everything. However, in this project,
I broke free from it. I used the `px` unit extensively thanks to the wisdom I collected from reading those
articles.


#### CSS Grid

I have read a lot about CSS Grid and its use-cases and tried almost everything that I learnt in 
this project. I am honestly in love with this feature as it makes layout so EASY! Up until this
point I have only been relying on Flexbox, but now that I'm armed with Grid, I'm sure I can tackle
almost any problem that I might face with layouts or positioning.

Although it would have been wise to use Flexbox at some places in thise project, I decided not to
because the sole purpose of this project was to get comfortable with using Grid, and I DID.

This project helped me bolster my understanding of the `auto-fit` property and its use-case. I
applied this property in this project and it worked flawlessly! I can safely say that I now
understand how to create layout with responsive columns that auto-generate depending upon the
available space of the container.

I also found out that the `auto` value in `grid-template` is very useful when used alongside `fr`
unit.


#### CSS pseudo-class Selectors

I found myself using some pseudo-class selectors for the first time and I realized how powerful they
are! I didn't even need to apply distinct class names to some elements as I could just access them
using these selectors.

`:first-child`, `:last-child`, `:nth-child(even)` were the classes I used and they helped me save the
use of extra class names on the divs of Projects panel, Announcements panel, and the Trending panel.

I know that there were definitely more places where I could use them and save the use of class or id
names. Anyways, this was just the start. I'm sure I'll be using them more frequently from now on.


#### CSS Reset

Although I did not use a full CSS reset on this project, I did end up using it on form elements like
`input`, `button`, etc.  
I also reset the margin of all elements using the universal selector (`*`).

I will probably be using more significant resets in future projects.


#### Colors and Box-Shadow

This project was my first time using `hex code` (although all I did was copy-paste the shades that I liked.)

As for `box-shadow`, I concluded that it is better done using these online box-shadow creators as I can make
adjustments and get results in real time, hence speeding up the process.


#### Icons and Images

This was my first project where I used them extensively. I downloaded a bunch of icons for profile, home, etc.
and this is where I realized the true power of `em` unit. Simply setting a height and width of 2em gave me icons
and images with the size the same as my text content!

One problem that I faced was that my icons were all initially black in color. So when I changed the background-color
of my dashboard to blue, I decided to make my icons white for a better look. But, I didn't know how to do so. I tried
different approaches like setting `brightness`, `saturation`, etc. but none of them worked.    
After some surfing, I found out that the solution was to use `fiter: invert(100%)`. This made all the black svg icons
completely white! I'm absolutely gonna remember this handy trick for my future projects!

#### Conclusion

This was by far, the most complex CSS project I've made till date and it was a REALLY valuable experience!. I saw myself
using even more complex CSS selectors and pseudo-classes than I've been used to. I pushed myself to read long articles
in order to tackle the issues I faced. I feel like I'm getting very good at this stuff, and IT IS FUN.

This project was a valuable experience, and by far the most cool looking one!