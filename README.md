# IIITH_DSA_T2_Y1_2021_ProjectRepo_Team36_MiniProject1


<h1><b>ReadMe File. </b></h1>


<br>

We add data for the Program here. <br>


There are 3 files 

main.c
treesl.c
treesh.c

//Describe Return type, argument and what a function broadly does. For all functions
// Digrammatic explaination of Heap and related functions
// take testcase of 10 and do step by step explaination of Algo of BFS. 



<h1>Work Allocation</h1>
<br><br>
<table>
  <tr>
    <th>Serial No</th>
    <th>Team Member</th>
    <th>Work Allocated</th>  
    <th>Github Profile</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Vivek Mathur</td>
    <td>Depth First Search(Comparator), Code merging, Data Analysis lead -<br> Time Complexity analysis and Graph Plotting</td>
    <td> <a href="https://github.com/Grimoors">LINK</a></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Karthick Ashwath</td>
    <td>Existed.</td>
    <td> <a href="https://github.com/KarthickAshwath">LINK</a></td>
  </tr>
  <tr>
    <td>3</td>
    <td>Abhishek Sharma</td>
    <td>Breadth First Search Algorithm, Greedy Algorithm (comparators) , <br>Implemented Heap functions, Code merging. Coding Lead</td>
    <td> <a href="https://github.com/Abhi7410">LINK</a></td>
  </tr>
  <tr>
    <td>4</td>
    <td>Amey Kunte</td>
    <td>Documentation ( Description of functions and Stepwise explaination), Moral Support</td>
    <td> <a href="https://github.com/ameykun">LINK</a></td>
    
  </tr>
  <tr>
    <td>5</td>
    <td>Keerthana K.</td>
    <td>Algorithm Development</td>
    <td> <a href="https://github.com/keerthana747">LINK</a></td>
  </tr>

</table>
<br><br>

<h1>Timeline</h1>


<h1>Documentation</h1>


<h1>LOG-></h1>

XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

<h2>Entry 1 ->   --> Entry by Vivek Mathur</h2>

<b>Actions Taken</b>

<i>(in Individual folder)</i><br>
Added Basic files, Restructured into Standard Form, Added a main.c and A Way to input into Tree.<br>
Added the find Parent and insert function, It is currently recursive, thinking of ways to make it iterative.<br>
<br>
<br>
Planning to add a print function for to test the Input function.

<b>Documentation :__</b>


The Data Structure that WE are Using initally --> As of 26/04/12<br>
______________________________________________________________________________________________________________________________________

                                       Data (Graph) Strcuture
                                        
                                        Tree - General, 
                                        
______________________________________________________________________________________________________________________________________

                                        node Root;
______________________________________________________________________________________________________________________________________                                        
                                        
                                        
                                        --------
                                       |  Node  | <---- Root Node
                                        --------
                                            |
                                            |
            ________________________________|____________________________    .........___________.............. 10000 terms
           |                                   |                                          |
           |                                   |                                          |
         
         Pointer                            Pointer                                     Pointer
      Root->children[0]                 Root->children[1]                           Root->children[i]
           
           
        --------                            --------  
       |  Node  | <----Child Node [0]      |  Node  | <----Child Node [1]     .......... NULL   .......... 
        --------                            --------
        
            |                                  |
            |                                  |
            |                                  |
           ...                                ...
           
           
______________________________________________________________________________________________________________________________________           
        
   
   There are other Stubs associated with each root : Namely :-<br>

    
    
    int depth, seen_time, number_of_children;
    
    int state_number;     //  "NAME" of a node<br>
    int value;            //    Data of graph, Used by comparator<br>
    int parent;           //    Holds the name of the "Parent"<br>
    
    // We shall remove the 'i' in the main .c and node.h soon.
    
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX 
        
        
