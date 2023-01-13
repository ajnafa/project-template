# Set Project Options
options(
  digits = 6, # Significant figures output
  mc.cores = parallel::detectCores(logical = FALSE), # Multicore processing
  scipen = 999, # Disable scientific notation
  repos = getOption("repos")["CRAN"],
  brms.backend = "cmdstanr",
  knitr.kable.NA = ''
)

# Load the helper functions on project start
.helpers <- lapply(
  list.files(
    path = "functions/", 
    pattern = ".*.R", 
    full.names = TRUE
    ), source
  )

# Base directory to write models to
models_dir <- "output/fits/models/"

# Base directory for the predictions/estimates
preds_dir <- "output/predictions/"

# Base Directory for the stan files
stan_dir <- "output/fits/stan-code/"

# Base Directory for the model diagnostics
diags_dir <- "output/diagnostics/"

# Base Directory for tables
tables_dir <- "output/tables/"

# Base Directory for standalone figures
figs_dir <- "output/figures/"

