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
<li>Old catering app</li>
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
* Contributions to GitLab

# Ruby projects
<ul>
<li>
<h2 class="project">Hack assembler</h2>
<img alt="Two files side-by-side; a hack file and the same file after being
converted to assembly" src="/assets/hack_assembler-screenshot.png"/>
<p class="description">

  In this project for the <a
  href="https://www.coursera.org/learn/build-a-computer" title="Build a Modern Computer from First Principles: From Nand to Tetris">
  Coursera Nand2Tetris course</a>, I write an assembler, which takes a given
  program in Hack assembly, and converts it to Hack machine code. Machine code
  is the combination of raw binary bits that a processor can take as
  instructions for a program. It is exceptionally tedious to read or write a
  program in machine code, as you must encode and decode 0's and 1's and exactly
  where they need to go to execute the instruction you want. Assembly is has a
  one-to-one correlation to machine code (each line of assembly is one
  instruction), but it is symbolic and therefore much easier to read and write
  for us mere mortals. However, the computer needs instructions sent to it in
  machine code, so the assembler does the work of converting assembly language
  to machine code.

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
  symbolic representation of the instructions being sent to the CPU, VM
  languages allow the programmer to think more abstractly; usually (and in this
  case), that abstraction is a stack machine. The commands allow the programmer
  to push data onto and pop data off of a virtual stack, instead of having to
  deal with memory directly. This level of abstraction is still not feasible to
  write large programs in. So why have the VM layer at all? VMs afford a level
  of flexibility that would otherwise not be possible. As an example, JRuby and
  Java can both be compiled into JVM, which can in turn be tranlated to work on
  multiple different architectures/CPUs. Instead of needing one compiler per
  language per architecture, you need only one compiler per language, and then
  one VM translator per architecture. So if there are 10 languages and five
  architechtures, without a VM intermediary you would need 50 compilers (5
  &times; 10); with a VM language you would need only 10 compilers and five VM
  translators (5 + 10).

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

  A compiler takes some code in a high-level language and converts it into code
  in a lower-level language. In this case, it converts code in Jack to code in
  the VM language discussed above. This process is broken down into two broad
  steps: <em>syntax analysis</em> and <em>code generation</em>. Syntax analysis
  involves turning the high-level code into a stream of tokens and parsing that
  stream into a tree structure using the grammatical rules defined by the
  high-level language. Code generation uses the semantic meaning derived from
  the syntax analysis and generates code with the same meaning, but in the
  lower-level language.

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

  In the <a href="https://www.coursera.org/learn/build-a-computer"
  title="Build a Modern Computer from First Principles: From Nand to Tetris">
  Nand2Tetris course</a> we build a computer from the bottom up, from a simple
  NAND gate, to a computer architechture, to machine code, a virtual machine,
  a programming language, an operating system, and the culmination is an
  object-oriented application of our choosing. For this project I chose to build
  a simple Sudoku game. The code is anything but simple though. While the OS
  does provide some libraries for manipulating the screen, the libraries limit
  you to writing 16&times;16 pixel sprites at pre-determined locations on the
  screen. Using this library would have meant using just a little over half the
  height of the screen; the game would have looked small and awkward. In order
  to make my sudoku grid take up as much of the screen as possible, I had to
  engineer a way to write an arbitrarily-sized sprite starting at any given
  pixel on the screen. This was a challenging task, but it was gratifying to not
  only figure out the details of the solution, but to also wrap those details in
  a layer of abstraction that made it easy to use in my game.

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
