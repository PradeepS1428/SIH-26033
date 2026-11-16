# Smart India Hackathon Workshop
# Date:16.11.2026
## Reference Number:26015813
## Name: PRADEEP S

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
Farmer Registration: Farmers register on the platform and upload their available products, prices, and quantities.

City and Date Announcement: Farmers announce the city they plan to visit and the date of their visit.

Customer Pre-Ordering: Customers select their city, browse available farmers and products, compare prices, and place orders one day before the farmer's visit.

Order Management: Farmers can monitor incoming orders and stop accepting orders when the available stock is exhausted or the required order quantity is reached.

Order Cancellation: Customers can cancel their orders until the previous night, before the specified deadline (for example, 9:00 PM).

Product Collection: Customers can receive their products through:

Home delivery by the farmer.

Collection from a common meeting or collection point.

Remaining Stock Management: Farmers can sell unsold products to nearby shopkeepers to reduce wastage.

Direct Purchase: Customers who do not use smartphones or applications can purchase products directly when farmers visit the city. Phone-based ordering can also be considered.

Example

Suppose a farmer normally sells potatoes to a middleman for ₹10 per kg. The same product is later sold to customers for ₹30 per kg.

Through FARM TO HOME, the farmer can directly sell the potatoes to customers for ₹20 per kg.

Farmer's previous selling price: ₹10/kg

Proposed direct selling price: ₹20/kg

Example retail price: ₹30/kg

The farmer receives a better selling price, while customers get products at a lower price than the example retail price.

The additional amount earned per kg can help cover the farmer's transport and other additional expenses, with the remaining amount contributing to additional earnings. No separate transport fee is proposed.

## Technical Approach
FARM TO HOME will be developed as a full-stack web application using the following technologies.

<img width="647" height="461" alt="image" src="https://github.com/user-attachments/assets/29cf0162-39f6-47c4-bad7-9007530a3824" />


System Architecture

The application consists of three main components:


A. Farmer Module

Farmer registration and login.

Add, update, and delete products.

Enter product prices and available quantities.

Announce visiting city and date.

View customer orders.

Manage stock and stop orders.

View remaining products.


B. Customer Module

Customer registration and login.

Select a city.

View available farmers and products.

Compare product prices.

Place advance orders.

Cancel orders before the deadline.

Select home delivery or common collection.

View order details and status.


C. Shopkeeper Module

View products remaining after farmer visits.

Check available quantities and prices.

Contact farmers to purchase unsold products.


Working Process

The frontend collects information from farmers and customers.

Django processes user requests and application logic.

SQLite stores farmer details, customer details, products, visiting schedules, and orders.

The backend checks product availability and order limits.

Customers and farmers can view updated order information.

Main Database Tables

Farmer

Customer

Product

CitySchedule

Order

Shopkeeper

Additional Features for Future Development

Location-based order grouping.

Minimum order threshold to help farmers decide whether a trip is worthwhile.

SMS or notification alerts.

Online payment integration.

Tamil and other regional language support.
<img width="1536" height="1024" alt="Farm-to-Home Technical Approach" src="https://github.com/user-attachments/assets/35794084-31ac-435a-a42d-505a7e569c53" />


## Feasibility and Viability


FARM TO HOME is technically, economically, and operationally feasible as a prototype and can be developed further through a small-scale pilot.

A. Technical Feasibility

The application can be developed using commonly available technologies such as Python, Django, HTML, CSS, JavaScript, and SQLite.

These technologies are suitable for developing a functional prototype without requiring expensive infrastructure.

B. Economic Feasibility

The platform aims to improve the financial benefits for both farmers and customers.

Farmers can receive a higher selling price by selling directly.

Customers can purchase products at prices lower than conventional retail prices.

Advance orders help farmers estimate demand before travelling.

Selling remaining products to shopkeepers can reduce unsold stock.


Example calculation:

Assume a farmer sells 50 kg of potatoes.

<img width="955" height="386" alt="image" src="https://github.com/user-attachments/assets/3a2f4a48-bfe9-4b54-ba57-6b4fd0140057" />


