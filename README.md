# News Site

The project is a responsive newssite with a header main and a content section. In mobile < 667 px 1 column, on tablet 668 px to 1024 2 columns and in desktop 2 column main and 4 column content section. 

## The problem

Describe how you approached to problem, and what tools and techniques you used to solve it. How did you plan? What technologies did you use? If you had more time, what would be next?

I based my project on the provided wireframe. I started by designing the html with a header and a main section and a content section. In css i restricted the size of the whole body to 1400 px and margin 0 and auto to keep the homepage centered and fixed on large screens. I followed with the mobile version with a explicit single column. Next I did the tablet version in a media query min-width 668px where I assigned my classes to grid-column-areas and followed to designate in what order they should be displayed as it differed from the html order. Last I did the desktop version in a media query min-width 1025px, the header in a flexbox, the main section in a grid with two uneven columns and the content section in four columns.

If I had more time I would fix the css styling where the images overflow.

## View it live
Every project should be deployed somewhere. Be sure to include the link to the deployed project so that the viewer can click around and see what it's all about.
