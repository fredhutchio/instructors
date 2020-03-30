# Information for fredhutch.io instructors

- [Preparing to teach](#preparing-to-teach)
- [During class](#during-class)
- [Teaching online](#teaching-online)
- [Accommodating learner absences](#accommodating-learner-absences)
- [After teaching](#after-teaching)

## Preparing to teach

- Our teaching methods generally follow those described by [The Carpentries' Instructor Training materials](https://carpentries.github.io/instructor-training/). In particular, we use live coding demos (learners following along with instructors) with challenge exercises interspersed throughout the material (preferably every 20-30 minutes, depending on the material).
- If you have any suggestions or corrections, please feel free to submit a pull request to the lesson in question!

## Introducing the first class session

- Welcome everyone to the class
- Introduce yourself, including your job/division, what you research, why you're teaching, etc
- Briefly describe fredhutch.io, a project that teaches reproducible computational methods at Fred Hutch
- Overview the course philosophy:
  - courses are designed for researchers who are not expert programmers
  - focus on applicable and reproducible data/coding skills
  - follow along with materials and try to stay engaged (e.g., try the challenge exercises)

## During class

### Introducing yourself

- Describe yourself, position at Fred Hutch, and why you're teaching the course
- Identify fredhutch.io as the program holding the course, and describe its [purpose](http://www.fredhutch.io/about/).
- More information on providing an effective introduction is available in [The Carpentries Instructor Training materials](https://carpentries.github.io/instructor-training/23-introductions/index.html).

### Tools and infrastructure

- Each class should have a course website available in something like [HackMD](https://hackmd.io) to share links and code snippets with learners. Instructors should be able to edit these, although we don't recommend having learners attempt to edit these pages. If the content of the page is disrupted, all material is available in `hackmdio.txt` in the class repository.
- There are three laptops available to learners to borrow during class sessions. These computers are kept in a locked cabinet in the Coop Lab and should not leave the room. The two Macs have the login and password listed on a sticky note attached to the machine; the Windows laptop can be accessed via HutchnetID.

### Starting each class

- Please have learners sign in to each class session, preferably using the Google Form available on each course's HackMD. This is useful for our records, and is also encouraged by Hutch Learning (the attendance is entered into Hutch Learning records as well).
- Turn on the Do Not Disturb option on your computer to ensure you don't have notifications popping up while teaching. Many computers automatically use this setting while in projection mode, but some applications may behave unpredictably.
- Begin each class session with a quick review of the previous week's learning objectives (if applicable), as well as an overview of objectives for the current class session. At the end of each session, repeat the current session's learning objectives and relate to the next week's materials. This is especially useful in multi-week courses to reiterate the overall learning objectives for the course.

### Challenge exercises

- Methods of administering challenges will vary based on the course content and interface.
- Regroup following challenge exercises and allow the class to suggest a variety of solutions to answer the problem.
- Timing and pacing can be adjusted with challenge exercises. You can add or remove challenges from a given class, or give more or less time as pacing allows. There are extra challenges in `exercises/`
- Remind participants frequently that challenge exercises (with solutions) are available with the course materials.

### Taking breaks

- For classes longer than 1.5 hours, it is useful to include a ~10 minute break halfway through the class session.
- For in-person courses, tell folks where the bathroom/kitchen/etc can be found.
- It works well to administer a challenge exercise and then take a break, so folks can work on the exercise and/or move around as necessary. Address the challenge after the break before moving on to the next section.

## Teaching online

Basic troubleshooting information for MS Teams is available for participants on the [fredhutch.io Software page](http://www.fredhutch.io/software/#online-courses), and [this blog post](https://fredhutch.github.io/coop/community/ms-teams/) overviews common info useful for working in MS Teams (and has links to other options for online meetings).

Participants and instructors will receive an Outlook calendar invite that has an MS Teams room included.

### General tips

- Prepare ahead of time.
  - Test out the online environment with a small group of peers.
  - Provide assistance before the first class for participants who need help installing software, checking audio, etc.
  - Enlist an additional instructor to provide technical support, watch the chat window, etc.
- Orienting participants to online etiquette.
  - Identify controls at the bottom of the screen.
  - Stay muted unless speaking.
  - Guidelines for where participants can ask questions or obtain help.
  - Clarity in how participants respond to instructor questions.
- Sharing your screen.
  - Ask if the font is large enough for participants to see comfortably.
  - Provide reference materials, such as the full teaching notes, so folks can keep up when necessary. Also remind participants of these materials often.
  - Periodically check that audio/visual are working appropriately.
  - Try to minimize switching among screens (e.g., from IDE to web browser), as this makes it difficult for learners to follow. A second monitor works great to hold your teaching notes, so you don't have to move among windows.
  - Use the Do Not Disturb (DND) option on your computer to prevent notifications from popping up while teaching.
  - Close all programs not being actively used for teaching, and all extra browser tabs. If you still have trouble with a slow connection, also turn off your video. If it's still a problem, consider calling in on a separate line (e.g., cell phone), so at least your audio is clear. If you are muted through MS Teams while on a phone, the unmute code is `*6`.
- If you would like to include breakout rooms,
[this video](https://techcommunity.microsoft.com/t5/microsoft-teams/breakout-rooms-for-microsoft-teams/m-p/1212601#) describes how to accomplish that with MS Teams.

### Introducing learners to MS Teams

Review this checklist at the beginning of each online class:

- The command bar at the bottom is where you can control sound, video, and screen share.
- Keep yourself muted if you're not speaking. Everyone in this session is included as a presenter, in case we need to do screen share; please do not use the "mute all" option.
- Keep your video input off (when requested by the instructor) to save bandwidth and keep the MS Teams window clearer
- Type "hand" in the Teams chat window if you'd like to ask a question (demonstrate this)
- If the instructor's audio or video freezes, or you can't hear for whatever reason, please put a note into the class chat
- There is a helper available to assist in a separate call if necessary. They will call you to do a quick screen share. You can stay connected to the original call with the rest of the class, and hang up the other call with the helper when you're done.
- When instructor initially does screen share, it will go to full screen mode. Hit `esc` to exit full screen, and do your best resizing windows to be able to see both the instructor's screen (via MS Teams) and your own RStudio window.

### Helpers

If you are assisting the primary instructor during an online session,
your main tasks are:

- taking over with teaching if the main instructor has difficulty connecting, or if their connection drops
- answering quick questions in the MS Teams chat window (keep track of relevant web links and locations for information, so they can be pasted in quickly)
- watching for participant "hands" in the chat, for when people want to speak
- inviting any participant who needs one-on-one help to a separate call:
  - you can create (or join) a new call in MS Teams without leaving the original (full class) meeting
  - search for the participant in the search bar at the top of MS Teams
  - click on the video icon by their name to call them
  - if the participant does not appear (e.g., because they are outside the Fred Hutch network, such as SCCA), you can create a call using their email address
  - after helping the participant in the extra call, you should hang up the extra call and hit "resume" on the original to rejoin the class

## Accommodating learner absences

Our course listings let learners know they are expected to attend most (e.g., three of four) sessions. Periodically, additional absences may be required; here's what you should offer:

- At the very least, a link to the fredhutch.io course material for the materials they will miss. In the case of lessons that are modified from other sources like The Carpentries, you can also offer the links to webpages for their better-formatted instructions.
- You can meet one-on-one with learners at your discretion (but please don't feel obligated to do this). Usually a half hour is sufficient to highlight the main themes and to link the missed material together with other course content. This could be directly prior to the next class session, although that's sometimes not enough time for them to review the material.
- Learners can attend fredhutch.io office hours (Tuesday mornings from nine to noon in the Coop Lab) and review the material with one of our team members.

## After teaching

- Learners have the opportunity to submit feedback on the course via Hutch Learning. Although our response rate for the surveys remain low, we'll synthesize and pass along any comments to you as we're able.
