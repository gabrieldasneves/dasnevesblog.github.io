## My personal Blog : https://gabrieldasneves.github.io/

This project is about the usage of **Jekyll** with **Github Pages**.

## Motivation

I apreciate to write about the things I find interesting and important but, not everything should be written in a network geared towards the professional area, right?

I went after platforms like Medium and I felt that something was bothering me.

"I know how to code, so I could make a blog by myself, I don't need to rely on a platform and I can even choose the style I want!"

Soon, I went after options to develop the Blog and discovered Jekyll. A Ruby on Rails-based tool for developing static websites.

There is still a lot to learn in this tool.

## Requirements

To run it with a code editor (E.G.: VS-code), you should have:


  - Ruby version 2.5.0 or above, including all development headers (ruby version can be checked by running ruby -v)
  - RubyGems (which you can check by running gem -v)
  - GCC and Make (in case your system doesn’t have them installed, which you can check by running gcc -v,g++ -v and make -v in your system’s command line interface)

## Installing

Before we install Jekyll, we need to make sure we have all the required dependencies.

<b>sudo apt-get install ruby-full build-essential zlib1g-dev</b>

<b>echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc</b>

then finally install it:

<b>gem install jekyll bundler</b>

## Features
It is hostted on GitHub Pages, more information [here](https://pages.github.com/)

## How to use?

To open it using an editor you should open your terminal, go into the projects folder and run:

<b>bundle exec jekyll serve</b>

Then browse to http://localhost:4000

## Credits
Proper credits given to https://github.com/willianjusten that has inspired me to build it. 

## That's it!

© [Gabriel das Neves](https://gabrieldasneves.github.io/)
