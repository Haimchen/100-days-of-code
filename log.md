# 100 Days Of Code - Log

Started on 2019-03-29

### Day 1: March 29, 2019

**Today's Progress**:
I got to do something really different at work: Learned a lot about AWS Cloudformation and how to write templates.
Our WIP template can now create a stack with one app plus an environment created from a template.
After work I joined WWG Berlin to learn some more Go.
Wrote some code snippets to benchmark iterations over multi-dimensional arrays.

**Thoughts:**
I am eternally torn between wanting to do more backend focused work (and use Go) and Frontend.
Styling and all that is not my passion, but on the other hand almost any project idea I have needs a good frontend (while the backend can be quite minimal sometimes).
Also automating AWS is fun and would be not as hard as I thought. The major obastacle is the complexity of our deployment.

**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1112285446028050432)

**Link to work:** [Go Examples](https://github.com/Haimchen/story-of-slices)

**Resources**
[Cloudformation Docs - Create Elastic Beanstalk Environment](https://docs.aws.amazon.com/de_de/AWSCloudFormation/latest/UserGuide/aws-properties-beanstalk-environment.html)


### Day 2: March 30, 2019

**Today's Progress**:
Joined a WWG Berlin event with Bill Kennedy and learned a lot about the details of how slices work and where the dangers lay.
I also learned that there is a third optional parameter when slicing a slice.
It allows you to define the capacity of the new slice to override the default.
In the evening I also did some work with CSS, trying to override some styles from a Wordpress Theme.
I also wrote my version of the Challenge rules on the U-Bahn...


**Thoughts:**
Using my laptop on public transport is very inconvenient and probably bad for my back.
But I am very happy to have my own ruleset now, so I can work on this challenge and have a chance to finish.
And feel good about it and not guilty for "cheating" :-)
Also Go is awesome and Bill Kennedy a great teacher.
And CSS is just CSS. It is a real challenge to adjust a wordpress theme with minimal use of `!important`.


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1112288496641892352)

**Link to work:** [Go Examples](https://github.com/Haimchen/story-of-slices)

**Resources**
[Three Index Slices in Go](https://www.ardanlabs.com/blog/2013/12/three-index-slices-in-go-12.html)


### Day 3: March 31, 2019

**Today's Progress**:
Short day, short Update: I fixed our repo for the React workshop.
Had to rewrite the git history a bit to fix an error in one of the first steps.
So a lot of git voodoo and a courageous force push at the end.


**Thoughts:**
I should write a blog post about this. Changing the git history can be so useful for cases like this.
Might also help people doing code challenges for a job :-)


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1112473324804866050)

**Link to work:** [Fixed Repo](https://github.com/WomenWhoCode/wwcodeberlin-react-workshop)

**Resources**
[Rewriting Git History](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History)



### Day 4: April 1, 2019

**Today's Progress**:
Spend a lot of time with the Gatsby.js tutorials and docs.
I wanted to try it for a new project with my husband, but in the process I discovered that it is not the right tool.
So I switched to React and Apollo instead (bootstrapped with create-react-app).
Next time I will have a look at typescript and rewrite the project (it is just tiny for now).
I also read a bit about how the current react version supports code splitting with lazy().


**Thoughts:**
What we need is an app that fetches data almost live.
So the perfect case for GraphQL subscriptions! Should be simple enough with Apollo.
Gatsby looks good, but more for a site that is built off a CMS.


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1112830149656023046)

**Resources**
[Code Splitting with React](https://reactjs.org/docs/code-splitting.html)
[Using a React App with a Full Stack Framework](https://www.fullstackreact.com/articles/how-to-get-create-react-app-to-work-with-your-rails-api/)


### Day 5: April 2, 2019

**Today's Progress**:
Hack Evening time, so I lost some of my coding time to organizational stuff like setting dates for the next events.
Also checked of some of the remaining todos for the React workshop.
I tried to also watch a video on Gatsby and Apollo which was interesting.


**Thoughts:**
Still some final tasks open for the workshop and it is already happening in two weeks!
Gatsby seem to offer some really nice features for a site that combines data from different sources and supposedly makes it load fast.
Really curious to try it on a real project.


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1113338841837051904)

**Resources**
[Video: Beyond Static - Gatsby + Apollo](https://www.youtube.com/watch?v=wNUg1jpj9T0)


### Day 6: April 3, 2019

**Today's Progress**:
Worked on my husbands newest project and added the first form to send a mutation.
I used Apollo and my first hook ever!
Loved how clean the hooks are and how uncluttered the file looks.
Have to say I was not too happy about Apollos render prop API. That causes too much indentation for my taste.
I also tried to remember form accessibility best practices, but I need to check that to be sure I remembered correctly.


**Thoughts:**
This is already confusing, I need a project overview and tags per project I am working on in parallel. Might be too many...
Love the new hooks, my form component was so nice and ordered using ` useState` as compared to how I had built it as a class.
Today I also talked to a friend who wants to start a coaching business and I wanted to recommend her something to built a simple business website.
But it is really hard to chose!
If I would make it for here, I would probably use it as a chance to try Gatsby plus a headless CMS :-)


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1112830149656023046)

