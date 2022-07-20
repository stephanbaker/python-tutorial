This was written for someone under the assumption they are running a Windows system.

Here is a link to the latest python release at the time this was written.

https://www.python.org/downloads/release/python-3105/

Scroll to the bottom where you will Find a `Files` section. Downdload the recommended file using the `Windows installer (64-bit)` link.

Once the download has completed, run the executable, and select "Install Now". Once this has completed, you will have `IDLE` (Python's Integrated Development and Learning Environment) and `pip` (Python's package manager) installed.

You should have an application called `Command Prompt` listed in your start menu. Run it and a terminal window should open. This window allows access to a variety of system commands, some of which came with Windows by default, and others that are installed by the user (that's you!). Since we just installed Python, you should have the `py` command available to you. Type `py` in your command prompt and hit `Enter`. You should see information about your system and the current python installation, followed by another prompt for input (`>>>`).

Let's run our first line of python code. It's customary in most programming languages to write a Hello World program at first, so let's do that. Type the following and then press enter.

```python
print("Hello, world!")
```

If everything was done correctly, you should see a new line generated that simply says "Hello, world!". We just ran a small python program that prints a simple message on the command line.

Let's dig in to the Python documentation to understand what we did above. Reading documentation can seem daunting at first, but doing so is invaluable as you continue working in various programming langauges.

The `print` function is one of the built-in functions provided to you in the Python langauge. Here is the documentation for this and the other functions available to you.
https://docs.python.org/3/library/functions.html

Looking at the documentation for the print function, you will see the following. 
```python
print(*objects, sep=' ', end='\n', file=sys.stdout, flush=False)¶
```

This is known as  the "signature" of this function, and it describes what parameters the function expects to receive when called. In this case, you can pass in a collection of objects. There are some optional parameters (sep, end, file, flush) you can use to customize how `print()` will format the output and where it will be sent. Each of these parameters has a default value assigned, so if you don't explicitly tell print what to do, it will use those values. In this case, it will separate objects with a space, write the output to the standard console output (as oppposed to a file), and will not flush the stream when writing is completed. Don't worry about what flushing means for now.

Let's change our Hello World program to test this out. Let's tell python we want to print multiple strings of characters, separate them with a hyphen, and end the line with an exclamation point and a new-line character. Run the following command and then press `Enter`.
```python
print("Hello", "world", sep='-', end='!\n')
```

If everything was done correctly, you should see a new line generated that says "Hello-world!".

Now you know how to open the python interpreter, write a simple program using the built-in `print` function, and find the documentation for that function when you want to customize your output.

If you are done for now, you can type `quit()` and hit `Enter` to exit this interpeter.


The Python team provides an online tutorial for those interested in learning how to program using the language. You can find it here if you are interested.
https://docs.python.org/3.10/tutorial/index.html
