# Customer-Retention-Analysis-PwC
#### Background / Objectives

The main objective of this task is to define proper KPIs and create a dashboard for the Call Centre Manager about customer retention reflecting the KPIs. Thereafter, I will write a short email to him (the engagement partner) explaining my findings, and include suggestions as to what needs to be changed.

#### Inputs

- Customers who left within the last month
- Services each customer has signed up for: phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information: how long as a customer, contract, payment method, paperless billing, monthly charges, total charges and number of tickets opened in the categories administrative and technical
- Demographic info about customers — gender, age range, and if they have partners and dependents
- 
#### On the Checklist;

- Customers in the telecom industry are hard-earned: we don’t want to lose them
- The retention department is here to get customers back in case of termination
- Currently, we get in touch after they have terminated the contract, but this is reactionary: it would be better to know in advance who is at risk
- We have done customer analysis with Excel: it has always ended in a dead-end
- We would like to know more about our customers: visualized clearly so that it’s self-explanatory for our management
  
#### Minds at Work

###### Data Source

The data was provided by PwC Switzerland as part of the Forage virtual internship.

###### Data Preparation

I loaded the Churn Dataset in Power BI desktop. Upon quick glance, it was clear that the dataset had 23 columns and 7,043 rows.
No duplicates found in data. View<>Column Quality, there was no empty cells across the dataset
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/b1332d36-f3f8-4571-8daa-371b5b4c9fef)

Replaced no, yes with retained and churned respectively in the churn column. I replaced

###### DAX Measures

1. Churned customers
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/d875aa76-d35f-4ee8-abeb-33b41d7251bc)

2. Retained customers
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/6f9c719e-9d7f-4ad7-b044-108028da37d9)

3. Total customers = Churned + Retained

![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/f41691e3-b10b-431d-8673-d4cc814481be)

4. Female customers
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/2ccffc00-0923-464a-8219-5d3611c9af93)

5. Male customers
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/6dbbf3df-c8d5-46f6-af83-9e0eed99eddc)
6. For revenue, I separated into two, since I figured out as total revenue has included both the retained and churned customers.
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/280a62e1-4e4a-4f90-a62a-76d5a6d11f39)

7. I had to group the tenure which was given in months to years and output is as shown in the duration column below
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/304f018a-cbaa-4d2e-8251-45d509d56bdc)
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/e4fe1c9e-5859-42da-9f41-30ca27539d80)

### Creating My Dashboard
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/93f42e36-7b78-4d17-8f77-afa79c5a9377)


### PwC Dashboard
After my submission, I learnt a lot, the dashboards were categorized into welcome, churn and customer risk analysis. Their imaginations and graphics were very amusing as well. Below were the workings of the PwC.
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/0e8c1137-71c5-4111-a96c-b23784805e26)
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/aff7e996-7824-47c7-ac27-765d12b63851)
![image](https://github.com/Essie-Wabomba-dmd/Customer-Retention-Analysis-PwC-/assets/63599016/b9edf9ff-1b80-4ba9-9a37-cf168137cc03)



