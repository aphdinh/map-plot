# map-plot

[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/aphdinh/map-plot)

The combination of a scatterplot (bubble chart) and radar plot can be used to examine product quantities in the supply chain.
The visualization starts with a scatterplot, the x-axis is the total orders, y-axis is the late delivery orders, and the data points are corresponding to specific material plants, and the size of the bubbles reveals the total sales volume. the slopes of the data points shows the late delivery rate, the steeper the slope then the higher the late delivery rate, indicates a potential supply issue. However in the Suncharge sales data, the late delivery rates of all the material plants are similar, which are around 20%, so we will just randomly choose 1 material plant for the radar plot illustration. 

By clicking the bubble, the details of the material plant is shown. It is presented by a radar plot. Each axis represents a different year-month of the material plant, spans from 2022-01 to 2024-02. The data presented here are the sales quantity in green and the gross inventory quantity in red. The values are standardized to address data mismatch issues and focus on dynamics rather than absolute quantities. In this example of material plant 20004, we can see that from May 2023 the sales quantity is higher than average while the gross inventory is lower, this indicates a potential supply issue.
