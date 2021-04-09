# Shiny Day ideas
Living document to organize ideas for an upcoming Shiny day at the Bank

### Date:
April 28 and 29
  
## Lightning talks
 Chair: Tony
 
 - Opening remarks - From prototype to production in minutes: RstudioConnect
 - Taka and Sasha - PTI for Madagascar 
 - TDB - Global institutional assessment
 - Rob Marty - Tanzania crash map (TBC)
 - Fabian Kreitzug - Strategy compass (Need to fix bugs)
 - Michael Wild - TBC (ideally sampling)
 - Rui and Carla - Working while female in Bolivia

## Workshops

Beginner - 
Intermediate - 
Advanced (Layout) -
Advanced (Production) - Tony

## Keynote: Shiny in production
Carson Sievert

# Random ideas

## Sharing apps and use cases
Having a space (Microsoft teams??) for Shiny developers to share their apps in production stage and link to code when openly available

## Session on non-Shiny/R tools

# Workshops content
## Shiny in production
### Is my Shiny app ready for production?
How do I know?
* Load-testing
How do I fix it?
* Profiling
### Performance
Rule #1: Move data processing out of your Shiny app
Rule #2: Use efficient file formats
  1. Small .csv
  2. Large .csv (Profile)
  3. .fst (benchmarck)
  4. Larger file (does not fit in memory)
  5. Arrow, partitionning + dplyr
Rule #3: Do heavy computations only once (caching)
### organization and Maintenance

# Resource and references
Following up with links to some of the things we talked about: 
* Runtime settings: https://docs.rstudio.com/connect/user/content-settings/#content-runtime
* Shiny async: https://rstudio.github.io/promises/articles/shiny.html
* shinyloadtest: https://rstudio.github.io/shinyloadtest/
* Shiny app performance: https://shiny.rstudio.com/articles/#performance 
