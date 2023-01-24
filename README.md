# Testimonials-Grid-Component-

<h2>Users should be able to:</h2>

- View the optimal layout for the site depending on their device's screen size


<h2>Built with:</h2>

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

<h2>Process:</h2>

The layout, the entire component is built (mobile first) using ```CSS grid``` along with ```grid-template-areas```; Which made everything extremely easy to layout.

```
.testimonial-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-template-areas:
      "daniel daniel jonathon kira"
      "jeanette patrick patrick kira";
  }
```

To make each testimonial semantically correct, I wrapped each individual testimonial component in a ```figure``` element, the individuals information ```figcaption``` element and lastly, the testimonial itself was wrapped in a ```blockquote``` element.

```
<figure>
   <figcaption></figcaption>
   <blockquote></blockquote>
</figure>
```



