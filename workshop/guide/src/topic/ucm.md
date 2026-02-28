# Unison Codebase Manager

Unison leverages the _Unison Codebase Manager_ to have great control over your
project.

Instead of relying on text-files to store the software models, _ucm_
manipulates the definitions in their abstract syntax tree form.

We already have seen a glimpse of the power of this tool, now we are going to
it in all its glory.

## Starting ucm

Start the `ucm` in a directory.

```plain
>> ucm
```

You will be greated by a banner

```plain
  Now starting the Unison Codebase Manager (UCM)...


   _____     _             
  |  |  |___|_|___ ___ ___ 
  |  |  |   | |_ -| . |   |
  |_____|_|_|_|___|___|_|_|
  
  👋 Welcome to Unison!
  
  You are running version: release/1.1.0


  📚 Read the official docs at https://www.unison-lang.org/docs/
  
  Hint: Type 'projects' to list all your projects, or 'project.create' to start something new.
```

## Create a Project

We are going to create a project to explore Unison in this workshop. As
suggested we are going to use `project.create` for that. If you don't provide
a name, the ucm will pick one for you

```plain
> procject.create
```

```
  🎉 I've created the project with the randomly-chosen name jolly-racoon (use
  `project.rename <new-name>` to change it).


  I'll now fetch the latest version of the base Unison library...


  🎨 Type `ui` to explore this project's code in your browser.
  🔭 Discover libraries at https://share.unison-lang.org
  📖 Use `help-topic projects` to learn more about projects.
  
  Write your first Unison code with UCM:
  
    1. Open scratch.u.
    2. Write some Unison code and save the file.
    3. In UCM, type `update` to save it to your new project.
  
  🎉 🥳 Happy coding!
```

If you already know a name, you could also provided it when using the
`project.create` command

```plain
> project.create awesome-name
```

## Unison Share

If we want to use the `booster-2026` project as a dependency in this workshop.

For that we are going to rely on [_Unison Share_][share]. This is the place to
discover all things awesome the community created.

Search for `booster-2026`.

And press the "use project" button. It will teach you how to install the
library.

```plain
> lib.install @dvberkel/booster-2026/main
```

```
  I installed @dvberkel/booster-2026/main into lib.dvberkel_booster_2026_main
```

## List the Terms

You can use ucm to explore the project.

```plain
> ls
```

And drill deeper in the dependencies

```plain
> ls lib
```

and deeper

```plain
> ls lib.dvberkel_booster_2026_main
```

## Viewing a Term

Not only can we list the terms in the project. We can `view` them as well.

```plain
> view lib.dvberkel_booster_2026_main.ucm.README
```

Notice that it describes more information about the ucm in a `Doc` format.


## Exercise

Explore the `ucm.README`.

[share]: https://share.unison-lang.org/
