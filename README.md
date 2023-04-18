

Bytesize Architecture Sessions are a workshop format that help teams understand the systems they work on. Each session focuses on a small slice of a system. After some sessions your team will become more homogeneous in the understanding of their systems, grow a consistent vocabulary and ultimately build tools to design the future together.

A  session lasts between 45 and 90 minutes, and has four well defined parts: Session Goal, Alone Together, Consensus and Summary. You can model your systems using different tools. I suggest starting with [C4 Diagrams](https://c4model.com/).

## You rather watch something?

<iframe width="560" height="315" src="https://www.youtube.com/embed/uJ0f8fLU2Vw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Why should you use Bytesize Architecture Sessions?

Consider using Bytesize Architecture Sessions if you experience any of the following common difficulties: 

* Codebase Knowledge. Planning for large work requires a solid understanding of current systems. Teams can end up with silos of knowledge, and not see the big picture
* Technical Debt. The system has grown and accidental complexity has not been addressed. Understanding how to solve the debt while still shipping features requires some planning
* Evolving teams. It is difficult to maintain cohesive knowledge in a team that has changed over time
* All of the above, likely compounded with process problems


These are some of the improvements I witnessed when running the sessions with different teams. The teams 

* Think about their systems
* Develop skills in systems modelling 
* Learn how to model systems **together**, which improves team dynamics
* As more sessions happen, they increasingly have an  **homogeneous** understanding of the system
* See the value of having a shared mental model
* Have better tools to model potential solutions
* Learn to actively listen 

Bytesize Sessions are especially valuable for new members of the team or those with less experience. This is especially true in teams that don't do pair programming or have deep silos. The Sessions "open up the 'world'"
It is hard to overstate how important it is to have an accurate mental model. Studies prove that mental models are particularly important when making difficult and time constrained decisions (Besnard et al. #)[^BGB].

[^BGB:]Denis Besnard, David Greathead, Gordon Baxter. When mental models go wrong. Co-occurrences in dynamic, critical systems.. International Journal of Human-Computer Studies, 2004, 60 (1), pp.Pages117-128. 10.1016/j.ijhcs.2003.09.001. Hal-00691813

## Who organises Bytesize Architecture Sessions?

Anyone can propose a Bytesize Session. The sessions should feel like they belong to the team.  

Although a host is not mandatory, it can be useful, especially at the start.  The role of the host is to be an enabler, someone that keeps the timing of the session and focuses the discussion on the goal.  The host can be anyone, not necessarily someone leading the team. The host should change from time to time.


## A guide to running your first few sessions
![Overview](http://bytesizearchitecturesessions.com/images/bytesize-overview.png)

### Before the session, prepare people 

One of the main objectives of the Bytesize Sessions is for a team to have a homogeneous understanding of the system they work with. The right people to attend are all the people that have a high level of influence on that system. 

Start with a team. Invite those that know about what needs to be done, those that build the system, and those that understand the stakeholder requirements best. If not sure, start with the people in the Stand Up. If there are more than ten people in the guest list, consider breaking the meeting into smaller groups.

The recommended modelling tool when starting is [C4](^C4). If the team is not experienced with it, train them on it first. During a Bytesize Session the attendees should focus on modelling, not the modelling tool of choice. 

### Running a Bytesize Architecture Session

The key to a good session is ensuring everyone knows what they need to do. At the start of the session explain the overall format, then for each section delve into the specifics. 

#### Goal

This section of the meeting should take about five minutes and it’s about having a _Goal_ for this particular session. A good first session is to model the system that the team actively works on *as it is right now*. Bear in mind that the attendees will have a handful of minutes or less to model this. If the system you are trying to model is too big, choose a subsection to focus on. 

It's good to have a suggestion of what to model before starting a session. However the final goal  should be the result of team agreement.

Before moving on to the next section, check that every attendee understands the goal. 

#### Alone Together

This section should take ten minutes or less.

For the first part of this section set a timer for three to five minutes. During this time everyone works individually and quietly on the same modelling task. After the timer elapses, each person explains their own diagram to the rest of the group. 

This modus operandi might be atypical, here are few reasons why it’s useful:

* The quiet time allows people to work and think individually, without other people's voices. It strengthens their focus on the aspect of the system the session focuses on
* Higher engagement levels on the topic for the rest of the session
* Helps participants self evaluate their perceived understanding of the system, highlighting areas where they can focus on learning more
* Understand how other people in the team think of the systems

![Image of participants with their individual models](http://bytesizearchitecturesessions.com/images/alone-together.png)

#### Consensus

The longer part of the session, lasting between twenty to thirty minutes. 

__Consensus__ is about coming together to create one diagram from scratch with the combined knowledge of the team. 

It's normal for things to get a little hectic. In order to achieve the goal, designate a scribe that can rotate every meeting. The scribe will be drawing the diagram from scratch with everyone’s help. 

The host plays a key role during this time when and if the conversation starts deviating from the goal of the session.


#### Summary

The last few minutes of the meeting.

Some retrospection on the workshop. This part of the session is about reviewing what was achieved and what needs to be done next. Set a timer for one minute, have people write about what they learned and any other feedback in sticky notes. 

Optional bonus task: ask for a volunteer to create a clean copy of the diagram, and to bring whatever outstanding questions remain to the next session.

#### Do it again!

Repetition is a great way to learn, it is ideal to do another session in a week or two. It shouldn’t be so often that it overwhelms people and it should be often enough to keep familiarity with things discussed.

Bytesize Sessions can be used for continuous learning. It's also possible to set long running goals, for example Bytesize Architecture Sessions can be used to create a Target Architecture  or help enable inter-team communication for a complicated piece of work.


# FAQ

## What are some symptoms that some Bytesize Sessions are needed

* It is clear that people in the team have an incorrect mental model of the system or that the mental model they have is incongruent with other people in the team
* When design decisions need to be made, there is only one person talking. No one else "knows enough" to contribute even with questions
* When design decisions need to be made, discussion takes forever and no decision is made (this can be reflected as changing decision or no one "remembers what we decided in the end")
* The team has changed a lot or is mostly formed of new people

## How did this format originate

I started with Bytesized Architecture Sessions around 2017. At the heart of the sessions is the   _Alone Together_ time. A short time when everyone in the session works separately and quietly on the same modelling task. 

After many sessions, people asked me to write about it. I thought it wasn't necessary because it's so simple. Then,  I realised how often I use and recommend the [Pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique) with the added advantage that this coordinates a team of people.





## More info soon

Any questions or comments please reach out via mastodon: [@roundcrisis@types.pl](https://types.pl/web/@roundcrisis)
