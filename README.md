# Bibliometric-with-R

The R programming language, with its powerful packages and libraries, is an excellent tool for conducting bibliometric analysis. One of the most popular R packages for bibliometric analysis is <b>bibliometrix</b>. It offers a comprehensive set of tools for importing data, analyzing publications, and building matrices for co-citation, coupling, collaboration, and co-word analysis. These matrices are crucial for performing network analysis and other data reduction techniques.

# Install the bibliometrix package from CRAN
From the RStudio console, type the code below:
``` r
install.packages("bibliometrix")
```

For more details, please refer to Figure 1.

![1](https://github.com/aprijunaidi/bibliometrix-with-R/assets/7279471/aef9653d-1290-4a0b-b021-7f1998c79570)

Figure 1. Install bibliometrix package.

### installation is complete
Figure 2 displays information confirming that the package installation is complete.
![2](https://github.com/aprijunaidi/bibliometrix-with-R/assets/7279471/8c70f2cc-027d-4547-bbf2-d96d06fb55d7)
Figure 2. Installation is complete.

# Load the bibliometrix library
After installing the bibliometrix package, please load the code corresponding to Figure 2.
``` r
library(bibliometrix)
```

When the library is loaded, the result resembles Figure 3.
![3](https://github.com/aprijunaidi/bibliometrix-with-R/assets/7279471/ce279e41-dc30-4614-b0fa-3719f6e83418)

Figure 3. Load the bibliometrix library

---

## Biblioshiny: A User-Friendly Interface for Bibliometric Analysis

**Biblioshiny** is an extension of the **bibliometrix** R package designed to simplify bibliometric analyses. It provides an intuitive web-based interface, making it accessible even to non-coders. Let's explore its key features:

### Functionality

1. **Data Importing**:
   - Import and convert data from various sources (e.g., Dimensions, PubMed, Scopus) into a data frame.
   - Collect data using APIs from these sources.

2. **Data Filtering**:
   - Filter data based on your research needs.

3. **Analytics and Plots**:
   - Generate visualizations for different metrics at four levels:
     - **Sources**
     - **Authors**
     - **Documents**
     - **Clustering by Coupling**

4. **Structures of Knowledge (K-structures)**:
   - Explore:
     - **Conceptual Structure**
     - **Intellectual Structure**
     - **Social Structure**

### Use Cases

- Researchers can:
  - Explore relationships between published articles, influential sources, authors, and affiliations.
  - Visualize research trends and network connections across different constituencies.

### Benefits

- **Non-Coders**: Biblioshiny empowers non-coders to conduct bibliometric analyses.
- **Comprehensive Analysis**: It facilitates in-depth exploration of science mapping data.

For more details, visit the [official Biblioshiny page](https://www.bibliometrix.org/home/index.php/layout/biblioshiny).

---

## Load biblioshiny extension 
To launch Biblioshiny in the R console, follow these steps:
on R studio console Type the following command

``` r
biblioshiny()
```
Press Enter to execute the command.


![4](https://github.com/aprijunaidi/bibliometrix-with-R/assets/7279471/970ccea7-a6ce-40cb-866c-309bf4b864a3)
Figure 3. Code for load the biblioshiny extension
