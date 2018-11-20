---
layout: page
title: User Experience Design Overview
---

# Personal CuraTour 
## Your museum experience, a bit *more* guided. 

--------------------------

# People bound by fate to work on something wonderful

Geoffrey - Run-on sentence kingpin

Julia - 4th dimensional support ferret

Kelvin - ProcrastinaTour Lvl 2

# Problem and Solution Overview

You enter a museum. What’s the first thing you do?...

Different museum visitors have different levels of enthusiasm, experience, and willingness to explore; yet the physical constraints of museum curation means that there are no ways to flexibly account for these drastically different levels of use. This makes museums less accessible for some, while others may be less engaged due to the implicit fragmentation of content and context. Our goal is to make museum visits more effortless, immersive and complete for everyone, regardless of enthusiasm, motivation, and prior knowledge. This can be done through optional curated or community sourced guidance, as well as curated narrative elements that tie together a visitor’s experience.

We chose to implement the watch app paired with wireless earbuds to accomplish two tasks: encourage exploration as intended by curators/suggested by community members and explore the museum as the user wants. Our design aims to be unobtrusive and seamless, augmenting rather than overpowering the already stimulating experience of visiting a museum, accomplishing tasks that our target audience has shown a need for.

# Initial Paper Prototype 

![](https://krtejeda.github.io/PersonalCuraTour/img/watch_12.jpg)

The goal of our initial design is to be simple and clean, presenting an intuitive interface that makes it easy for the visitor to get started, while also receding into the museum experience so to no obtrude from said experience. 

This goal is mainly accomplished through seamless deliverance of audio and navigation instructions. Specifically, the audio snippets, which are played at key moments during the user’s experience and are typically mapped to physical locations in the museum via GPS, supplement the placards in the museum and allow the user to place full attention on the surrounding exhibit. Navigation is communicated through haptic vibrations so that the user can spend more time staring at the art, and trust that they only have to look at the watch when they have to make a turn.

The user has two options upon opening the app: “free roam” or “tour.” These two options reflect our two main tasks: explore the museum as intended and explore the museum whatever way makes sense to you. If the user chooses free roam, they begin exploring the museum at their own pace but have their experience supplemented with appropriate context via audio. The artworks that the user visits are saved so that once they are done, they can save their path, provide a title, and upload it for other visitors to experience what they experienced! On the other hand, if the user chooses a guided tour from the selection of community or curator sourced tours, they are provided navigation instructions for the tour that they selected. These tours are also supplemented with audio to further immerse the user in the experience. Upon completion of a tour, they rate the tour on a scale of one to five stars. 

# Testing Process

We conducted usability tests on Geneviëve, Nüelf, and Kwintïn. All of our usability tests were conducted by different pairs of two of our team members. One of us took notes and recorded the feedback while the other member ran the usability test.

Our initial test protocol was as follows. We first introduced ourselves and briefed them on the purpose of this usability test, their role, and our project, before asking for their consent to record audio of the interaction. They were told that if they wanted to stop participating at any time, they were free to do so. Next, before we started the testing, we encouraged them to think aloud during their use of the app, verbally saying their thoughts on the design of the app, the experience, or anything that wasn’t clear or effective to them. After demonstrating this think-aloud process, we further clarified that we were not evaluating them, only our design.

After our first usability test, we refined our usability test to simulate the museum environment more accurately. We had our participants imagine that they were in a museum and that they had just opened the app on there watch. We had pretend art pieces on a wall and prepared a description that one of us would recite to simulate the audio of our system. We presented them with two tasks: exploring the museum as intended and exploring the museum as they want. After this point, we notified them that we would not give further instruction in order to capture how they navigate the interface on their own. They completed both tasks without any major mishaps and thought aloud the whole way through.


# Testing Results 

The test subjects generally viewed the design positively, but also identified a plethora of smaller design flaws that were unclear. 

Our first test subject, Geneviëve, focused more on the aesthetic aspects of the design.  She generally responded well to the arrangement and layout of the watch application, but had smaller suggestions on the arrangement of the icons and text.  For one thing, she felt that the number indicating the user’s distance from an art piece could be moved closer to the directional arrow, in order to better associate the two.  It also felt important for her to clearly be able to select between the guided tours created by other users, versus those made by curators.  Lastly, she was also confused by how to navigate after the audio had ended: "When the audio is over, do I click end?"  This contributed to us changing the way in which the interim watch face was arranged--we adjusted how the transitions between the audio occurred. Something to note is that this problem came up again in our second test, upon which we finally overhauled the design to a satisfactory level. Overall, this first test provided a good starting point for our next two.

Our second subject, Nüelf, an extremely avid museum goer, uncovered similar details in the design that we had not thought through enough from the perspective of the user.  For one thing, the ambiguity of the transition between subsequent pieces, perhaps partially emergent from the fact that the paper prototype would ostensibly have slower response than an actual smartwatch, threw Nüelf off.  He also wasn’t sure how he could move on to the next piece if he wanted to skip through the current one--a valid confusion since we had implicitly implemented this by allowing the user to fast forward in the audio clip.  Since this initial approach was evidently unclear, we added a button to allow users to skip onto the next piece.  Nüelf also didn’t necessarily want to create a tour with every free roam experience; taking this into account, we removed this default tour creation to a deliberate “create tour” mode in the application.  In general, though, Nüelf resonated with the fundamental idea of the guided tour portion of our app, relating the design to a less-satisfactory experience he had recently had at a museum: “I could really see how the navigation application could be useful.  I went to a museum recently and they had a similar system but where the destinations were all numbers on a small map.  You couldn’t really find each one without walking all over.”

Our final subject, Kwintïn, was not highly experienced with museums.  He generally followed along well with the app; the buttons made sense to him, as did the directions displayed the tour.   Most of interactions and thoughts he shared reflected comprehension of the app and usage along the expected paths, as we had him test out all possible use cases.  However, he did not understand how to name the tour he created when under the “create a tour” mode.  We initially implemented a system that allows users to draw each letter they wish to enter, but this was not apparent to our subject.  He felt it would be easier to have the user input title via audio, or at least have the option to, so we added the ability to choose between the different input modes at this point of use.  Kwintïn also did not pick up on the ability to scroll during the tour to view one’s viewing history; this led us to rethink our design and move this feature to the end of a tour, given that there would be a lot of information presented during the tour already.  He noted: "It would be better if I could input the title using voice." Overall, though, Kwintïn felt that the application made sense and could have useful impact in a museum.

# Final Paper Prototype

Present your final version of your paper prototype, as you did for your initial paper prototype above. Convey the critical aspects of your design, including your two primary tasks.

We retained the critical aspects of our original paper prototype in our final prototype while revising certain aspects according to Nielsen’s heuristics.  Some of the problems that were addressed in the revision of the paper prototype were incorporating a consistent and clear mental model for the  user to understand their affordances in our design. Another thing that became a critical component of the design was ensuring that we allowed the user to always have control over their actions. This involved the addition of  the “No Audio” option for users, the option to skip the piece that they are at in a tour, and the ability to view a history of the pieces visited. One of the largest changes that we made was we distinguished between a free explore option and creating a tour. This option was added to our main screen to clarify exactly what pressing the button will lead to which connects to our general work of clarifying actions possible in our design, in reflection of the notion that not all users will want to upload their tours.  Another change that was made in the final paper prototype was the addition of the choice between input methods for the title of the user generated tour. This adds to the user’s control and accounts for differences in accessibility. The two primary tasks have not changed from the original prototype. Major changes in the free roam task are that the user may choose not to have audio and on the explore screen there is a prompt that says “go find a piece of art”. The major changes in the tour task are that we added a menu so the user can decide between curator created tours and user generated tours, however other than this the task remains the same. 

![](https://krtejeda.github.io/PersonalCuraTour/img/overview3_noLetters.jpg)

# Digital Mockup

Present your digital mockup. Convey the critical aspects of your design, including your two primary tasks. Briefly discuss any changes you needed to make as you switched to your digital tools instead of paper. Briefly discuss any changes you made in response to critique. Include descriptions of how your design supports each of your primary tasks (e.g., one paragraph per task).

The important aspect of our design was the ability to seamlessly enhance the visitor’s museum experience with relevant context for art pieces, regardless of their decision to explore or navigate through the museum. To support this, we had to make sure that the design was easily interpretable and accessible throughout the museum experience. However, we also didn’t want the design to be a constant distraction so that the museum experience could remain the focus. Luckily, both these goals complement each other and we were able to make a lightweight and effective design.
Changes we made in response to critique were reflected in the final paper prototype, however some design decisions were made during the implementation of the digital mock-up. Transitioning from a paper prototype to digital mockup meant that the visual identity of our app, which we had largely ignored during our paper prototypes that tested for functionality, now had to be carefully considered. Since we were constrained by the limited screen size of the watch modality, we used our space wisely by carefully considering the necessity of each piece we present to our users. To facilitate rapid comprehensions we added small icons to the buttons on our home screen; this adds another way for users to interpret the labels--important for those who may not be as fluent in English.  Since the colors chosen would have an increased effect on usability in such small form factor, as mentioned in our readings, we sought to find a color palette optimized for small screens. Therefore, we referenced Apple’s Apple Watch visual identity documentation, which contains guidelines for our very purpose. This led us to design an app with a black background, buttons of at least 52 pixels in width, and high contrast, neon-like colors. Again based on Apple’s recommendation, we chose the SF Compact Design font that is highly readable at small screen sizes. Our goal with following these recommendations was to not only produce a design consistent with other applications ostensibly on the user’s watch, but also to produce a final design that is highly usable, even for users who may be visually impaired.
The task of exploring the museum according a guided tour was enhanced in several respects with our alterations in transitioning to a digital prototype. For one thing, we added icons to the home screen that first appears, not only adding more visual dynamism through the color of the small pictures, but also making the home screen more accessible for those who may not be highly fluent in English. In short, they help users to more quickly interpret the meaning of the buttons.  We also added text to the back buttons, again to increase clarity and accessibility. Finally, we made two major alterations to the screens that control the audio playback. First, we overlaid the pause/play button on top of the painting icon that appears when the user arrives at a destination; this provides a more direct metaphor towards what the icon does, while also allowing us to maximize the space-efficiency of our design. Second, we also made the option to skip to the next piece in the experience a separate button, in response to our user tests. This clarity is important in allowing users to have an enhanced feeling of control over their experience.  
The same changes mentioned for the guided tour task also apply to the other main task, free roaming the museum while learning more about the art. The changes mentioned for the first task all carry over to this one, since the only major difference between the two is that the user is guided between the pieces in sequence during the first task. One thing to note is that the skip button does not necessarily have as powerful an effect in this case, since it merely causes the current audio the user is listening to cease and disappear, returning the user to the interim screen that waits for the user to physically approach another piece it can prompt on. Also worth mentioning but not directly related to the task was the choice made to follow the visual identity of Apple, along with using neon colors that contrast well with the black background--both of these changes helped increase the clarity and accessibility of our app.  

# Discussion

This is new content to generate! Reflect upon and discuss your project and your results. For example: What did you learn from the process of iterative design? How did the process shape your final design? How have your tasks changed as a result of your usability tests? Do you think you could have used more, or fewer, iterations upon your design?

This process has led to the exciting realization that despite our lack of refined artistic prowess, by utilizing appropriate design tools and techniques, even we can create a usable interface and design that we are proud to call ours.  
One important lesson we learned from the iterative design process is that each user test can uncover new confusing bottlenecks in our app design, but what one user finds confusing another may find clear. An example of this was with the apparent clarity/confusion of the title input method for user created tours. One of our test subjects failed to catch on to the implication that he should draw letters on the screen to input the title, but all the other users deciphered this functionality as intended. We ultimately felt that one instance of confusion outweighed the ease of use experienced by the other two users, and decided to add the option of verbal input for the title. However, we also recognize that it is not always possible to account and accomodate for all opinions; in a different case we may have chosen to ignore the one confused user.  

We also learned that testing uncovers the model and flow of the design as perceived by the user. Since we spent countless hours plotting out the flow of our design, we already had a strong mental model of what the intended functionality. When creating our design, we sometimes overlooked certain things that would be confusing to new user because they were extremely familiar to us; in essence, we did not truly interpret the meaning of “the user is not like you.”  This resulted realization led us, for example, to add the skip button that was initially embedded implicitly in the audio playback keys. This overall process shaped our design into a more interpretable and intuitive design, but the fundamental tasks and features largely stayed the same. We did separate the task of creating a tour from the free roam option by adding “create a tour” as a separate option in the menu, since users might want to be more deliberate when creating a tour.
Ultimately, our design is far from perfect, and more feedback via testing is always welcomed. We especially would have liked to test our digital mockup to gauge the effect of the significant changes that it incorporated. However, we flexibility of the paper prototype meant it was easy to edit the prototype before the next test, allowing us to obtain the most relevant feedback. As a result, we hope that this allowed us to uncover as many design flaws as possible. 


