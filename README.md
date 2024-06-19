# Abstract

This thesis covers a novel proof connecting the comparability graphs of posets and transitive graphs. I define transitive graphs as graphs G that have a labeling such that a non-attacking rook placement directly corresponds to the partition of G’s vertices into non-adjacent cliques, i.e. a set of proper colorings of the vertices.
The proven theorem states that the class of comparability graphs is exactly the class of transitive graphs. In applications, the rook vector of a board can be directly used to find the chromatic polynomial of the board’s corresponding comparability graph.
I also observe and define ”bi-relevant chain labeling”, which is a labeling of complementary comparability graphs such that their combined partial orders forms a coherent linear order. Further study is needed to explore how theories for rooks, graphs, chromatic polynomials and posets meet.
Chapters 1-3 provide the necessary background, and Chapters 4-5 contain the meat of this work.

[See the full Thesis in a PDF viewer.](https://annachrome.github.io/Math_Thesis.pdf)

# Key Figures
### A Toy Example: Graph Proper Coloring
<p align="center">
  <img width="838" alt="Screenshot 2024-06-19 at 12 27 07 PM" src="https://github.com/annachrome/annachrome.github.io/assets/84694222/20e2d539-79e8-4da8-b2b3-7241eac40f49">
  
  
  <img width="834" alt="Screenshot 2024-06-19 at 12 27 14 PM" src="https://github.com/annachrome/annachrome.github.io/assets/84694222/2e61b2ca-6239-451f-b8c4-831fba683a26">
</p>

<p align="center">

<img width="990" alt="Screenshot 2024-06-19 at 1 26 47 PM" src="https://github.com/annachrome/annachrome.github.io/assets/84694222/9541c6d9-7abd-431e-9567-8cb52bcb2356">

<img width="849" alt="Screenshot 2024-06-19 at 12 41 46 PM" src="https://github.com/annachrome/annachrome.github.io/assets/84694222/2c799bd6-01c5-43be-9f21-ae564251f9e5">

</p>


### Introducing the Game of Non-Attacking Rooks
<p align="center">
  
  <img width="700" alt="Screenshot 2023-12-15 at 11 54 31 AM" src="https://github.com/annachrome/Math_Thesis/assets/84694222/7deb5764-4ae6-41bf-8312-92abdae276c1">
</p>


### Duality: Translating between Proper Graph Coloring and Non-Attacking Rooks
<p align="center">  
<img width="696" alt="Screenshot 2024-06-19 at 12 42 20 PM" src="https://github.com/annachrome/annachrome.github.io/assets/84694222/b4d978d4-ca49-49a2-b672-c6137f96d3f2">
<img width="730" alt="Screenshot 2024-06-19 at 12 42 39 PM" src="https://github.com/annachrome/annachrome.github.io/assets/84694222/da2172ca-b2b1-4d4e-9821-0ab87de36fa6">
<img width="820" alt="Screenshot 2024-06-19 at 12 44 01 PM" src="https://github.com/annachrome/annachrome.github.io/assets/84694222/2ddd806b-0f68-4ede-8492-d4e63e144f17">

</p>



<p align="center"> 
  <img width="700" alt="Screenshot 2023-12-15 at 11 53 45 AM" src="https://github.com/annachrome/Math_Thesis/assets/84694222/bc28d674-7370-45d1-88ee-1c4e2c6c7eb1">
  
  
  <img width="720" alt="Screenshot 2023-12-15 at 11 54 03 AM" src="https://github.com/annachrome/Math_Thesis/assets/84694222/8b354c43-21ee-486e-a022-aca2e0af49c6">
  

</p>


### Labeling Graph Vertices
To see if a graph fulfills the duality above, we need to see if we can find a "chain labeling" of its vertices. In the thesis, **I prove that graphs satisfying this duality are exactly the set of comparability graphs**.
Comparability graphs are representations of posets (partially ordered sets), and partial orders satisfy the transitive relation. 
Hence the chain labeling essentially requires the vertices to be ordered such that they fulfill transitivity.

<p align="center">
  <img width="718" alt="Screenshot 2023-12-15 at 11 57 03 AM" src="https://github.com/annachrome/Math_Thesis/assets/84694222/a8773516-3fc0-44cf-9369-19a8ea2548ef">
  <img width="713" alt="Screenshot 2023-12-15 at 11 56 22 AM" src="https://github.com/annachrome/Math_Thesis/assets/84694222/79f059c2-d427-4bac-a0fe-5c5a5a157691">
  
  
  <img width="719" alt="Screenshot 2023-12-15 at 11 56 17 AM" src="https://github.com/annachrome/Math_Thesis/assets/84694222/ef138d55-49c3-488c-b85f-d58c408c795d">
  
  
  <img width="717" alt="Screenshot 2023-12-15 at 11 56 31 AM" src="https://github.com/annachrome/Math_Thesis/assets/84694222/dc3e6424-c535-4ed3-a2c8-69662909bee2">
</p>


