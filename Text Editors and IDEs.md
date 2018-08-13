# Text Editors and IDEs

*Note: Parts of this guide, included the editors mentioned, are subjective.  I tried to keep things informative overall, which still applying my own judgement to avoid making this guide cumbersome to use.*

For a quick recommendation, jump to the editors by subject section.


## Table of Contents

1. [Introduction](#introduction)
    1. [What is a text editor?](#what-is-a-text-editor)
    2. [What is an IDE?](#what-is-an-ide)
    3. [Why does my choice matter?](#why-does-my-choice-matter)
2. [Editors by Type](#editors-by-type)
    1. [Command line editors](#command-line-editors)
    2. [GUI text editors](#gui-text-editors)
    3. [IDEs](#ides)
3. [Editors by Subject](#editors-by-subject)
    1. [Web Technologies (HTML, CSS, JS)](#web-technologies-html-css-js)
    2. [Ruby on Rails](#ruby-on-rails)
    3. [C#, C++, and C](#c-c-and-c)
    4. [Delphi](#delphi)
4. [Conclusion](#conclusion)

## Introduction

So you want to write some code, and you've heard of programs called "Text Editors" which are built for writing text, specifically code.  But which text editor is the right tool for what you're trying to do?  What are the differences between the many options out there?

This guide offers an brief look at both the variety of options for creating code, including Text Editors and IDEs.

### What is a text editor?

A [text editor](https://en.wikipedia.org/wiki/Text_editor) is a computer program which allows you to create and edit plain text data via [character encodings](https://en.wikipedia.org/wiki/Character_encoding).  Most advanced text editors are built for programmers, and have advanced functionality to make creating and editing code easier.

It's important to understand the distinction between a text editor (which works with plaintext) and a word processor (which works with rich text).  Microsoft's Notepad program is an example of a very basic text editor.  Microsoft Word is an example of a word processor - it's not a text editor.

![](http://puu.sh/BdlzY.png)

### What is an IDE?

An IDE is like a text editor with a bunch of added functionality to make managing, refactoring, optimizing, and compiling code easier.  A good example of an IDE is Microsoft Visual Studio.

![](http://puu.sh/BdlER.png)

### Why does my choice matter?

The tools you use while developing software can have a huge impact on how things go.  Using bad tools can make your life harder, where making good tools can make it easier.  The text editor or IDE you use is no exception, and can be central to your productivity.

## Editors by Type

### Command line editors

- **[vim](https://www.vim.org/):** The text editor which comes with the "I wanna write code and look cool while doing it" starter kit.  Annoyingly [counterintuitive](http://www.commitstrip.com/en/2017/05/29/trapped/), but its proponents will never stop singing its praises.
- **[Emacs](https://www.gnu.org/software/emacs/):** Lisp-based text editor which has a plugin for literally [everything](https://xkcd.com/378/).  It's not really a text editor so much as an operating system.
- **[nano](https://www.nano-editor.org/):** Incredibly simple (and limited) command line editor.  Good option if you don't want to edit text files on the command line and just want to quickly paste some text over SSH.

### GUI text editors

- **[Notepad++](https://notepad-plus-plus.org/):** A great text editor to fallback to when you don't feel like opening a big heavy IDE to view/edit a single file.  It's not incredibly pretty, but it's snappy and generally gets the job done.
- **[VS Code](https://code.visualstudio.com/):** Quickly becoming the best text editor on the market, VS Code is worth trying regardless of the languages you're coding for.
- **[Sublime Text](https://www.sublimetext.com/):** A popular freemium text editor.  Many users swear by its feature set, though I personally don't see it as anything special.
- **[Atom](https://atom.io/):** VS Code's obese older brother.  Has had recurring issues with being slow and resource heavy, which aren't problems you want to have with a text editor.  However, it does have one of the most extensive ecosystems of user-created extensions.

### IDEs

- **[JetBrains IDEs](https://www.jetbrains.com/):** Pretty much the best IDEs out there.  If there's a JetBrains IDE for the language you're coding in you probably should probably be using it.  Even if you don't make use of 90% of the features, the text editing experience is phenomenal.
- **[Visual Studio](https://visualstudio.microsoft.com/):** Microsoft's extremely extensive IDE.  It has a lot of features and is a pretty solid piece of a software overall.
- **[Delphi Community Edition](https://www.embarcadero.com/products/delphi/starter):** Embarcadero finally decided to make a community edition of their Delphi IDE.  The IDE isn't that bad, though writing code in a fading language can be painful.
- **[Eclipse](https://www.eclipse.org/downloads/):** "The IDE" for Java development.  Can also be used to develop software in a number of [other languages](https://en.wikipedia.org/wiki/Eclipse_(software)).

## Editors by Subject

*Note: More subjects may be added here in the future.  The current subjects are limited to ones which I have a lot of experience with.*

### Web Technologies (HTML, CSS, JS)

**Recommended:** [WebStorm](https://www.jetbrains.com/webstorm/)  
**Description:** The JetBrains IDE for web development.  WebStorm offers a number of invaluable features for web development, including reference resolution for JavaScript identifiers and CSS classes, linter integration, project and library search, and easy file navigation.

**Second Choice:** [VS Code](https://code.visualstudio.com/)  
**Description:** VS Code is a responsive and powerful text editor, and is great for editing JavaScript.  It's pretty great, but isn't quite as smooth to use as WebStorm.

### Ruby on Rails

**Recommended:** [RubyMine](https://www.jetbrains.com/ruby/)  
**Description:** The JetBrains IDE for Ruby on Rails and web development.  It's very similar to WebStorm but made for a RoR stack.

### C#, C++, and C

**Recommended:** [Visual Studio](https://visualstudio.microsoft.com/)  
**Description:** Microsoft's fantastic IDE.  Though it has a bit of an initial learning curve, Visual Studio is one heck of an IDE.  It's definitely the tool to use for C++ and C unless you're developing for Mac/Linux.

### Delphi

**Recommended:** [Delphi Community Edition 10.2+](https://www.embarcadero.com/products/delphi/starter)  
**Description:** The first free Embarcadero Delphi IDE.  You'll want to use this version of the Delphi IDE for all of your projects.  Note, however, that it cannot compile for x64.