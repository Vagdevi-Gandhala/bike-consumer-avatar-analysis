# bike-consumer-avatar-analysis
**Creating Dashboard to analyse the consumer avatar of a product (bike) using Excel Pivot tables**


![excel collage](https://user-images.githubusercontent.com/111446453/185659264-7c174872-a172-4a59-8a9f-bfbaa93f304e.png)
# Business Request & User Stories
The business request for this data analyst project was an executive sales report for sales managers. 
Based on the request that was made from the business we following user stories were defined to fulfill delivery and ensure that acceptance criteria’s were maintained throughout the project.

![Screenshot (48)](https://user-images.githubusercontent.com/111446453/185663880-cb1039f6-d2c1-4e0c-9673-f7b7e5fea104.png)

# Data Cleaning and Transformation
## Remove Duplicates
![Screenshot (68)](https://user-images.githubusercontent.com/111446453/185925053-9519d831-b386-4cd9-a250-64279d4ea2c2.png)




## Marital status and Gender columns
The M's and S's in Marital status column are not inherently known to everyone as married and single.
So using **ctrl+h** find and replace M with married and S with single for the whole column Marital status.

The M's and F's in Gender column are not inherently known to everyone as Male and Female.
So using **ctrl+h** find and replace M with male and F with Female for the whole column Gender.

## Change the Number formate in Income column

For this select the whole Income colume and decrease decimal point

![collage_excel](https://user-images.githubusercontent.com/111446453/185923988-d695b52a-a486-4203-8284-eddfeff138f6.jpg)


## Create a column "Age brackets"
As the Age column contains all numbers, which when used would make visualization messy
The preferred kind of data in age category would be Age brackets

Below is the formula applied on age column to categorise ages in to 3 categories

This is done by using a **Nested IF** Formula statement as follows
![Screenshot (70)](https://user-images.githubusercontent.com/111446453/185929910-9c89a18d-2ff7-4b41-9a9d-b80c1a022677.png)

***=IF(L:L>54,"Old",IF(L:L>=31,"Middel aged",IF(L:L<31,"Adolescent","Invalid")))***





![Screenshot (69)](https://user-images.githubusercontent.com/111446453/185929943-ac9a3aed-309b-425e-b54e-8862c7782974.png)


# The Data Modelelling
To create the necessary data model for doing analysis and fulfilling the business needs defined in the user stories the following tables were extracted using Pivot table in Excel.
To create the necessary data model for doing analysis and fulfilling the business needs defined in the user stories the following tables were extracted using Excel Pivot table and Pivot charts. 

## Does Income Influnce whether a potential consumer purchases a bike or not?

Should we cater to people with high Income ranges 


![Screenshot (a)](https://user-images.githubusercontent.com/111446453/185932331-2dce45e1-beb3-4b3e-ac30-80edd3f1fe25.png)

## How Commuting distance influences whether a consumers buys a bike or not?

![Screenshot (b)](https://user-images.githubusercontent.com/111446453/185932396-5eeadf1c-e0f4-4af9-a2be-83971b88e056.png)

## How Age of a consumer effect the choice to purchase a bike?




![Screenshot (c)](https://user-images.githubusercontent.com/111446453/185932463-846eafe1-49d7-4f08-a557-2451411098d7.png)






![Screenshot (49)](https://user-images.githubusercontent.com/111446453/185730809-19b97991-76e0-4bcb-ad19-f9ad66624a30.png)



# Dashboard

Paste all the three Pivot charts and create a dashboard.

Finally to make this Dashboard even more precise for the Marketing department, add MARITAL STATUS, EDUCATION & REGION Slicer and connect them to all three Pivot tables.

[Click this link to to open the dashboard and try it out!](https://1drv.ms/x/s!AsGPhe3EDTlvsVCsPvtR1vEMx7k0)
![Screenshot (47)](https://user-images.githubusercontent.com/111446453/185663987-a6e1972c-3d92-423a-b3de-255456aac73d.png)
