Godog Plugin
=======================

IntelliJ IDEA / GoLand plugin for [godog BDD testing](https://github.com/cucumber/godog)

While searching for a Cucumber / Gherkin plugin for GoLand, I noticed that I couldn't find one that was targeted at
GoLand so I decided to write one.  This repo contains a Godog plugin intended for GoLand.

What does it do?
----------------

I'm still working that out.  I'm starting with the following features:

- [x] Syntax highlighting for `.feature` files
- [x] Run a single feature file
- [x] Run a single scenario
- [x] Run all feature files in a directory
- [x] Run all feature files in a module
- [x] Run all feature files in a project
- [x] Run all feature files in a project with a specific tag
- [x] Continuous testing

There's more that I'm thinking about just haven't been able to get to yet.

I am currently learning as much as I can from the implementation of the Cucumber plugin for IntelliJ IDEA.
The intent of this plugin is to be a GoLand specific version supporting Cucumber / Gherkin testing as best I can.


## References

- [Gherkin Plugin](https://plugins.jetbrains.com/plugin/9164-gherkin)
- [GoLand Plugin Development](https://plugins.jetbrains.com/docs/intellij/goland.html)
- [Intellij Go Method Generator](https://github.com/pkondratev/Intellij-go-method-generator/tree/master)
- [Go Builder Idea Plugin](https://github.com/OddCN/go-builder-generator-idea-plugin/tree/master)
