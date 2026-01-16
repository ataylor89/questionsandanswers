# qa2

## Dialogue

Q: I know that you use vi. You said, "I use vi and that's all I use." I'm curious, how can I get started with vi?

A: Honestly, vi is my favorite text editor. I really like vi. I'd be happy to give a brief tutorial on vi.

Q: Thanks! Let's get started.

A: So I should start by saying that I use a MacBook. I'm running MacOS Sequoia on an Apple M1 chip.

Q: What operating systems have vi?

A: I think that MacOS, Linux, and Unix all have vi.

Q: Okay.

A: When I log into my computer, I open Terminal. Terminal is stored in my Dock, at the bottom of my screen.

Q: What if Terminal isn't in your Dock?

A: You can use the Finder application to open Terminal. I think that Finder might be in your Dock. I go to Finder->Applications->Utilities and then I see Terminal in the list. I double click on Terminal (from the Finder window) and that opens Terminal.

Q: How can I add Terminal to my Dock?

A: Starting Terminal is the first order of business. After you have started Terminal, you should see it appear in your Dock. There is actually a separator in my Dock that separates permanent docked applications from temporary docked applications. If Terminal isn't permanently added to your Dock, and it's currently running, then it should appear on the right hand side as one of the temporary docked applications. You can right-click on it, select Options, and then check "Keep in Dock". This will keep it in your dock permanently, unless you remove it from the Dock.

Q: Thanks! I just did that. I tested it out by opening and closing it, and I think it's permanently added to my Dock.

A: Great!

Q: I just opened Terminal and I see that it appeared on my screen. Now what should I do?

A: Okay, now let's proceed with the next step. We have opened Terminal. I think it helps to maximize Terminal so that it fills up the screen.

Q: I maximized it. What's next?

A: You should see the Terminal menus appear at the top of your screen, in your menu bar.

Q: There's an Apple logo at the top left corner of my screen. And next to that there is a Terminal menu.

A: Great. You can click on the Terminal menu, which opens a drop down list of submenus (also called menu items). Then, click on Settings.

Q: I clicked on Settings. Now what?

A: You can choose a theme that appeals to you. You can create a profile, with a specified theme, and have it open that profile in every Terminal window.

Q: Do you have a theme?

A: Yes, I have it set to a color theme that I like. There are many appealing color themes to choose from.

Q: Okay, I chose a theme. What's next?

A: So we have set up Terminal. We stored it in our Dock for easy access. We chose a color theme. Now let's run a command.

Q: Okay.

A: In your Terminal window, there's a command prompt. My prompt looks like [username]@[computername] ~ %.

Q: My prompt is similar.

A: Type the one-word command "date" and then press enter or return.

Q: I did. It gives me the date and time in my time zone.

A: Great! That's an example of a command.

A: Terminal has an interpreter (usually Bash or Zsh) which interprets your commands and prints an output.

Q: Is vi a command?

A: Yes, vi is one of the many commands you can choose from. I think that the two commands "vi" and "vim" are interchangeable (at least, on MacOS). When I run the command "vi", it actually brings up a screen that says "VIM - Vi IMproved".

Q: Okay. I'm going to try it out. I'm going to try running the command "vi". Is there anything I should do beforehand?

A: Let's create a new folder. Type the command "mkdir ~/vi_tutorial".

Q: I did.

A: Now navigate to that folder. Type the command "cd ~/vi_tutorial".

Q: I did. What does the ~ character mean?

A: The ~ character is a shorthand for your user directory, which is located at /Users/[username] on MacOS.

Q: Okay.

A: So we're in the folder ~/vi_tutorial. Now try running the command "vi".

Q: I just did. It says VIM - Vi IMproved.

A: Good. Good.

Q: Now what do I do?

A: I think we need to take a break, and resume in a third Q&A.

Q: Okay.

A: In our next Q&A, we'll talk about the two different modes that can be used in vi: Insert Mode and Command Mode.

** Q is eager to learn about Insert Mode and Command Mode, and asks if they can start the third Q&A right away. A agrees. They begin.

Q: What is Insert Mode?

A: You use Insert Mode when you want to insert text and write source code.

Q: What is Command Mode?

A: You use Command Mode when you want to navigate a file, edit a file, copy and paste, delete lines of text, search for a word, search and replace, open a new tab, switch between tabs, undo a change, redo a change, save to a file, or exit vi.

Q: That's a long list!

A: Yes, I wanted to include a lot of important features. Command Mode has many uses.

Q: So I use Insert Mode to write a file and write source code? I use Command Mode to execute commands, copy and paste, et cetera?

A: Exactly.

Q: I'm staring at a screen that says "VIM - Vi IMproved". What mode am I in?

A: When you first open vi, you're in command mode.

Q: How do I get to Insert Mode?

A: You can get to Insert Mode by typing "a" or "i" on your keyboard.

Q: I did that, and now it says "INSERT" in the bottom left corner.

A: Nice!

Q: Now I can enter text.

Q: How do I create a new line?

A: You can create a new line by typing the Enter key or the Return key. On my keyboard it's Return.

