# Loan Outcomes Among Pell Grant Recipients: A Comparison of HBCUs and Non-HBCUs
In this project, we investigate the Loan Default and Repayment rate among Pell
Grant Students in HBCUs and non-HBCUs. We also go on to investigate how loan debt
differ by HBCU status. Then we analyzed how loan debt is associated with loan default
and repayment rate while controlling for institutional characteristics, such as 
net cost, admission rate, etc. Thereafter, we go on to build a model using synthetic
data using predict loan default for Pell Grant students. The aim of this project 
is to gain a deeper understanding of the relationship between Pell Grant debt and
financial outcomes and inform the creation of more equitable financial aid policies
for low income students, especially in institutions that are underfunded. This 
will help stuents attain higher financial security and decreasing financial burdens
that are common after graduation. 

## Research process

### Data collection and Research proposal
First, we collected the data from the United States Department of Education College
Scorecard website. Then we explored and made the data a little tidy. A full version
of how we did this is in the [data section](./data/README.md). We wrote a research
proposal based on this data, which can be found in the [proposal section](./proposal/proposal_revision.pdf)

### Exploratory Data Analysis
Next, we did a full Exploratory Data Analysis on the data and found interesting 
patterns that aided our research proposal. A full exploration of the data is seen 
in the [eda section](./eda/full_college_scorecard_eda.ipynb)

### Preliminary Report
We proceeded to analyzing our data, answering our research proposal questions in 
the process. then we wrote a report on our findings. The report and analysis can
be found in the [preliminary_report section](./preliminary_report/)

### Presentation and Peer review
We presented our findings in the class and got feedback from the class and the 
Professor. Before our presentation, we had sent our preliminary report for peer
review and feedback. These feedbacks were very essential in finalizing our report.
Our slides presentation can be found in the [presentation section](./presentation/presentation_slides.pdf). 

We also reviewed other team's report and analysis and gave [feedback](./peer_review/peer_review.pdf)
on possible areas of improvement. 

### Final report
After gathering all the feedback from the peer review and presentation, we polished
our final report and added areas of future work. This can be found in the [final report section](./final_report/)

## Report Findings
Among the findings made in this research, we realized that Pell Grant recipients 
in HBCUs have high default rate and low repayment rate then their counterparts 
in non-HBCU schools. These differences were also statistically significant. However,
when we control for other factors such as net cost, admission rate, completion rate,
and median earnings, the type of school (HBCU or non-HBCU) become insignificant,
signifying that there could be structural inequalities, which are beyond the status
of schools, that account for high default rate in Pell Grant students. Moreover, 
our predictive model (trained on synthetic data) achieved a high accuracy of 90%,
further solidifying our findings in the paper. A more detail review of the findings
is found in our final report.