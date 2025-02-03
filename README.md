
# AI-Powered Travel Assistant

## Introduction
The AI-powered Travel Assistant leverages the Function Calling API to provide travel and food recommendations based on user preferences. This project integrates travel and food datasets to enhance user experience by offering personalized suggestions for destinations, accommodations, and dining options.

## Objectives
- Develop an AI chatbot to assist users in travel planning.
- Integrate Function Calling API for improved query handling.
- Provide personalized travel recommendations based on budget and duration.
- Suggest accommodations and food options using structured datasets.

## System Design & Architecture
### Core Components
- **TravelFoodBot**: Handles travel and food recommendations.
- **ToolCallingBot**: Implements Function Calling API for processing user queries.

### Data Sources
- `travel_data.csv`: Contains travel destinations, costs, and durations.
- `food_data.csv`: Includes restaurant details, pricing, and sales data.

### Technology Stack
- **Programming Language**: Python
- **APIs**: OpenAI API
- **Libraries**: Pandas for data processing

## Implementation
### Data Processing
- Loaded and cleaned travel and food datasets.

### Function Calling API Integration
- Defined functions for:
  - Travel search
  - Accommodation recommendations
  - Food suggestions
- Implemented API calls to analyze queries and determine the appropriate function to execute.

### Recommendation Logic
- Filtered travel destinations based on budget and duration constraints.
- Extracted top accommodations per destination.
- Recommended restaurants based on popularity and budget.

## Challenges & Solutions
- **Data Cleaning**: Handled missing and inconsistent values using Pandas.
- **API Response Handling**: Structured responses to ensure user-friendly output.
- **Performance Optimization**: Efficient filtering of datasets to return top recommendations quickly.

## Benefits of Function Calling API
- **Enhanced Query Handling**: Automates function selection based on user input.
- **Improved Accuracy**: Ensures recommendations are tailored to user preferences.
- **Scalability**: Allows seamless expansion by adding new recommendation functions.

## Lessons Learned
- Importance of structured datasets in AI-driven applications.
- Efficient API integration improves chatbot responsiveness.
- Handling edge cases enhances the robustness of recommendation systems.

## Conclusion
The AI-powered Travel Assistant successfully integrates Function Calling API to provide efficient travel and food recommendations. This approach enhances the chatbot’s ability to deliver personalized and relevant suggestions, improving overall user experience.

## Author
**Shailesh Patel**

## License
This project is open-source and available for modification and distribution under the MIT License.
