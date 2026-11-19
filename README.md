# Reflection

## [Bento Grid](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj)

Starting off, I chose the bento project, it looked like it could present a good challenge for me—it is doing that completely. 

I'm currently [Tue Nov 17] trying to the media queries to work; I realize now that the way I structured my file—the combo of utility classes—is keeping my grid stuck in place; I cannot get it to resize at the breakpoints, so I will need to find that out. [Tue Nov 17, 12:54 PM] I needed some help understanding why my grid was locked and I recieved some insight. I've seen a video where the creator places `grid grid-cols-1` on the main container and then proceeds to define the smaller screens `sm/md:grid-cols-x`, my resource says to make the default layout one column then add breakpoints but I'm not sure why this works at the moment.

I tried a couple things and now I feel I need to start over, it's now [Tue Nov 17, 7:25 PM]. Gap wasn't working for a moment `<main id="container" class="mx-auto w-full max-w-6xl grid-cols-1 gap-4 p-4">` I realized that I hadn't established `grid` before `...grid-cols-1...` so grid wasn't completely activated. Making progress around at around 9:20 PM; able to control the grid a bit more using `...md:grid-cols-2 grid-flow-col grid-rows-10...` the two columns and getting them to position where they are in the design is going to prove interesting.

[Wed, Nov 18, 10:59 PM] Most of the styling is done for the default mobile/phone sizes, now I'm working on tightening the styling for the medium sized devices. The text design is tough, how we do it in design programs will always have a level of polish that computers might not be able to achieve when working from designs—we have optical illusions that make it look right even when it's not—regardless, I'm really close. However, my desktop/larger size grid still hasn't organized itself properly 😬 I am trying my best to figure that part out.

[Thu, Nov 19, 7:50 AM] I went to bed knowing that a couple of the images within the cards broke, the size got small and I couldn't undo it—-happend after I merged into my main. I managed to get one of the two corrected with `justify-center` and `w-full` while the other, the inner-grid is out of alignment, on `md` its correct but as I scale back down to small sizes the image scales down with it; setting `sm:...` isn't working either because by default tailwind is mobile first. Anyhow, if given more time, I would continue learning more about tailwind's grid... it feels like the bento should be easier but the lock up keeps breaking.
