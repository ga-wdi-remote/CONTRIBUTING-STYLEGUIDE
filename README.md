# How to use this organization and contribute

* [Contributing](#contributing)
* [Naming Conventions](#naming-conventions)
  - [Repos](#repositoris)
  - [Branches](#branches)
* [Making Changes to Existing Content](making-changes)


## What it is

This Organization holds repositories of lessons and daily class work, labs, homework, and installation lessons.

## <a name="contributing">Contributing</a>

Before creating a new repository search through organization to make sure your content is unique. You can search by repo topic names like lesson and homework or by topics like javascript, express, mongoose, ruby, rails,

*If it is not unique*

Clone the repository that contains an version of your content and make a new branch to push your content to.

_see naming conventions below_

*If it is unique*

Create a new repository with a master and a solution branch.

Label your repo with [Topics](https://github.com/blog/2309-introducing-topics) by clicking the Settings tab in the organization, and clicking Repository topics.

Find your repo in the list and add the relevant tags to make the repo easily searchable from the org home page.

Be sure to definitely label your repo as either lesson, homework, lab etc and the technologies required.

## <a name="naming-conventions">Naming Conventions</a>

#### <a name="repositories">Repositories</a>

Name of the repo should start with language/tech abbreviation followed by the type of content and the name of the assignment.

_examples:_
```
js-hw-function-reps
ruby-lab-banana-stand
```

Once the repo is created add a description to the repository describing the content if there are things specific to the content that should be known early.

For Example:

That the lab in a repo is a multi-day assignment or dependent on the content in some other repo etc.

## <a name="branches">Branches</a>

Every repo should have the starter code, lesson, README, instructions, examples, on the `master` branch.

The solution code in a solutions branch.

#### Iterating on existing content

If changes are updates be sure to update the master branch as well as the solution branch.

#### Adding a new version of existing content

Your branch name should include your name and whether it's the master or the solution.

```
master
<your name>-solution
```

## <a name="making-changes">Making Changes</a>

Create an issue on the repo in question and list the problem, proposed fix, or addition and the associated branch, file, line number, etc.

The content owner can either make that change or suggest that it goes into a new version of the lesson made by _you!_