The ₹400 is the amount remaining after the assumed transport expense, before considering other additional costs such as packaging and handling. Actual earnings depend on the farmer's expenses and sales.


C. Operational Feasibility

The platform follows a simple process:

Farmers announce their city and visiting date.

Customers place advance orders.

Farmers prepare products according to confirmed orders.

Products are delivered or collected at a common point.

This can reduce uncertainty about demand and help farmers plan their visits.

D. Practical Challenges and Solutions
<img width="887" height="405" alt="image" src="https://github.com/user-attachments/assets/6df8cc94-0899-4b4c-9904-3b6e0224bdad" />


The initial prototype can be tested in one city with a small group of farmers and customers before expanding to additional cities.

## Impact and Benefits
FARM TO HOME aims to create a more transparent and accessible agricultural marketing system.

Benefits to Farmers

Direct access to customers.

Better selling prices compared with their previous selling arrangements.

Reduced dependency on intermediaries.

Advance information about customer demand.

Better planning of product quantities and city visits.

Opportunities to sell remaining products to shopkeepers.

Benefits to Customers

Access to fresh agricultural products.

Potentially lower prices.

Ability to compare products and prices from different farmers.

Convenience of advance ordering.

Choice between home delivery and common collection.

Reduced dependence on traditional retail channels.

Benefits to Shopkeepers

Opportunity to purchase remaining agricultural products.

Access to products directly from farmers.

Additional local sourcing opportunities.

Social and Economic Impact

Supports local farmers and agricultural communities.

Encourages direct farmer-consumer relationships.

Promotes transparency in agricultural pricing.

Can reduce unsold agricultural stock.

Encourages the use of digital technology in agriculture.

Can improve access to fresh produce in cities.

Long-Term Vision

FARM TO HOME aims to establish a reliable connection between rural farmers and urban consumers through scheduled visits, advance orders, and direct selling.

Our Vision: Better Prices for Farmers, Better Value for Customers.


## Research and References
The proposed system is based on research into existing agricultural marketing systems and digital platforms in India.

1. Uzhavar Sandhai – Tamil Nadu Government

Uzhavar Sandhai is an initiative introduced by the Tamil Nadu Government in 1999 to help farmers sell agricultural products directly to consumers without intermediaries.

It provides a real-world example of how direct farmer-to-consumer selling can benefit both farmers and customers.

Relevance to FARM TO HOME: Our idea builds on the concept of direct selling by adding advance online ordering, scheduled city visits, order management, and delivery or collection options.

Reference: Tamil Nadu Department of Agricultural Marketing & Agri Business.

2. National Agriculture Market (e-NAM)

e-NAM is an electronic trading platform launched by the Government of India to connect agricultural markets and improve transparent agricultural trading.

It provides farmers with access to a larger pool of buyers and supports better price discovery.

Relevance to FARM TO HOME: It demonstrates how digital technology can improve agricultural marketing. Our proposed system focuses specifically on scheduled direct selling to urban consumers.

Reference: Ministry of Agriculture & Farmers Welfare, Government of India.

3. RBI Bulletin – Agriculture Supply Chain Dynamics: Evidence from Pan-India Survey (2024)

This research examines India's agricultural supply chain using information collected from farmers, traders, and retailers.

The study found that farmers' average share in the consumer price varied between 33% and 70% across the crops covered by the survey.

Relevance to FARM TO HOME: The research highlights the importance of improving agricultural market efficiency and understanding the price difference between farmers and consumers.

Reference: Reserve Bank of India, January 2024.

4. Tamil Nadu Agricultural Marketing and Agri Business Department

The department provides information about agricultural marketing infrastructure, Uzhavar Sandhais, regulated markets, and facilities available to farmers.

Relevance to FARM TO HOME: It provides background information about the existing agricultural marketing system in Tamil Nadu.

Research Links

Tamil Nadu Uzhavar Sandhai: https://www.agrimark.tn.gov.in/index.php/Infra/us_details

e-NAM Official Portal: https://www.enam.gov.in/

RBI Research: https://www.rbi.org.in/Scripts/BS_ViewBulletin.aspx?Id=22326

Tamil Nadu Agricultural Marketing Department: https://agrimark.tn.gov.in/

