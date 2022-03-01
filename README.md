select top 10* from [DataDB].[dbo].['sample-csv-file-for-testing$'] ORDER BY[ Gross Sales ] DESC
 ![image](https://user-images.githubusercontent.com/100667693/156118727-60039edd-4971-4972-8718-6145875098fc.png)
 select top 3 *from [DataDB].[ dbo].['sample-csv-file-for-testing$']
 ![image](https://user-images.githubusercontent.com/100667693/156119006-b16c8b4d-9420-4394-ac49-3ef747a94188.png)
 select top 5* from [DataDB].[dbo].['sample-csv-file-for-testing$']ORDER BY [ Profit ] DESC;
 ![image](https://user-images.githubusercontent.com/100667693/156119192-50babb5c-ca6b-40b9-9a71-aa15462ab948.png)
  select Country, SUM([  Sales ]) TOTAL_Sales From [DataDB].[dbo].['sample-csv-file-for-testing$'] GROUP BY Country
  ![image](https://user-images.githubusercontent.com/100667693/156119426-6c52d46d-d4f6-46b2-b96e-9c10722ab008.png)
 select Country, SUM([ Profit ])  TOTAL_Profit from [DataDB].[dbo].['sample-csv-file-for-testing$'] GROUP BY Country 
 ![image](https://user-images.githubusercontent.com/100667693/156119625-465864f8-17b2-4b93-8c77-af0b70761db1.png)
  select Segment, SUM([  Sales ]) TOTAL_Sales from [DataDB].[dbo].['sample-csv-file-for-testing$']  GROUP BY Segment ORDER BY TOTAL_Sales DESC;
 







 



