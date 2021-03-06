---
layout: page
title: Portfolio
permalink: /portfolio/
id: portfolio
---

The following is a sampling of some of the software projects I have created (or
contributed to).

# Ruby on Rails projects

<ul>
<li>
<h2 class="project">Catering Event Manager</h2>
<img alt="Catrr: a catering event manager" src="/assets/catrr_quote-screenshot.png"/>
<p class="description">

This is a partially-built commercial rails application for caterers who want an
easy way to manage and track all of their events, provide quotes to customers,
etc. I worked on this in my spare time for fun, but never got it to a point
where I felt comfortable releasing it. I learned a valuable lesson about how to
prioritize what's actually important to get a viable app deployed and <em>in the
wild</em> instead of getting everything perfect.

</p>
<h3>My contributions</h3>
<ul>
  <li>Full-stack development</li>
  <li>Behaviour-driven design using Cucumber and rSpec</li>
</ul>
<p class="source">
<a href="https://github.com/fapapa/em1/tree/original_version">source</a>
(private repo; send me an email and I can grant access on a case-by-case basis.)
</p>
</li>

<li>
<h2 class="project">Fitagotchi</h2>
<img alt="Fitagotchi: Winning final project at Lighthouse Labs" src="/assets/fitagotchi_screenshot.png"/>
<p class="description">

Fitagotchi is a mashup of the 90's toy phenomenon <em>Tamagotchi</em> with your
Fitbit activity tracker. Instead of keeping a little critter alive-and-well by
clicking some buttons, you keep it alive using your calories on your Fitbit. You
can also challenge friends to three-day battles to see who can burn the most
calories; for which you will be rewarding with an animated fight scene when
finished. <strong>Won first prize for final project at Lighthouse Labs Web
Development Boot-camp.</strong>

</p>
<h3>My contributions</h3>
<ul>
  <li>Full-stack development</li>
  <li>Rails back-end/API</li>
  <li>React front-end</li>
  <li>Involved in everything from planning to design, architecture, and
  development</li>
</ul>
<p class="source"><a href="https://github.com/fapapa/Bit-Fit">source</a></p>
</li>

