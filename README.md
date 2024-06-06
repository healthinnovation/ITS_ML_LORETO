ITS-ML LORETO
================
`R` code and outputs to support [Carrasco-Escobar G](https://github.com/gcarrascoe),[Jesús M. Quispe Quispe](https://jesusrqp96.github.io/JesusQuispe), Arnab K. Dey, Changwoo Han, François Rerolle, Verónica Soto, Hugo Rodrigues, Alejandro Llanos-Cuentas, Tarik Benmarhnia. **Two-Stage Interrupted Time Series Analysis with Machine Learning: Evaluating the Effectiveness of Malaria Interventions in Peru as a Case Study**

--------------------------

Study description
================
This study proposes that malaria interventions were effective in reducing malaria incidence during the period of their effectiveness, even when considering seasonal climate factors such as temperature and precipitation. We assessed the effectiveness of these interventions using monthly malaria incidence data for Plasmodium vivax and P. falciparum in Loreto, Peru (2001–2019). Employing a two-stage machine learning model, we examined how both the **"Plan Malaria Cero"** and **PAMAFRO** interventions contributed to reducing malaria incidence.



----------------

## Repository structure
- [Data](analysis) Data Employed to reproduce the results
- [analysis](analysis) `R` markdowns and outputs.
  - [02_Calculate_ML.Rmd](02_Calculate_ML.Rmd) `R` markdown for data preparation,preprocessing and model building.
  - [03_Results.Rmd](03_Results.Rmd) `R` markdown to present the results of the data analysis.
- .Rprofile
- README.md
- [ITS_ML.Rproj](ITS_ML.Rproj) `R` project file.

----------------


## `R` environment and version

Detailed information about the `R` environment and version used for running this project.

```bash
               _                           
platform       x86_64-w64-mingw32          
arch           x86_64                      
os             mingw32                     
system         x86_64, mingw32             
status                                     
major          4                           
minor          3.1                         
year           2023                        
month          06                          
day            16                          
svn rev        84548                      
language       R                           
version.string R version 4.3.1 (2023-06-16 ucrt)
nickname       Beagle Scouts 
```
