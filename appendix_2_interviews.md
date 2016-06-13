# Appendix 2: Interviews

These informal interviews are meant to cover a broad range of organizational and individual experiences and funding/resource models.  A list of potential interviewees and discussions about topics and experiences to explore can be found [here](https://github.com/shaunagm/free-culture-in-an-expensive-world/issues/2).

#### Interview with Ari Pollack, 6/7/2016; topics covered: Debian

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
