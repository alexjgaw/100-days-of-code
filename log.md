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
