# DS-and-ALGO
Data structures and Algorithms with JavaScript


## Big O Notation
-Used to measure efficiency of code
-function of executed operation count
-Can be of Time complexity or Space complexity

#### Time Complexity:
- measures how much time needed to execute.
- Simple operations happen instantaneously almost
- If there is no loop only C number of operations then O(1)
- If for n amount of entry n or an+c amount of operations has to happen then O(n)
- If n things happen n times or Cn times hence number of operations become Cn^2 + Dn + E then O(n^2) as for bigger inputs others are insignificant.
- If for each step number of operations becomd half i.e. divided by 2 the it's complexity is O(log(n))
- if for n input n lines of code happen and for each line of code half the previous line of code happen then complexity is O(nlogn)

#### Space Complexity
- measures how much space it takes
- assigning or reassigning values to a variable takes constant space
- longer strings means longer space
- longer the array more the spacw
- if for n input n elements in an array addad it would be O(n)
- similar goes of O(n^2) or others
