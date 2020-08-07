# Julia fractals demo - Avenga Labs falls in love with Julia

## What is it

It's a demo showing Julia language capabilities by [Avenga](https://avenga.com) Labs.

## How to build

1. Make sure you have **julia** installed.

```brew cask install julia```

2. Start Julia and install required dependencies
```julia
  julia> using Pkg
    
  julia> Pkg.add("IJulia")
  julia> Pkg.add("Plots")
  julia> Pkg.add("Interact")
  ```

## How to run locally

1. Open **julia**

`julia`

2. Start notebook

```julia
  using IJulia
  notebook()
```

3. Navigate local filesystem and open **AvengaLovesJulia-fractals.ipynb**

4. For **Plots** libary overview please open **Plots overview.ipynb**

## Contact

[Jacek Chmiel](jacek.chmiel@avenga.com)

Follow us:

[Avenga Magazine](https://avenga.com/magazine)

[Medium](https://medium.com/avenga)

[Twitter](https://twitter.com/avenga_global)

[LinkedIN](https://www.linkedin.com/company/avenga/)
