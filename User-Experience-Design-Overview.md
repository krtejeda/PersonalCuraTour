---
layout: page
title: User Experience Design Overview
---

# Personal CuraTour 
## Your museum experience, a bit *more* guided. 

--------------------------
--------------------------
--------------------------

# People bound by fate to work on something wonderful

Geoffrey - Run-on sentence kingpin

Julia - 4th dimensional support ferret

Kelvin - ProcrastinaTour Lvl 2

# Problem and Solution Overview

You enter a museum. What’s the first thing you do?...

Different museum visitors have different levels of enthusiasm, experience, and willingness to explore; yet the physical constraints of museum curation means that there are no ways to flexibly account for these drastically different levels of use. This makes museums less accessible for some, while others may be less engaged due to the implicit fragmentation of content and context. Our goal is to make museum visits more effortless, immersive and complete for everyone, regardless of enthusiasm, motivation, and prior knowledge. This can be done through optional curated or community sourced guidance, as well as curated narrative elements that tie together a visitor’s experience.

We chose to implement the watch app paired with wireless earbuds to accomplish two tasks: encourage exploration as intended by curators/suggested by community members and explore the museum as the user wants. Our design aims to be unobtrusive and seamless, augmenting rather than overpowering the already stimulating experience of visiting a museum, accomplishing tasks that our target audience has shown a need for.

