Apartment Rent Predictor
Final project for the Building AI course

Summary
This project uses a neural network to predict monthly rent prices for apartments based on their features such as size, location, and number of rooms. The model helps renters and landlords get accurate price estimates to make better decisions.

Background
Finding a fair rent price for apartments is a common problem in many cities. Renters want to avoid overpaying, and landlords want to price competitively. However, prices vary widely depending on many factors.

My motivation for this project comes from the difficulty I faced finding fair rent prices in my city. Automating this process with AI can save time and reduce guesswork.

Problems this solves:

Renters can estimate expected prices before searching

Landlords can set competitive rents based on market data

Helps make rental markets more transparent and fair

How is it used?
Users input details about an apartment, like size (in square meters), number of bedrooms, floor level, and neighborhood. The neural network processes these inputs and outputs a predicted monthly rent price.

Typical use cases:

Renters comparing offers in real estate apps

Landlords evaluating new listings

Real estate agents providing price estimates

Example user workflow:

Enter apartment details

Press "Predict Rent"

Receive an estimated rent price based on current market data

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/Apartment_building_Brooklyn_NYC.jpg/320px-Apartment_building_Brooklyn_NYC.jpg" width="300">
Data sources and AI methods
The dataset consists of publicly available apartment rental listings from online real estate platforms collected over the past year.

AI methods:

Neural networks with ReLU activation in hidden layers

Regression output layer for price prediction

Trained using mean squared error loss function

Challenges
The model may not capture sudden market changes (e.g., economic shocks)

Ethical considerations: prices should not reinforce unfair discrimination based on location or demographics

Data bias if dataset is incomplete or unbalanced

Does not account for tenant creditworthiness or landlord preferences

What next?
Incorporate additional features like amenities, building age, or proximity to public transport

Collect user feedback to improve model accuracy

Explore more advanced architectures (e.g., deep learning with more layers)

Develop a mobile app or API for easy access

Acknowledgments
Inspired by the Building AI course and logistic regression foundations

Apartment image: Apartment Building Brooklyn NYC by Jeffrey Zeldman / CC BY 2.0
