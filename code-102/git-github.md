### Things I've learned so far:
- [Github](https://github.com/holdermatthew5) is basically an entire code language turned into a social media platform.
- Github uses emojis :shushing_face:
  [Here's](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) a list of usable emojis!
Pressing enter doesn't actually start a new line if you don't start that line with code. It just adds a space between the start of that line and the end of the previous one.
- This ~ is apparently called a tilde, but don't ask me how to pronounce it lol.

- version control system (vcs)allows you to view and reverse changes as well as view who made the changes (by recording changes) in order to fix mistakes.
- central version control system (cvcs)records all changes across a whole team through one server and gives team leads a greater ability to assign revision priviliges.
- distributed version control (dvcs) allows clients to make mirrored copies of the code to prevent total loss of work in the event the single server goes down. with this system the lost code can easily be replaced by what is already saved to a different server.
- Git is a DVCS. When changes are saved with a `commit` it creates a snapshot of the changed file and saves a reference to it. If there's no change it saves a reference to the original file.
- Git works mostly from the computer you're working on because most of the information it needs is already there. This means if you're offline or on a vpn you can still work on the roject.
- git saves all changes, detects corruption in transit and protects snapshots from being lost. these saves can reside in 3 main states: modified (changed but not commited), staged (marked to be commited[saved to terminal but not to github])and commited (data securely stored in a local database[github in my case]).
