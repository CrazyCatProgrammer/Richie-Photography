# Getting started


## Requirements
Ruby
Cloned or downloaded version of this repo

Visual studio code (optional)
Github Desktop (optional)
Ungodly amounts of patience (optional)

## How to view Locally
**Note** don't include the "" when coping the code below :) 

First you're going to want to clone the github repo to your computer

So open up your command line or terminal and type
"git clone https://github.com/CrazyCatProgrammer/Richie-Photography.git"

Then either through command line or your favorite editor you will want to check that you have bundler installed

Command line
"
cd C:\Users\(your username on your computer)\Documents\GitHub\Richie-Photography
"

I'm writting this from a windows computer so if you're using a mac or linux machine the slashes "/" might be the other way

Once you're in the folder type 
"
gem install jekyll bundler
"

It will install a crazy ammount of gems, yes you want them, they're pretty and shiny and make your website run. If it helps, you can imagine yourself as a now fabulously wealthy website pirate. Aaarrr.

Here is where things get fun. In your command line once you've cloned everything and set up bundler you will want to type 

"
bundle exec jekyll serve
"

you should see something like

"
$ bundle exec jekyll serve
Configuration file: C:/Users/Documents/GitHub/Richie-Photography/_config.yml
            Source: C:/Users/Documents/GitHub/Richie-Photography
       Destination: C:/Users/Documents/GitHub/Richie-Photography/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 2.294 seconds.
  Please add the following to your Gemfile to avoid polling for changes:
    gem 'wdm', '>= 0.1.0' if Gem.win_platform?
 Auto-regeneration: enabled for 'C:/Users/Documents/GitHub/Richie-Photography'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
"

show up

Copy and paste the server address (http://127.0.0.1:4000/) into your browser and VOILA. You are now viewing your personal website locally. Thus giving you the ability and opportunity to make it personal and professional before letting it loose for the world to see. Have fun!