**Resources**
[Code Splitting with React](https://reactjs.org/docs/code-splitting.html)
[Using a React App with a Full Stack Framework](https://www.fullstackreact.com/articles/how-to-get-create-react-app-to-work-with-your-rails-api/)


### Day 7: April 4, 2019

**Today's Progress**:
Worked on the project repo for the react workshop and added some final touches here and there.
Also a little bit of git magic with interactive rebase to fixup / squash some commits.
Also read through the material again and added an overview of the steps, so I wrote a lot about code and just a tiny bit of code.


**Thoughts:**
I should really prioritise my blog higher.
Having a place to collect all the things I learn and thoughts I have would be so useful!


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1113928608807030784)


### Day 8: April 6, 2019

**Today's Progress**:
Added another layer of form nesting to the husband's project and it is still so pretty!
I have about 130 lines of code for the whole form with now 4 different inputs, including the GraphQL mutation.
Besides admiring the code I have started to think about the CSS and how I want to handle that.
But it is a hard decision, as my skills in organising CSS are not very great - I am lacking good examples.


**Thoughts:**
Hooks look so nice and clean in compairson to some of the alternatives. I love it.
Next up will be some accessibility checks on the form and some CSS added.
For now it only has the very basic stuff.


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1114685781312974848)



### Day 9: April 7, 2019

**Today's Progress**:
Did some research on CSS and how to organise styles. My current plan is to go with a CSS/ SCSS approach and not use CSS-in-JS.
We will see how long I can stick to that!
Rachel Andrew's CSS courses look really good, I have started the free one on the basics, but unfortunately the advanced ones are not free.
I am thinking about buying the one about structuring CSS...


**Thoughts:**
I feel like CSS-in-JS is so attractive in an existing project, is that it easily allows to scope the styles to one component only.
And if the existing CSS is already a mess, this might feel like the only way to change something without breaking everything in unknown places.
Variable sharing is also nice, I assume.


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1115128696522907653)

