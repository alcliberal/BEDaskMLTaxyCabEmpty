# Functional Programming

## Functional Programming for Distributed Data

[Link to slides](lectures/2_2_functional_programming.html)

<iframe
  src="lectures/2_2_functional_programming.html"
  style="width:100%; height:600px;"
></iframe>


## Introduction to Julia

As the first exercise, you'll need to install Julia and IJulia locally or make a working Julia Colab Notebook. While Colab is sufficient for today's exercises, it is recommended to make a local installation:

[Julia download](https://julialang.org/downloads/)
[Julia kernel for Jupyter](https://github.com/JuliaLang/IJulia.jl)

Here is a [Colab template](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_Colab_Notebook_Template.ipynb) from [this Github repository](https://github.com/ageron/julia_notebooks) which will install the Julia kernel for a single Colab instance.

Once you have a Julia Jupyter kernel, follow this **Julia for Pythonistas** notebook.

[Github](https://github.com/ageron/julia_notebooks/blob/master/Julia_for_Pythonistas.ipynb)
[Colab](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_for_Pythonistas.ipynb)

## Functional Programming in Julia

Julia documentation explaining:

+ [Functions](https://docs.julialang.org/en/v1/manual/functions/), showing that they are first-class
+ [the `map` function](https://docs.julialang.org/en/v1/base/collections/#Base.map) which is a higher-order function
+ [distributed computing](https://docs.julialang.org/en/v1/manual/distributed-computing/) allowing for transfer of functions between threads or workers

## Distributed Data in Julia

Julia's base language supports distributed calculation but there are a few packages which facilitate data processing tasks over distributed data: 

+ [DistributedArrays](https://github.com/JuliaParallel/DistributedArrays.jl) - A general Array type which can be distributed over multiple workers.
+ [JuliaDB](https://juliadb.org/) - A data structuring package which automatically handles distributed data storage and computation
+ [Spark.jl](https://github.com/dfdx/Spark.jl) - A Julia interface to Apache Spark. [Related blog post](https://juliacomputing.com/blog/2020/06/julia-spark/).
