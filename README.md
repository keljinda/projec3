# Project-3 NLP

# Factors Influencing Seller Success on POD  

## **Introduction to Print-on-Demand (POD)**  
Print-on-Demand (POD) is a business model that enables sellers to create and sell customized products—such as clothing, mugs, and home decor—without maintaining inventory. Once a customer places an order, the product is produced and shipped by the POD provider, making it an appealing option for entrepreneurs looking to minimize upfront costs.

## **Problem Statement**  
Many sellers struggle to identify where to start and what factors contribute to becoming a successful POD seller. By analyzing conversations from Reddit communities focused on Printify and Printful, this project aims to uncover the key topics and trends that influence seller success.

## **Approach**  
To understand seller concerns and priorities:  
1. Data was scraped from Reddit communities focused on Printify and Printful.  
2. Text preprocessing techniques were applied, including:  
   - Removing special characters.  
   - Tokenizing, lemmatizing, and stemming words.  
   - Vectorizing text data for analysis.  
3. Analysis was conducted to identify commonly mentioned topics and patterns.  

### **Dataset Structure**  
- **Input (X):** Combined post titles and body text (`merged_df['title'] + " " + merged_df['body']`).  
- **Output (y):** Source platform (`merged_df['source']`).

## **Key Findings**  
![alt text](https://github.com/jjaytiya/Project-3-NLP/blob/main/images/Top10_mentions.png)

### **Topic Trends by Platform**  
1. **Shipping**  
   - Ranked #1 for Printify but #3 for Printful, showing its slightly higher importance for Printify users.  

2. **Etsy Integration**  
   - Ranked #2 for Printify but #1 for Printful, suggesting Etsy is equally or more crucial to Printify sellers.  

3. **Common Themes**  
   - Both platforms emphasize product customization, marketplace integration, and shipping.  
   - Printful users frequently discuss more on products and especially clothes.  
   - Printify users often highlight concerns with new feature updates and seek platform support.

## **Conclusions**  
- Sellers on both platforms prioritize customization, shipping, and marketplace compatibility.  
- Printful users may be more focused on product niches like clothing and detailed platform features.  
- Printify users appear to seek for support.

This analysis provides actionable insights into what factors matter most to POD sellers, helping aspiring entrepreneurs navigate the journey to success.
```
