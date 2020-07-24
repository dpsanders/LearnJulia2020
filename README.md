# Learn Julia via epidemic modelling

## Workshop at JuliaCon 2020

These are materials for the live workshop "Learn Julia via epidemic modelling" at JuliaCon 2020, 
which will take place on Friday 24 July, 2020 online.
For access, please register for a free ticket at https://juliacon.org/2020


## Setup

- Install the latest release (1.4.2) of Julia from [here](https://julialang.org/downloads/)

- Run Julia. At the Julia prompt, add the packages we will need as follows (copy and paste):

    julia> using Pkg
    
    julia> Pkg.add("IJulia")
    julia> Pkg.add("Plots")
    julia> Pkg.add("Interact")
    
- Once those packages have finished installing (which will install a collection of other packages that these depend on), type

    julia> using IJulia
    julia> notebook()

  This should launch the [Jupyter notebook](https://jupyter.org) in your browser; this is a web application that provides a computational notegbook interface.
  
- Copy the notebook files (ending in `.ipynb`) from this repository to your computer by `git clone`-ing the repository or downloading the Zip file
(hit the green button which says `Code`).


- Navigate inside the file browser in the Jupyter notebook to the place on your computer where the files you just downloaded are. Load notebook number 1!
