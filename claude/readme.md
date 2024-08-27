## Initial Prompts

I am an architect who designs residential and commercial buildings and want to create my own website using HTML, CSS and JS and I want to leverage TailwindCSS styles. My website intend to be my portfolio and will have the next features and pages:

- Responsive design
- Elegant horizontal navbar
- Minimalist Footer including social media links
- Home page: with a hero and a call to action, and then some introduction
- Projects page: Grid to display all projects with thumbnails and short titles
- Project details page
- About me page: that includes a professional bio, profile picture, experience and skills progress bars, awards and publications, client testimonials and contact information
- SEO optimized

Make it look professional as a real website (using correct image URLs, including proper sections, etc)

You will share the HTML, CSS and JS code for each page and I might ask for changes, until I ask you for the next page. Then you will share just the section code as \<head> and navbar and footer will be the same. Start with the home page

## Anthropic Claude

🟢 Correct Tailwind CSS import

🟢 Responsive navbar - Home | Projects | About Me

🟢 Responsive design

🟢 Home layout - Standard distribution but looks really good/clean

🟢 All projects layout - nice 2 rows with 3 projects, good titles and descripctions

🟢 project details - I liked the texts generated, very close to a real example, I just replaced the images

🟢 about me - Very happy with the results the layout is very close to a standard CV layout, I only change the profile picture.

🔴 Navbar links - all were set to `href="#"` I could ask to fix it, but I was expecting to work by default

🟢 Footer icons - Really good svg's for facebook, twitter and linkeding (I didn't specify which social media I want)

🟢 Client testimonials - It genereated two card in the about me page, but I used the following prompts:

```
> let's tweak just the Client Testimonials div/section so it is a slider
> something is wrong. I'm see all three texts in a single slide, so when I click to the second slide I see nothing
```

🟢 Time for each response (faster than chat gpt)
