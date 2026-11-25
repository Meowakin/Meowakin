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
Rethinking my blog structuring, putting those thoughts in an issue on my 'profile' repo.  AKA getting distracted from the training modules, but figuring out how to get my thoughts out of my head efficiently is important to me!  Also figuring out how to do those things in a way that helps build other skills effectively.

Lunch!

Moving onto the next module: Manage an InnerSource program by using GitHub (another thought re: format - maybe I can just have these time stamped automagically which is part of why I like IM platforms).

Preach, module!
>  If misused, metrics can harm the culture, existing processes, and diminish the collective sentiment towards the organization or leadership team.

Love some metrics, but I'm at a loss for how to evaluate *myself* and my *own* progress.  Step one is to create a record of the things I am doing, so here we are!  It does bring to mind how people have metrics showing the history of their job hunt, and I am quite curious how most of them go about doing that.  I personally feel that it is not terribly healthy to need those sorts of personal metrics, but I presume they are using something standardized that generates those for them.

And done with the Innersource module - really just a reframing of the principles already learned.  Metrics is an interesting thing to bring up in that context when they haven't been mentioned before - I presume this is because Innersource implies working in an organization that needs to prove their value, a pressure that isn't as relevant to open source (but I would argue is still present).

Doing some repository management before moving onto the next module - archiving obsolute repositories that I've moved on from (trying to stay organized).

And now onto the next module - Maintain a secure repository by using GitHub best practices!  (that timestamp thing might be nice, 3 hour granularity is probably fine, though)  Looking forward to this, I hate doing things without understanding what the best practices are, and knowing when they can be broken safely.

Things to consider:
> There's a general knowledge problem: Many developers and other staff members assume they understand security, but they don't. Cybersecurity is a constantly evolving discipline. A program of ongoing education and training is essential.
Amen to that - I know I don't know enough and it's slightly terrifying.
> Code must be created correctly and securely: We need to be sure that the code is created correctly and securely implements the required features. We also need to make sure that the features were designed with security in mind.
This definitely slips through the cracks a frightening amount of time - this kind of thing is its own full-time job!
> Applications must comply with rules and regulations: We need to make sure that the code complies with required rules and regulations. We have to test for compliance while building the code and then retest periodically, even after deployment.
Also its own full-time job, I don't think it's practical for any one person to manage all of this well, though I am sure there are some grizzled veterans out there that can.

This has a lot of parallels with Observability and the challenges there.  Operations (shift right) has had monitoring and been trying to understand what the applications they support are doing, and the real answer is to have Development (shift left) instrument their code rather than having Operations cobble together some weird endoscope to investigate from the outside.

### 3pm-6pm