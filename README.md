# Recommender-systems-NCF-vs-GPT

## Project Description

The goal of this project is to provide personalized movie recommendations based on user preferences. The project incorporates two main components: Neural Collaborative Filtering (NCF) and OpenAI's GPT.

### Neural Collaborative Filtering (NCF)

Implemented NCF using PyTorch to deliver personalized recommendations. The Mean Absolute Error (MAE) achieved is 0.91, indicating the effectiveness of the collaborative filtering approach.

### OpenAI's GPT Integration

Explored the application of OpenAI's GPT to predict movie ratings based on users' tastes and preferences. While GPT showed promising results on a small scale with MAE = 0.6, several challenges were encountered due to limitations in the number of tokens allowed.

## Challenges Encountered

1. **Limited Use of Training Data:** Constraints on token count led to a significantly smaller train and test dataset for GPT.
2. **Slow Real-time Analysis:** Real-time analysis is required for each user, slowing down inference during real-time scenarios.
3. **Struggle to Capture User-Item Interactions:** Limited data made it challenging to explore various aspects, such as similarities between users and items.
4. **Challenge in Capturing Long-Term Preferences:** GPTs, designed for contextual understanding within a specific window, may struggle to capture long-term user preferences or evolving tastes over time.

## Future Work

For future iterations of this project, consider the following improvements:

1. **Fine-tuning GPT:** Explore fine-tuning techniques to enhance GPT's performance on movie rating predictions.
2. **Customized GPTs:** Consider using customized GPTs trained on movie rating-specific data to address token limitations.
3. **Combined Approach:** Investigate a combined approach using both collaborative filtering and GPT to leverage the strengths of both models.