<li>
<h2 class="project">Catering Manager (Orlando's Catering)</h2>
<img alt="Catering Manager app screenshot" src="/assets/catering_manager-screenshot.png"/>
<p class="description">
  Rails application to manage menus, and generate and send quotes for a small
  catering company.
</p>
<h3>My contributions</h3>
<ul>
	<li>Back-end development using Rails 5</li>
	<li>HTML, CSS and Javascript development</li>
	<li>Behaviour-driven development with Cucumber/rSpec</li>
	<li>DevOps/deployment/maintenance</li>
</ul>
<p class="source">
<a href="https://gitlab.com/fapapa/catering-menus">source</a>
(private repo; send me an email and I can grant access on a case-by-case basis.)
</p>
</li>
</ul>

# Ruby on Rails contributions

<ul>
<li>
<h2 class="project">
  GitLab - merge request <a
  href="https://gitlab.com/gitlab-org/gitlab-ce/merge_requests/29718"> !29718
  </a>
</h2>
<img alt="Conversation on GitLab showing my contribution"
     src="/assets/mr_!29718-screenshot.png"/>
<p class="description">

GitLab is an open-source dev-ops toolchain for developers. In this contribution
I added a requested feature that adds a preference to allow maintainers to
create subgroups, instead of having to ask the owner of the group to create the
subgroup, giving developers the option to be more agile.

</p>
<p class="source">
  <a href="https://gitlab.com/gitlab-org/gitlab-ce/issues/51610">issue</a>
  <a href="https://gitlab.com/gitlab-org/gitlab-ce/merge_requests/29718">
  merge request</a>
  <a href="https://gitlab.com/gitlab-org/gitlab-ce/commit/e48851de62086b65c75a3dd802743e722d5d7be8">
  commit</a>
</p>
</li>
<li>
<h2 class="project">
  GitLab - merge request <a
  href="https://gitlab.com/gitlab-org/gitlab-ce/merge_requests/25942"> !25942
  </a>
</h2>
<img alt="Conversation on GitLab showing my contribution"
     src="/assets/mr_!25942-screenshot.png"/>
<p class="description">

My first contribution to <em>GitLab</em>! Simply a matter of deleting some
unnecessary lines and updating the unit tests. I wanted to get a flavour for
installing GDK and stepping through the workflow of squashing bugs and adding
features.

</p>
<p class="source">
  <a href="https://gitlab.com/gitlab-org/gitlab-ce/issues/50386">issue</a>
  <a href="https://gitlab.com/gitlab-org/gitlab-ce/merge_requests/25942">
  merge request</a>
  <a href="https://gitlab.com/gitlab-org/gitlab-ce/commit/60713c1fc6c6513246dd066b2e71d2bfd28c8e3a">
  commit</a>
</p>
</li>
<li>
<h2 class="project">
  GitLab - merge request <a
  href="https://gitlab.com/gitlab-org/gitlab-ce/merge_requests/29511"> !29511
  </a>
</h2>
<img alt="Conversation on GitLab showing my contribution"
     src="/assets/mr_!29511-screenshot.png"/>
<p class="description">

I fixed an issue where, when pushing a repository to a new and default branch,
the commit messages would not get processed for issue references, which was
stopping some users of competitive products from switching to GitLab.

</p>
<p class="source">
  <a href="https://gitlab.com/gitlab-org/gitlab-ce/issues/56683">issue</a>
  <a href="https://gitlab.com/gitlab-org/gitlab-ce/merge_requests/29511">
  merge request</a>
  <a href="https://gitlab.com/gitlab-org/gitlab-ce/commit/0c4059efc146c869d3ffd1bc075c67c8b4ae921d">
  commit</a>
</p>
</li>
</ul>

# Ruby projects

<ul>
<li>
<h2 class="project">Hack assembler</h2>
<img alt="Two files side-by-side; a hack file and the same file after being
converted to assembly" src="/assets/hack_assembler-screenshot.png"/>
<p class="description">

In this project for the <a
href="https://www.coursera.org/learn/build-a-computer" title="Build a Modern
Computer from First Principles: From Nand to Tetris"> Coursera Nand2Tetris
course</a>, I write an assembler, which takes a given program in Hack assembly,
and converts it to Hack machine code. Machine code is the combination of raw
binary bits that a processor can take as instructions for a program. It is
exceptionally tedious to read or write a program in machine code, as you must
encode and decode 0's and 1's and exactly where they need to go to execute the
instruction you want. Assembly is has a one-to-one correlation to machine code
(each line of assembly is one instruction), but it is symbolic and therefore
much easier to read and write for us mere mortals. However, the computer needs
instructions sent to it in machine code, so the assembler does the work of
converting assembly language to machine code.

</p>
<h3>My contributions</h3>
<ul>
<li>Wrote a <strong>Ruby implementation</strong> of the Hack assembler</li>
<li>100% grade</li>
</ul>
<p class="source">
  <a href="https://gitlab.com/fapapa/nand2tetris-course/tree/master/projects/06">
  source
  </a>
</p>
</li>

<li>
<h2 class="project">VM Translator</h2>
<img alt="Two files side-by-side: a VM file and the same file after being converted to assembly"
src="/assets/vm_translator-screenshot.png"/>
<p class="description">

A VM Translator is a program that translates programs written in a VM language
into programs written in an assembly language. VM languages provide a level of
abstraction above assembly languages. So, whereas assembly languages are a
symbolic representation of the instructions being sent to the CPU, VM languages
allow the programmer to think more abstractly; usually (and in this case), that
abstraction is a stack machine. The commands allow the programmer to push data
onto and pop data off of a virtual stack, instead of having to deal with memory
directly. This level of abstraction is still not feasible to write large
programs in. So why have the VM layer at all? VMs afford a level of flexibility
that would otherwise not be possible. As an example, JRuby and Java can both be
compiled into JVM, which can in turn be tranlated to work on multiple different
architectures/CPUs. Instead of needing one compiler per language per
architecture, you need only one compiler per language, and then one VM
translator per architecture. So if there are 10 languages and five
architechtures, without a VM intermediary you would need 50 compilers (5 &times;
10); with a VM language you would need only 10 compilers and five VM translators
(5 + 10).

</p>
<h3>My contributions</h3>
<ul>
<li> Wrote a <strong>Ruby implementation</strong> of the VM translator</li>
<li>100% grade</li>
</ul>
<p class="source"><a href="https://gitlab.com/fapapa/nand2tetris-course/tree/master/projects/08">source</a></p>
</li>

<li>
<h2 class="project">Jack Compiler</h2>
<img alt="Two files side-by-side: an object-oriented Jack file, next to its output after being compiled"
src="/assets/jack_compiler-screenshot.png"/>
<p class="description">

A compiler takes some code in a high-level language and converts it into code in
a lower-level language. In this case, it converts code in Jack to code in the VM
language discussed above. This process is broken down into two broad steps:
<em>syntax analysis</em> and <em>code generation</em>. Syntax analysis involves
turning the high-level code into a stream of tokens and parsing that stream into
a tree structure using the grammatical rules defined by the high-level language.
Code generation uses the semantic meaning derived from the syntax analysis and
generates code with the same meaning, but in the lower-level language.

</p>
<h3>My contributions</h3>
<ul>
<li>Wrote a <strong>Ruby implementation</strong> of the compiler</li>
<li>100% grade</li>
</ul>
<p class="source">
<a href="https://gitlab.com/fapapa/nand2tetris-course/tree/master/projects/11">source</a>
</p>
</li>
</ul>

# Other projects

<ul>
<li>
<h2 class="project">JackDoku (Sudoku game built in Jack language)</h2>
<img alt="" src="/assets/jackdoku_game_in_progress.jpg"/>
<p class="description">

In the <a href="https://www.coursera.org/learn/build-a-computer" title="Build a
Modern Computer from First Principles: From Nand to Tetris"> Nand2Tetris
course</a> we build a computer from the bottom up, from a simple NAND gate, to a
computer architechture, to machine code, a virtual machine, a programming
language, an operating system, and the culmination is an object-oriented
application of our choosing. For this project I chose to build a simple Sudoku
game. The code is anything but simple though. While the OS does provide some
libraries for manipulating the screen, the libraries limit you to writing
16&times;16 pixel sprites at pre-determined locations on the screen. Using this
library would have meant using just a little over half the height of the screen;
the game would have looked small and awkward. In order to make my sudoku grid
take up as much of the screen as possible, I had to engineer a way to write an
arbitrarily-sized sprite starting at any given pixel on the screen. This was a
challenging task, but it was gratifying to not only figure out the details of
the solution, but to also wrap those details in a layer of abstraction that made
it easy to use in my game.

</p>
<h3>My contributions</h3>
<ul>
<li>Wrote the game from nothing</li>
<li>Wrote a low-level library to write any sprite to any location on the
screen</li>
<li>Used binary math, logical operators and bit-shifting to manipulate graphics
on the screen</li>
</ul>
<p class="source">
<a href="https://gitlab.com/fapapa/nand2tetris-course/tree/master/projects/09/JackDoku">source</a>
</p>
</li>
</ul>
