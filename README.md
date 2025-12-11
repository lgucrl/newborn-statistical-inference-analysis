# Statistical Inference Analysis to predict newborn weight

This repository contains an inferential statistics project in **R** with the goal of building, validating, and interpreting a statistical model capable of **predicting newborn weight** from collected clinical variables, such as maternal, pregnancy, and newborn measurements. The analysis combines classical hypothesis testing with multiple linear regression, model selection, diagnostics, and scenario-based prediction. The full project is contained in the R Markdown document and the HTML output can be visulized in this [Github Page](https://lgucrl.github.io/statistical-inference-analysis-newborn/).



## Dataset

The dataset (`newborns.csv`) contains **2,500 newborns** observed across **three hospitals**. It is structured with **one row per newborn** and includes the following variables:

- **Mother.age**: mother’s age
- **Pregnancies.n**: number of the mother's previous pregnancies
- **Smoker**: mother smoking status (0 = non-smoker, 1 = smoker)
- **Gestation.w**: gestational age in weeks
- **Weight**: newborn weight in grams (**response variable**) 
- **Length**: newborn length in millimeters
- **Cranium**: newborn cranium diameter in millimeters
- **Birth.type**: delivery mode (Natural or Cesarean)
- **Hospital**: hospital identifier (1, 2, or 3)
- **Sex**: newborn sex (Male or Female)
