# Fibonacci Sequence - Clojure  
This is my first Clojure script! What better way to learn the language than to
apply it to a concrete problem?

## Current project
This is the beginning of my Clojure journey, so as normal, there isn't much to
go. I'll outline the scripts that I am developing here as a way to track what
I have worked on.

  * **Fibonacci Sequence - Iterative Solution**  
  This Clojure script calculates the fibonacci number given a positive integer,
  and returns a hash map containing:
    * a) The fibonacci number at the input value
    * b) The fibonacci sequence up to the input value

## Running Project,
There are several ways to run this sample project (**NOTE:** some of these may
not be available until all project files are uploaded.):  

  * **REPL:** The easiest way to run is to execute in the REPL.
    * Start the REPL with `lein repl`; it should load in the project's namespace
      `fibonacci.core`
    * Run the desired function, with a given argument, like so:  
      `fibonacci.core => (fNumberIterative 10)`  

  * **Jupyter Notebook**
    * If you have [Jupyter](https://jupyter.org/) installed, you can download
      and run the notebook in an interactive fashion.  
    * Alternatively, follow the `notebooks` folder in this repo, and see the
      code and output, though you will not be able to interact with it otherwise.

  * **Standalone JAR**  
    * *instructions coming soon!*

## To Do  
Fleshing out these scripts will help me not only learn Clojure with Leiningen
and REPL, but it will also help me learn Clojure unit testing with Midje.

  * Write a script for the iterative solution of calculating the fibonacci
    sequence.
  * Write test for both solutions using Midje.
  * Implement memoization of the recursive solution to mitigate the expense of
    recursion.

## Notes:

* [Leiningen](https://github.com/technomancy/leiningen/tree/stable) - Automate
  Clojure projects without setting your hair on fire! Can be install on macOS
  with Homebrew.
* [Jupyter Notebook](https://jupyter.org/) - Prototype experimental code, right
  in the browser! For Clojure projects, you'll need the
  [Clojure kernel](https://github.com/roryk/clojupyter).
* [Clojure Kernel](https://github.com/roryk/clojupyter) - Allow running Clojure
  code in Jupyter Notebook.
* [Midje](https://github.com/marick/Midje) - Testing for Clojure.
