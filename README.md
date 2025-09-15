Reappraisal of Factorial Survey Experiments to Predict Real-World Behavior: A Cautionary Tale from Hiring Studies
Description:

This project is a critical reappraisal of the paper:

Forster, A.G. and Neugebauer, M., 2024. Factorial survey experiments to predict real-world behavior: A cautionary tale from hiring studies. Sociological Science, 11, pp.886-906.

The original study evaluates the validity of Factorial Survey Experiments (FSEs) by comparing them to Field Experiments (FEs) in the context of hiring discrimination in Germany. The authors conclude that FSEs fail to replicate real-world behavior due to factors such as social desirability and respondent effort.

My reanalysis challenges this conclusion by identifying a critical design flaw in the FSE; imbalance in vignette assignment. After restricting the analysis to a subset of balanced vignettes (those shown approximately equally across respondents), I find that the FSE estimates closely match those from the FE. This suggests that the divergence found in the original study may stem not from inherent methodological weaknesses of FSEs, but from overlooked imbalance in the experimental design.

The project includes:

    Replication of the original study’s main results
    Diagnostic tests of randomization and vignette balance
    A reanalysis using only balanced vignettes
    Revised conclusions about the validity of FSEs
    Full annotated R Markdown source code and figures

Replication Data:

    Replication code and data for the original paper can be downloaded from here as a single .zip folder named replication_package_incl_data.
    The folder includes:
        validation_fe.dta — Field Experiment (FE) data
        validation_fs.dta — Factorial Survey Experiment (FS) data
    The subfolder /01_code/ also includes the original authors' STATA .do files for replication.