Q: Great. That works.

A: Now let's run a command. Type the key sequence control+c to get to command mode.

Q: So I hold the control key and press the c key, while holding the control key?

A: Exactly.

Q: I just did. The "INSERT" message at the bottom left corner disappeared.

A: Good. Now you're in command mode.

Q: What command should I run?

A: Type the command ":set nu", without the quotes. It starts with a colon.

Q: I did. The editor has line numbering now.

A: Exactly. The ":set nu" command enables line numbering.

Q: How do I save my text to file?

A: Type the command ":w filename.txt" without the quotes. You can replace the name filename.txt with whatever filename you want.

Q: I just did. I saved my text to file. Now how do I see the file?

A: Let's exit vi. Type the command ":q" (without the quotes) to exit vi. If you're not in command mode, you can get back to command mode with the sequence control+c. You hold the control key and then press the c key. This should put you back in command mode.

Q: That's how I return to command mode. How do I return to insert mode?

A: You can return to insert mode by typing the "a" key or the "i" key on your keyboard.

Q: I see.

A: On some computers, you can get to command mode by pressing the escape key. I, personally, use the sequence control+c.

Q: That makes sense.

A: Were you able to run the ":q" command?

Q: I'll do that.

Q: Okay, it worked. I see the command prompt again.

A: Now type the command "ls". This gives you a listing of the current directory.

Q: Okay, I did. I see the file I created.

A: Great!

Q: How do I know it has the right contents?

A: Type the command "cat filename.txt", without quotes, and replace filename.txt with the name of your file.

Q: Okay, I did that. I see the text I entered. It looks correct.

A: Awesome.

Q: I just created a file in vi.

A: It's time to celebrate.

Q: It's time to celebrate.

A: It takes a while to get the hang of vi, but after some time, it becomes second nature.

Q: Is it second nature to you?

A: It is. But if I ever took a six-month break from vi, I would probably forget a lot of things. The upside is that... if you learn it once... it's a lot easier to learn in the future. You end up memorizing certain key sequences. If you ever forget a key sequence, you can look it up.

Q: That makes sense.

Q: What are some key sequences that you can think of off the top of your head?

A: In command mode, the key sequence "gg" skips to the top of the file. The key sequence shift+g skips to the bottom of the file.

Q: Cool.

A: The key sequence shift+6 (the caret symbol) skips to the beginning of a line. The key sequence shift+4 (the dollar symbol) skips to the end of a line.

Q: I see. There are a lot of key sequences that I have to learn.

A: There are many useful key sequences.

Q: How do I search and replace?

A: In command mode, you can type ":%s/hello/world/g" to replace all occurrences of "hello" in the file with "world".

A: It will work if you have any occurrences of the word "hello" in your file.

Q: Okay, I'll try that.

Q: How do I open my file in vi?

A: Type "vi filename.txt", without quotes, in your Terminal session, and replace filename.txt with the name of your file.

A: That will open your file in vi.

Q: Okay, I did that. It shows the name of my file in the bottom left corner of the screen. Am I in command mode?

A: vi always starts in command mode. You can type the "a" key or the "i" key to enter insert mode.

Q: I did.

A: Now add the word "hello" to your file, in one or more places.

Q: I did.

A: Now type control+c to enter command mode (alternatively, you can type the escape key).

Q: I did.

A: Now type the command ":%s/hello/world/g", without the quotes, in command mode, to replace all occurrences of "hello" with "world".

Q: I did. It worked.

A: Great!

Q: I think that's enough for one tutorial.

A: I think so too.

Q: How do I save my file?

A: Type the command ":w", without the quotes, in command mode.

Q: I did.

A: You can also type the command ":wq", without the quotes, to save and quit.

Q: I just did. I see the command prompt once again.

A: Now type "cat filename.txt" to view the contents of your file. Replace filename.txt with the name of your file.

Q: I did. I see the contents of my file. It looks correct. It replaced "hello" with "world".

A: Great!

Q: Okay, I think we're done for now. This is a lot to learn in one tutorial.

A: It is.

Q: I have Terminal in my Dock. I have vi at the power of my fingertips. I'm excited for the next Q&A.

A: I am too.

Q: It's late, and now I want to take a break. I might listen to some music or watch TV. I might cook some food and have a meal.

A: Have fun.

Q: I wish you the best.

A: You too.

Q: Talk to you later.

A: Adios.

## Afterword

That concludes our first tutorial on vi

There might be more tutorials, on vi, in the future

You might notice that, at one point in the dialogue, I say, "I think we need to take a break, and resume in a third Q&A"

I ended up running over, and explaining the difference between Insert Mode and Command Mode

One thing led to another, and I kept on finding more and more things that I wanted to talk about

There is more to say about vi... there is a lot more material to cover... but I'm glad we discussed Insert Mode and Command Mode

Now, I'm going to take a break from writing

I enjoyed writing this document

Vi is my favorite text editor, and it's really fun to talk about vi

I hope you found this document instructive and engaging

Thanks for reading,  
Andrew
