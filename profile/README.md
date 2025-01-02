# Various R Packages

Welcome to [@coatless](https://github.com/coatless) and contributors' collection of R packages! 
This GitHub organization serves as a central repository for R packages that provide statistical computing tools, data analysis utilities, and enhanced R programming capabilities.

Each R package is maintained in its own repository, making it easy to find, use, and contribute to specific projects.

## Installation

Most packages can be installed from either CRAN (Stable) or GitHub (Developmental).

For CRAN released packages, you can install them using: 

```r
install.packages("package_name")
```

For developmental and cutting-edge features, please install the package using:

```r
# install.packages("remotes")
remotes::install_github("coatless-rpkg/package_name")
```

## Getting Started

To use any of the packages:

1. Install the package using the instructions above
2. Load the package in R with `library(package_name)`
3. Access package documentation with `?function_name` or `help(package = "package_name")`
4. View package vignettes with `browseVignettes("package_name")`

## Package Structure

Our packages typically follow this structure:

```sh
package-name/
├── R/
│   ├── package-name.R
│   └── functions.R
├── tests/
│   ├── testthat.R
│   └── testthat/
├── src/
│   ├── Makevars{.win}
│   └── compiled-code.cpp
├── man/
├── vignettes/
├── DESCRIPTION
├── NAMESPACE
├── NEWS.md
├── LICENSE
└── README.md
```

## Requirements

We assume at least the following is available:

- R (>= 4.2.0)
- RStudio (recommended), Positron, or VS Code
- Additional dependencies specified in individual repository DESCRIPTION files

## License

Unless otherwise specified, all packages in this organization are released under the AGPL-3 License. See individual repositories for specific license information.

## Contact

For questions, suggestions, or issues:

- Open an issue in the relevant repository
- Contact [@coatless](https://github.com/coatless) directly through [social media](https://thecoatlessprofessor.com/)

## Resources

- [Writing R Extensions](https://cran.r-project.org/doc/manuals/r-release/R-exts.html)
- [roxygen2 documentation](https://roxygen2.r-lib.org/)
- [R Packages (2e)](https://r-pkgs.org/)
- [Advanced R](https://adv-r.hadley.nz/)

## Status

Check individual package repositories for R CMD Check results, CRAN status badges, and latest release information.

## Acknowledgments

We thank all contributors who have helped improve and maintain these packages. Special thanks to the R community for their continued support and inspiration.

---

*This organization is maintained by [@coatless](https://github.com/coatless). For more information about other projects, visit [thecoatlessprofessor.com](https://thecoatlessprofessor.com).*
