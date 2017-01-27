# Appendix 2: Interviews

These informal interviews are meant to cover a broad range of organizational and individual experiences and funding/resource models.  A list of potential interviewees and discussions about topics and experiences to explore can be found [here](https://github.com/shaunagm/free-culture-in-an-expensive-world/issues/2).

#### Interview with Ari Pollak, 6/7/2016; topics covered: Debian

_Hi Ari!  Thanks for agreeing to this interview.  Someone shared with me [this graph of Debian's structure](http://kevix.org/DEBIAN/newdebian2.png).  Obviously Debian is a long-running project with a lot of complexity but could you give me a rough overview of how the project functions?  How do decisions get made?_

So at a super high level, Debian has a constitution that defines the most basic processes and priorities involved in running the Debian Project. It defines the role of the Debian Project Leader (DPL) and its election, how to amend the constitution or make other large decisions through a voting process, and various other things. Debian Developers all have voting rights, but the constitution doesn't actually define the process of becoming a Developer, and that's left up to DPL and his/her delegates. The constitution also defines the role of the Technical Committee, which is tasked with resolving conflicts between Developers if they can't agree on a solution to a technical problem.

On a day-to-day basis, the project is basically managed by individual Developers (say, by uploading packages), DPL-delegated people or teams (like the ftpmasters, who must manually approve all new packages but have automated processes to handle new versions), and the DPL. 

_You mention the Technical Committee, which resolves conflicts.  How often do conflicts come up?  Are they usually minor, or have there been conflicts which threaten to cause permanent rifts in the community?_

It's very rare that something makes it to the Technical Committee, in the grand scheme of things. You can see all of the past decisions at https://www.debian.org/devel/tech-ctte. When they do decide on something, I think it's usually not a really big deal, it's just that there was no easy consensus reached independently. Probably the most controversial decision in recent memory is the one that decided that systemd should be the default init system on new installations; that actually had a very narrow scope, since other init systems are still available to be installed manually, but there are very strong opinions all around about this issue.

_I read a report recently that over 80% of Linux kernel developers are employeed by companies to work on Linux.  Does anyone ever get employed to work on Debian, or are people mostly volunteers?_

I think the vast majority of people are doing it in their free time, but some do get paid to work on it full-time. I can't find statistics on this at the moment, but I seem to remember there being a survey about it a while back, or maybe there's something in Biella Coleman's dissertation about free software. 

_And do you volunteer your time?  How much of a commitment is it, and has the amount of time you've spent on it changed over time?_

Yes. I currently spend at most a few hours a month on it, and that's definitely gone down over time. I spent much more time on it while in high school and college. Some people (obviously the ones working full-time on it, at least) spend much more time. 

_So you started volunteering with Debian while you were in high school.  Is that unusual, or is that a typical story of someone getting involved with Debian?_

I'm not sure how common it is, but I do know quite a few people who started in high school or college. My gut tells me that most people start in college, but that's not backed up by anything. 

_What appealed to you about the project when you first became involved?  Why Debian?_

Debian was the GNU/Linux distribution that was the most appealing to me. This is not a knock on the other distributions, but I had tried Slackware and Red Hat previously and Debian seemed like the sanest one at the time, and got me to stick with GNU/Linux for the long term. Probably the most appealing thing to me (and probably for a lot of other people as well) was the package system, APT, which made software installation way easier than anything I had seen at the time, and has been imitated in many other systems since then. It was also pretty easy to get involved - even though the New Maintainer process (to become a Developer) could take years at the time, you don't need to have that title just to contribute, and assistance is generally welcomed. 

_How large is the Debian community?  Has it changed significantly in size over the years, or had periods of significant turnover?_

I think I can't really speak to that. Some other people have probably tried to quantify the number of contributors over time; I think it's tricky to measure since there are many ways of contributing that don't involve just being a Debian Developer. Participation feels like it's been roughly stable over time since I've been involved (since around 2000). 

_You mentioned earlier that the amount of time you've spent volunteering for Debian has gone down over time.  Was navigating that tough at all?  Did you have to formally pass off specific responsibilities?  What's the process when someone who was doing something can't do it anymore?_

It's a pretty common occurrence for people to spend less time on the project or leave entirely, so there are easy formal ways of indicating your intentions. For package maintenance specifically, you can formally request that someone else adopt your package or request that other people help out by using the Work-Needing and Prospective Packages (WNPP) list. If you've been appointed by the DPL to a particular position, you'd usually try to ensure a smooth transition and resign. I did pass off some of my packages to other people, but for my remaining packages I've just spent less time on them, so I haven't really improved them, just continued to update new versions from upstream and triage bug reports where possible. 

_Are there any areas of Debian - specific packages, perhaps, but also types of work like design or marketing or community management - that you think would really benefit from having more time and attention?  Of course there will always be room for improvement with any project, but with a project like Debian you can't exactly hire people to make up technical debt or fix an ongoing issue.  How do you deal with that?  Do people get burned out trying to take on too much?_

I think all of those - design (including UI/UX), marketing, community management, are definitely things that are historically underrepresented in Debian and most free software projects, and could always stand to be improved It's always been hard to recruit people interested in those areas by the very nature of these kinds of projects - they tend to be started by highly technical people whose interests don't lie in the less technical aspects but are scratching their own itch. I don't really have a solution, but it seems like the desire to expand free software communities is at least getting more attention these days.

There are instances where SPI (the nonprofit organization backing Debian financially) or outside sources have paid people to work on specific areas of Debian. That funding tends to be controversial and narrow in scope. I think that in the past, when people have spent larger amounts of money on improving Debian, they've generally done so with a profit motive, and resulted in forking Debian (see Progeny and Ubuntu).

People definitely get burned out by taking on too much or just waning interest over time, but I feel like the highest-profile resignations have been over disagreements within the community.

_How does SPI decide when to pay someone to work on Debian?  When there's controversy, how does that get resolved?  And can you talk about the Debian community's relationship with forks like Progeny and Ubuntu?  Sorry, I know that's three questions in one._

I'm not sure of the SPI process exactly, but there's a board of directors that makes the ultimate decisions. I think they tend to err against controversy when possible. 

I think relationships with large (especially for-profit) forks start out pretty negatively, This might only reflect on the loudest people in the community, but there seems to be a general feeling of unfairness when certain existing Debian contributors get picked as employees. Not only is it a pretty sweet gig to get paid for something they already work on and enjoy, but there's also the perception that they might contribute less to Debian directly because of it.  That feeling tends to improve over time, somewhat because there are visible contributions from downstream (the fork) to upstream (Debian), but also just because the existence of the fork becomes normal. 

_How much upstream contribution is there?  Do you think that Progeny, Ubuntu and others like them are a net benefit to Debian, and how common is that opinon?  I know you can't speak for anyone else, but I'd love to get your general sense of community opinion, with as many caveats and hedges as needed._

I don't really have a sense for how much upstream contribution there is to Debian. Having seen good examples of it, whether that's via patches submitted or new contributors joining Debian, I do think the forks have a net benefit. I feel like that's the majority opinion at this point.

Debian has a reputation for not being as user-friendly as some other distributions. It's gotten a lot better over time, but certainly still has some rough edges. So from that perspective, if other projects can encourage more users of free software by investing in polishing those rough parts, which in turn encourages more contribution all around, I'm certainly in favor of that. 

_I use Ubuntu myself, and I find the user design very straight-forward and approachable.  I've not used Debian, so I can't compare their UX, and I certainly can't compare either to pre-Ubuntu Debian.  But perhaps you can!  Would you say that Debian's user design has improved since Ubuntu came around?  If so - do you think it's due to upstream contributions from Ubuntu, or to a general sense of "oh, this is more important than we thought", or is it unrelated?  If it hasn't really improved, is there a sense that people who want better UX can just use Ubuntu?_

I think that the major desktop environments used with both Debian and Ubuntu (GNOME Shell and Unity, respectively) are pretty comparable at this point in terms of usability. I think the biggest issue that people have with Debian UX is from the perspective of a non-technical user who has never used a Linux distribution before and doesn't want to learn much about the inner workings of the system, they just want a stable, reliable OS on commodity hardware. For that kind of user, I still recommend Ubuntu. I think their desktop installer is friendlier and makes it easier for non-technical users to just get up and running, though Debian has made huge strides in its own installer. Ubuntu's 6 month release cycle also helps to ensure that it can run relatively successfully on recent systems; there have been many discussions in Debian about similar ideas, but nothing concrete has materialized. I do think the forks have resulted in some motivation for Debian contributors to improve the user friendliness of the system, so that it can be the first choice for more and more types of users, even if it might not ever be the first choice for everyone. I think overall, UX improvements in Ubuntu have mostly stayed in Ubuntu, since they developed a lot of things (the installer, Unity) only for use with Ubuntu, without looking for feedback from other distributions.  Debian does still reap the benefits of improvements in other free software, so as things like GNOME improve, so will Debian. 

_I have one last question.  Circling back to the question of burnout - how does the Debian community deal with this issue?  Is there a culture of disclosure and support, where you'll find people saying things like, "I'm really overwhelmed right now" and their fellow community members validating that and sharing advice?  And are there ever cases where someone's burned out or overwhelmed but not willing to step down from maintainership of a given package?_

I think there's inherently a culture of both ownership and community. Packages can be officially maintained by a particular person, but just like in any organization, there are still collective goals to be attained. Enough people feel a sense of collective responsibility to produce the highest quality product possible that they'll pitch in and help out where needed, whether that's at a bug squashing party or simply lending a hand on their own. I haven't followed the mailing lists enough to recall instances of people asking about advice for burnout specifically, but I get the sense that everyone knows it's a thing that happens and that we should try to accomodate people as much as possible to prevent it. There have been cases where a maintainer will be unresponsive for a long time or is not keeping up to date with the package, and there are processes to deal with that, though that could take a long time.

_Okay, I lied about that being the last question.  Can you elaborate a bit on the processes for dealing with unresponsive maintainers?_

For bugs considered release-critical (as in, there's a serious problem with it such that it shouldn't be officially released, as defined by some known criteria), it's a special case and Non-Maintainer Uploads (NMU) are allowed, provided the standard process is followed, which can take a couple of weeks. There's also a "Low Threshold NMU" list where maintainers can voluntarily declare that their own packages are allowed to be fixed immediately by anyone. For maintainers that refuse to fix a particular issue, that can be escalated to the Technical Committee.

For maintainers that are mostly or completely unresponsive, the Debian QA MIA team handles it. The process involves some steps over a period of months and will eventually result in a takeover of that maintainer's packages and finally the removal of their credentials from the project. 

_Thanks for taking the time to answer my questions, Ari._

#### Interview with Carol Willing, 6/13/2016; topics covered: OpenHatch, Jupyter, Linux

__Disclaimer: This interview contains the personal opinions of the interviewee.  They are not speaking on behalf of any of their employer or any of the organizations mentioned within.__

_Hi Carol!  Thanks for agreeing to be interviewed.  Can you start us off by talking about your history with open source communities - which ones you've participated in, and which ones you're working with now?_

Hi Shauna. My history with open source communities goes back to Linux in the 1990s. At the time I wanted to contribute to the project but found the process to contribute somewhat mysterious and not well documented.

I've participated with Open Hardware, like Arduino, Raspberry PI and the micro:bit. I also over the years worked on OpenHatch, Requests, PyLadies, CPython, Cookiecutter, IPython, Jupyter as well as some other Python projects. Currently, I work full time as a core developer on Jupyter. In my spare time, I work on Cookiecutter, PyLadies, OpenHatch, Software Carpentry, and CPython.

_Have you been paid to work on any open source projects other than Jupyter, or have the rest all been as a volunteer?_

Other than Jupyter, all the other contributions have been done as an unpaid volunteer.

_Can you talk a bit about how this volunteer work has fit into your life?  Have you ever struggled to make time for it, or felt like you were getting burned out?_

Good question. I have been very involved in Education non-profits over the years. Contributing to open source has its roots in my interests in making educational materials more accessible for others. There have certainly been times where other priorities in my life (family, illness, travel, etc.) have made it difficult to contribute to open source. I have found myself getting burned out from time to time. Usually the catalysts for burnout for me are hostile or aggressive messages or comments, demands by a community member for a change or fix, and underappreciation for the work that I provide in my spare time.

_Are there projects you've volunteered with that you think handle those burnout-catalysts particularly well?  If so, what did they do/how did they approach the problem?_

A few projects come to mind. OpenHatch, Requests, Cookiecutter, and PyLadies are all projects that have been flexible about my needs as a contributor and were supportive if I needed to take a break from contributing. One of the things that Requests did particularly well was allow me to pair and work with one of the maintainers. Since I was pairing, there was less pressure to have the project's expectations only on my shoulders. I was able to step in and out as time and energy permitted.

_I'm glad to hear that OpenHatch is/was a supportive environment for you.  Some context for readers: I (Shauna, the interviewer) was a paid contractor for OpenHatch for about two and a half years.  For a year and a half of that, I was the only person being paid to work on the project.  I definitely felt some discomfort on my end, that I was being paid to do work that sometimes bled into the volunteer work that others were doing.  Has the fact that some of your collaborators were being paid ever influenced your experiences as a volunteer?_

I think that paid collaborators have both positively and negatively influenced my experiences as a volunteer. For OpenHatch, a paid collaborator, Shauna, added so much structure and community positivity that the project flourished under her leadership. The same level of activity and contribution at OpenHatch was negatively impacted on Shauna's departure.

Jupyter/IPython also had a positive impact when I worked on the project before being hired to work on it full time. The paid contributors had a genuine interest in seeing the research project be successful and made a concerted effort to have contributors be successful.

As for CPython, there have been times where I have felt that others were advocating more from the position of their employer than the best interests of the language. Overall, it hasn't been a frequent occurance or really impacted my experience as a volunteer.

After spending time observing the Linux contribution process and going to Linux conferences, I chose not to contribute because the project put corporate interests before individual contributors. The project tolerated aggressive and hostile comments and posts. The corporations that were funding both the development work and the Linux Foundation showed weak interest in acting on behalf of the greater community and condoned the unprofessional behavior and comments.

_OpenHatch is a non-profit with mostly volunteer contributors.  I know that the vast majority of Linux contributors are corporate employees.  Can you talk a bit about the structure of Jupyter and CPython?  Where does the funding come from, and (roughly) what percentage of contributors are volunteer vs paid?_

Jupyter is structured as an open community that has its roots in building consensus on decisions and decision making is sometimes made by the Steering Council when consensus can not be reached. Overall, the discussions are very civil and professional. The bulk of Jupyter's funding comes from generous foundations, like the Helmsley Charitable Trust, the Alfred P. Sloan Foundation, and the Gordon and Betty Moore Foundation. These foundations recognize the impact that Jupyter has in furthering scientific research and data science and fund the Jupyter project to further important real world solutions to complex, cross-discipline problems. There are many unpaid volunteers on the project; there is also a small number less than a dozen academic individuals employed to contribute to the project which helps give the project sustainability and direction.

As for CPython, it is largely a volunteer project. A few individuals are paid by their employers to work on CPython. Those that do are typically paid to spend a percentage of their time on an open source project and the individuals have chosen core Python. While the Python Software Foundation's mission is to further the adoption and use of Python globally, a small percentage of the funds are spent on infrastructure to maintain CPython. In fact, the technical direction of CPython is largely separate from the PSF.

_So of the four projects/communities you listed in the previous question, three are mostly comprised of volunteers, albeit with different levels of funding from donations, foundations, or employers.  Linux, whose environment you have problems with, is largely made up of for-profit contributors.  Do you think that volunteer and non-profit communities are more likely to be welcoming and healthier than for-profit-dominated communtiies?  Or do you think that's just the way these particular projects have turned out?_

These are tough questions. I suspect that we could find positive and negative examples of communities in both non-profit/volunteer based projects as well as projects with funding from for-profit companies. 

Largely, I believe a community's health and inclusion of others is driven by the leadership and core contributors of the project. If health and inclusion are both valued and acted upon genuinely, I believe that communities see positive results and repeat contributors (particularly contributor beyond just those writing software). 

One very interesting aspect of communities that receive the bulk of their funding from for-profit companies is that repeat sponsorship by those companies becomes critical to sustain the project's baseline as well as growth. Non-profit/volunteer projects tend to grow more organically and rely upon their community for sustainability and viability. If the project has a yucky environment for contributors, interest wanes and volunteers leave. However, a for-profit project can greater afford to maintain a minimal viable community behavior standard since employees paid to work on the project are unlikely to leave as quickly as volunteers.

One other element to think about is the impact that economics play when a project provides a product or code base that is a standard with no large or viable competitors. For example, the cloud infrastructure is largely based on the Linux operating system. In essence, if not in practice, Linux is a single source or a technology monopoly. The costs of trying to build a cloud infrastructure without Linux would be cost prohibitive. The dominance of Linux as an infrastructure OS lends itself to some interesting economic externalities.

For example, each company is acting in their own corporate best interests to increase their shareholder value. As such, they wish to increase revenue while maintaining or reducing costs. Which begs the question what incentives does an individual company have to improve a community's working environment such as inclusion and healthy activities. Very few incentives since each company can look to the others to take action and maintain that their company is doing its best. It becomes easier and less expensive to print brochures espousing missions and a commitment to inclusion; while resourcing actions to truly improve the community fall by wayside.

_I'm intrigued by this "minimal viable community behavior standard".  Many companies have HR departments and standards of behavior that employees need to meet.  Do you get the sense that the Linux community largely meets those standards, but fails to rise above them?  Or is there some behavior that's falling between the cracks?_

Much like research done on economics and cybersecurity, I believe that the funding of a healthy and inclusive community faces similar economic factors. First, measurement of a healthy community, as security, is a difficult task with many variables. The difficulty of measurement creates a corporate decision of how much to invest in community behavior and sustainability. On the one hand the company does not want to underinvest and look as if they are flaunting popular expectations of behavior and HR (remembering that HR protects the corporation's interests not the employee's) practices. On the other hand, the companies definitely do not wish to overinvest in improving community behavior since overinvesting impacts the shareholders and the bottom line.

Investing in community behavior and inclusion falls into a similar economic explanation that Gordon, Loeb, and Lucyshyn observed for security expenditures that it is actually economically sensible to invest only a portion of the total funds available for community until serious outcry actually happens. This is much like a deferment option in capital budgeting. Only resource upfront a small amount and wait and see if you need to take further action.

Anderson, an expert on economics and cybersecurity, discusses how security investment is difficult to measure and the associated costs to society are particularly difficult to quantify. What are the actual opportunity costs to society when a higher behavior standard is not funded? Are resources being misallocated between technical projects and community sustainability? It's tough to measure.

_As you said in your last answer, Linux is in some ways a monopoly.  You can't see the cost of a lower community standard because there's no real alternatives at all to compare it to.  Now I'm curious - are there any examples you know of, where a non-monopoly project has been forked specifically to improve community behavior standards?_

While I'm not aware of a project that has been forked to improve community behavior standards, I do think that there is quality academic research that lends itself to providing a comparison for community behavior and inclusion which supports that a healthier, more diverse community has financial benefits, as well as the more difficult to measure social benefits. Academic research demonstrates that corporations with diverse boards of directors outperform homogenous boards. I also believe that research that has been done on open source communities does tend to support that the less tangible community factors do impact the adoption and sustainability of a project.

As a technical monopoly, if you will, the Linux core team has little incentive to foster new ideas and developers. Maintaining the status quo becomes more important than the risk of opening the project to more ideas where it is harder to control the contributions and technical direction. Ultimately, until there is a viable alternative to the flavors of Linux, Linux will be viewed by companies that it must support Linux or risk being excluded from an important market. The companies that support Linux have little incentive to rock the "community" boat.

_Let's refocus now on your personal experiences of open source contribution.  How has working as a paid contributor for Jupyter been different than your previous volunteer contributing?_

Hmm... In many ways, it is largely the same. In some ways, working as a paid contributor is more stressful since I wear more hats than strictly development work on issues that I choose myself. While I'm encouraged to try new ideas and technologies on Jupyter, I feel a personal obligation to test the viability of an idea before really diving in. As a volunteer, I was only accountable to myself so I could freely experiment with new packages and nurture the creative side of software development. Happily Jupyter is used in education and I still see many creative ways to improve and enhance education with Jupyter. I feel that I should disclose that I have both financial and educational privilege so my personal burden as a volunteer was less than others.

_Thanks for clarifying that, Carol.  Are you comfortable talking a bit more about that financial and educational privilege, and how it has affected your ability to volunteer?_

Financial privilege is pretty straightforward. Family assets and early career success combined with investing along with modest needs for accumulation of things have allowed me to volunteer my time without the worry of meeting the essential needs of life such as food, shelter, and health.

As for educational privilege, I have an MS in Management from MIT and a BSE in Electrical Engineering from Duke. As a woman in tech both of these universities give me a baseline of credibility that is sadly not necessarily given freely to other women or minorities. My time at MIT years ago included a strong emphasis of giving back to the world and I'd like to think that I am doing that in some small way.

_How do decisions get made in Jupyter?  You mentioned feeling accountable - how does that accountability work?_

Decisions are largely made on the mailing list and within GitHub issues through discussion and working toward the best approach. Like many projects, there are far more tasks and needs than we have contributors to fill. My feeling of accountability is largely my own personal integrity and desire to work on high value tasks which will benefit the community or the project. I also feel that I have a responsibility to do my best to fulfill the mission of the grants that the foundations have funded since doing so will improve scientific collaboration.

_How does the community decide which work gets done?  Is it largely an individualized process depending on personal judgments?_

We have been trying to do a better job of curating issues for contributors to work on. Our core team prides itself on being accessible and interested in helping our users succeed. We encourage users to ask about a proposed feature before doing too much work on it. As a project that has many repos and is evolving quickly, we recognize that creating a collaborative community is important. So is supporting the research efforts of other projects that are tangential or related to Jupyter.

_Are there any particular areas of Jupyter that you feel are under-resourced?_

Like many open source projects, sustaining infrastructure, maintenance engineering, community management, and documentation are challenging to resource while at the same time working on new features and projects for the future. We're working on automating some things and trying to make it easier for contributors to assist with documentation and community outreach.

_Are there any resources that you've used, or that you've created for others to use, that help with those under-resourced areas?_

Documentation, documentation, documentation, Read the Docs, Write the Docs. Triaging issues also helps contributors. Overall, it's the many little things that I do during the day that have the greatest impact: answering questions, adding small changes to docs based on user questions, documenting the contribution process including installing a dev environment, working with user groups. Not a huge surprise to you given our experience with OpenHatch and helping communities be more inviting and welcoming. 

_Thank you for your time and your thoughts, Carol!_
