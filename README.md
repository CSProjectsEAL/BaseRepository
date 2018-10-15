https://img.shields.io/badge/waffle.io-dependency-yellowgreen.svg

# Scrum Base Repository

Clone this repository when you want to start a new repository and reuse templates and labels that was used in previous projects. Using scrum and managed in github.


## Install Instructions

```sh
git clone git@github.com:CSProjectsEAL/ScrumBaseRepository.git
```

- Go into the newly created folder and run the following command:

```sh
 rm -r remove .git
```

- Initialise the git and push the base to a new repository.

```sh
	git init
	git remote add origin [NameOfRepository]
	git push -u origin master
```

- On the new repository if you want to reuse the labels that this repository has, go to github.com/yourusername/newreponame/labels page and open the js developer console in your browser. Then copy in the script found in the gist below:

- https://gist.github.com/alex855k/69de4efdc7464eb904cbd3ea3df61dfa


# Credit goes to https://github.com/jvandemo/github-scrum-workflow/blob/master/README.md

<img src="https://cloud.githubusercontent.com/assets/1859381/5397698/9972fe22-815c-11e4-8be6-21e1d0d05849.jpg" alt="codecat" align="right">

# HOWTO : GitHub scrum workflow

Turn any GitHub repository into a simple but powerful agile work environment.

**Summary:**

+ [How it works](#how-it-works)
+ [1. Create issues as backlog items](#1-create-issues-as-backlog-items)
+ [2. Add labels to issues](#2-add-labels-to-issues)
+ [3. Define sprints as milestones](#3-define-sprints-as-milestones)
+ [Overview](#overview)
+ [Helpful links](#helpful-links)
+ [Change log](#change-log)

---

## How it works

- items are reported as **issues**
- points and meta data are assigned to items as **labels**
- **milestones** are used to group issues in sprints

## 1. Create issues as backlog items

To create a new backlog item, just create a new issue.

Once a new issue has been created, assign it the right labels and/or assign it to a sprint (milestone).

Issues allow you to have a conversation about the item and even allow you to create task lists inside the issue using [GitHub's markdown](https://guides.github.com/features/mastering-markdown/).

## 2. Add labels to issues

Add the following labels to your repository:

### Priorities

`priority` labels allow you to prioritize items in your backlog e.g.:

- `priority: low`
- `priority: medium`
- `priority: high`

### Points

Add these extra labels for points, or use waffle.io framework to manage that kind of meta date

`point` labels allow you to to assign velocity points to individual items (issues) e.g. using [Fibonacci numbers](http://en.wikipedia.org/wiki/Fibonacci_number):

- `point: 1`
- `point: 2`
- `point: 3`
- `point: 5`
- `point: 8`
- `point: 13`
- `point: 21`

### Types

`type` labels allow you to easily filter items (issues) in the dashboard e.g.:

- `type:bug`: bug
- `type:hotfix`: fix that requires immediate attention
- `type:feature`: new feature
- `type:feature`: new feature
- `type:infrastructure`: infrastructure related change or addition
- `type:performance`: performance related issue
- `type:refactor`: refactor issue
- `type:test`: test related issues

### Other

You can define and assign custom labels that you need within your workflow or organization.

## 3. Define sprints as milestones

You can create a milestone for every sprint and add items (issues) from the backlog to a milestone.

This allows you to group items in sprints and track them by milestone in your [issue dashboard](https://github.com/issues).

The backlog then consists of all items (issues) that have no `milestone` attached to it.

**TIP**: Use `no:milestone` in the search field on your [issue dashboard](https://github.com/issues) to find backlog items.

## Overview

![en_overview](https://cloud.githubusercontent.com/assets/1859381/5411950/c44c229e-8207-11e4-915f-d31ccd66c5bd.png)

Image: [Scrum primer](http://www.scrumprimer.org/overview).

## Helpful links

- [Mastering GitHub issues](https://guides.github.com/features/issues/)
- [Mastering GitHub markdown](https://guides.github.com/features/mastering-markdown/)
- [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)
