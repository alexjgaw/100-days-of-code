# 100 Days Of Code - Log

### Day 0: January 11, 2017

**Today's Progress**: Forked 100 days of code repo, had trouble cloning it with SSH. Fiddled around for some time trying to figure out what was wrong. Eventually realized I had my config file set with Bitbucket.org as the only host, so I added Github and everything worked. I didn't do any actual coding, but I did go to the Open Austin Civic Hack Night at Dev Bootcamp.

**Thoughts:** As I say, I didn't get to code, but I did start the process of getting involved with Open Austin, which I think is a really cool organization. I'm excited about the things they're working on and the prospect of being able to help with projects. I don't feel like today was a failure. Maybe if I were more experienced the actual coding would be more important in order to push myself to grow, but at this stage there's so much I don't know, and I do believe that the best thing I can do for my growth right now is get involved with organizations and people who can provide some kind of guidance. Autodidacting is great and all, but if dancing has taught me anything it's that you can't beat being part of a community.

**Link to work:** [My forked repo](https://github.com/alexjgaw/100-days-of-code/tree/alex-gaw)

### Day 1: January 12, 2017

**Today's Progress**: Worked on a random quote generator. Set up the HTML and styled it. Found a quote api for when I start the JS.

**Thoughts:** No real challenges today, just a lot of fiddling with properties to make it nice. I peeked at the source of the example so I could see what API they used, and was a little daunted. I've never used an API that requires a key. So I searched for and found an API that doesn't require a key.

**Link to work:** [Random Quote Generator](http://codepen.io/alexjgaw/full/WxXbJX/)

### Day 2: January 13, 2017

**Today's Progress**: Finished random quote generator.

**Thoughts:** This was an interesting day. First, I was awakened well before I meant to be by my asshole cat (whom I love despite her being an asshole). I feel pretty good about the fact that even though I didn't want to be up, I went to my desk, applied to a job, and got to work coding. The API I found was a *bad* idea for right now. It didn't require a key, which was nice, but you accessed a quote by using a URL-encoded method and arguments. I tried to access it with a normal ajax request and got an access-control-allow-origin error. I tried to switch to jsonp, but ran into issues with the fact that the getQuote method was URL encoded. I tried appending a script tag to the body but it seemed like CodePen wouldn't let you do that. In any case, after messing with it for some time I decided to just go with the API that the example used and figure out how to use a key. Surprise surprise, it was really easy. There's a chance I'll go back and make this app outside of CodePen so I can try the append solution, but for now screw that. Definitely got more than my hour for today, and I got a good taste of important concepts like Same Origin Policy, Cross-Origin Resource Sharing, and API keys.

**Link to work:** [Random Quote Generator](http://codepen.io/alexjgaw/full/WxXbJX/)

### Day 3: January 14, 2017

**Today's Progress**: Started and finished local weather app

**Thoughts:** I'm proud of myself for coding on the weekend. This app wasn't too difficult but I'm very glad to be getting practice using APIs. The app is more or less finished, having satisfied the user stories in the prompt, but I want to go back and figure out the Unsplash API so I can have the background image be the result of searching Unsplash using the weather description from the weather API. Other than the APIs, I got some good practice thinking about which variables should be `const` vs `var` and what should be global vs scoped to a function. Also good thinking about asynchronous operations and assignments within callbacks. At first I tried to set variables within the callback for the `get` method and then access them outside of it, but quickly remembered that when I was trying to access the variables in the global execution context they were still undefined. Neat stuff!!

**Link to work:** [Local weather app](http://codepen.io/alexjgaw/full/rjLvqR/)

### Day 4: January 15, 2017

**Today's Progress**: Began Wikipedia search app

**Thoughts:** Today's block of time was mostly spent looking at an example, setting up the HTML file and doing some styling. The look of the example is really cool and I'd like to get a handle on it. I couldn't code much more than an hour because I was scheduled to help a friend. The last thing I was working on before I had to stop was being able to click on an element within the form to close the search bar without it also registering as a click on the form itself and opening the search bar again.

**Link to work:** [Wikipedia search app](http://codepen.io/alexjgaw/full/ygaVJZ/)

### Day 5: January 17, 2017

**Today's Progress**: Started Advanced class at Austin Coding Academy

**Thoughts:** The actual day I was bad about coding because I expected to do plenty during class. This was folly. First day was mostly orientation and environment setup. We then discussed in a basic way how the internet works. Good to know, but not coding per se. The next day was mostly spent on an online class with the new stuff in ES2015. Again, not so much coding, but very JS intensive so I'm counting it anyway. Again, I'm so new that anything that contributes to my growth is fair game. Plus it's my challenge, so my rules.

**Link to work:** None

### Day 6: January 18, 2017

**Today's Progress**: First react app

**Thoughts:** React, though a little scary at first, seems like it's going to be really handy. The modularity of everything will take some getting used to, but I definitely see the value of not having a giant document with a whole bunch of code that takes forever to scroll to whatever you're trying to look at. I think the most annoying thing so far about web development has been dicking around with the DOM. Yes I'll still have to do that, but React makes it so much easier.

**Link to work:** [First react app](https://github.com/alexjgaw/advanced-lesson-zero/commit/e64ab3970785f7024b761ff86ca0338eb5e5ac93)
