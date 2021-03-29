# Shiny Day ideas
Living document to organize ideas for an upcoming Shiny day at the Bank

### Date:
February 2021 (as part of data day)
  
## For general staff/TTLs
Showcase existing uses of shiny within the Bank and how projects can use this tool. 
- Possibly a ligthning talks format
- Preferrable to have TTLs/users presenting, and not only the developers.

### Possible topics
   - M&E (DIME has a couple of examples, IFC used to have quite a few)
   - Allow clients to interact with data (DIME has a few examples)
   - Sampling (Michael Wild)
   - Share information within teams (DIME has a couple of examples)
   - Creating a live COVID19 dashboard (Div?)
   - Mapping app in FCV country context (Fabian)
   - Helping allocate Bank resources in Madagascar (Taka & Sasha)
   - From prototype to production in minutes: RstudioConnect (Tony)
   - Police traffic reports (Rob)

## For R users
Sequential series of Shiny development workshop building a client-focused use case based on Bank data

### Led by us
* Beginners: very basic
* Intermediate: adding some functionalities
* Advanced: customize layout

### Led by RStudio
* Shiny in production (How to structure a Shiny app that will hold the test of time - golem framework)  
  - Analytics in RstudioConnect: Number of views, unique visits, locations, etc.
  - Best Shiny debugging practices
  - best practice to optimize dashboard and make them faster
  - Shiny application examples in developing countries and other international organizations
  

# Random ideas

## Sharing apps and use cases
Having a space (Microsoft teams??) for Shiny developers to share their apps in production stage and link to code when openly available

## Session on non-Shiny/R tools

# To discuss with RStudio
- [ ] Can we use the material available in https://shiny.rstudio.com/tutorial/?
  - If we can, I think the sessions led by us can be basically a walk-through the materials, with some instructors online to answer questions and help people. This seems easy to scale up depending on the number of people registered.
  - Brian says: "we're happy for you to use the materials on shiny.rstudio.com with the request to please not copy the materials."
  - The presentations are published under a CC BY-NC 3.0 license, so we can use them as well.
- [ ] Can we use RStudio Cloud for the trainings?

# To discuss among us
- [ ] Send a survey to RStudio connect users to ask about:
  - Example of dashboards to showcase on lightning talks
  - Topics for the RStudio lecture on production
  - Whether they want to be added to a Microsoft teams group of WB R Users -- used to share examples of dashboards and send announcements on the Bank's servers

# Shiny Day schedule

## Day 1: 04/28
- 9.30am to 11.45am: Beginners workshop - [How to build a Shiny app](https://shiny.rstudio.com/tutorial/)
- noon to 1.15am: Lightning talks
- 1.30pm to 3.45pm: Intermediate workshop - [How to customize reactions](https://shiny.rstudio.com/tutorial/)

## Day 2: 04/29
- 9.30am to 11.45am: Advanced workshop - [How to customize appearance](https://shiny.rstudio.com/tutorial/)
- noon to 1.15am: Rstudio keynote on Shiny in production
- 1.30pm to 3.45pm: Advanced workshop - Shiny in production (Maintenance and speed).  
  The idea of this one would basically be to review and put in practice the main points of the keynote
  
  
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
