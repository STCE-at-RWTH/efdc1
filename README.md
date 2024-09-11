# STCE @ EFDC 2024

This repository contains the abstract and slides for STCE's submission to EFDC2024, as well as some interactive materials.

## Using the Interactive Materials

`notebooks/` contains some [Pluto.jl](https://plutojl.org/) notebooks that can be downloaded and experimented with. `Pluto.jl` is a package for the Julia programming language. Simply install Julia language from [their website](https://julialang.org/downloads/), and start a REPL by running `julia` in your terminal.

From there, you need to make the package manager aware of [STCE's package registry](https://github.com/STCE-at-RWTH/STCEJuliaRegistry). We maintain our own registry to avoid cluttering the general public registry with prototype code or abandonware. Type `]` to switch to package mode, and add the registry:

```julia
pkg> registry add https://github.com/STCE-at-RWTH/STCEJuliaRegistry
```

You also will want to get the latest version of Pluto:

```julia
pkg> add Pluto
```

Backspace out of the package manager and start Pluto, which should open a browser tab that you can use to open the notebook files:

```julia
julia> using Pluto
julia> Pluto.run()
```

## Contact Us

Feel free to send us an email at [`info@stce.rwth-aachen.de`](mailto:info@stce.rwth-aachen.de) if you have questions about what we do! If you have questions or comments about this work, send me an email at [`fleming@stce.rwth-aachen.de`](mailto:fleming@stce.rwth-aachen.de) instead.
