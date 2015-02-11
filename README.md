# The Bug Fix Manifesto

[http://krasimir.github.io/TheBugFixManifesto/](http://krasimir.github.io/TheBugFixManifesto/)

I could split my programming experience in two parts. The first one is a little bit more creative. That's the time where the application still does not exist. You invent and architect the program. The second part is extending and fixing the already created system. They, these two parts, have their own interesting and boring sides. However, I believe that they both are in the essence of delivering quality software. This article focuses on bug fixing. It aims to give you bunch of advices how to properly handle the problems in your applications.

## The preparation

The bug, the problem, in your system should be documented. It should be described somewhere. No matter if you are the developer that will work on it or the tester that found it. Create a ticket, issue, card, or whatever you use for managing your projects. Don't rely on instant messengers for bug reporting. Emailing is a little bit better but still not the right way to go.

Here are few things that you have to include in your report:

* What exactly (you think) is the problem. Please be as detailed as possible. Description containing only one sentence saying "The product's page is broken!" does not help.
* Write down how (you think) the software should look/behave. It is possible that you don't know that and something reported as a bug may be a working feature.
* Include steps to reproduce section. The ability of proper and quick bug reproducing is really important.
* In the end, guide the developer (if possible) how to fix the bug. If you for example know which parts of the system are involved you better mention them.

## Get the things done

Now you have a nice bug report and can't wait to start working. Check out the steps below to make sure that you are on the right track.

* Never make code changes before understanding what exactly the issue is. That's just a waste of time. Invest as much time as needed for finding the real problem.
* It will be nice if you reproduce the bug with an automated test. Especially in web development. You don't want spending half of your time in the browser filling forms and clicking links.
* Think of the best solution possible. Plan the changes and discuss them with the team.
* And finally do the job. Fix it!
* Look back and refactor your code. For sure you missed something.

## Finish line

When everything is done and you are proud of yourself take some time to document your work. It takes just a few minutes but it matters to the reviewers. While submitting your changes list the following:

* A link to the ticket/issue/card in your project management system (if you use one).
* Explain briefly the problem.
* Explain your solution. What parts you changed and why.
* Write down steps for reproducing the problem.

## Summary

I hope that some of the advices above apply to your workflow. They work for me and really help solving bugs quickly.
