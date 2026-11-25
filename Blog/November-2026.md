# November, 2026
## November 24th, 2026
Practicing git via https://learngitbranching.js.org/ today!

Not entirely certain that I need to learn navigating git repos to this depth, but I got through the first two 'tracks'.

Dabbled with my homelab (using a new mini-PC) and got the framework setup for using Ansible to configure the mini-PC (and any other compute in the future) - one of the biggest mental hurdles I had here was wrapping my head around working through containers.  I already had Docker Desktop setup for a local OTel collector I wanted set up, so I have the Ansible server essentially spin up from scratch (a docker image) and run its tasks based on configurations and then shut down.  Then I was able to get it to setup Docker on my mini-PC.

https://github.com/users/Meowakin/projects/4/views/1 - and to get some more practice with GitHub, I set this up as a Project (private for now) and setup some issues for next steps.  Throughout this I've been using Claude chat to work through and understand each of the steps. I have a lot of trouble trusting a fully vibe-coded environment, and I think the most important thing for me in building out a homelab is that I personally understand the mechanisms down to at least the architecture level.  There are still a number of decisions that I just have to trust the abstraction, though (i.e. Ansible, Docker - I don't know how *those* work on a fundamental level).

## November 25th, 2026
### 9am-12pm
Starting blog post

Starting part 2 of 2 for Microsoft's [GitHub Foundations](https://learn.microsoft.com/en-us/training/paths/github-foundations-2/?ns-enrollment-type=Collection&ns-enrollment-id=1oz2iotxo7xqr0) training today, starting with 'Contribute to an open-source project on GitHub'

Choosing where to focus my efforts is definitely the hard part - anything I choose is an investment of my time just to become familiar with the project enough to contribute. Personal thought - that's probably the #1 challenge of any open source project, being accessible to newbies.

Interesting rule of thumb: 
> "Put roughly as much time into writing your PR as you did in making the change to the project."

Code reusability blurb strikes home: 
> For all three of the suggested paths, consider that you're now a maintainer of a project. People will come to you with praise, questions, and complaints. Are you ready for such a commitment?

> If your project takes off, people's apps might depend on your bit of code. Can you involve more people to take some of the potential load off? Do you have time to add documentation, triage issues, and review suggestions from people you've likely never met before? Consider your "bandwidth," and instead set expectations in your project's README file. Or, you can release your code in a public gist or a blog post. Code doesn't need to be on GitHub to be open source, after all.

This echoes my belief that if I am building something, I do not want to be stuck maintaining it into perpetuity.  So anything I design needs to prioritize the ability for someone else to carry the torch (if they so desire).  Provided it is something that others will use, at any rate.  This increases the threshold for what I am willing to share with others, though.

### 12pm-3pm
