# RPROFILE: controls hidden R variables
# michael decrescenzo

# For global profile: set non-essential functionality only.

# Project-specific .Rprofile files may alter functionality,
#   but those should be sourced by project scripts
#   to ensure dependencies.


# ---- Prompt -----------------------

options(prompt = "R > ",
        continue = "... ")


# ---- Rstudio default CRAN repo -----------------------

repo_urls <- getOption('repos')
repo_urls['CRAN'] <- 'https://cran.rstudio.com/'
options(repos = repo_urls)