**Resources**
[Prodigy Finance Style Guide - BEM like approach](http://uif.prodigyfinance.com/v2.0/docs/base/developing-css-js.html)
[Rachel Andrew's CSS Basics Course](https://thecssworkshop.com/css-basics)


### Day 10: April 9, 2019

**Today's Progress**:
I wrote two articles for my unpublished tech blog!
They are only short ones, but I hope this helps me to get more into the hapit of writing things down for the blog.
Both are about handy tricks to debug and refactor javascript / React code that help me in my daily work.
Still counts, because usually I am not writing about it!


**Thoughts:**
I need to bit the bullet one day and really work on the style (or at least pick a theme!) to finally publish this blog.
Probably best if I set myself some kind of deadline, like write 10 posts until May 1st and then it is Go Live!
At least I have some more notes lined up for more articles to write.
The next one will be less technical but more about roles in tech teams and what we can learn from RPGs.
Just need to figure out which Games is very widely known and makes a good example...


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1115706769274298368)

**Resources**
[Hugo Docs - Links and Cross References](https://gohugo.io/content-management/cross-references/)



### Day 11: April 10, 2019

**Today's Progress**:
Started another article for my blog, but I count it only partially because it is more process than programming related.
But I did build something nice:
A new react app that renders a dynamic Game board.
Dimensions can be passed in and the component creates as many fields as are needed.
The layout is done with CSS grid (and flex inside the fields).
Was also looking at themes for Hugo, but still no decision made.
I also learned about `String.repeat(n)` in Javascript and `Array.fill()`.


**Thoughts:**
Being able to build a dynamic grid layout based on some props (width and height) feels amazing.
Next step will be to figure out how to handle the state of the children (fields) because they should be active / inactive.
It is also always worth it to check the Docs for the standard library if I do not now a nice way to do something.


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1116100687488745473)

**Resources**
[CSS Tricks: CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
[Hugo Theme - Hyde](https://themes.gohugo.io/hyde-hyde/)


### Day 12: April 11, 2019

**Today's Progress**:
I read some in depth blog posts on React hooks, useEffect in particular.
After that I was very motivated to put some of my new knowledge to work, but then I got distracted:
I worked on my GraphQL subscription game frontend and got very excited when I discovered how CSS can be used on Emojis.

**Thoughts:**
Emojis with a bit of CSS can be great way to add icons to an app.
transforms and filters work well to e.g. flip them or change the colors.
React hooks continue to be a great addition. All the examples I see look so much shorter and cleaner than the same code with classes.
Well, not the same: In Dan Abramov's blog post he explains some of the finer differences between useEffect and the lifecycle methods.
In many ways hooks are even better!


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1116478511680761856)

**Resources**
[Dan Abramov's Complete Guide to useEffect](https://overreacted.io/a-complete-guide-to-useeffect/)
[Rules of Hooks - React Docs](https://reactjs.org/docs/hooks-rules.html)
[How to fetch Data with React Hooks](https://www.robinwieruch.de/react-hooks-fetch-data/)

### Day 13: April 12, 2019

**Today's Progress**:
Today I was really exhausted from work, so not much was done at home.
I read an interesting article about logging in distributed systems.
And I prepared for an Elm workshop I am doing tomorrow. Installed the language, checked that everything works and also added some vim syntax highlighting and an autoformatter.


**Thoughts:**
Excited for the workshop! Elm has been on my list of things I want to learn for years now.
And it is one of the main influences on the design of react.
The article on logging was really useful, because it explained some of the "old" best practices and why they do not make sense any more in modern, distributed environments.


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1116829232909430787)

**Resources**
[Logs vs. Structured Events by mipsytipsy](https://charity.wtf/2019/02/05/logs-vs-structured-events/)


### Day 14: April 13, 2019

**Today's Progress**:
I learned the Basics of Elm at a full day workshop with ElmBridge.
The curriculum started with some basics where we had function headers and tests given and had to implement the functions.
After that we worked on a small project: A webapp to encrypt and decrypt text with emojis.


**Thoughts:**
The curriculum was really well structured and had a good flow.
I feel I learned a lot and enjoyed working with the language. I am defintely interested in learning more, especially about the core aspects of a real world project:
Code splitting / modules and connecting to APIs are the ones on top of the list.
We also did not cover some of the cool functional features like Maybe types and pattern matching.
What I am not too fond of is what the view part looks like:
Even though I was initally very sceptical of JSX, I would now prefer it because it looks more natural and very close to the final HTML.


**Link to tweet** [Status Tweet](https://twitter.com/Go_Haimchen/status/1117113593160400896)

**Link to work:** [My Emoji Encryption App](http://emoji-encyrption.getforge.io/)
[My pull request against the curriculum repo](https://github.com/elmbridge/curriculum/pull/133)

**Resources**
[ElmBridge Curriculum](https://elmbridge.github.io/curriculum/)

### Day 15: April 14, 2019

**Today's Progress**:
I wanted to learn more about Elm so I went on to find answers to some of the questions I had after the workshop.
1. There seems to be a GraphQL implementation for Elm!
2. There are libraries to support server side rendering
3. I also read a few sections of the offical guide, in particular the section about optimizations.
4. It might be worthwile to explore Elm for Games: Apparently it is smaller and more efficient than most pure javascript libraries.


**Thoughts:**
The official guide describes the optimisation techniques really well. This seems to be one aspect where Elm heavily influenced the design of react.
It also uses a virtual DOM to track changes and diffing to decide when the real DOM needs to update.
It also provides keys as an optional feature. React went one step further in this and made them a requirement for lists of elements.

Now that I know that Elm works with GraphQL, I think my next step will be a PoC with Elm and GraphQL subscriptions.


**Link to tweet** [Status Tweet]()

**Resources**
[Elm Offical Guide](https://guide.elm-lang.org/)
[Elm SVG Package](https://package.elm-lang.org/packages/elm/svg/latest)
[Elm Conf Repo (uses GraphQL)](https://github.com/elm-conf/2019.elm-conf.com)
[elm-graphql package](https://github.com/dillonkearns/elm-graphql)

