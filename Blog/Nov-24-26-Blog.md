Practicing git via https://learngitbranching.js.org/ today!

Not entirely certain that I need to learn navigating git repos to this depth, but I got through the first two 'tracks'.

Dabbled with my homelab (using a new mini-PC) and got the framework setup for using Ansible to configure the mini-PC (and any other compute in the future) - one of the biggest mental hurdles I had here was wrapping my head around working through containers.  I already had Docker Desktop setup for a local OTel collector I wanted set up, so I have the Ansible server essentially spin up from scratch (a docker image) and run its tasks based on configurations and then shut down.  Then I was able to get it to setup Docker on my mini-PC.

https://github.com/users/Meowakin/projects/4/views/1 - and to get some more practice with GitHub, I set this up as a Project (private for now) and setup some issues for next steps.  Throughout this I've been using Claude chat to work through and understand each of the steps. I have a lot of trouble trusting a fully vibe-coded environment, and I think the most important thing for me in building out a homelab is that I personally understand the mechanisms down to at least the architecture level.  There are still a number of decisions that I just have to trust the abstraction, though (i.e. Ansible, Docker - I don't know how *those* work on a fundamental level).

