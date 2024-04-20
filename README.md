# DATAWAREHOUE-GROCERYSTORE-POWERBI
## I) DATA  
  
   Supermart Grocery Sales
   - This is a fictitious dataset created to help data analysts practice exploratory data analysis and data visualization. The dataset has data about customer orders on a grocery delivery app. The dataset is designed with the assumption that orders are placed by customers living in the state of Tamil Nadu, India.
   - The data set includes: 11 columns, 9994 rows  
## II) STEPS
   1) Business process  
      Sales reporting:
      - Store sales by time, region, category?
      - Store profitability by time, region, category?
      - Discounts by time, region, category?
      - Which product categories sell the most and least?
      - Which area has the most profitable sales?
      - Which customers buy the most in each area?
      - Which region has the highest total discount? Compare the discount to have a big impact on the profit of that region (does the discount help the region sell better or not?)
      - Factors affecting profit (location, discounts?)
   2) Dim and Fact table data (Using Excel based on the design of KimbaIIU team)  
      Use SQL server to create Dim and Fact tables  
      - Dim Category  
          <img width="301" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/353a2df1-6476-47f7-8400-96816f990fb1">
         
      - DimCustomer  
         <img width="301" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/c9e7a976-b4d8-43b5-96f6-505e7dd2592e">
  
      - DimDate  
          <img width="300" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/bd02c725-142c-4a06-98b4-dc7bc74fa775">
            
      - DimLocation  
        <img width="300" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/b7767ed0-04a3-4cf0-ab72-a3f5808b360c">
  
      - FactSales  
          <img width="296" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/3f2d5a75-c554-4264-a00f-f965c774939a">
  
      - Star diagram  
           <img width="439" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/8dfd00a0-f869-419e-939b-6ab256f3c1e5">
          
   3) Integrate data into data warehouse (SSIS)  
      - Control Flow
        <hr>

        <img width="439" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/5ef037fe-3307-4ece-ad92-ae0cb9f264c2">
        <hr>

        <img width="439" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/36983727-802c-4c26-8a9b-d239fe31b649">
        <hr>

        <img width="439" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/9f0b2986-c623-49ca-9c6d-d3983dad7034">  
        <hr>
        
        <img width="418" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/6bb268c5-4cda-447d-992a-86a43acee34c">
        <hr>
          
        <img width="428" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/696e0737-8053-4efd-a156-4a184ec44afa">  
        <hr>
          
        <img width="369" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/00da44b5-6836-4fff-a99e-385fd4228b13">  
        <hr>
          
   4) Data analysis (SSAS)    
      - Data Cube  
        <img width="439" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/9f308b59-23b7-4ad1-8307-1101ed65fd2c">
   
      5) Data mining (power bi)  
      <hr>
      <img width="439" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/62e91bd7-400c-49f5-b4e6-06350c0ebe7a">
      <hr>
      <img width="369" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/fb48171e-c34a-4451-b91c-da26c49b7aa4">
      <hr>
      <img width="397" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/6e95a9fc-6e44-413e-8c87-b222058af39b">
      <hr>
      <img width="369" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/27a2ab53-c5c0-4a55-b928-1d2cd4bee3d1">
      <hr>
      <img width="369" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/0403b5a6-9925-43cc-9b4f-24bfa1a81964">
      <hr>
      <img width="369" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/293cb439-b73a-4336-8ea7-aded097bbf1f">
      <hr>
      <img width="369" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/ad6ac309-720e-44d1-b78e-75a9210ba472">
      <hr>
      <img width="428" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/b2081c41-d564-4577-a6f4-7fee8dadce1c">
      <hr>
      <img width="439" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/c8247a72-9bbd-4251-aad0-0aeda3f4ad5e">
      <hr>
      <img width="439" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/a3430b71-a86f-4e2c-80b6-7f41ca2759e6">
      <hr>
      <img width="439" alt="image" src="https://github.com/Nguyenvivi0909/DATAWAREHOUE-GROCERYSTORE-POWERBI/assets/112494867/590a85fb-d8d9-45a8-bdc6-2ed2b65abda3">
