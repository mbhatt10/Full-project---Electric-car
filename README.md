Project Title: Electric Car Inventory Optimization Dashboard

Description:

This is a self-initiated project where I built an end-to-end data analytics solution focused on the electric vehicle (EV) market. Starting from scratch, I gathered, cleaned, and analyzed data to develop an interactive Power BI dashboard that helps stakeholders make informed inventory decisions for EV components.

The main objective of this project is to prevent out-of-stock and overstock situations by identifying which EV parts are in high demand and should be prioritized in stock planning. Through data-driven insights, the dashboard supports better forecasting and inventory optimization for automotive suppliers or retailers.

1. Demand Forecasting for EV-Specific Spare Parts

Problem: Which BEV/PHEV models and components (e.g. battery modules, inverters, onboard chargers) will see the highest replacement demand over the next 6–12 months?

Why it matters: Prevent costly over- or under-stocking; improve cash flow and customer satisfaction.

Data approach:

Clean and aggregate historical registration counts by model year, make, and electric range.

Incorporate seasonality (model-year peaks), region-level adoption rates (2020 census tract, legislative district).

Build time-series forecasting (ARIMA, Prophet) or regression models using external signals (gas prices, utility rates).

Dashboard: forecast vs. actual, inventory recommendations by SKU.

Answer - “We used actual state-level EV registration data to determine which brands and models dominate the roads. By combining this with age, range, and type (BEV/PHEV), we identified which vehicle categories are phasing out ICE parts and increasingly need EV-specific components like batteries, power electronics, and motors. This analysis gives our e-commerce business a clear, data-backed roadmap for stocking the right parts for the right vehicles, in the right quantities.”


2. Adapting to Specialized and Rapidly Evolving Components
Problem: EVs require specialized parts (e.g., lithium-ion batteries, inverters, onboard chargers) that differ significantly from ICE vehicles, and technology is evolving rapidly.

Why it matters: Sourcing and stocking components that require unique manufacturing and expertise can be challenging. Incorrect or outdated inventory can lead to obsolescence and lost sales opportunities.

Data tasks: Track the introduction of new models and component types, monitor trends in battery and motor technology, and forecast demand for emerging parts categories.
Ans - To stay competitive in a fast-evolving EV ecosystem, I used registration data to identify newly launched models with advanced electric ranges and high adoption. By tracking makes like Lucid, Rivian, and recent Tesla models, I forecasted the need for next-gen lithium batteries, onboard chargers, and motor electronics. This data helps our parts business stock high-tech components aligned with real-world EV innovation—and avoid outdated inventory


3. To optimize spare part distribution and improve targeted marketing by identifying the most registered EV make and model in each U.S. state using actual vehicle registration data.
Ans- Using EV registration data grouped by State, Make, and Model, we analyzed which electric vehicle is most popular in each region. By determining the top-registered EV models per state, we can directly align marketing strategies and inventory planning to actual demand.
By aligning parts availability and marketing focus with real-world EV registration patterns, this approach will:

Improve customer satisfaction by reducing part wait times.

Reduce logistics costs through smarter regional stocking.

Increase marketing ROI through more relevant regional targeting.


4. Pricing Strategy Based on MSRP and Vehicle Type
Analysis: Analyze the base MSRP and electric vehicle type to understand the price sensitivity and value segment of your potential customers..
We analyzed the average base MSRP (Manufacturer’s Suggested Retail Price) across different electric vehicle types—specifically Battery Electric Vehicles (BEVs), Plug-in Hybrid Electric Vehicles (PHEVs), and others. The analysis revealed that Plug-in Hybrid Electric Vehicles (PHEVs), on average, have a higher MSRP than BEVs and other EV types in the dataset. This indicates that PHEVs are often positioned as premium offerings in the current market, likely due to dual powertrain technology and added driving flexibility.

Business Insight:
This pricing trend suggests that PHEV buyers typically belong to a higher purchasing power segment and may be more receptive to premium features and services. In contrast, BEVs include more mass-market models, making them attractive to budget-conscious or eco-motivated customers.

Business Value:
Understanding these pricing segments enables targeted product and service bundling:

For PHEVs: Offer high-end packages such as extended warranties, at-home charger installation, and concierge maintenance services.

For BEVs: Focus on affordability-driven bundles like financing plans, basic maintenance kits, and utility-based rebates.

This segmentation ensures better alignment with customer expectations, maximizes perceived value, and improves conversion across distinct EV buyer personas.
