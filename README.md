## Finance Dashboard

Fully responsive MERN application that shows in-depth statistics for finances with key performance indicators in a nice and clean UI.

The app can also predict the revenue for the next year using machine learning and shows the linear regression line of the actual year.

Other technologies/libraries used:

- Material UI for application design
- Regression for linear regression machine learning
- Recharts for charts
- Redux/RTK for frontend data management
- React Router for page navigation
- Mongoose ODM for working with MongoDB
- Mongoose Currency for currency types

### App presentation

#### Dashboard page

Dashboard page consists of a lot of charts, tables and overall data about the finance data - key performance indicators, revenue, expenses etc.

AreaChart, LineChart and BarChart
![Dashboard1](_readmeimg/row1.PNG)

LineChart, PieChart and ScatterChart
![Dashboard2](_readmeimg/row2.PNG)

Tables and PieChart
![Dashboard3](_readmeimg/row3.PNG)

#### Predictions page

Regression line through the yearly data about the revenue

![Regression](_readmeimg/regression.PNG)

Predicted regression line about the revenue for the next year

![Predictions](_readmeimg/prediction.PNG)

### What I learned?

In this project I learned about implementing advanced MUI features in a responsive complex layout.

I also learned about using different types of charts with recharts and how to customise them.

Basic machine learning integration for regression line and predictions.

### How to run ?

Frontend(client)

> npm run build

Backend(server)

> npm run dev
