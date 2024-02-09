# Hello, World!

Let's kickstart your journey with `Falgun` by writing a simple program. As per the convention when diving into a new language, we'll create a program that displays `Hello, world!` on the screen. Let's get started!

### Setting Up the Project Directory

Launch your terminal and execute the following commands. These will create a main directory for your projects, and within it, a specific directory for the `Hello, world!` project.

```bash
$ mkdir ~/Code/hello-world
$ cd ~/Code/hello-world
```

### Writing and Running a Falgun Program

Next up, create a new file and name it `main.fg`. Remember, Falgun files always end with .fg. And if your filename has more than one word, just use a dash to separate them, like `hello-world.fg`.

Now open the main.fg file you just created and enter the code.

```rust
fn main() :void {
    println("Hello, world!");
}
```

Save the file and go back to your terminal window in the `~/Code/hello-world` directory and enter the following commands to compile and run the file:

```
$ fgx main.fg

Hello, world!
```

No matter what operating system you're using, you should see the message Hello, world! pop up in your terminal.

If you do see Hello, world!, then well done! You've just written your first Falgun program. You're now officially a Falgun programmer—welcome aboard!



