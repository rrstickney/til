# Sudo can make fun of you for mistyping your password

adding `Defaults   insults` to your sudoers file enables insults when a sudoer password is mistyped.

Is this helpful? No.<br>
Is this fun? It sure is.

Here's a sample of what it will throw at you.

```rrstickney@ice-station-zebra:~# sudo touch foo
[sudo] password for rrstickney:
You'll starve!
[sudo] password for rrstickney:
The more you drive -- the dumber you get.
[sudo] password for rrstickney:
You type like i drive.
```

Sudoers insult game seems kinda weak. The insults are stored in the sudo binary so updating them requires recompiling. A future TIL post should include "hilarious insults" and "recompiling the sudoers binary from source".
