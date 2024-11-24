# SolarEase (Oct 2023 - Jul 2024)
- I played an active role in contributing to my graduation project by participating in various aspects of its development.
- I worked on implementing the backend using ASP.NET Web API and SQL Server database.
- I also worked on developing prediction models employing Support Vector Regression (SVR), which integrated with the OpenWeatherMap API to retrieve real-time features. 
- Furthermore, I contributed to implementing an online marketplace that facilitates buying and selling solar products.
- I contributed to integrating the Google Maps API to organize and display certified solar installation companies based on proximity to the user’s location. 
- I also participated in building a rule-based chatbot using NLTK techniques such as tokenization, stemming, and Jaccard similarity. 
- Additionally, I took part in deploying the backend on Monster ASP hosting, while the prediction models and chatbot were deployed using FastAPI on HuggingFace hosting.
- I was actively involved in gathering the data required for all components of the project, ensuring its accuracy and relevance.
This collaborative effort enhanced my expertise in backend development and strengthened my problem-solving and technical skills across various domains.

-------------------------------------------------------------------------------------------------------------

Adopting solar cells is crucial for addressing climate change and transitioning to clean energy. Solar cells can power residential and commercial buildings, reducing carbon emissions and promoting a cleaner environment. The rising costs of traditional electricity sources lead to higher electricity bills, while solar power provides an independent energy source, reducing or eliminating these bills. Government incentives and the ability to sell excess energy back to the grid further enhance the financial benefits. Investing in solar energy offers long-term savings and environmental advantages. 

Our app provides a comprehensive solution that considers all scenarios of solar installation for accurate results. It includes a robust calculator for customized recommendations, an assistant chatbot for user guidance, a directory of certified installers sorted by nearest, and an online marketplace for seamless buying and selling of solar products. Additionally, users who already have solar systems can track their solar system's productivity.

-------------------------------------------------------------------------------------------------------------
Functional Requirements
1) Calculations:
- Calculate System Size: Provides the user with the appropriate solar system size and roof space needed for this system, including solar panels, inverter, and battery capacity, based on user-provided monthly electricity consumption and location.
- Calculate Cost: Provides the user with the total cost of the recommended solar system size. The cost calculation must consider the expenses associated with solar panels, inverters, batteries, installation, and any additional components.
- Calculate Financial Savings: Provides the user with the savings resulting from the recommended solar system size, considering the user's monthly, yearly, and 25-year savings. It also provides the user with a payback period for the solar system.
- Calculate Environmental Savings: Provides the user with the annual reduction in CO2 emissions that would be saved by installing a solar system, based on solar system size.

2) Prediction:
- Predict solar energy: We implemented two prediction models for solar irradiance, one for hourly forecasts and another for daily forecasts based on datasets from NASA POWER, covering all 27 governorates of Egypt. Our models integrate with the OpenWeatherMap to retrieve real-time features every three hours as well as daily forecasts, extending up to five days. This prediction should be based on the user's solar system size and user’s location, as well as forecasted solar irradiance data.

3) Find Solar Installers: Provides the user with a list of certified solar installation companies, ordered by the nearest to the user's location, utilizing Google Maps APIs.

4) Online Marketplace:
- Solar Market Prices Section: Provides the user with a price list of solar products including panels, inverters, and batteries from various brands and capacities. Users can add any products to their favorite products page for easy reference and comparison.
- Online Trade Marketplace Section: Users can post solar products for sale, whether new or used. These products must be displayed to other users interested in purchasing them. The marketplace should allow sellers to provide their contact information, such as a phone number, within their product posts to allow potential buyers to communicate with them. Users should be able to search, view, and add any post to their favorite posts page for easy reference and comparison.

4) Chatbot: The user can chat and interact with a rule-based chatbot. It has two interactive sections: text input queries and predefined category selection. By offering these two distinct sections, our solar energy chatbot ensures that users can efficiently access relevant information tailored to their preferences.

5) Posts Filtration: 
- Filter Post: Admin can review and filter posts before publishing in the marketplace and reject the posts that violate the standards.
