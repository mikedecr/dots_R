# RPROFILE: controls hidden R variables
# michael decrescenzo

# For global profile: 
# set non-essential functionality only

# For project profiles: 
# profiles may alter functionality 
# but they MUST be bundled with project repo
# source ~/.rprofile


# ---- Prompt -----------------------

options(prompt = "R > ", 
        continue = "... ")


# ---- Rstudio defualt CRAN repo -----------------------

repo_urls <- getOption('repos')
repo_urls['CRAN'] <- 'https://cran.rstudio.com/'
options(repos = repo_urls)


# --- Colored terminal output -----------------------

# we used to hard-code colors in here.
# but we want to do that, 
# it should be a modular tool w/r/t terminal theme colors
