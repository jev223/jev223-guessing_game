## CSE262-SP21
guessing_game: A programming exercise to introduce students to git, GitHub, GitHub Classroom, rust, and cargo

## Learning Objectives
- Learn how to use git (clone, add, commit, and push)
- Learn about the Cargo package manager
- Learn how to create mutable and immutable variables in Rust
- Learn how to read from stdin and write to stdout
- Learn how to generated random numbers
 
## Assignment Description
This assignment is based on an assignment prepared by Dr. Corey Montella.

For this assignment, you will follow the guessing game tutorial in [Chapter 2 of the Rust Book](https://doc.rust-lang.org/stable/book/ch02-00-guessing-game-tutorial.html).

The first thing you'll want to do is decide where you want to do your development work. You can work on sunlab, as Rust and Cargo is already installed on all sunlab machines. If you want to work on your system, you'll need to set up the Rust toolchain. This is covered in [Chapter 1 of the Rust Book](https://doc.rust-lang.org/book/ch01-01-installation.html). Alternatively, you could use an online integrated development environment (IDE) like [Repl.it](https://repl.it/languages/rust) or some other online IDE to do your work.

## Instructions
I want you to do this assignment a particular way. To begin, you'll clone this repository I created in GitHub Classroom. You can use either of the following commands to clone onto a sunlab machine, your machine, Repl.it, or wherever. 

```
git clone <repository HTTPS URL>     # prompts for GitHub username and password
git clone <repository SSH URL>       # uses SSH keypair (public key placed on GitHub)
```

To obtain the HTTPS or SSH URL, click on the green "Code" button above and to the right of your repository file listing. I had an issue (could have just been me) when I attempted to use the HTTPS URL to clone my repo to sunlab, so I ended up using the SSH URL. To learn how to generate an SSH key pair, read the link on Coursesite entitled, `"How to Create an SSH Key Pair"`. 

Once your repo is cloned, you should edit the Cargo.toml file to update the `"authors"` line to reflect your name and email address.

Next, you'll start following the tutorial. It will start out by telling you to make a directory called `guessing_game`. Do NOT type `cargo new guessing_game` as you have, through cloning, already set up the project. Read through the rest of the instructions in this section of the tutorial, and then pause when you reach the start of the section entitled `"Processing a Guess"`. When you've gotten to this point in the tutorial, I want you to commit all the changes you made with the commit message `"Setting Up a New Project"`.

This is something you'll have to get used to for this semester. Many students are used to working on an assignment and then submitting it at the end. In this remote environment, I want more of a log to prove that the work you've done is your own. Therefore, I will require you to periodically commit your work by breaking an assignment into steps or sections.

For instance, in this assignment I want you to just follow along with the code as it's explained in the tutorial. When the tutorial demonstrates new code to you, I want you to modify your source to match. Then at the end of each section, I want you to commit your progress with the message being the title of the section.

Here are the sections you need to commit:

- Setting Up a New Project
- Processing a Guess
- Storing Values with Variables
- Handling Potential Failure with the Result Type
- Printing Values with println! Placeholders
- Using a Crate to Get More Functionality
- Updating a Crate to Get a New Version
- Generating a Random Number
- Comparing the Guess to the Secret Number
- Allowing Multiple Guesses with Looping
- Quitting After a Correct Guess
- Handling Invalid Input

In total you should have at least 12 commits to your repository. You can always have more, but I want you to have at least the above.

For the first couple assignments it will be okay if you get this wrong. You'll have a chance to get used to this process. For the next homework, the graders will start taking it more seriously and you will lose 1 letter grade if you forget to commit your work until the end. After the next assignment, work will not be accepted if there is no git history to prove the provenance of your work.

By the end of this assignment, you should have a working guessing game. For full credit, graders should be able to download or clone your repository and run the following.

```
cd guessing_game
cargo run
```

