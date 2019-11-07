# AAA_market_segmentation
market segmentation and recommendation model for AAA members

# Objectives
Provide a market segmentation of AAA members (or member households) that allows AAA Northeast to better serve their members.  They would use this analysis to:
# Outcomes
- Better anticipate the needs of members.
- Customize communications and offering to various segments.
- Expend more effort driving acquisition and renewal of desirable members.

# Methodology
all the models mentioned in this project follow the same approach (if at all there's a difference in the approach, it will be mentioned accordingly)
- Stage 1: Summarize data to the household level.
- Stage 2: Divide data into training and validation sets.
- Stage 3: Develop a series of “look-alike” models to determine the probability of purchasing each product.  
- Stage 4: Validate models.
- Stage 5: Develop models to predict the likelihood of using roadside service as well as the total cost of roadside usage.
- Stage 6: Join training and validation sets. 
- Stage 7: Score all the members that do not have the purchase of a product with the probability of purchase.  If they have purchased the product, score them a 1.  Score them on the likelihood of roadside usage and the expected cost (in the next 12 months).
- Stage 8: Use model results to cluster/segment the members.  (Used a small number of clusters (4-6)).

# Resources created:
- Aurora tables
- S3
- Athena

# Various customer segments
- Age Group
- Gender
- Parents
- Credit Ranges
- Dwelling type
- Education
- Home Owner
- Income Range
- Language
- Mosaic
- Occupation Type
- Race
- Right Dwelling Type
- Car Manufacturer

# Outreach type
- Needs (ND)
- Communications and Offerings (CO)
- Renewal Opportunity (RO)
