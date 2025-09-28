# My-Mathematical-Modeling-Projects
This repository contains selected mathematical modeling papers authored during my high school career. These works highlight my quantitative analysis, problem-solving, and data-driven modeling skills applied across economics, biology, and optimization.

- **2023 Mathematical Contest in Modeling (MCM, Collegiate level)**  
  Awarded **Global Meritorious (Top ~10% among 11296 teams, the only high school team that achieved this among the 728 teams that selected problem B)**.  
  We first built an optimization model by subtracting the predicted economic profit using the modeled negative impacts, and conducted **simulated annealing** to obtain the value of each variable for the optimized policy. To account for changes in animal populations and propose an alternative policy that preserves these populations, we developed our animal population model using the **logistic model** framework. This model includes the additional mortality rate resulting from policies that permit hunting. We converted the differential equation into a recursive form using the Euler Method to solve it. To estimate the natural growth rates of various animals within the national reserve, we employed an exponential growth model, aligning it with the existing population data. The main model was refined by incorporating a constraint derived from the differential equation. 
  [Download Paper (PDF)](./2312480.pdf)

- **2023 International Mathematical Modeling Challenge (IMMC) Greater China International Round**  
  Advanced to **Final Defense (Top 26 among 900+ teams)**.  
  Applied machine learning methods (**Entropy Weight** and **K-Means**) to evaluate different development plans for the 5-square-kilometer land and find the optimized land development strategy (environmental impacts, economic profits, and community utilities were taken into consideration). 
  [Download Paper (PDF)](./IMMC23618025.pdf)

- **2023 High School Mathematical Contest in Modeling (HiMCM)**  
  Received **Finalist Award (Top ~7%)**.  
  We constructed a Dandelion Spread PDE Model (DSM) to investigate the spread of dandelions over time. We developed four coupled **partial differential equations** that model population densities of settled dandelion seeds, dandelion plants, puffballs, and drifting seeds. We corrected the **Fisher model** by multiplying a logistic term to obtain a logistic population growth that depicts the effect of intraspecific competition on the dandelion population. For the PDE of drifting seeds, we used the **advection-diffusion** equation by adding **Brownian Random Dispersal** to the equation. This allows us to effectively predict the spread of dandelions in various kinds of winds. We used FEniCS to obtain the final predictions of the DSM model, and a sensitivity analysis was conducted. Finally, we used the Analytic Hierarchy Process to measure the dandelions’ invasiveness. One of the indicators, total biomass, was calculated using the DSM model.
  [Download Paper (PDF)](./13718.pdf)

- **2023 International Mathematical Modeling Challenge (IMMC) Greater China National Round**  
  Advanced to **International Round**.  
  Applied machine learning methods (**logistic regression, decision tree, and random forest**) to classify lizards into 26 species. 
  [Download Paper (PDF)](./IMMC23479442.pdf)
