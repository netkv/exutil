# fun
define functions, should be in $PATH

In execline script:

	fun function-name { funtion's prog1... } prog2...

	- fun reads prog1 in block, then reads prog2 and replaces all words same as function-name with function's prog1

	- better use some non-common words, because `fun` doesnt consider what should and what should be executed, it replaces all mentions of function-name

	- can be quite slow for bigger scripts, but i think it should be possible to optimize

	- wip but it somehow works
