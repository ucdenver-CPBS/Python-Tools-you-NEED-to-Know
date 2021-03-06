If you are going to use python, these tools will make your life much easier.

1. First, for beginners, definitely start with this tutorial. For more advanced users, take a look. There's probably at least a few techniques here you didn't know about. 
  -http://www.diveintopython3.net/index.html

2. List comprehensions. Ditch the for loops whenever possible and use these. They may seem cryptic at first, but they're worth learning for their speed and ease of writing.
  -Example: my_list = [1, 2, 3, 4]
            [x + 1 for x in my_list]
            output: [2, 3, 4, 5]
            

3. Pandas. This is package makes handling data intuitive and easy. You can slice, grab columns by name, etc. This will be familiar to those who use R.
  -Installation: pip install pandas OR conda install pandas

4. Anaconda. Why use Anaconda? It manages all of your python packages (which you should and will have a lot of). Managing packages means you can use it to check for updates so you won't miss bug fixes when they come out. It also allows you to create environments that contain everything that is needed to run your code so that other people can run it without issue.
  -Installation: https://conda.io/docs/user-guide/install/download.html

5. Multiprocessing. Large programs can take a long time to run. You can help speed it along by telling your python program how to run itselt more efficiently. A python package called multiprocessing makes this easy. You create a pool of processes and then set them running in batches. That way, your computer (or cluster)'s resources can be used to their maximum potential.
  -Here is the official tutorial: https://docs.python.org/3/library/multiprocessing.html
  -Another tutorial. Take note of the section that discusses using partial(). It is very handy. http://python.omics.wiki/multiprocessing_map/multiprocessing_partial_function_multiple_arguments
  

  
