# ChromaScope
Pseudo library for python, provides custom colored formatting in a convenient way through the use of ANSI codes.

### Why?
Basically, i was tired of using Blessings and related libs, nothing personal towards the authors of those libs. However i wanted something a bit simpler and a bit more portable. So i decided to write this. I wrote it so that it can easily be expanded upon. And since it's more of a pseudo lib, you can just copy and paste this script into a project where you wish to use colored text and symbols for your terminal output.

Whether you import the script as a library or not, it is very easy to use.

```
# As library
from chroma import text

print text('green',"This line will not be printed green")
```
If you simply copy the script to your main python file all you need to do is invoke the function with 
`print text('color','message')`

### Note

Should you have any questions with regards to the contents of this repo please feel free to open a ticket.


