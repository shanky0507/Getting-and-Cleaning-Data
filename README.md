# Getting-and-cleaning-data-course-project
## **Review criteria**
   
   
   * The submitted data set is tidy.
   * The Github repo contains the required scripts.
   * GitHub contains a code book that modifies and updates the available codebooks with the data to indicate all the variables and      summaries calculated, along with units, and any other relevant information.
   * The README that explains the analysis files is clear and understandable.
   * The work submitted for this project is the work of the student who submitted it.

   
### Project details
     The R script, run_analysis.R, does the following:
    1. Downloads the dataset if it does not already exist in the wd.
    2. Loads the activity and feature informatio into R studio.
    3. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation.
    4. Loads the activity and subject data for each dataset, and merges those columns with the dataset.
    5. Merges the two datasets.
    6. Converts the activity and subject columns into factors.
    7. Creates a tidy dataset that consists of the average value of each variable for each subject and activity pair.
    8. The tidy data  is now shown in the file tidy.txt.
    
    
