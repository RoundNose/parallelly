# CRAN submission parallelly 1.22.0

on 2020-12-12

I've verified this submission have no negative impact on any of the 147 first and second generation of reverse dependencies (139 from CRAN + 8 from Bioconductor).

Thank you


## Notes not sent to CRAN

### R CMD check validation

The package has been verified using `R CMD check --as-cran` on:

| R version | GitHub Actions | R-hub | win-builder |
| --------- | -------------- | ----- | ----------- |
| 3.3.x     | L              |       |             |
| 3.4.x     | L              |       |             |
| 3.5.x     | L              |       |             |
| 3.6.x     | L              | L     |             |
| 4.0.x     | L M W          |     S | W           |
| devel     |   M W          | L W   | W           |

Legend: OS: L = Linux S = Solaris M = macOS W = Windows
