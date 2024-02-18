# Clinical-Trial-Aggregator
Python script that collects clinical trials from www.clinicaltrials.gov based on the users specification (disease, type of therapy, location, trial conditions (on-going, completed, etc)), and graphs the location of the trial sites on a map.   The script assumes that the clinicaltrials.gov database is accurate - and this is * *generally* * true.   However, there are excellent sites with clinical trial aggregators that provide assistance for those in need.   Sites like https://sparkcures.com/ verify their database and are set-up to help match patient to clinical trial. 
 

**A script diagram:**

![Clinical Trials Data Aggregator Pipeline](https://github.com/timrobinson/Clinical-Trial-Aggregator/assets/15863043/bd5b4bee-15df-431e-b833-e0a203d30d3a)


The program provides a map with locations of all trial sites for trials with parameters the user specifies.  For example, the map below shows all the clinical trials for Parkinson's Disease either currently active and recruiter, and not yet recruiting.  The user also specifies the location; in this case United States was specified.  The program also provides a legend/bar chart that associates the color of the marker with the NCT trial number.  The length of the bar indicates the number of sites for the particular trial.  With this example, the type therapy was not specified.  All user selected conditions are listed in the map title.  Maps without specified therapies can be used to identify key research sites for a particular disease (on the premise that sites with a number of clinical trials and heavily invested in research for this particular disease).

**Example Output 1 (minus my commentary in the last column of the table:**

![Parkinsons Disease](https://github.com/timrobinson/Clinical-Trial-Aggregator/assets/15863043/50ca46b5-c00a-460e-9bdb-9bb5536b680b)


With the second example, the location has been changed to South Africa.  Also, the type of therapy has been specified.

**Example Output 2:**
<p align="center">
<img width="600" src="https://github.com/timrobinson/Clinical-Trial-Aggregator/assets/15863043/9167ed60-45ce-4c4d-91d2-cfb8bdd55cf8">
</p>
