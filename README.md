# OSS Project Status Indicators

[![OSS Status: Healthy](/healthy/oss_status.png)](/healthy/OSS_STATUS.md)

Often, when you're looking at a project on GitHub, it's hard to tell how "loved" the project is.

- Is anyone reviewing the Issues?
- Are pull requests welcomed?
- Has the original maintainer lost interest in mainting this project? Is the project looking for a new owner?
- Is the project simply a snapshot in time, and not something that should be taken as a dependency?

The answers to these questions can sometimes be determined by looking at commit history, or the open and closed issues. Often, you can look at the age of pull requests, and the number of PRs that have been accepted or merged. Sometimes, however, it's not clear.

Wouldn't it be easier if, like build status, this were clearly signalled within the README of the project?

Maybe.

## What you'll find here

This repository contains a set of folders. Each folder contains:

- a `OSS_STATUS.md` file, that you can copy/paste into the root of your OSS project
- an image named `oss_status.png` that you can link to within your `README` file

## How to use the files

1. Copy the appropriate OSS_STATUS.md into the root of your project, much like you would do with a `LICENSE` file.
2. Update your own `README` file to contain an image and link such as:

## What an example of how this is used?

Sure. You're looking at it. This repository has an `OSS_STATUS.md` file at its root, and this `README.md` file links to one of the images at the top. Take a look at the raw Markdown for an example.

## Which status should I use?

At present, you'll find a number of status options. I would suggest they're used according to the guidelines that follow:

| OSS status | Indicator | Folder | Description | Use Case
--|--|--|--|--
healthy | [![OSS Status: Healthy](/healthy/oss_status.png)](/healthy/OSS_STATUS.md) | `/healthy` | Project is actively being worked on. Issues and Pull Requests are welcomed.| Software that you actively want help with.
healthy-closed | [![OSS Status: Healthy, Closed](/healthy-closed/oss_status.png)](/healthy/OSS_STATUS.md) | `/healthy-closed` | Project is actively being worked on, but at this stage isn't looking for contributions. You're welcome to raise issues, comment on code, or create pull requests, but they may well be politely turned down.| A personal blog/website. A project in the very early stages of development, where things are changing rapidly and aren't yet full defined.
dormant | [![OSS Status: Dormant](/dormant/oss_status.png)](/healthy/OSS_STATUS.md) | `/domant` | Project is *not* being actively worked on. Issues and Pull Requests may not be actioned/considered, but you're welcome to raise them. | Projects where the owners have stopped active maintenance.  
abandoned | [![OSS Status: Abandoned](/abandoned/oss_status.png)](/healthy/OSS_STATUS.md) | `/abandoned` | Project is not being worked on, and is very unlikely to ever be worked on again. Software should be considered read-only. If you want changes, forking the repo is preferred. The owner may well be interested in handing ownership over to someone. | Software that the owner knows is old, broken, and where they don't have the time to fix things.

## What if I have a slightly different situation to the ones defined here?

You're welcome to modify or adapt these to fit your needs. You're also welcome to submit PRs for new statuses, or to modify the existing ones.

The main thing to remember is that you're trying to set expectations in a succinct manner. You want visitors to your project to very quickly get a general idea of the status of your project.

If you have nuences and subtlties that aren't expressed easily with a status image and some template text, then maybe you should be more explicit in your README or elsewhere in the repository.

## Isn't this rather gloomy? Why would an OSS project ever get into these states?

Stuff happens. The life of an OSS maintainer changes. If you generate a lot of useful OSS projects you can find yourself inundated with issue, pull requests, and requests for features/changes/whatever. For many, that's **an awesome situation to be in** but, once in a while, maintainers find themselves having to support their legacy OSS projects, and feel guilty when they can't devote time to OSS project that they've pretty much stopped using, or thinking about.

It can often take a long time for an OSS maintainer to remember "what does this code even do!?!" before they're able to properly respond to an issue or PR.

These statuses help the maintainer feel like they've set expectations with a potential user, and will hopefully warn users about the status of a project before they take a dependency on the code, or spend time on a pull request that then goes nowhere.

It's better to be honest, than to disappoint people and feel stressed in doing so.

## Is this a good idea?

Not sure. You tell me. Feel free to raise an issue or open a PR.

## Licensing

Copyright (c) 2019 Martin Peck

Covered by MIT license (see [`LICENSE`][license] file)

[license]: LICENSE