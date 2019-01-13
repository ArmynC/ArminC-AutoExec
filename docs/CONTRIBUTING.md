# Introduction

First off, thank you for considering contributing to ArminC AutoExec. It's people like you that make ArminC AutoExec such a great config.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

Keep an open mind! Improving documentation, bug triaging, or writing tutorials are all examples of helpful contributions that mean less work for you.

ArminC AutoExec is an open source project and we love to receive contributions from our community — you! There are many ways to contribute, from writing tutorials or blog posts, improving the documentation, submitting bug reports and feature requests or writing code which can be incorporated into ArminC AutoExec itself.

Again, defining this up front means less work for you. If someone ignores your guide and submits something you don’t want, you can simply close it and point to your policy.

Please, don't use the issue tracker for [support questions](https://github.com/ArmynC/ArminC-AutoExec#troubleshooting). Check whether the issue fix is already posted somewhere in this repository. If your problem is not strictly related to your fault, try to [contact me](https://github.com/ArmynC/ArminC-AutoExec#support). Searching on the community is also worth considering.

# Ground Rules

This includes not just how to communicate with others (being respectful, considerate, etc) but also technical responsibilities (importance of testing, project dependencies, etc). Mention and link to your code of conduct, if you have one.

Responsibilities:
* Ensure compatibility for every change that's accepted. Older, current and beta game versions.
* Ensure that code that goes into core meets all requirements in this [checklist](https://github.com/ArmynC/ArminC-AutoExec/blob/master/docs/PULL_REQUEST_TEMPLATE.md).
* Create issues for any major changes and enhancements that you wish to make. Discuss things transparently and get community feedback.
* Be welcoming to newcomers and encourage diverse new contributors from all backgrounds. See the [r/GlobalOffensive](https://www.reddit.com/r/GlobalOffensive/).

# Your first contribution

Unsure where to begin contributing to ArminC AutoExec? You can start by looking through these easy issues, issues which should only require a few lines of code, and a test or two, rather than issues which should be a bit more involved than beginner issues.

Working on your first Pull Request? You can learn how from this *free* series, [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

At this point, you're ready to make your changes! Feel free to ask for help; everyone is a beginner at first :)

If a maintainer asks you to "rebase" your Pull Request, they're saying that a lot of code has changed and that you need to update your branch so it's easier to merge.

# Getting started

For something that is bigger than a one or two line fix:

1. Create your own fork of the code
2. Do the changes in your fork
3. If you like the change and think the project could use it:
    * Be sure you have followed the code style for the project.
    * Look at all the Pull Request rules.
    * Check your code for a perfect condition.

Small contributions such as fixing spelling errors, where the content is small enough to not be considered bug fixing, can be submitted by a contributor as a patch, without a request.

As a rule of thumb, changes are obvious fixes if they do not introduce any new functionality or creative thinking. As long as the change does not affect functionality, some likely examples include the following:
* Spelling/grammar fixes.
* Typo correction, white space and formatting changes.
* Comment clean up.
* Adding logging messages.
* Changes to ‘metadata’ files like .gitignore etc.

# How to report a bug

If you find a critical bug, [contact me](https://github.com/ArmynC/ArminC-AutoExec/blob/master/docs/README.md#support), after that open an issue.

Any critical issues should be submitted directly to the [contact](https://github.com/ArmynC/ArminC-AutoExec/blob/master/docs/README.md#support).

In order to determine whether you are dealing with a critical issue, ask yourself these two questions:
* There is a significant negative change in the gameplay?
* Is there any important value mistyped (like network, frame rate, mouse)?

If the answer to either of those two questions is "yes", then you're probably dealing with a critical issue. Note that even if you answer "no" to both questions, you may still be dealing with a critical issue, so if you're unsure, just [contact me](https://github.com/ArmynC/ArminC-AutoExec/blob/master/docs/README.md#support).

Before you submit an issue, [search](https://github.com/ArmynC/ArminC-AutoExec/issues) the issues archive; maybe the issue has already been submitted or considered. If the issue appears to be a bug and hasn't been reported, open a [new issue](https://github.com/ArmynC/ArminC-AutoExec/issues/new).

Please do not report duplicate issues; help us maximize the effort we can spend fixing issues and adding enhancements.

Providing the following information will increase the chances of your issue being dealt with quickly:

* Issue Title - provide a concise issue title.
* Complete the full Issue Template - GitHub support issue templates and ArminC AutoExec provides one to make submitting an issue with all of the required information more straightforward.
* Suggest a Fix - if you can't fix the bug yourself, perhaps you can point to what might be causing the problem (line of code or commit).

When filing an issue, make sure to answer correctly at the [all questions](https://github.com/ArmynC/ArminC-AutoExec/blob/master/docs/ISSUE_TEMPLATE.md). Be careful not to jump over any step of the process.

# How to suggest a feature or enhancement

ArminC AutoExec provide an optimized gameplay, making it a great solution for the gamers overall.

It does not lack any important feature. With the support over this repository, you can quickly set your configuration.

If there is back-and-forth about a feature, ask them to scope the feature, thinking through why it’s needed and how it might work.

If you find yourself wishing for a feature that doesn't exist in ArminC AutoExec, you are probably not alone. There are bound to be others out there with similar needs. Many of the features that ArminC AutoExec has today have been added because of the need to the community. 

Before opening an [issue](https://github.com/ArmynC/ArminC-AutoExec/issues) on our issues list on GitHub where you can describe the feature you would like to, tell why you need it and how it should work take into account that this config has a high standard of quality for references and will not accept changes based on simple tutorials or assumptions.

Also, make sure to use spaces (no tabs) and CRLF line endings for configs, and continue the Valve convention in the other file overrides. Ensure is no trailing space at the end of lines. Keep the max line before the needing of a scroll (in Fullscreen), otherwise, skip to a new line.

The template of the command required:

```
// Description of the command.
// Default: value
//
// In-deep documented information about the command, recommended actions etc.
prefix_command "value"
```

Every setting and change should be based on information found in:

* [Counter-Strike: Global Offensive blog posts/patch notes](http://blog.counter-strike.net/).
* [Valve Developer Wiki](https://developer.valvesoftware.com/wiki/).
* [Source SDK 2013](https://github.com/ValveSoftware/source-sdk-2013)
* [Source Engine 2007](https://github.com/csnxs/source-2007).
* [GameTracking-CSGO](https://github.com/SteamDatabase/GameTracking-CSGO/).
* [GameNetworkingSockets](https://github.com/ValveSoftware/GameNetworkingSockets)
* [CSGO Cvars list](https://github.com/funeralchris/csgo-list-of-cvars).

# Code review process

The author looks at Pull Requests on a regular basis in a weekly check. 
After feedback has been given we expect responses within two weeks. After two weeks we may close the pull request if it isn't showing any activity.

# Wiki

Do you have a workaround, some resources or anything else interesting you'd like to share?
Contribute to the [wiki](https://github.com/ArmynC/ArminC-AutoExec/wiki).

# Community

You can chat with the author on [Steam](https://steamcommunity.com/id/arminc/). I'll answer to any request, but at an undetermined time.

The code needs to be nicely placed, easy to read, pleasing to the eyes and documented. Each user must be documented about commands, that's our mission.
