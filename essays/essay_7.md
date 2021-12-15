---
layout: essay
type: essay
title: Class Retrospective BLOG
date: 2021-12-14
labels:
  - Assignment3
---

<h3>Briefly describe your system (e.g. A store selling Pokemon game cards)</h3>
This is a store that sells tennis gear. It’s like a general sports shop, but with an emphasis on tennis. We sell anything from rackets and tennis balls to tennis shoes and clothes.

<h3>Any notable shortcomings, bugs, problems, or additional features not implemented?</h3>     
Overall, I’ve managed to settle most of the problems. There’s still a few UI design errors that show up depending on how you resize the window or if you use the website on a different browser, but I consciously decided to settle with I had for the sake of time. A feature that I really wanted to add was the ability to automatically log someone out after inactivity of 30 minutes. Currently, I have it set up so the cookie expires after 30 minutes and so they get logged out regardless if they were browsing for the whole 30 minutes or not. 

<h3>Describe what you are most proud of about your system:</h3>
One of the last things I did was find a way to update the total amount we had in stock for a particular item if a user were to make changes after they added it to cart. Initially, since I was removing quantities from the inventory as soon as a user clicks the add to cart button, it wouldn’t update the stock available. That would result in this weird thing happening where sometimes, you wouldn’t even be able to get the current amount of items that you had in your cart because it would be compared to the stock amount property of the item, and it would see that it was more than the updated quantity after clicking the add to cart and prevent you from purchasing it. I literally sat down for 4 hours thinking it out and writing the what I wanted to happening in sudo code. FINALLY I thought up a solution, implemented the code, and it worked! I don’t know if it’s just because it is fresh in memory, or that I’m genuinely proud of it; regardless, I’m sooo happy that it’s working.

<h3>Describe what you are least happy with your system:</h3>
I am not happy with the design aspects. There are a ton of visual issues that arise from resizing the window. But the website itself is operational despite that so I decided to overlook that.  

<h3>How was developing this assignment different than assignment #2?</h3>
It was different in it that this assignment required me to read more on sessions. For some reason, during the class lab, although I was following along, but I couldn’t wrap my mind around how a session could be used for a shopping cart. Basically, I had to do more reading/watching youtube tutorials (specifically about sessions and cookies) than I had to in the previous assignments. My initial lack of understanding was probably why the brainstorming of how to approach assignment 3 took so long.

<h3>When you ran into a problem, what did you do to address it?</h3>
My problems mostly arose during the brainstorming portion of writing the code. There are some things that I was just completely blank on. Whenever that happened, I would write down what I wanted to happen in steps, then in sudo code, and then finally actual code. It worked for the most part, and, if it didn’t, I would just use google to find documentation.

<h3>Describe what worked well in doing this assignment?</h3>
Actually reading the documentation worked really well. I definitely relied on documentation on this assignment much more than I did in previous assignments. Also, opening my note pad and writing down the steps that I wanted to happen for a specific feature I was working on worked really well. 

<h3>Describe what did not work well in doing this assignment?</h3>
Trying to figure out how I could use sessions without really having a base understanding of it. That seems like a horrible way to approach an assignment in hindsight. After reading the documentation, It turned out to be much simpler than what I initially thought.

<h3>What did you learn from doing this assignment?</h3>
I learned that maybe I should anticipate future assignments, especially if it builds off of the previous one. Thinking about future requirements would have saved me so much time. It took a good chunk of time just getting a working assignment 2 again after changing a few things for assignment 3. 

<h3>If you could go back in time and do things differently, what would you change?</h3>
I would have started this assignment even earlier. I started before the checkpoint for the assignment was due, but even then I feel like I didn’t have enough time. A huge portion of it was also changing assignment 2 code to fit the new assignment 3 requirements (i.e., changing the product data to include 3 categories).

<h3>Estimate the % of time you spent (a) thinking about how to do something, (b) writing code (but do not include testing, (c) testing and debugging</h3>
I must’ve spent 75% of the time thinking about how to do something because I initially could not wrap my head around sessions and then when I read the documentation about it, I realized that it was actually so simple. Writing the code probably took up about 10% of the time because, as I said, once I thought out how to do something, it wasn’t too hard to implement it. Testing and debugging probably took like 5% of the time. I got pretty quick at reading the error message and then seeing what line it was and fixing it.


<h3>Assign an estimated percentage on the amount each team member contributed to the assignment (including yourself) and explain briefly your rationale for the percentage breakdown. Be sure to include an overview of what specifically you and your partners contributed (e.g. “I worked on the security and my partner 1 worked on personalization”)</h3>
I worked on the project entirely on my own so I’d say I contributed 100%.
     

