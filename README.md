#Overview
This website is for Robotics and Automation Society at University of Pittsburgh. Developed by Zhijie Wang in 2014. The website is a static HTML using Jekyll as compiling tool, Hanlebar and CSS for templating. The theme is originally forked from Jekyll theme "Minimal Mistake".

## Development Setup Instruction
To develop this wbsite, suggest *NIX environment. In widows, prefer setup is a Linux Virtual Box. However, it is possible via RailsInsrtaller.

Requirements

* Ruby runtime, > 1.9.3 (use RVM for quick setup and gem management)
* A text IDE
* A webbrowser with development tools.
     
First of all, clone this repository. Then change the current working directory to the cloned directory. run the following commands:

    bundle install
    jekyll serve


If the setup is correct, you should see similar output in command line:


    $  minimal-mistakes-master  jekyll serve
    Configuration file: /Users/zhijewang/Developer/jekyll theme/minimal-mistakes-master/_config.yml
            Source: /Users/zhijewang/Developer/jekyll theme/minimal-mistakes-master
       Destination: /Users/zhijewang/Developer/jekyll theme/minimal-mistakes-master/_site
      Generating... 
                    done.
    Configuration file: /Users/zhijewang/Developer/jekyll theme/minimal-mistakes-master/_config.yml
    Server address: http://0.0.0.0:4000/
    Server running... press ctrl-c to stop.

Consult this page for Jekyll env task, [link](http://metaskills.net/2013/09/02/jekyll-tips-and-tricks/).

To use output the static site use this 

`` jekyll build --config _config_production.yml``