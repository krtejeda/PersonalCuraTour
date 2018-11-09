---
layout: page
title: Usability Testing Review
---

All of our usability tests were conducted by different pairs of two of our team members. One of us took notes and recorded the feedback while the other member ran the usability test. 

Our test protocol was as follows. We first introduced ourselves and briefed them on the purpose of this usability test, their role, and our project. We asked if it was okay to collect their feedback via voice recording and note taking and they allowed it. We reassured them that if at anytime they wanted to stop participating, they were free to do so. Next, before we started the testing, we encouraged them to think aloud there thoughts about the design of the app, the experience, or anything that wasn’t clear or effective to them. We gave them an example of what thinking aloud was so that it was clear. They were made aware that we were not evaluating them, only our design.

For our actual testing phase, our participants were prompted to imagine that they were in a museum and that they had just opened the app on there watch. We presented them with two tasks: exploring the museum as intended and exploring the museum as they want. After this point, we notified them that we would not give further instruction in order to capture how they navigate the interface on their own. They completed both tasks without any major mishaps and thought aloud the whole way through. 

# Test 1

The participant for our first usability test was Geneviëve, a studio art major at Williams. This participant was ideal because of her visual/aesthetic expertise and willingness to provide constructive feedback. She also spends a lot of time at museums due to her interest in art, so we consider her to be museum adept. We conducted the test in a Schow study room.The location was ideal because it provided us the freedom to move around and speak freely. 

After this test, we revised our prototype with feedback provided from Geneviëve. We placed the “distance from next art” number closer to the directional arrow, added a screen to distinguish between curated and community sourced tours, and added a no audio option.

# Test 2

The participant for our second usability test was Nüelf, an extremely avid museum goer. We chose this participant because he described himself as very confident in museums and seemed to engage with them at a level even higher than our last user, so we chose to move forward with him. We conducted our usability test in a dormitory common space. This location allowed us to move around freely, so we could simulate moving from art piece to art piece by having the user walk across the room to a piece of paper we taped on the wall.

After this test, we revised our prototype to make it more apparent on how to move on to the next piece in the guided tour by adding a “next/skip” button. This change led us to refactor how the guided and free roam experiences flowed. We added a new “create tour” experience instead of bundling it with free roam. Finally, we changed the wording of “save tour” into “upload tour”.

# Test 3

The participant for our third usability test was Kwintïn, an economics major at Williams. We chose this participant because they do not visit museum frequently, or in fact have any strong feelings about museum experiences. We conducted our usability test in a dorm common space like our second test. This location allowed us to move around freely, so we could simulate moving from art piece to art piece by having the user walk across the room to a piece of paper we taped on the wall.

After this test, we revised our title writing screen for tour creation to have the option for both drawing letters and speaking. We modeled this after the way Apple does it for their other applications so that we could be consistent with writing methods a user would be familiar with. We also added a screen where users could review and edit the art that they visited during tour creation before they decided on uploading the tour. 

# Overview of Revised Prototype

