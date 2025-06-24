----------------
## **Context**
----------------

**BREAD as an Inflation Index.**

The price of "The Baguette" in France, along with the purchasing power based on the minimum wage (SMIC), is often compared to assess the country’s economic health. This index provides an estimate of how inflation impacts the population.

In this project, we will create a model to predict bread sales in a bakery over the next six months in order to evaluate the purchasing power of the French.

------------------
## **Objective**
------------------

The price of bread is a **fluctuating mirror of society.** The famous “Baguette Index” (referring to the classic French baguette) compares the evolution of the price of bread with that of the minimum wage in force.

The dataset used here belongs to a French bakery and contains daily transaction details of customers from January 1, 2021, to September 30, 2022. We will build a time series model using AR, MA, ARMA, and ARIMA techniques to predict future sales of French bread (all types) over the next 6 months.

--------------------------
## **Data Dictionary**
--------------------------

- `date`: date order
- `time`: time order
- `ticket number`: identifier for every single transaction
- `article`: name of the product sold (in French)
- `quantity`: quantity sold
- `unit_price`: price per product
