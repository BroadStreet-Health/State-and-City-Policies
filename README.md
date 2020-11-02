# COVID-19 Executive Orders Dataset (USA)
  
In April, BroadStreet and The COVID-19 Data Project partnered with Temple University’s Center for Public Health Law Research (CPHLR) to look longitudinally at executive orders, health directives, proclamations, and policies related to COVID-19. We have refined CPHLR’s process, enabling the collection of city, state, and US territory  orders which are then reduced to quantitative and qualitative data to allow for simple access and analysis. ![BroadStreet Health](https://github.com/BroadStreet-Health/images/blob/main/covid-dark@2x.png)
  
## Structure
The data is in wide format. It is stored in a csv file <file_name> with the following 22 column fields. 
  
### Content
| field_name | description | value |
| :-- | :-- | :--: |
| iden_num | The identification number of the location using FIPS codes for states and counties | |
| geo_type | Whether the order applies to a city/state/territory | |
| name | The text name of the city/state/territory | |
| order_num | The name of the Executive Order or Proclamation | |
| amend | If the order is an amendment to a previous order | 0=no, 1=yes |
| start_d | The date that the order goes into effect | MM/DD/YYYY; with leading zeros (02/17/2009) |
| end_d | The date that the order will no longer be in effect | MM/DD/YYYY; with leading zeros (02/17/2009; 0 = no date |
| initial_emgcy | If the order is the initial state of emergency declaration | 0=no, 1=yes |
| cont_emgcy | If the order is in result of state of emergency declaration | 0=no, 1=yes |
| reopen | If the order contains measures related to re-opening | 0=no, 1=yes |
| stay_home | If the order contains measures related to stay at home directives | 0=no, 1=yes |
| curfew | If the order contains measures related to mandated or suggested curfew | 0=no, 1=yes |
| mask_req | If the order contains measures related to mask/face-covering requirements | 0=no, 1=yes |
| gather_ban | If the order contains measures related to gathering ban | 0=no, 1=yes |
| social_dist | If the order contains measures related to social distancing | 0=no, 1=yes |
| bsns | If the order contains measures related to the operation of businesses | 0=no, 1=yes |
| restaurant | If the order contains measures related to the operation of restaurants | 0=no, 1=yes |
| school | If the order contains measures related to the operation of schools | 0=no, 1=yes |
| med_proc | If the order contains measures related to medical procedures | 0=no, 1=yes |
| travel | If the order contains measures related to travel restrictions | 0=no, 1=yes |
| correc_fac | If the order contains measures related to correctional facilities | 0=no, 1=yes |
| notes | Notes about the Order or Proclamation | plain text |
  
## Methodology
On a weekly basis, new releases of Executive Orders are pulled from The Council of State Governments and are gathered, converted, read, and coded for a quality assurance process by the Policy Track team. Each order is reviewed and compared with the current COVID-19 statutes, regulations, emergency declarations, and mitigation policies dating back to January 20, 2020, as it is the day prior to the first confirmed case of COVID-19 by the Centers for Disease Control and Prevention.  
  
The original format of the documents is either HTML or PDF. Once the documents have been converted into the Google Doc format, the direct links are incorporated to the shared spreadsheet for the data entry teams to access. Both conversion methods generate spelling and formatting inconsistencies which must be corrected manually. Manual correction may include “auto spell check,” image removal, border removal, and/or hand-typing documents in full. The scope topics and descriptions have been created by Policy Track leaders based on CPHLR’s “protocol notes.” Data entry following the CPHLR protocols includes the analysis and mark-up of the documents and the entering of binary variables pertaining to the inclusion of “in-scope” content. The marked-up document provides the Track leaders and the Quality Assurance (QA) team members with important information and creates a track record of the logged binary variables. The individuals place a 0 (zero) in cells to signify a document does not contain content about the given scope topics; a 1 (one) is placed in cells to signify a document does contain content about the given scope topics. Any ambiguous information in the documents is noted and a detailed review is conducted by the QA team to determine if the content is applicable to the scope topics. 

State and territory orders are gathered weekly and typically included in our data one week after they were released. City and county orders are gathered monthly and currently included in our data when the quantity of released state and territory orders is low. 
  
## About Us
The Covid-19 Data Project began in March to satisfy the driving need for accessible data tracking the spread of the coronavirus across the United States. Over 120 interns and volunteers were recruited via the BroadStreet website, and through institutional reference for interested undergraduate or graduate students. The project quickly grew as the virus spread, leading to a large data set involving historical and present data collection, input, and analysis.
  
## Suggested Citation
When using data images, downloaded data, or shared document formats, please attribute BroadStreet as well as the original source, when applicable. For examples and more information, review this article which answers the question "How do I cite BroadStreet?"
  
## Contributors
Isaiah Banta, Robert Birds, Samin Charepoo, Alessandro Malave, Allison Muir, MHA. 
A full list of the Broadstreet Covid-19 Data Project volunteers can be found at https://covid19dataproject.org/team-2/ 
  
## Questions / Feedback
Email the primary contributors at: hello@broadstreet.io

