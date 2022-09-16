# Design Thinking, Agile Methods, and Data Science

> Most outsiders see design as an applied art, as having to do with aesthetics, unlike a solid profession unto itself, with technical knowledge, skills, and responsibilities to rely on. Insiders to design, by contrast, talk of innovative ideas, coordinating the concerns of many disciplines, being advocates for users, and trying to balance social, political, cultural,
and ecological considerations.
> Klaus Krippendorf (2006, 47)

![](design_embrace.jpg)
_[Source](https://www.flickr.com/photos/edrethink/33566499814/in/photostream/)_

__[Reading for class](DT-IT.pdf)__

## The Design Thinking Diagrams

![](img/designthinking_hex.png)
_[Source](https://citl.illinois.edu/paradigms/design-thinking)_

![](img/designthinking_circles.png)
_[Source](https://www.stephaniebaseman.com/design-thinking-process)_

![](img/designthinking_infinite.png)
_[Source](https://www.maqe.com/insight/the-design-thinking-process-how-does-it-work/)_

![](img/ITDesign.png)
_[Source](https://link.springer.com/chapter/10.1007/978-3-642-13757-0_1)_

![](img/design_thinking_table.png)
_[Source](https://onlinelibrary.wiley.com/doi/10.1111/caim.12153)_

### Design Thinking in Practice

- [ABC Nightline: IDEO Shopping Cart](https://www.youtube.com/watch?v=M66ZU2PCIcM)
- [IDEO and a Story of Design](https://www.youtube.com/watch?v=_KK958OkD6g)

## Agile Data Science

> The basic idea behind agile is to manage IT development not by rigid milestone-based process roadmaps that the team has to follow, but by a set of obligatory rules and roles in which the team can act flexibly in order to sustain learning about the project and adaptability to unexpected events. The requirement analysis is not a preceding step, but a parallel process to the actual development.  ... short iterative steps while the goal of each step is to produce an incremental intermediate solution that serves to generate feedback by users and specialists.
> [Source](https://link.springer.com/chapter/10.1007/978-3-642-13757-0_1)

### Agile DS Manifesto

Russell Jurney provided some [Agile guidelines for data science projects](https://www.oreilly.com/radar/a-manifesto-for-agile-data-science/) that resonates;

1. __Iterate, Iterate, Iterate:__ _In data science, iteration is the essential element to the extraction, visualization, and productization of insight. When we build, we iterate._
2. __Ship intermediate output:__ _Good systems are self-documenting, and in Agile data science, we document and share the incomplete assets we create as we work. We commit all work to source control. We share this work with teammates and, as soon as possible, with end users._
3. __Perform experiments, not tasks:__ _Managing a data science team means overseeing multiple concurrent experiments more than it means handing out tasks._
4. __Listen to the data:__ _The data’s opinion must always be included in product discussions, which means that they must be grounded in visualization through exploratory data analysis in the internal application that becomes the focus of our efforts._
5. __Respect the data-value pyramid:__ `plumbing > clean and question > explore and summarize > Infer and predict > deliver and drive value`
6. __Find the critical path:__ _A product manager cannot manage this process from the top down; rather, a product scientist must discover it from the bottom up._
7. __Get meta:__ _We can’t easily ship good product assets on a schedule comparable to developing a normal application. As we document the analytics process and iteratively climb the data-value pyramid to pursue the critical path to a killer product our Agile deliverables are intermediate content._

![](https://www.oreilly.com/radar/wp-content/uploads/sites/3/2019/06/pyramid-af326273fc483542da476defc8f0b684.png)
### Comparing Agile to DS

> In comparison with design thinking, agile shows some strong parallels: core features like “user-centricity”, “iterative learning and development processes”, and “extensive team communication” seem to suggest that design thinking methodology has been already introduced to IT development. On closer examination, however, one can see crucial differences. __Primarily, agile rather concentrates on continuous incremental refinements than on exploring and comparing radically new solution paths.__
> [Source](https://link.springer.com/chapter/10.1007/978-3-642-13757-0_1)

## Notes

See the [notes](notes.md) for other references that could be of value. You can look over the [a curated list of design thinking resources](https://byuidesignthinking.github.io/course_guide/readings/readings_table.html) to review more material on design thinking.

### Josh's guide on Agile

Roles in Agile -

- **Product Owner:** creates a vision for the final software based on the customer’s needs (the teacher, from SafeGraph project description)
- **Project Manager/Scrum Master:** each team would have one (set by the team, could change weekly). They are in charge or making sure everyone on the team is working productively. Leads the daily stand up meeting.
- **Development Team:** The class teams.

Sprint Planning (Monday every 2 weeks, could be done in 30min) -

- We can create new backlog tasks that need to be done (create these in github even)
- Tasks are assigned a difficulty rating (typically 1-5, 1 being relatively trivial, 5 being a multi person problem, or something that needs to be split into multiple tasks.)
- As a class we discuss what things we are going to take from the backlog to work on for the next 2 weeks. (assigned to doing on github)

Daily Stand Up (Every class period, first 5-10min, should be fast) -
Each team could do it individually and then any big concerns could be brought up to the whole class.

- What **did you work on** since the last stand up (over the last 2 days, or weekend)?
- What are they **going to work on** over the next few days or weekend?
- What are the **big issues** they are currently facing?

Sprint Review Meeting (Every other Friday, starting on week 2; 30 min or half of class) -

- Each group ‘presents’ or shares what they accomplished. Did they finish all of the assigned items from the backlog? Why or why not?
- If a team didn’t finish something then it doesn’t hold up the deadline (end of semester), but for that team it carries over and they need to get more done on the following sprint.

Sprint Retrospection (Same day as Review, following Monday, or done over slack on the weekend) -
Each team discusses as a team:

- What went well
- What didn’t go well
- What changes are going to be made if any?

It’s all about **accountability, and communication** and if a team starts to get really behind then a conversation with the teacher may be warranted.A lot of the meetings could be a hybrid meeting since the project is being done by the whole class, but split into groups. A meeting could start as a team meeting and then expand where each Scrum Master is then a representative of their team for the class meeting.
