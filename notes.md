neat algo works on the following

1. INPUT -->bird_y , top_pipe , bottom_pipe or only one of them either or you can implement
2. OUTPUT --> jump ? yes or no
3. ACTIVATION FUNCTION --> this is to set the thresh for when to jump , for this we use tanh . we can also use sigmoid or other such funciton
4. POPULATION SIZE --> 100 (number of birds per generation)
5. FITNESS FUNCTION --> bird with highest score or the bird that went front the most number of frames
6. MAX GENERATIONS --> max no of gens before you decide its gotten messed up adn restart from gen 0 as things can sometimes go wrong and unexpectedly

#it is basically like ai using natural selection and breeding succesive generations based on fitness function