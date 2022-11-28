# Bicycle-World
Transcript of newly learned Bash commands (pwd, ls, cd, mkdir, and touch) in action! 

Given directory:
```
bicycle-world-ii
|—— brands.txt
|—— freight/
|   |—— messenger/
|   |—— porteur/
|—— mountain/
|   |—— downhill/
|   |   |—— heavyweight/
|   |   |—— lightweight/
|   |—— hardtail/
|—— racing/
    |—— road/
    |—— track/
```

Transcript of work (following given steps):
```
$ pwd
/home/ccuser/workspace/bicycle-world-ii
$ ls
brands.txt  freight  mountain  racing
$ cd freight/
$ ls
messenger  porteur
$ cd porteur/
$ cd ../..
$ ls
brands.txt  freight  mountain  racing
$ cd mountain/downhill/
$ touch dirt.txt
$ touch mud.txt
$ ls
dirt.txt  heavyweight  lightweight  mud.txt
$ mkdir safety
$ cd ../..
$ ls
brands.txt  freight  mountain  racing
$ mkdir bmx
$ touch bmx/tricks.txt
$ ls
bmx  brands.txt  freight  mountain  racing
$ 
```

---------------------------------
Another similar project
--------------------------------
Daily Buzz

Transcript of Bash commands:
```
$ pwd
/home/ccuser/workspace/daily-buzz
$ ls
culture  health  national  technology
$ cd national/politics
$ ls
policy
$ mkdir elections
$ cd elections/
$ touch candidates.txt
$ touch issues.txt
$ cd ../../..
$ pwd
/home/ccuser/workspace/daily-buzz
$ mkdir business
$ cd business/
$ ls
$ mkdir startups
$ cd startups/
$ cd ..
$ mkdir startups/disruptors
$ touch startups/disruptors/tech.txt
$ touch startups/disruptors/design.txt
$ touch startups/disruptors/education.txt
$ cd ..
$ pwd
/home/ccuser/workspace/daily-buzz
$
```
