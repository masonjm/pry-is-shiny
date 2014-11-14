# Cool Stuff You Can Do With Pry

Pry is a replacement for IRB. You can use it just like IRB, but it has a bunch of cool features that make it better.

* edit
    - Enter multi-line commands
    - Edit your last command
    - Iterate while you're trying to figure something out
* cd & ls
    - Inspect elements
    - No more `puts @foo.methods.sort.to_yaml`
* ; and _
    - No more messy extra output
    - `Model.all;` # Note the trailing semicolon
    - But you can check it later
    - `_`
* .
    - Run shell commands
    - `.ls`, `.git diff`
* pry-doc, ? and $
    - ? and $ let you view source and documentation
    - `? []#each`, `$ puts`
    - Install the `pry-doc` gem to make it work for core classes
* binding.pry
    - Start pry from anywhere in your code
    - Kinda like a debugger, but fancier
    - You can also get a gem that makes it exactly like a debugger
* help
    - docmentation for built-in commands
    - `help gem`
* gem-cd
    - Great when you don't know where a gem is installed
    - `gem-cd yard; .subl .` to open sublime in the gem's directory
* pry-rails
    - Make the rails console by pry by default
