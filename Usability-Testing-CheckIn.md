---
title: Usability Testing Checkin
layout: page
---

# Overview

We completed cognitive walkthroughs of our two tasks, as well as a usability test with one user who was moderately experienced with museums.

# Cognitive Walkthroughs

![](https://krtejeda.github.io/PersonalCuraTour/img/cogWalkthrough1.jpg)

![](https://krtejeda.github.io/PersonalCuraTour/img/cogWalkthrough2.jpg)

## Issues uncovered during walkthrough

| Photo of Prototype | Description of Incident | Photo of Revision |
| -------- | -------- | -------- |
| A | In our screen for selection of a guided tour, it is not evident that the buttons select for exhibits.  It is not clear from the buttons that what kind of tour is being selected, one that focuses on an exhibit or the entire museum, for example, or even the creator of the tour.  |  F/G |
| -------- | -------- | -------- |
| B | Need a “no audio” option for those who just want guidance to pieces, without voice-overs playing. | H |
| -------- | -------- | -------- |
| C | There is no option for the user to not rate the tour, but we are not giving users the option to not rate tours in order to force the generation of sufficient feedback | No revision made |
| -------- | -------- | -------- |
| D | The end experience button should be an ‘x’ instead of an arrow, to more graphically correspond with the action being executed | I |
| -------- | -------- | -------- |
| E | The user might want the option to enter the title of the tour differently--for example, to enter the title via voice input.  We will not make this change because it would disrupt the quiet environment of a museum  | No revision made |
| -------- | -------- | -------- |

![](https://krtejeda.github.io/PersonalCuraTour/img/cogWalkthroughImg.jpg)

![](https://krtejeda.github.io/PersonalCuraTour/img/cogWalkthroughFix.jpg)


# Usability Test 1

Our first usability test was conducted by two of our team members. One of us solely took notes and recorded the feedback while the other member ran the usability test. We conducted our first usability test on Geneviëve, a studio art major at Williams, in a Schow study room. This participant was ideal because of her visual/aesthetic expertise and willingness to provide constructive feedback. She also spends a lot of time at museums due to her interest in art, so we consider her to be museum adept. The location was ideal because it provided us the freedom to move around and speak freely. 

Our test protocol was as follows. We first introduced ourselves and briefed them on the purpose of this usability test, their role, and our project. We asked if it was okay to collect their feedback via voice recording and note taking and they allowed it. We reassured them that if at anytime they wanted to stop participating, they were free to do so. Next, before we started the testing, we emphasized the importance that she share her thoughts/criticisms about the design of the app, the experience, or anything that wasn’t clear or effective to her. She was made aware that these comments would be used to iterate and improve the design. 

Then we began testing the prototype. She was prompted to imagine that she was in a museum and that she had just opened the app on her watch. We presented her with two tasks: exploring the museum as intended and exploring the museum as they want, and allowed her to explore.  After this point, we stopped giving her further instruction unless she was absolutely stuck, which fortunately never happened. She completed both tasks without any major mishaps, but she did provide feedback through her comments on how the experience could be improved, which we mention later. 

After we finished our usability test, we learned to not underestimate the importance of having smooth and seamless transitions between frames. Our test felt disjointed at some points due to the lag between subsequent frames introduced by physical limitations of our prototype. We felt that this ruined whatever semblance of immersion the user had, and potentially limited the serious feedback they provided. We will organize our frames better so that we can have a smooth testing experience. 

We also learned that it is difficult to elicit the thought processes of the user. They interpreted our desire for audible feedback as having reactionary responses to certain frames, when what we really wanted was the reasoning behind those reactions. We didn’t realize how often we would have to probe the user for more substantive content/feedback. In the future, we will be more clear about the type of feedback that we want by giving an example.

*Letters in table below correlate to photos above

| Photo of Prototype | Description of Incident | Severity (if neg) | Revision |
| -------- | -------- | -------- | -------- |
| D | In progress - the user was confused as to the meaning of the “in progress” screen most likely due to vagueness or lack of context | 3 | Removed the words “In progress” |
| -------- | -------- | -------- | -------- |
| A | Scrolling option for in tour experience - not clear exactly what effect scrolling will have. User said she would normally just try this feature to see what would happen. Suggested a couple of possible fixes.  | 3 | We are going to hold off on fixing this to see what other usability tests generate for this feature. |
| -------- | -------- | -------- | -------- |
| C | “Community Experience” text on menu for tours was not clear. User did not know what that meant and suggested a different way to differentiate between curator and user created tours. | 2 | Created a new screen to choose between curator and user submitted tours. |
| -------- | -------- | -------- | -------- |
| photo below | User noted a lot of info on the navigation screen compared to others, user suggested clustering the information that is related, art and navigation elements.  | 2 | Move the distance to the piece to be closer to the arrow for directions so that all the navigational elements are clustered together. |
| -------- | -------- | -------- | -------- |
| B | User struggled to know what to do and expect when the audio ended.  It was not clear where the start and end occured after the audio played; this may be more clear if there were actual audio playing, and the context was more clear since the watch face should transition automatically in a real version of the app, but did not in this case.   | 2 | No changes, will wait to see if other users have different response, will see if more realistic audio in future tests (see below) has an effect. |
| -------- | -------- | -------- | -------- |

Aside from flaws in our process itself, the usability test was also instrumental in uncovering flaws in our design.  These are detailed below on the table, but were, in this case, primarily flaws in the user interface.   There were flaws identified in a variety of areas.  Selecting tours elicited confusion when it wasn't clear who made the tours.  Within the tour, our user was confused by the “in progress” screen, which was pointed out due to a lack of context for the text.  In response, we removed the text underneath the picture, but also noted that this lack of context could also be due to the isolated nature of the test.  The scrolling feature that allows users to view the history of their pieces during their tour was also not properly understood, perhaps due to the way in whcih it was drawn as the cues we design relied on subtle shadowing effects not apparent on our prototype.  In between pieces during the guided tour, our user suggested better organization of the information, and lastly, the user also felt that what to do after the audio was confusing.  We fixed some of these design errors, and left others as they were for furture testing.  The changes can be seen in the overall prototype view below.

# Prototype Overview

![](https://krtejeda.github.io/PersonalCuraTour/img/overview2.0.jpg)

# Task 1: Explore and learn more about pieces

![](https://krtejeda.github.io/PersonalCuraTour/img/freeroam1.png)

![](https://krtejeda.github.io/PersonalCuraTour/img/freeroam1.png)

1) select free roam option 
2) choose automatic audio 
3) designate audio start after 5 seconds
4) exploring in progress screen as user browses between pieces
5) vibration when user arrives and stops at piece, piece appears on display, audio plays after 5 seconds
6) exploring in progress screen, able to scroll to view past pieces visited
7) vibration when user arrives and stops at piece, audio plays after 5 seconds
8) exploring in progress screen, user ends tour
9) error catching 
10) option to save tour - if yes
11) user is able to enter name by drawing letters


