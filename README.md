# 2024 ACS Workshop - Designing and Analyzing Agricltural Studies: intro and example in R  

Hey there!  

This is the prep page for the **2024 Agronomy, Crop, and Soils Graduate Student Committee Workshop - Designing and Analyzing Agricltural Studies: intro and example in R**, taught by [@leombastos](https://github.com/leombastos).    

The workshop was presented on May 10th 2024 for ~1 hour where we covered:  

- Treatment vs. Experimental design  
- Randomized complete block design (RCBD)  
- R code to conduct a 2-way factorial RCBD analysis workflow including data import, wrangling, EDA, model running, assumptions checking, mean extraction, pairwise comparisons, and final plot.  

Follow the slide deck [here](https://leombastos.github.io/bastoslab/teaching/2024-acs/2024-acs-deck.html#/title-slide).  

Follow the rendered script [here](https://leombastos.github.io/bastoslab/teaching/2024-acs/2024-acsworkshop-rcbd-Bastos.html).  

Follow the recording [here](https://youtu.be/UYDQvEv65wA).  


## **Interested in conding along during the workshop?**  

1. New to R and/or RStudio? Follow steps 1 and 2 of [these instructions](https://leombastos.github.io/bastoslab/teaching/2024-dsa/slides/lab01-prep.html) to install them before the workshop (if you want to be able to follow along).    

2.  Download this repository to your computer (click on the green "Code" button above and select "*Download ZIP*").

3.  Unzip the repository.  

4. On your computer, go on the subfolder `code` and double-click on the file `2024-acsworkshop-rcbd-Bastos.qmd` to launch in an RStudio window.  

5. The first chunk (called `setup`) contains code to install the package `easypackages`, load this package, and then use its function `packages()` to either load or install each of the other packages needed for the workshop. To be able **to code along**, you will need to run the code **lines 54-65 to install all the required packages**. Make sure to do this **BEFORE** the workshop, as we won't have time to troubleshoot during the workshop.   