![](https://krtejeda.github.io/PersonalCuraTour/img/overview3.jpg)

# Table of Revisions

Labels associate with the overview photo above.

| Photo of Prototype | Description of Incident | Severity (if neg) | Revision |
| ----- | ----- | ----- | ----- |
| L | Scrolling option for in tour experience - not clear exactly what effect scrolling will have. User said she would normally just try this feature to see what would happen. Suggested a couple of possible fixes. | 3 | We axed this in response to a later usability test where similar confusion was expressed over the scrolling.  The ability to view past pieces now comes up after the end of the experience, where users can scroll through the list of pieces they have viewed. |
| ----- | ----- | ----- | ----- |
| D | “Community Experience” text on menu for tours was not clear. User did not know what that meant and suggested a different way to differentiate between curator and user created tours. | 2 | Created a new screen to choose between curator and user submitted tours. |
| ----- | ----- | ----- | ----- |
| J | User noted a lot of info on the navigation screen compared to others, user suggested clustering the information that is related, art and navigation elements. | 2 | Move the distance to the piece to be closer to the arrow for directions so that all the navigational elements are clustered together. |
| ----- | ----- | ----- | ----- |
| H/I | Within a guided tour, it was unclear to the user how to progress onto the next piece in the sequence; we had designed it to be implied, that the tour would progress when the user walked away regardless of the point of the audio, but realized that the user’s input was correct. | 3 | We added a next/skip button that provided a concrete way for users to skip to the directions towards the next piece |
| ----- | ----- | ----- | ----- |
| L (bottom of panel) | User was confused by the “save tour” screen; he was not aware that he was making a tour in the first place, and the wording of the save tour screen was confusing. | 3 | Changed screen to “upload tour”, which implies a more active ability to share the experience just had  rather than implication of an extant responsibility |
| ----- | ----- | ----- | ----- |
| M/N/O | User confused by drawing letter option to enter the tour title.  Was not familiar with the interface and simply stared blankly at the empty box--we had to intervene and teach him how to use it. | 2 | We added the option to input the name of the tour via voice command because and added a screen to choose between the two options for clarity. |
| ----- | ----- | ----- | ----- |
| G | User was confused by how to initiate information during the free roam; i.e. he didn’t understand the meaning of the walking man thing. | 4 | We replaced the unlabeled interim walking man screen with a “approach art piece to begin audio” screen that is more explicit on what users should do |
| ----- | ----- | ----- | ----- |
| L | User confused by scrolling option during tour, not sure what the scrolling should do (it was supposed to allow users to scroll through their history of pieces visited). | 2 | We axed the scrolling option and replaced it with the ability to view a list of pieces visited at the end of the tour (either free roam or guided).  This provides more clarity |
| H/G | User understood that once the audio ended, he should turn around and progress to next art piece during explore museum as intended. | ----- | ----- | 
| ----- | ----- | ----- | ----- |
| E/F | User was confused by the tour choice screen because there was only one choice and no clear scroll | 1 | No change made because this was due to the limitations of our paper prototype; we will add clearly marked additional choices in our hifi prototype |
| ----- | ----- | ----- | ----- |

# Task 1: Explore and Learn more about pieces

![](https://krtejeda.github.io/PersonalCuraTour/img/task2-usabilityReview.jpg)

1) select free roam option 
2) choose automatic audio 
3) designate audio start after 5 seconds 
4) exploring in progress screen as user browses between pieces 
5) vibration when user arrives and stops at piece, piece appears on display, audio plays after 5 seconds 6) user ends tour      

# Task 2: Follow Guided Tour

![](https://krtejeda.github.io/PersonalCuraTour/img/task1-usabilityReview.jpg)

1) choose tour option 
2) select tours by curators 
3) choose desired tour, noting rating 
4) choose to have audio start after 5 seconds 
5) navigate to piece, following directional changes at vibrations 
6) arrive at piece, audio plays after 5 seconds 
7) reach end of tour, rate tour by scrolling wheel, submit

# Salient Revisions

Two salient revisions that we discovered were changing the types of experiences offered and streamlining how guided experiences operate. 

The first important change was refactoring our “Free Roam” option into “Free Roam” and “Create Tour” options. We discovered this change after our second participant, Nüelf, was surprised by the “save tour” prompt at the end of his free roam experience. He was unaware that he was building a tour that would be uploaded for other people to experience. We evaluated that it was a critical mistake on our part to assume that a visitor would know that their roaming experience was actually being recorded. We decided it would indeed be better to have an option for those who just wanted to free roam without having to create a tour. It also allows people who choose “Create Tour” to make intentional experiences from the start. 

The second important change that we made was clarifying next steps that are possible once they finish the audio at a piece of art. Two of our users, Nüelf and Kwintïn, expressed audible confusion with phrases like “now what?” and “okay?...what do I do next?” after I simulated the audio experience they would get at a piece of art. We initially felt that this may have been due to the nature of the testing process and waiting for us to do something to them, but we decided it was a mistake on our part to assume that a user’s inclination would be to just walk away from the art once the audio is finished. To make it more clear to the user that they are free to move on to the next peice, we added a “next/skip” button that appears when they arrive at a piece of art. By pressing this button, the screen is forced to direct the user to the next piece of art. This change also led us to also revise the “in progress” screen for the “free roam” and “create tour” screens. They are now more explicit with what the user should do next by reminding them that they should visit a piece of art to utilize the audio features of the app or add it to their tour. 







