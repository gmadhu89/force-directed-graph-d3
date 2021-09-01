This network visualization identifies similarity between board games from a simplified available dataset (calculated based on categories and game mechanics). The goal of this was to experiment the force-directed visual styling of this data using D3.js.  

Force-directed layouts use simulations of physical forces to arrange the elemnts(nodes in this case) on the screen. This is implemented using d3.forcesmimulation() module.  

Input file: input.csv  
Code: index.html  

Execution Steps(to run in local):    
1) Copy the lib/ folder to your local.
2) Setup a local [http.server](https://ryanblunden.com/create-a-http-server-with-one-command-thanks-to-python-29fcfdcd240e)
3) Open graph.html after initiating http server to view the visualization.

Click here to access the [Interactive Visualization](https://gmadhu89.github.io/force-directed-graph-d3/)  
Single click on any node to move its position and pin to a specifc position.  
Double click on pinned node to release it.  

![Snapshot of Visualization](https://github.com/gmadhu89/force-directed-graph-d3/blob/main/force-graph.JPG?raw=true "Snapshot of Visualization")
