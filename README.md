# Project Name : SalesVision 
  

## Screenshots:
![image](https://github.com/pranavsutar/TechathonSalesVision/assets/84005308/b0f69e36-b71d-4760-b092-cf64d91a778a)
![image](https://github.com/pranavsutar/TechathonSalesVision/assets/84005308/db7c3523-55a6-4783-8cb7-b36545c83743)
![image](https://github.com/pranavsutar/TechathonSalesVision/assets/84005308/1a2fd76f-d8c9-4858-8396-533d94f13eef)



Installation Instructions  
--
(For python backend to run, download code runner and ensure you have these libraries installed. Run the python backend using coderunner)   
```pip install flask os pickle pymongo datetime pandas statsmodels flask_cors prophet```    

(For node backend, either setup a cloud mongodb and change URI accordingly or download mongodb community server as it currently runs on local community server)  
Install the following, `npm i bcrpytjs express cors body-parser mongoose nodemon`  
`nodemon index.js` or `node index.js` to run  

(For frontend)  
`npm i `  
`npm start  `

## Additional Info  
--
Dashboard will crash as there is no data initially, for that once logged in change URL to http://localhost:3000/graphsPanel  
and upload an excel file (as per the format one column, first row = category name, second row = region/continent name, all other rows = sales data)  
You can use 4 models to customize your prediction

## READ (Known Issues)  

Do not upload the same file twice (same name)  
Do not click on file upload from Dashboard route, only upload files from "File Upload" that is /graphsPanel route  
