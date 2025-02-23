# Guided Hike/Git Good
> _Note:_ This document will evolve throughout your project. You commit regularly to this file while working on the project (especially edits/additions/deletions to the _Highlights_ section). 
 > **This document will serve as a master plan between your team, your partner and your TA.**

## Product Details
 
#### Q1: What is the product?
We are establishing a website, intended to be used on mobile devices, to allow for an exploration of points of interest through a guided hike for Arrowhead Provincial Park. Our partner is John Leadston — the park supervisor who is looking to enhance the user experience while not disrupting the natural environment. The problem we are solving is allowing interested park visitors to learn more about features that the park offers, without needing a tour guide, who some people are still uncomfortable with having due to the pandemic. The plan is for the website to display a map of the park. Interesting features of the park, such as trillium flowers, will be plotted on the map. These plotted points will not specify what exactly can be seen there. It will, however, have a general idea of what is there. In the trillium flowers example, the point on the map would say _Flowers_ as opposed to trillium. Once a user gets to the point, which will be identified using geolocation, a short textual and audio passage (30-45 seconds) will be played which describes the speacial feature at that location.

 > Short (1 - 2 min' read)
 * Start with a single sentence, high-level description of the product.
 * Be clear - Describe the problem you are solving in simple terms.
 * Specify if you have a partner and who they are.
 * Be concrete. For example:
    * What are you planning to build? Is it a website, mobile app, browser extension, command-line app, etc.?      
    * When describing the problem/need, give concrete examples of common use cases.
    * Assume your the reader knows nothing about the partner or the problem domain and provide the necessary context. 
 * Focus on *what* your product does, and avoid discussing *how* you're going to implement it.      
   For example: This is not the time or the place to talk about which programming language and/or framework you are planning to use.
 * **Feel free (and very much encouraged) to include useful diagrams, mock-ups and/or links**.
 
 Guided Hike -- the hike that guides you as move across the trail. People can travel and go anything they want -- they will get their own interests. 
The person's interests: ie: animals, birds | cultural history 
 Wht it will do is the: tell them about it? 
 Filters -- some people want to vocalziation/ text -- viusually impaired. -- Vibrations. 
 
 Administrator - can see which info stays and stuff -- maintentaince -- blooms. 
 
 Core functionalities: 
  - BasicProduct - Process of adding - georeferenced - notifies them (vocal/text). 30 seconds.  plant/animal
 
 Arrow on the way they are -- ie: compass??? 
 Changes season by season -- they wont find it. They have checked off the toogle (invasive species) example he used wild mustard. 
 tracks of wolves -- beaver -- birds (more like the waze app) people can have a point of the activity (expiry dates in the activity) Plants/aniaml seasonal. 
 
 Only can listen to it if the filter is checked. More of a discorvery thing?? 
 Outcome: engages, relative to the people, 
 
 employer interests: indigneous history 
Access only if they are there - sense of discovery 
transforming the torusim. 

Audio - default? - Administrator voice? - highlights, significance

#### Q2: Who are your target users?
Our target users are Arrowhead Provincial Park tourists who are interested in enhancing their park experience by engaging with the special features that the park has to offer. There is no particular age group for our product so long as the user can understand English.
  > Short (1 - 2 min' read max)
 * Be specific (e.g. a 'a third-year university student studying Computer Science' and not 'a student')
 * **Feel free to use personas. You can create your personas as part of this Markdown file, or add a link to an external site (for example, [Xtensio](https://xtensio.com/user-persona/)).**

#### Q3: Why would your users choose your product? What are they using today to solve their problem/need?
Users will use our product if they want to learn about the features the park has to offer. Today, they are using tour guides or self-research using search engines, and our goal is to combine it all into one simple platform. This product gives them a sense of direction and it saves them from having to individually research every aspect of the park. Currently, the park has no similar application. We were told that they had a similar guide called "My Campsite." However, after talking with John Leadston, we learned that that project is not similar to what we intend on doing. The concept of having geolocation which leads to audio is similar to that of Waze — a traffic navigation app.

> Short (1 - 2 min' read max)
 * We want you to "connect the dots" for us - Why does your product (as described in your answer to Q1) fits the needs of your users (as described in your answer to Q2)?
 * Explain the benefits of your product explicitly & clearly. For example:
    * Save users time (how and how much?)
    * Allow users to discover new information (which information? And, why couldn't they discover it before?)
    * Provide users with more accurate and/or informative data (what kind of data? Why is it useful to them?)
    * Does this application exist in another form? If so, how does your differ and provide value to the users?
    * How does this align with your partner's organization's values/mission/mandate?

#### Q4: What are the user stories that make up the Minumum Viable Product (MVP)?

 * At least 5 user stories concerning the main features of the application - note that this can broken down further
 * You must follow proper user story format (as taught in lecture) ```As a <user of the app>, I want to <do something in the app> in order to <accomplish some goal>```
 * User stories must contain acceptance criteria. Examples of user stories with different formats can be found here: https://www.justinmind.com/blog/user-story-examples/. **It is important that you provide a link to an artifact containing your user stories**.
 * If you have a partner, these must be reviewed and accepted by them. You need to include the evidence of partner approval (e.g., screenshot from email) or at least communication to the partner (e.g., email you sent)
- BasicProduct - Process of adding - georeferenced - notifies them (vocal/text). 30 seconds.  plant/animal
 

#### Q5: Have you decided on how you will build it? Share what you know now or tell us the options you are considering.

> Short (1-2 min' read max)
 * What is the technology stack? Specify languages, frameworks, libraries, PaaS products or tools to be used or being considered. 
 * How will you deploy the application?
 * Describe the architecture - what are the high level components or patterns you will use? Diagrams are useful here. 
 * Will you be using third party applications or APIs? If so, what are they?

The technology that we will use are all to optimize the site for mobile devices. We will be creating a website optimized for mobile devices using HTML, CSS, and React frameworks to help build an interactive expereince for the user. For the backend we will use Djanngo to store and handle data that is sent or processed.

As for the geolocation and map, we are currently looking into tools that could help us. As things progress, we may also need gyroscopic data due to the nature of the project. Since we require accurate location data for our website to function accordingly, we need to research possible works we could use. Once again, we have not decided on how to do this
<!-- - Website which is optimized for mobile devices
- Bank-end: Django
- Front-end: HTML, CSS, React
- We need a tool for geolocation and the map. We may also need gyroscopic data. We have not decided on how to do this. -->
----
## Intellectual Property Confidentiality Agreement 
> Note this section is **not marked** but must be completed briefly if you have a partner. If you have any questions, please ask on Piazza.
>  
**By default, you own any work that you do as part of your coursework.** However, some partners may want you to keep the project confidential after the course is complete. As part of your first deliverable, you should discuss and agree upon an option with your partner. Examples include:
1. You can share the software and the code freely with anyone with or without a license, regardless of domain, for any use.
2. You can upload the code to GitHub or other similar publicly available domains.
3. You will only share the code under an open-source license with the partner but agree to not distribute it in any way to any other entity or individual. 
4. You will share the code under an open-source license and distribute it as you wish but only the partner can access the system deployed during the course.
5. You will only reference the work you did in your resume, interviews, etc. You agree to not share the code or software in any capacity with anyone unless your partner has agreed to it.

**Your partner cannot ask you to sign any legal agreements or documents pertaining to non-disclosure, confidentiality, IP ownership, etc.**

Briefly describe which option you have agreed to.
We have agreed to #5.
----

## Teamwork Details

#### Q6: Have you met with your team?

Do a team-building activity in-person or online. This can be playing an online game, meeting for bubble tea, lunch, or any other activity you all enjoy.
* Get to know each other on a more personal level.
* Provide a few sentences on what you did and share a picture or other evidence of your team building activity.
* Share at least three fun facts from members of you team (total not 3 for each member).
- We played Among Us together while talking on Discord and got to know each other.
- 3 fun facts: We all like golf. Most of us like the Toronto Raptors while others like the Oklahoma City Thunder. None of us wanted to meet for bubble tea because none of us like it.

#### Q7: What are the roles & responsibilities on the team?

Describe the different roles on the team and the responsibilities associated with each role. 
 * Roles should reflect the structure of your team and be appropriate for your project. One person may have multiple roles.  
 * Add role(s) to your Team-[Team_Number]-[Team_Name].csv file on the main folder.
 * At least one person must be identified as the dedicated partner liaison. They need to have great organization and communication skills.
 * Everyone must contribute to code. Students who don't contribute to code enough will receive a lower mark at the end of the term.

List each team member and:
 * A description of their role(s) and responsibilities including the components they'll work on and non-software related work
 * Why did you choose them to take that role? Specify if they are interested in learning that part, experienced in it, or any other reasons. Do no make things up. This part is not graded but may be reviewed later.
(DO THIS ON YOUR OWN)

#### Q8: How will you work as a team?
Currently, we meet from 4-6PM every Monday as a team in-person at the Gerstein library, and on Thursdays we meet online on Microsoft Teams with John Leadston from 3-4PM. Every other Friday, we meet with an IT specialist with Ontario Parks using Microsoft Teams.

Describe meetings (and other events) you are planning to have. 
 * When and where? Recurring or ad hoc? In-person or online?
 * What's the purpose of each meeting?
 * Other events could be coding sessions, code reviews, quick weekly sync meeting online, etc.
 * You should have 2 meetings with your project partner (if you have one) before D1 is due. Describe them here:
   * You must keep track of meeting minutes and add them to your repo under "documents/minutes" folder
   * You must have a regular meeting schedule established for the rest of the term.  
  
#### Q9: How will you organize your team?
For our scheduling, we will use Google Docs to assign tasks since we are all comfortable using that. We also meet often so we will have an idea of where everone is in their work. Since we also have a product manage and Scrum master, we have a structure in place to delegate and ensure that work is completed on time.

Artifacts that we will have will be on Github actions. We will be able to see groups actions and progress to better organize our team. Artifacts may also be stored on github for ease of access. To prioritize tasks, we will have team meetings to decide what we need to focus on for things to run smoothly and also have an idea of how other parts are working.
- Task schedule using Google Docs.
- Github actions
List/describe the artifacts you will produce in order to organize your team.       

 * Artifacts can be To-Do lists, Task boards, schedule(s), meeting minutes, etc.
 * We want to understand:
   * How do you keep track of what needs to get done? (You must grant your TA and partner access to systems you use to manage work)
   * **How do you prioritize tasks?**
   * How do tasks get assigned to team members?
   * How do you determine the status of work from inception to completion?

#### Q10: What are the rules regarding how your team works?
The way that our groups work will be that the whole team meets the every week on a designated day. If someone is not able to make a meeting the should seek to fill themselves in. Every two weeks, the individual groups will meet. For example, backend people will meet together and front end people will meet together to discuss their work. Communication will be done on discord since that is what most people are comfortable with. Also, by using discord, people can tune into other groups to see their progress. Discord is organized by creating a server in which all people can access it.
- Rules: Full team meets in-person every two weeks. People working on the same part of the project (i.e., backend, frontend) communicates frequently (at least once a week). Online meetings between team members will take place on Discord (we have a server for our group, called CSC301 Git Good).
**Communications:**
 * What is the expected frequency? What methods/channels will be used? 
 * If you have a partner project, what is your process for communicating with your partner?
 
**Collaboration: (Share your responses to Q8 & Q9 from A1)**
 * How are people held accountable for attending meetings, completing action items? Is there a moderator or process?
 * How will you address the issue if one person doesn't contribute or is not responsive? 
