# COVID-19_onlinesurvey

Hagihara, H., Yamamoto, N., Meng, S., Sakata, C., Wang, J., Watanabe R., & Moriguchi, Y. (under review). COVID-19 school and kindergarten closure affects children's social relationships: A longitudinal study in Japan. *Journal Name*. doi:
  
  
## Dataset and R Scripts
- **0_situationInJapan**
  - Data and R scripts to visualize the correspondence between the spread of COVID-19 in Japan and time points of data collection (Figure 1)
- **1_preprocessing**
  - R scripts to analyze the sample characteristics (Table 1)
- **2_AnalysisOfSocialLives**
  - R scripts to analyze children's social lives (Figure 2)
- **3_AnalysisOfSDQ**
  - R scripts to analyze children's social behavior using SDQ (Figure 3 & Table 2)        
- **4_AnalysisOfIOS**
  - R scripts to analyze children's perceived closeness to others using IOS (Figure 4)
- **data.csv**
  - Dataset used in the folders from 1 to 4
   
  
## Description of labels for data.csv
| label | description |
|:----|:----|
| id | Participants' IDs |
| time | Time when data were collected (i.e., T1, T2, and T3) |
| res_gender | Caregivers' gender (2 = female, 1 = male) |
| res_age | Caregivers' age in years (only T1 and T2) |
| ch_ageY |	Children's age in years (only T1 and T2) |
| ch_ageM | Children's age in months (only T1 and T2) |
| ch_gender | Children's gender (2 = girl, 1 = boy) |
| school | Classification of children (i.e., infants, preschoolers, and schoolers) |
| fa_num | The number of family members | 
| sib_num | The number of siblings |
| education | Caregivers' education level, which was graded from 1 (less than high school) to 5 (graduate level) | 
| conduct | Score of conduct problems in SDQ |
| hyperactive | Score of hyperactivity in SDQ |
| emotional | Score of emotional symptoms in SDQ |
| peer | Score of peer problems in SDQ |
| prosocial | Score of prosocial behavior in SDQ |
| sdq_sum | Total Difficulties Score (TDS) in SDQ, which is calculated by summing each score of emotional symptoms, conduct problems, hyperactivity, and peer problems (prosocial behavior is not included!) |
| ch_sh | Days spent by children being at home and not going to schools or kindergartens per week |
| ios_cg | IOS score towards caregivers |
| ios_oth | IOS score towards others such as peers |
| scr_time | Screen time of children (hours per day), which is calculated by summing scr_passive and scr_interactive columns |
| outside_playing | Hours spent by children playing outside per day |
| lessons | Hours spent by children taking lessons or classes other than formal schooling per day |
| excludeT1T2 | Whether children participating at T1 retained participation at T2 |
| excludeT2T3 | Whether children participating at T2 retained participation at T3 |
  
  
## Contact
If you have any questions, please email at moriguchi.yusuke.8s <at> kyoto-u.ac.jp or hiromichi.h <at> gmail.com (please replace <at> with @).							
