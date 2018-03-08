# Hello Clojure World

So, i wanted to learn functional programming. I was told, try clojure. This
is my repository for experiments and fails with clojure. Lets see. I have no
real plan for now. The only thing i want to do, is learn functional programming
in clojure.

So this is most likely for me and my future reference. I do have
a programming background, but have never touched anything functionl before. Well
I did some haskell yeats back, but actually i only remember that i was unable
to follow anything that was told. As said, i do have a solid understanding
of programming. Some Resources i will obviously need to work through are

 * https://clojure.org/index (that felt kind of rough for a newbie like me)
 * http://clojure-doc.org/ ()
 * https://learnxinyminutes.com/docs/clojure/
 * https://www.braveclojure.com/ (Looks like a good starting point)
 * http://www.learn-clojure.com/ (seems inactive?)
 * https://github.com/functional-koans/clojure-koans

Yeah, actually https://www.braveclojure.com/ seems like exactly the thing i need. Will have to leave the Atom now and read.

## The Environment

I am doing this right now on my mac. So the obvious first step is
to install clojure using homebrew. That installed me 1.9.0 of the language.

That installs the Java Implementation  of the clojure compiler. So
Java should also be installed. Besides that, one needs Leiningen. Leiningen
is (afaiui - as far as i understand it) the project generator/management
tool that sets things like folder structure up. https://leiningen.org/

Lets see:

    lein new app clojure-noob

Creates a new clojure Project!

    lein run

Runs it and

    lein uberjar

builds an executable jar file from it that can be run using java

    java -jar target/uberjar/clojure-noob-0.1.0-SNAPSHOT-standalone.jar

Woah... Holy moly!

Even spiffier:

    lein new cryogen a-blog