Read our full project proposal at [Project Proposal](https://krtejeda.github.io/PersonalCuraTour/Project-Proposal/)

# Initial Paper Prototype 

![](https://krtejeda.github.io/PersonalCuraTour/img/watch_12.jpg)
Full version at [Paper Prototype](https://krtejeda.github.io/PersonalCuraTour/Paper-Prototype/)

The goal of our initial design is to be simple and clean, presenting an intuitive interface that makes it easy for the visitor to get started, while also receding into the museum experience so to no obtrude from said experience. 

This goal is mainly accomplished through seamless deliverance of audio and navigation instructions. Specifically, the audio snippets, which are played at key moments during the user’s experience and are typically mapped to physical locations in the museum via GPS, supplement the placards in the museum and allow the user to place full attention on the surrounding exhibit. Navigation is communicated through haptic vibrations so that the user can spend more time staring at the art, and trust that they only have to look at the watch when they have to make a turn.

The user has two options upon opening the app: “free roam” or “tour.” These two options reflect our two main tasks: explore the museum as intended and explore the museum whatever way makes sense to you. If the user chooses free roam, they begin exploring the museum at their own pace but have their experience supplemented with appropriate context via audio. The artworks that the user visits are saved so that once they are done, they can save their path, provide a title, and upload it for other visitors to experience what they experienced! On the other hand, if the user chooses a guided tour from the selection of community or curator sourced tours, they are provided navigation instructions for the tour that they selected. These tours are also supplemented with audio to further immerse the user in the experience. Upon completion of a tour, they rate the tour on a scale of one to five stars. 

# Testing Process

Our first experience with usability testing came in class, during heuristic evaluations done with other groups. Those results are summarized at [Heuristic Evaluation](https://krtejeda.github.io/PersonalCuraTour/Heuristic-Evaluation/).

We conducted usability tests on Geneviëve, Nüelf, and Kwintïn. All of our usability tests were conducted by different pairs of two of our team members. One of us took notes and recorded the feedback while the other member ran the usability test.

Our test protocol was to first introduced ourselves and brief them on the purpose of this usability test, their role, and our project. This was followed by asking for their consent to record audio of the interaction. They were told that if they wanted to stop participating at any time, they were free to do so. Next, before we started the testing, we encouraged them to think aloud during their use of the app, audibly sharing their thoughts on the design, the experience, or anything that wasn’t clear or effective to them. After demonstrating this think-aloud process, we further clarified that we were not evaluating them, only our design.

One at a time, we presented them with two tasks: exploring the museum as intended and exploring the museum as they want. After this point, we notified them that we would not give further instruction in order to capture how they navigate the interface on their own. They completed both tasks without any major mishaps and thought aloud the whole way through. After our first usability test, we refined our usability test to simulate the museum environment more accurately. We had our participants imagine that they were in a museum and that they had just opened the app on there watch. We had pretend art pieces on a wall and prepared a description that one of us would recite to simulate the audio of our system. The hope of this change was to capture any nuances in the time to travel between art pieces and how people interpreted how to activate the audio.

# Testing Results 

The test subjects generally viewed the design positively, but also identified a plethora of smaller design flaws that were unclear. 

![](https://krtejeda.github.io/PersonalCuraTour/img/prototypeEdits.JPG)
*Labels in the text associate with the overview photo above

Our first test subject, Geneviëve, focused more on the aesthetic aspects of the design.  She generally responded well to the arrangement and layout of the watch application, but had smaller suggestions on the arrangement of the icons and text.  For one thing, she felt that the number indicating the user’s distance from an art piece could be moved closer to the directional arrow, in order to better associate the two. (screen D)  It also felt important for her to clearly be able to select between the guided tours created by other users, versus those made by curators.  Geneviëve was also confused by the scroll bar, and felt that it should be depicted more clearly--this was supposed to allow users to view the history of pieces they had visited, but is something we later removed (screen D/E/F).  Lastly, she was also confused by how to navigate after the audio had ended: "When the audio is over, do I click end?" (screen F)  This contributed to us changing the way in which the interim watch face was arranged--we adjusted how the transitions between the audio occurred. Something to note is that this problem came up again in our second test, upon which we finally overhauled the design to a satisfactory level. Overall, this first test provided a good starting point for our next two.

Our second subject, Nüelf, an extremely avid museum goer, uncovered similar details in the design that we had not thought through enough from the perspective of the user.  For one thing, the ambiguity of the transition between subsequent pieces, perhaps partially emergent from the fact that the paper prototype would ostensibly have slower response than an actual smartwatch, threw Nüelf off.  He also wasn’t sure how he could move on to the next piece if he wanted to skip through the current one--a valid confusion since we had implicitly implemented this by allowing the user to fast forward in the audio clip (screen F).  Since this initial approach was evidently unclear, we added a button to allow users to skip onto the next piece.  Nüelf also didn’t necessarily want to create a tour with every free roam experience; taking this into account, we removed this default tour creation to a deliberate “create tour” mode in the application.  In general, though, Nüelf resonated with the fundamental idea of the guided tour portion of our app, relating the design to a less-satisfactory experience he had recently had at a museum: “I could really see how the navigation application could be useful.  I went to a museum recently and they had a similar system but where the destinations were all numbers on a small map.  You couldn’t really find each one without walking all over.”

Our final subject, Kwintïn, was not highly experienced with museums.  He generally followed along well with the app; the buttons made sense to him, as did the directions displayed the tour.   Most of interactions and thoughts he shared reflected comprehension of the app and usage along the expected paths, as we had him test out all possible use cases.  However, he did not understand how to name the tour he created when under the “create a tour” mode.  We initially implemented a system that allows users to draw each letter they wish to enter, but this was not apparent to our subject (screen C). He felt it would be easier to have the user input title via audio, or at least have the option to, so we added the ability to choose between the different input modes at this point of use.  Kwintïn also did not pick up on the ability to scroll during the tour to view one’s viewing history; this led us to rethink our design and move this feature to the end of a tour, given that there would be a lot of information presented during the tour already (screen D/E/F).  He noted: "It would be better if I could input the title using voice." Overall, though, Kwintïn felt that the application made sense and could have useful impact in a museum.

The full results for our usability tests can be found in our [Usability Testing Review](https://krtejeda.github.io/PersonalCuraTour/Usability-Testing-Review/), with more detailed breakdown of the first Usability Test we conducted in our [Usability Testing Check-In](https://krtejeda.github.io/PersonalCuraTour/Usability-Testing-CheckIn/).  Both also discuss the testing process we used.

# Final Paper Prototype

![](https://krtejeda.github.io/PersonalCuraTour/img/overview3.jpg)
*Labels in the text associate with the overview photo above

We retained the critical aspects of our original paper prototype in our final prototype while revising certain aspects according to Nielsen’s heuristics.  Some of the problems that were addressed in the revision of the paper prototype were incorporating a consistent and clear mental model for the  user to understand their affordances in our design. Another thing that became a critical component of the design was ensuring that we allowed the user to always have control over their actions. This involved the addition of  the “No Audio” option for users, the option to skip the piece that they are at in a tour (B), and the ability to view a history of the pieces visited (L). One of the largest changes that we made was we distinguished between a free explore option and creating a tour (A). This option was added to our main screen to clarify exactly what pressing the button will lead to which connects to our general work of clarifying actions possible in our design, in reflection of the notion that not all users will want to upload their tours.  Another change that was made in the final paper prototype was the addition of the choice between input methods for the title of the user generated tour (M). This adds to the user’s control and accounts for differences in accessibility. The two primary tasks have not changed from the original prototype. Major changes in the free roam task are that the user may choose not to have audio and on the explore screen there is a prompt that says “go find a piece of art” (G) to mimimize ambiguity. The major changes in the tour task are that we added a menu so the user can decide between curator created tours and user generated tours (D), however other than this the task remains the same. 


# Digital Mockup

![](https://krtejeda.github.io/PersonalCuraTour/img/mockupReview2.png)
![Walkthrough of the free roam task on our digital mockup](https://krtejeda.github.io/PersonalCuraTour/img/mockupReview1.png)


The important aspect of our design was the ability to seamlessly enhance the visitor’s museum experience with relevant context for art pieces, regardless of their decision to explore or navigate through the museum. To support this, we had to make sure that the design was easily interpretable and accessible throughout the museum experience. However, we also didn’t want the design to be a constant distraction so that the museum experience could remain the focus. Luckily, both these goals complement each other and we were able to make a lightweight and effective design.

Changes we made in response to critique were reflected in the final paper prototype, however some design decisions were made during the implementation of the digital mock-up.  In implementing visual identity, we sought a color palette and font choice that would maximise legibility on a small screen.  To this end we made the following design choices, many based off of Apple's guidelines for Apple Watch visual identity, that apply to both tasks:
 
- Black background
- Buttons at least 52 pixels in width, making them easier to tap accurately
- Color palette comprised of high contrast, neon-like colors, maximising legibility against black background
- SF Compact Design Font, which is highly readable at small screen sizes

We also made the following revisions to the design itself for the guided tour option:

- Added icons to the home menu, improving user comprehension, especially for those who do not speak English
- Added text to the back button, to clarify its function
- Overlaid pause/play button on top of painting during audio playback, maximizing screen usage and creating visual metaphor
- Added separate button to skip piece in tour, enhancing sense of user control and removing confusing prior implementation 

These largely all apply to our other task, free roaming the museum.  However, there is no skip button in free roam since there is no tour the user is following.

Full analysis and walkthrough of our digital prototype can be found at our [Digital Prototype Overview](https://krtejeda.github.io/PersonalCuraTour/Digital-Mockup/).

# Discussion

This process has led to the exciting realization that despite our lack of refined artistic prowess, by utilizing appropriate design tools and techniques, even we can create a usable interface and design that we are proud to call ours.  
One important lesson we learned from the iterative design process is that each user test can uncover new confusing bottlenecks in our app design, but what one user finds confusing another may find clear. An example of this was with the apparent clarity/confusion of the title input method for user created tours. One of our test subjects failed to catch on to the implication that he should draw letters on the screen to input the title, but all the other users deciphered this functionality as intended. We ultimately felt that one instance of confusion outweighed the ease of use experienced by the other two users, and decided to add the option of verbal input for the title. However, we also recognize that it is not always possible to account and accomodate for all opinions. As such, it was a difficult balancing act between preserving our desire to produce a lightweight and simple design, but adequately support user needs.

We also learned that testing helps uncover the true model and flow of the design. We spent countless hours plotting out the flow of our design, so our rich mental model deceived us into believing our design was clearly interpretable. As a result, we sometimes overlooked certain features that would end up confusing new user because we were extremely familiar with the meaning and the context; in essence, we did not truly interpret the meaning of “the user is not like you.” Luckily, this overall process shaped our design into a more interpretable and intuitive design thanks to the user feedback. The fundamental tasks and features largely stayed the same, although we did rebrand our task of “understanding the art” into “explore the museum as you want” because “understanding the art” is a task that is accomplished regardless of the level of guidance. 

Ultimately, our design is far from perfect, and more feedback via testing is always welcomed. We especially would have liked to test our digital mockup to gauge the effect of the significant changes that it incorporated. However, we appreciated the flexibility of the paper prototype because it was easy to incorporate new edits before the next test, allowing us to obtain the most relevant feedback. As a result, we hope that this allowed us to uncover as many design flaws as possible. 

# Appendix of Previous Deliverables

- [Paper Prototype](https://krtejeda.github.io/PersonalCuraTour/Paper-Prototype/)
- [Heuristic Evaluation](https://krtejeda.github.io/PersonalCuraTour/Heuristic-Evaluation/)
- [Usability Testing Checkin](https://krtejeda.github.io/PersonalCuraTour/Usability-Testing-CheckIn/)
- [Usability Testing Review](https://krtejeda.github.io/PersonalCuraTour/Usability-Testing-Review/)
- [Prototype Overview](https://krtejeda.github.io/PersonalCuraTour/Digital-Mockup/)
- [User Experience Design Overview](https://krtejeda.github.io/PersonalCuraTour/User-Experience-Design-Overview/)

