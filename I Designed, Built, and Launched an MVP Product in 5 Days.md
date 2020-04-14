[Original post is here](https://medium.com/better-programming/i-designed-built-and-launched-an-mvp-platform-in-5-days-c06fa629adb9)

#I Designed, Built, and Launched an MVP Product in 5 Days  
Crucial realizations on how to launch faster

Over the past year, I’ve launched a few products, each of which required between 3–6 months to go from ideation to launch. At the time, I thought this was moving fast and launching quickly. But after all that time invested, the total profit for all those projects is hovering just under the $500 mark.

While the time I invested grew my coding experience and knowledge, I wish I had done things differently and failed quicker.

This time around, I took a different approach.
I Started by First Building a Community

I have an idea of what kind of product I wanted to build, but I have no desire to commit to a single concept until my target audience says they really have a need for it. At this early stage, my goal is simply to build an audience and start a dialogue. For me, my target audience is front-end developers like myself.

Rather than attempting to build some concrete vision from the beginning, I first whittle down the ideas until I have a basic element of value. This would be a minimal product that would allow me to deliver value to my specified target group of users and get them interacting regularly with the site.

This is sometimes called a Minimal Lovable Product.

I know that if I start with a community that is interested in what I’m providing for free, I could have an ongoing conversation to then develop a product specifically around their needs. It is best to create your minimal product around your long-term product goals. However, it doesn’t have to be a smaller version of your final idea. It just needs to deliver value to your eventual target group of customers.

Here’s an example of how I set a long-term product goal while starting with a basic element of value.
My long-term goal

I know that many developers have full projects and UI components that they spend weeks on and then never do anything with. I think many of these could be sellable, but there isn’t really a marketplace that focuses on this specific aspect of the market. So, my long-term goal revolves around allowing devs to buy and sell resources they’ve created.

I have an initial idea, but it could change or pivot at any time, and I’m not going to risk the time involved in developing a full-featured platform. I still have no idea what my final product in this market segment is going to be, and I don’t have to. My community will help me decide what I build next, and it will be decided based on data and direct feedback from the market.
My short-term, basic value delivery

What I can do is start with the project’s basic element of value: a place where developers go to find curated resources for their next project. Essentially, this concept is the same as my original idea, minus the heavy features. While no buying or selling will take place on the platform itself, I should at least be able to gauge the interest in this kind of product (i.e. curated resources) and see what kind of resources people show the greatest interest in.
I Said No to Features That Required More Time to Code

    No database
    No login system
    No user profiles
    No payment integration
    No docs (terms and conditions or guides)
    No features that would make the project take more than a week to develop

I Focused on the Unique Value I Could Bring to the Market

I’d like to think that I have a knack for curation, especially when it comes to design and development resources. It was with this thought that I decided to create a curated front-end resource platform. While similar repositories exist, I wanted something specific. I wanted a range of frameworks and to focus on quality over quantity. Each resource would be hand-picked and well-considered before posting. I decided I would only post things that I myself could imagine using.

I already had a ton of saved bookmarks and have written pieces on Medium about some resources I’ve curated, so I figured that was a great starting path. I first decided which frameworks I was going to curate resources for, and in the end, I chose only those frameworks with which I had direct experience.
The Launch Process
1. Simplify the UX

I spent half a day creating a UI wireframe in Sketch. I referenced other similar sites and compiled the best ideas into a two-page site. I have the tendency to add extra detail during the design stage, but I forced myself to cut any and all elements I wasn’t ready to build within the following few days. Also, for the first time as a designer, I didn’t care about making things look good. Black and white was enough for this stage, and any colors or element designs would come later.
2. Decide on styles

While I could have chosen an off-the-shelf CSS framework like Bootstrap or a UI kit, I recently built my own minimal CSS framework for a different project and decided to use it instead. It’s super small, including only browser resets, basic elements like buttons, forms, a navbar, and a card, so it was perfect to use for my MVP project. I prefer frameworks without a grid, as I tend to use CSS Grid for everything these days. If you’re building a card-based site yourself, learn the basics of Grid (it’s incredible for fluid card layouts). Overall, customizing my CSS framework to fit this project took less than a day.
My minimal, grid-less CSS framework.
My minimal, grid-less CSS framework.
3. Create components

I use Vue for most web apps I build these days, and this site was no different. I began by outlining the individual components (based on my Sketch wireframe), the routes, and a detailed card element that I would loop through for each resource in my data. You might notice that I found a few ways to further simplify the UI once I started coding compared to my wireframe. Rather than using a modal component to show the download/view buttons for each resource, I found the UI was better if I let people access these through a hover overlay on the card itself. Again, this was a good reason to stick with a wireframe, as I ended up not even using that design (more hours saved). This hover overlay also worked on mobile by tapping the card.

In the end, this was just a better UX that allowed faster access to resources. If I need extended functionality like modals at a later date, I can easily add them if/when that day comes. Getting all the pages, components, and app logic finished took around two full days.
This is the entire app. Simple, right?
This is the entire app. Simple, right?
4. Decide on data structure and source

I separated the .json data files by framework to make them easy to add to later and decided I’d keep them inside the project files rather than use an external database. That way, if I changed my mind as to what database to use, I wouldn’t have to change a bunch of code to fit it (which, as you’ll see in step 5, was a smart decision). Gathering resources really was the most time-consuming part of the job, especially when I manually optimized every image. All in all, this took just over two full days of work.
5. Deploy to host

Once the site was ready, I decided to launch it on Netlify, as I’d heard good things about it. While deployment was easy, I was having major issues with image loading. Even after manually optimizing every image by hand (reducing width, running them through multiple image optimizers like Ezgif, etc.) some 300kb files were taking over a minute to get served by Netlify. After a full day of troubleshooting, I decided to completely move the site over to Firebase to see if that would improve load times. Two hours later and the site was moved, the DNS records had propagated, and my site was suddenly blazing fast. If I had committed to using a single database, this might have caused major launch delays. By keeping things simple and building only what I needed, I had saved myself time and energy and yet still got the best result in the end. I could have launched faster, but dealing with these issues lost me at least a day.
6. Prepare launch and go live

At this point, I was pretty much ready to launch. I added a few more resources and a few convenience features (like a button to clear text in the search field), but nothing major was added. To prepare for the launch on Product Hunt, I created 12 individual frames in Sketch, then uploaded them to ProductHuntGif, which instantly turned them into a perfectly sized gif for my product page. Getting the launch ready took less than half a day. However, I didn’t need to find a hunter, as I already am one on PH. Expect a few days of waiting for a response after you contact people to hunt your product for you (I’d be happy to help too).
Sketch artboards for my GIF.
Sketch artboards for my GIF.
Tip: You might have to reverse the order of images before upload for them to play correctly.
Tip: You might have to reverse the order of images before upload for them to play correctly.

For the other images (including the GIF at the top of this article), I used GIF Brewery 3 to quickly snap and resize previews of the product. So far, it’s the best tool I’ve found for quick GIF creation on the fly.
Conclusion

I’m not sure what will come of this product, but I know that this time around, I’ve taken the best first steps along the product development path. At the very least, I’ll have fostered a community that I can utilize to get feedback on whatever I do next.

Rather than launching an entirely new platform, now I’ll have a base to cross-promote with and gather early-stage users.

Whether it’s curated assets, a simple tool, or email templates, there are many free products we can make that cost us very little time or money to get up and running. As entrepreneurs, we must first bring value to the market, and afterward, we can figure out exactly what kind of product our communities are in need of.

I hope you’ll use this guide to consider the best path of development for your future projects and discover the fastest route to market while also saving yourself later regret from not properly vetting your market ahead of time.
