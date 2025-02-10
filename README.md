# python_class

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beauty and Cosmetic Products 2024 - Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        a {
            color: #0073e6;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        ul {
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Beauty and Cosmetic Products 2024 - Python Analysis</h1>
        <h2>Final Project Report</h2>
        <h3>For the course: Python Programming for Business Analytics</h3>
        <p><strong>Under the guidance of:</strong> Prof. Uros GODNOV</p>
        <p><strong>By:</strong> Aashita Gloria NOAH</p>

        <h2>1. Introduction</h2>
        <p><strong>Link to the dataset:</strong> 
            <a href="https://colab.research.google.com/drive/1ybbxZMrAF3Pnaq_BusQ4Csj63EnloLV2?usp=sharing" target="_blank">Colab Notebook</a>
        </p>
        <p><strong>GitHub Repository:</strong> 
            <a href="https://github.com/aashitagloria/python_class/blob/main/Most_used_beauty_and_cosmetic_products_2024_python_analysis.ipynb" target="_blank">Project Code</a>
        </p>

        <h3>Motivation</h3>
        <p>As an Assistant Intern in the Global Luxe CRM & Loyalty team at L'Oréal, Paris (June 2024 - September 2024), I developed a passion for analyzing beauty trends and product performance. This led me to analyze a dataset of widely used beauty and cosmetic products to gain deeper insights into market trends, product popularity, and bundling strategies.</p>

        <h3>Dataset Overview</h3>
        <p>The dataset, sourced from Kaggle, contains information on 15,000 beauty and cosmetic products, including brands, categories, pricing, ratings, skin types, packaging, and country of origin.</p>
        
        <h4>Data Columns:</h4>
        <ul>
            <li>Product Name, Brand, Category</li>
            <li>Usage Frequency, Price (USD), Rating</li>
            <li>Number of Reviews, Product Size, Skin Type</li>
            <li>Gender Target, Packaging Type, Main Ingredient</li>
            <li>Cruelty-Free Status, Country of Origin</li>
        </ul>

        <h2>2. Methodology</h2>
        <h3>Basic Python Programming</h3>
        <ul>
            <li>Used variables, lists, dictionaries, loops, and conditionals.</li>
            <li>Created a function to calculate average ratings and prices for different categories.</li>
        </ul>

        <h3>Data Manipulation</h3>
        <ul>
            <li>Checked for missing values and duplicates.</li>
            <li>Grouped products by category, country, and cruelty-free status.</li>
            <li>Sorted and filtered data to extract top-rated and most expensive products.</li>
        </ul>

        <h3>Mathematical Operations</h3>
        <ul>
            <li>Calculated the average price per category.</li>
            <li>Compared prices of cruelty-free vs. non-cruelty-free products.</li>
            <li>Identified countries producing the highest-rated products.</li>
        </ul>

        <h3>Data Visualization</h3>
        <ul>
            <li>Bar Chart: Most common product categories.</li>
            <li>Scatter Plot: Number of reviews vs price, price vs rating.</li>
            <li>Histogram: Rating distribution of beauty products.</li>
            <li>Box Plot: Price distribution across different product categories.</li>
        </ul>

        <h3>SQL Integration</h3>
        <ul>
            <li>Stored dataset in an SQL database.</li>
            <li>Executed queries to determine top-rated categories, most expensive brands, and countries with highest-rated products.</li>
        </ul>

        <h2>3. Findings</h2>
        <h3>Key Business Insights</h3>
        <ul>
            <li><strong>Product Bundling:</strong> Skin care products dominate, allowing bundle offers (beauty kits) to increase sales.</li>
            <li><strong>Customer Segmentation:</strong> Prices vary widely, with some premium products. High-paying customers can be targeted with specific marketing strategies.</li>
            <li><strong>Price vs Rating:</strong> Higher prices do not always result in better ratings.</li>
        </ul>

        <h2>4. Conclusion & Recommendations</h2>
        <ul>
            <li><strong>For Businesses:</strong> Use product bundling to increase customer purchases.</li>
            <li><strong>For Consumers:</strong> Price alone does not guarantee quality—rely on ratings and reviews.</li>
            <li><strong>For Marketing:</strong> Implement loyalty programs with discounts and personalized offers.</li>
            <li><strong>Future Work:</strong> Further analysis of customer sentiment in reviews can provide deeper insights.</li>
        </ul>
    </div>
</body>
</html>
