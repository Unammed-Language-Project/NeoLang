## Setting Up
Currently, there isnt a proper way to install or set up Neo. So, the only way is to clone the entire repository and run it from there. 

There are a few prerequisites, so make sure you have these tools installed before you start:
- [Java 11 or higher](https://adoptopenjdk.net/)
- [Git](https://git-scm.com/)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)

First, run `git clone https://github.com/Unammed-Language-Project/Neo`. This will clone the Neo repository onto your local machine. Now, fire up the project inside of Intellij IDEA! 

Now, if you're not wanting to work on the compiler itself, I would advise you to not touch anything inside the `Neo` folder. To write Neo code, you can start editing the `hehe.neo` file, which should be inside of the `src/` folder.
Once you write your code, head over to the `Neo` folder, and find the `Neo.java` file. Right click and hit run on the little arrow beside the Neo class, and that should run your program! A little window should pop up at the bottom of IntelliJ, and the output of the program you wrote in your `hehe.neo` file should show at first, then fire up a REPL, where you can write and test small snippets of code.
To exit the REPL, you can run `#exit` to quit the REPL and go back to editing your `.neo` file!

Once you run `Neo.java` using the arrow for the first time, you should be able to re-run the REPl everytime by clicking on the green arrow at the top.
