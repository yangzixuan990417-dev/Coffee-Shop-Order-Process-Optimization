# Coffee Shop Order Process Optimization

## Project Overview
This is a personal Information Systems (IS) project completed as part of my studies at Victoria University of Wellington.  
I analyzed the current ("As-Is") coffee shop order and inventory management process, identified inefficiencies, and proposed improvements using business process modeling.

## As-Is: Current Process Flow
![As-Is Coffee Order Business Process Flow](As-Is-Flow.png)

**Key Issues Identified:**
- Inventory checks occur too late in the process (after order entry), leading to stockouts and poor customer experience.
- Manual order taking and confirmation increase the risk of errors.
- Reorder process is heavily manual and depends on manager approval, creating bottlenecks.
- Limited handling for out-of-stock situations and payment failures.

## To-Be: Proposed Improved Process
![To-Be Coffee Order Business Process Flow](To-Be-Flow.png)

## Process Comparison

This section compares the original As-Is process with the improved To-Be process to demonstrate how the redesigned workflow improves efficiency, accuracy, and inventory visibility.

See the full comparison here: [Process Comparison](process-comparison.md)

## Business Impact and KPI Analysis

This section explains the expected business impact of the redesigned To-Be process and identifies KPIs that could be used to evaluate the improvement.

See the full analysis here: [Business Impact and KPI Analysis](business-impact.md)

**Key Improvements:**
- Real-time inventory check before order confirmation to prevent stockouts.
- Automatic low-stock alerts and reorder requests.
- Customer receives ready notification via app.
- Reduced manual steps and manager approval.

## Power BI Dashboard

A Power BI dashboard was created to support the redesigned To-Be process by visualising order volume, sales performance, product demand, and potential inventory pressure.

The dashboard is interactive in Power BI and includes store-location filtering, daily order trend analysis, product category sales comparison, and high-demand product monitoring.

The dashboard includes:
- Total orders and total sales
- Sales by product category
- Daily order trends
- High-demand products requiring stock monitoring
- Store location filtering

![Power BI Dashboard](dashboard-screenshot.png)

## Tools Used
- Draw.io (diagrams.net) – for creating professional swimlane flowcharts
- Planned next step: Power BI for sales data visualization and dashboard

## Learning Outcomes
- Developed skills in business process analysis and modeling.
- Learned to identify bottlenecks in real-world operations and propose IT-based solutions.
- Gained experience documenting processes for stakeholders.

## Future Enhancements

- Develop a small sample dataset to simulate customer orders, stock levels, and reorder events.
- Build a Power BI dashboard to visualize order volume, stock usage, low-stock alerts, and reorder trends.
- Add additional exception handling scenarios, such as payment failure, customer order cancellation, and supplier delay.
- Create a simple data model showing how POS, inventory, and reorder data could be connected.
