# Preschoolers
In this repository we show all the available material to reproduce the results presented in the article title "Unlocking the Potential of Active Play: A Systematic Review and Meta-Analysis on Enhancing Fundamental Movement Skills in Preschoolers with Insights into Effect Modifiers".

For a better understanding of the dataset, next we are going to explain the data extracted from the original studies included in this systematic review.

  + `studyID` indicates the name of the study.
  + `n` refers to the total sample size of the study.
  + `age` represents the average age of the children included in the corresponding study.
  + `BMI_baseline` indicates the average Body Mass Index of the sample at baseline.
  + `region` indicates the region/continent where the study was carried out.
  + `arm` refers the specific study-arm.

These variables were characteristics that help us to qualitative describe the sample of our included studies. The next variables correspond with descriptive statistics.

  + `pren` is the sample size of a specific study-arm at baseline time point.
  + `premean` is the mean score of a specific study-arm at baseline time point.
  + `presd` is the standard deviation of a specific study-arm at baseline time point.
  + `postn` is the sample size of a specific study-arm at post-intervention time point.
  + `postmean` is the mean score of a specific study-arm at post-intervention time point.
  + `postsd` is the standard deviation of a specific study-arm at post-intervention time point.
  + `measure` indicates the scale used to assess the Fundamental Movement Skills (FMS), the outcome of interest of our *PICOs framework*.
  + `lower_better` refers whether a reduction in the mean score indicates a general improvement in the outcome. If *YES*, a lower score in the post-intervention time point can be translated as an improvement.
  + `mean_diff` is the mean change from baseline of a specific study-arm.
  + `se_ped` is the standard error associated to the mean change from baseline. The `ped` refers to the use of a correlation coefficient of 0.54 related to *Pediatrics* when an approximation is required.
  + `int_1` refers to the type of intervention at *overall* level (i.e., Active Play, or Control).
  + `int_2` refers to the type of intervention at *intervention-specific* level (i.e., Structured Playtime, Motor Skills, or Non-Structured Playtime).
  + `Included` corresponds whether the intervention is included in the educational programme.
  + `duration` indicates the duration of the intervention when corresponds in weeks.
  + `sessions`refers to the frequency of the intervention in sessions per week.
  + `time_ses` is the average session time in minutes per day.
  + `sd_pooled` is the pooled sample standard deviation at baseline time point for each study and scale. It was calculated to standardise our data using an internal standard deviation reference (i.e., the average of pooled of pooled SDs at baseline). 
