# Unbeatable-tic-tac-toe
Ai driven tic-tac-toe using Minimax  Algorithm in JS   ![Formula](https://www.gstatic.com/education/formulas2/355397047/en/minimax.svg)


Implementation :- http://mrsiddy.me/AI-Tic-Tac-Toe



![](D:\AI-Tic-Tac-Toe\Tic-tac-toe_AI\game.gif)

## Pseudo-code for MinMax Algorithm:

1. function minimax(node, depth, maximizingPlayer) is 
2. **if** depth ==0 or node is a terminal node then 
3. **return** **static** evaluation of node 
4.  
5. **if** MaximizingPlayer then   // for Maximizer Player 
6. maxEva= -infinity      
7.  **for** each child of node **do** 
8.  eva= minimax(child, depth-1, **false**) 
9. maxEva= max(maxEva,eva)    //gives Maximum of the values 
10. **return** maxEva 
11.  
12. **else**             // for Minimizer player 
13.  minEva= +infinity  
14.  **for** each child of node **do** 
15.  eva= minimax(child, depth-1, **true**) 
16.  minEva= min(minEva, eva)     //gives minimum of the values 
17.  **return** minEva 



![](D:\AI-Tic-Tac-Toe\Tic-tac-toe_AI\Game-tree-for-Tic-Tac-Toe-game-using-MiniMax-algorithm.png)