# Task 2: Follow Guided Tour

![](https://krtejeda.github.io/PersonalCuraTour/img/guidedtour.png)

1) choose tour option
2) select tours by curators
3) choose desired tour, noting rating
4) choose to have audio manually start
5) navigate to piece, following directional changes at vibrations
6) press play audio button to start audio manually
6) click end tour button
7) rate tour by scrolling wheel, submit

# Plan for remaining usability tests

Our plan for the remainder of the usability testing is to target several different user demographics as they relate to level of prior experience.  The test we have already done focused on an individual who had a moderate level of experience with museums.  She was a studio art major, implying that she had a higher sense of aesthetics, as stated, but was not highly experienced with museums.  This means that she had valuable insights from the perspective of an individual who has moderate experience with museums, but is not a total expert.  To cover the two other user bases that we are interested in, we will also try to conduct a test on someone who is an expert at museums, or is at least someone who has gone often to many different museums.  This will allow us to hear the views of someone who has lots of prior experience with exhibits, knows the mode of interaction desired, and even potentially has used other types of MuseTech and will be able to make useful contrasts.  Lastly, we will also seek out an inexperienced user to test upon.  This will provide insight with how a user with less preconceptions may view the prototype, and how it may help them relate to art.  

We may also look into changing the test environment itself.  The test we conducted occured in a more casual environment, a Schow study room, without much prior preparation of the space.  This in itself could be improved upon, as we could work to set up a more realistic exhibit-like environment with at least one to two mock pieces that the user could physically transition between, since our application does not exist within a vacuum, but rather a very specific kind of environment.  Further, our application is heavily audio-based; a large portion of the watch interface is used to control the user’s interaction with the audio being played.  This means that the audio we simulate must be at least somewhat realistic in order to engender a believable response from the end user.  Therefore, we will either prepare a sample recording or at least write a script that one of our testers will read off of to simulate operation of this component of our app.  This will ostensibly improve the simulation over the ad-libbing that was done for our first round, which was better than nothing but certainly not quite there.

Our goals with these two broad-based changes, in addition to improvements in how we operate our prototype, are to discover smaller nuances in how the relationship between the user, art, and exhibit may be hindered by flaws in our design.  Therefore, simulating a more realistic experience overall will allow user tests to uncover smaller things we may have overlooked and may not have come up in our less-realistic first test, especially in how the user can use the app to relate to the surrounding artwork.  
