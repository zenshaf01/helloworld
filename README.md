helloworld

Rules for cli ux as per the unix philosophy
- Simple
- Clear
- Composable
- Extensible
- Modular
- Small

Application: A TODO CLI APPLCIATION

Features: - Think features you want you app to have.
* Add Todo
* List Todos
* Mark Done
* Search / Filter
* Pritorities
* Archive
* Edit
* Create Dates
* Due Dates
* Tags
* Projects

Steps:
1. Imagine how would your app look and feel

Cli apps are made up of commands. You run commands and those commands do something.
Commands have:
1. Noun: App name
2. Verb: Action
3. Flag: -p1 (Flags change teh behaviour of the application) (Priority)
4. Object: Value adding to todo

Structure of a command:
> tri add -p1 "Add item"
> tri <- Noun (name of application), add <- Verb, -p1, "Add item" <- Object

