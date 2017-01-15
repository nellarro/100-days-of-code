# 100 Days Of Code - Log

##Day 13: January 14, 2017
#### ENKI

**Today's Progress**:
Photo-gallery is running a little better and published on github.io. **Five** FCC algorithms complete!

**Thoughts**: Algorithms. Honestly, I just want to fix my React projects but the quest for knowledge keeps me awake all day and night. I'm trying to understand these algorithms, understand the test cases so that I can become a better developer in the end. 

**Goals**: FIX. REACT. PROJECTS. ASAP.

**Links**:
- [Deployment through Github](https://medium.freecodecamp.com/surge-vs-github-pages-deploying-a-create-react-app-project-c0ecbf317089#.1cix6uu1b)
- ["Title Case a Sentence (without using CSS)" Solution](https://www.freecodecamp.com/challenges/Title%20Case%20a%20Sentence?solution=%0Afunction%20titleCase(str)%20%7B%0A%20%20str%20%3D%20str.toLowerCase().split(%22%20%22)%3B%0A%20%20for%20(var%20i%20%3D%200%3B%20i%20%3C%20str.length%3B%20i%2B%2B)%20%7B%0A%20%20%20%20str%5Bi%5D%20%3D%20str%5Bi%5D.charAt(0).toUpperCase()%20%2B%20str%5Bi%5D.slice(1)%3B%0A%20%20%7D%0A%20%20return%20str.join(%27%20%27)%3B%0A%7D%0A%0AtitleCase(%22I%27m%20a%20little%20tea%20pot%22)%3B%0A)
- ["Return Largest Number in Array" Solution](https://www.freecodecamp.com/challenges/return-largest-numbers-in-arrays#?solution=%0Afunction%20largestOfFour(arr)%20%7B%0A%20%20%2F%2F%20You%20can%20do%20this!%0A%20%20return%20arr.map(function%20(secondArr)%20%7B%0A%20%20%20%20return%20Math.max.apply(null%2C%20secondArr)%20%2F%2F%20Math.max%20does%20not%20accept%20arrays%20as%20arguments%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20that%27s%20why%20you%20use%20.apply()%20%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20apply()%20sets%20the%201st%20argument%20as%20%27this%27%20which%20you%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2F%2F%20do%20NOT%20want%20so%20you%20set%20as%20%27null%27%0A%20%20%7D)%0A%7D%0A%0AlargestOfFour(%5B%5B4%2C%205%2C%201%2C%203%5D%2C%20%5B13%2C%2027%2C%2018%2C%2026%5D%2C%20%5B32%2C%2035%2C%2037%2C%2039%5D%2C%20%5B1000%2C%201001%2C%20857%2C%201%5D%5D)%3B%0A)
- ["Confirm Ending" Solution](https://www.freecodecamp.com/challenges/confirm-the-ending#?solution=%0Afunction%20confirmEnding(str%2C%20target)%20%7B%0A%20%20if%20(str.substring(str.length%20-%201)%20%3D%3D%20target)%20%7B%0A%20%20%20%20return%20true%0A%20%20%7D%20else%20if%20(str.substring(str.length%20-4)%20%3D%3D%20target)%20%7B%0A%20%20%20%20return%20true%0A%20%20%7D%20else%20%7B%0A%20%20%20%20return%20false%0A%20%20%7D%0A%7D%0A%0AconfirmEnding(%22Bastian%22%2C%20%22n%22)%3B%0A%0A)
- ["Repeat a String" Solution](https://www.freecodecamp.com/challenges/Repeat%20a%20string%20repeat%20a%20string?solution=%0Afunction%20repeatStringNumTimes(str%2C%20num)%20%7B%0A%20%20%2F%2F%20repeat%20after%20me%0A%20%20if%20(num%20%3E%200)%20%7B%0A%20%20return%20str.repeat(num)%3B%0A%20%20%7D%20else%20%7B%0A%20%20%20%20return%20%22%22%0A%20%20%7D%0A%7D%0A%0ArepeatStringNumTimes(%22abc%22%2C%203)%3B%0A)
- ["Truncate a String" Solution](https://www.freecodecamp.com/challenges/Truncate%20a%20string?solution=%0Afunction%20truncateString(str%2C%20num)%20%7B%0A%20%20%2F%2F%20Clear%20out%20that%20junk%20in%20your%20trunk%0A%20%20%2F%2F%20shorten%20a%20string(str)%20if%20it%20is%20longer%20than%20the%20given%20maximum%20string%20length(num)%0A%20%20%2F%2F%20return%20string%20with%20...%20ending%20%0A%20%20if%20(str.length%20%3E%20num%20%26%26%20num%20%3E%203)%20%7B%0A%20%20%20%20str%20%3D%20str.substring(0%2C%20num-3)%20%2B%20%22...%22%0A%20%20%7D%20else%20if%20(str.length%20%3E%20num)%20%7B%0A%20%20%20%20str%20%3D%20str.substring(0%2C%20num)%20%2B%20%22...%22%0A%20%20%7D%0A%20%20return%20str%3B%0A%7D%0A%0A%2F%2F%20%0A%0AtruncateString(%22A-%22%2C%201)%3B%0A)

##Day 12: January 13, 2017
#### ENKI

**Today's Progress**:
Got photo gallery and Kiss N Makeup back online. FCC algorithm solved. Github was down in the morning.

**Thoughts**: Got a lot of constructive criticism today.

**Goals**: Work on more React projects to completion and push photo gallery to github.io.

**Links**:
- [FCC](https://www.freecodecamp.com/challenges/return-largest-numbers-in-arrays)

##Day 11: January 12, 2017
#### ENKI

**Today's Progress**:
Did all of the Enki challenges and games that were assigned today (git, Linux, JavaScript, and CSS).  

**Thoughts**: Honestly, a really great thing to do as a "day off" of coding while still coding. My brain isn't fried but I definitely learned a lot.

**Goals**: Get back in it tomorrow.

**Links**:
- [Enki](http://enkipro.com/)
- ![screenshot1](./images/enki-classes.PNG)


##Day 10: January 11, 2017
#### Linux, Portfolio, FCC

**Today's Progress**:
Completed the algorithm I was on on FCC. Successfully killed a process without having to Google it (finding the process was an hour long affair, however). Changed a font on my portfolio. Went to the CodePen meetup tonight.

**Thoughts**: I love React and <code>create-react-app</code> but sometimes, when I want to work outside of React and the project that I am in, I would like to not have to kill processess. Merp. But other than that it was fun playing CSI Jenell's computer! The CodePen meetup was super fun and I got to meet some wonderful people! The talks were great!

**Goals**: Complete the next algorithm challenge by week's end.

**Links**:
- [CodePen Meetup](https://nvite.com/OrlandoCodePen/dbf2)
- [Current Algorithm: Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)




##Day 9: January 10, 2017
#### Soft Skills

**Today's Progress**
Practiced a lot of soft skills today and put some in action. ODevs meetup. Currently finishing up [this algorithm test](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string) on Free Code Camp.

**Thoughts**: I love meeting new people. I love learning about other people and their perspectives!

**Goals**: Completely finish this algorithm, though.

**Links**:
- [Talk on Open Code](https://docs.google.com/presentation/d/1n92CP9eYAQ3HUDTkO8m103TUuWnEgrkqEN4qp-HkcGM/pub?start=true&loop=true&delayms=3000)

##Day 8: January 9, 2017
#### Kiss N Makeup @ Open Code Orlando

**Today's Progress**:
Broke the images while trying to understand how to delete them from Firebase.   

**Thoughts**:
[Open Code Orlando](https://www.meetup.com/Open-Code-Orlando/events/236564561/) is an amazing place to get work done and to meet new people who are doing things that you wouldn't even think of doing. Got a lot of great ideas today about working with chatbots, Raspberry Pi, Alexa, and holy all the Firebase help I could need.

Also, I went to sleep at 9:30pm. I woke up at 10pm because I freaked out that I hadn't committed anything on Github yet or posted anything. This is becoming **that** much of a habit now!

**Goals**:
Delete images. Still.
Also eventually checkout and complete this Pokemon chatbot:
- [Pokemon chatbot Tutorial (NodeJS)](https://chatbotsmagazine.com/a-nodejs-chatbot-tutorial-part-1-a2abd1b1c715#.e2gh5o2eh)

**Link to work**:
- [Code](https://github.com/nellarro/v2-kiss-n-makeup)
- [Kiss N Makeup live](https://nellarro.kiss-n-makeup.surge.sh)


##Day 7: January 8, 2017
#### Kiss N Makeup & JavaScript Koans


**Today's Progress**:
Fixed the footer problem on User component and Single Pic component. Also fixed the image problem on Single Pic.  

**Thoughts**:

![](http://i.giphy.com/LFphDKjQV17O0.gif)

Nuff said. :)

**Goals**:
Delete images.

**Link to work**:
- [Code](https://github.com/nellarro/v2-kiss-n-makeup)
- [Kiss N Makeup live](https://nellarro.kiss-n-makeup.surge.sh)


##Day 6: January 7, 2017
#### Kiss N Makeup


**Today's Progress**:
Still working on it but wanted to make sure I got something in here. Read up on the new Firebase Docs to see if Twitter authentication would be easier (it's not). Tried to fix some of the log-in errors like profile images not coming up if it's Twitter (yep, shade at Twitter right now). Trying to fix that atm. Ran <code>npm outdated</code>.

**Thoughts**:
Never will I ever eject from <code>create-react-app</code> for the sake of Sass when CSS now has variables. Also, webpack dashboard is cool and all but can't deal with the crashing when the page refreshes more than 10x. Also, it's hard to come back to a project that you haven't touched in a while and look at everything with fresh eyes. It's like: "Who wrote this and why does it look like that?! Why did you write that method there?! What's wrong with you?!" And then you realize that it was you and you do one of these ¯\_(ツ)_/¯. also <code>npm outdated</code> is a godsend!

**Goals**:
Get images to show up.

**Link to work**:
- [Code](https://github.com/nellarro/v2-kiss-n-makeup)
- [Kiss N Makeup live](https://nellarro.kiss-n-makeup.surge.sh)

## Day 5: January 6, 2017
#### Harley Quinn Photo Gallery (working title)


**Today's Progress**:
Unfortunately not a lot. Got <code>react-router</code> *sort of* working. Can't figure out why my button won't take the link route or change in the address bar.

**Thoughts**:
A little frustrating but I'm excited to continue tackling it tomorrow after I get some [Free Code Camp](https://www.freecodecamp.com/challenges/check-for-palindromes) in!

**Goals**:
Tackle this 100%.

**Link to work:**
- [Harley](https://github.com/nellarro/harley)



## Day 4: January 5, 2017
#### Harley Quinn Photo Gallery (working title)
#### Jr_Dev_Resource (a twitterbot)


**Today's Progress**:
Tinkered with my twitterbot for a few minutes so that it could run while I was working on the Harley project. Added <code>react-router</code> *finally*. Added gradients to the top and bottom of landing page to make it look completely like an Arkham thing. Added more fonts. Set up component layouts for the rules of the game as well as the <code>App</code> component.

**Thoughts**:
Since it is only a layout, it looks kind of janky to the naked eye right now code-wise. Visually it looks like it's supposed to do. It even has a little note from Harley in the console which is pretty nifty.

**Goals**:
Completely implement <code>react-router</code> and wireframing the two next JS file.

**Link to work:**
- [Harley](https://github.com/nellarro/harley)
- [bot](https://github.com/nellarro/twitterbot)
- [Twitter post](https://twitter.com/nellarro/status/817235098642903042)




## Day 3: January 4, 2017
#### Harley Quinn Photo Gallery (working title)

**Today's Progress**:
Finished the form as boring as I could make it! Added the bones of a motto at the bottom as a footer. More "styling".

**Thoughts**:
It is really taking EVERYTHING in me not to make the landing page look better. Right now it looks terrible (because it's meant to look like a low budget, couldn't care less, Arkham Asylum corporate log-in page). I'm pretty proud of it so far.

**Goals**:
Officially link in that Router to the submit button!

**Link to work:**
- [Harley](https://github.com/nellarro/harley)
- [Twitter](https://twitter.com/nellarro/status/816863403939692544)


## Day 2: January 3, 2017
#### Harley Quinn Photo Gallery (working title)

**Today's Progress**:
More design. Progress was a bit slower due to working on a FreeCodeCamp thing prior that gave me a brain fart.

**Thoughts**:
I am excited with its progress so far but I definitely need to put in more time.

**Goals**:
Get the landing page completely finished by tomorrow!


**Link to work:**
- [Harley](https://github.com/nellarro/harley)



## Day 1: January 2, 2017
#### Harley Quinn Photo Gallery (working title)

**Today's Progress**:
What I did was create the bare bones of the landing page so it has an input field where an "administrator" can submit their username and password to get to the inmate database.


**Thoughts**:
Got started a little late but decided to re-do one of my favorite web applications. The old one uses create-react-app out of the box from about 4 months ago so it is a little outdated. It also does not have React Router. I'm pretty excited about it!

**Goals**:
Still need to work on a lot of design choices and then will implement TypeJS and React Router on the submit button.


**Link to work:**
- [Harley](https://github.com/nellarro/harley)
- [Twitter Recap](https://twitter.com/nellarro/status/816084341390446592)



## Day 0: January 1, 2017
#### JavaScript Koans

**Today's Progress**: Worked on FreeCodeCamp during the day until 5:09 and then took a break to do JavaScript Koans and time myself. 5 out of 8 completed by 6:20. 4 checked by Jasmine.

**Thoughts:** Pretty excited about how well I did. I remember when the entire koan took me about 5 hours. Positive things that I noticed- I understand arr.shift(), arr.unshift(), arr.pop(), and arr.push() a ton more than what I did before! Needs improvement: lexical scopaing and arr.slice().

**Goals:** Make JavaScript Koans part of my weekly ritual. Each Sunday, I'll repeat koans from scratch and see if my time gets better and what things I understand more.

**Link to work:**
- [JavaScript Koans Day 0](https://github.com/nellarro/javascript-koans)
- [Twitter Recap](https://twitter.com/nellarro/status/815701265908895744)
