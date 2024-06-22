
# Stock Price Analysis using Sentiment Score.

Create an interactive and insightful Stock Price Analysis tool using Python and sentiment analysis, where users can track and predict stock price movements based on real-time sentiment scores derived from news articles and social media, offering a comprehensive and user-friendly interface for investors to make informed decisions.

## Steps

- Data Collection
For the data collection phase, the focus will be on selecting stocks listed on the NASDAQ exchange, targeting a comprehensive analysis period from 2017 to 2020. This time frame ensures that the analysis covers various market conditions and trends. Gathering daily news headlines from reliable and diverse sources is essential to capture a broad spectrum of information relevant to the selected stocks. This diversity in sources helps mitigate biases and provides a more accurate representation of the market sentiment. Ensuring the reliability and diversity of news sources is critical to maintain the integrity and accuracy of the sentiment analysis.
- Vader Sentiment Analysis
VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis will be utilized to evaluate the sentiment of each daily news headline. VADER is particularly suited for analyzing social media and short text, making it ideal for headline analysis. The compound sentiment score (Vh) generated by VADER ranges from -1 (strong negative sentiment) to 1 (strong positive sentiment). For each day, the daily sentiment score (St) is calculated as the average of these compound scores, providing a single sentiment measure for the day's news. This approach leverages VADER's ability to interpret nuanced sentiment expressions and punctuation intensification, offering a holistic evaluation of the overall sentiment conveyed in the news headlines.
- Correlation Analysis
The correlation analysis involves acquiring historical daily stock prices for the selected NASDAQ stocks, including high, low, close, and open prices. The Pearson correlation coefficient (ρ) will be employed to quantify the linear relationship between the daily sentiment scores (St) and each stock price metric (high, low, close, open). The Pearson correlation coefficient provides a measure of the strength and direction of the relationship between two variables, in this case, sentiment scores and stock prices. By calculating ρ, we can determine how sentiment influences stock price movements and identify any significant correlations that may exist during the specified time period.
- Heatmap Generation
To facilitate the interpretation of the correlation analysis results, a heatmap will be generated to visualize the correlation matrix. A heatmap provides an intuitive graphical representation of the correlations between sentiment scores and stock prices, with color coding to indicate the strength and direction of the relationships. This visual tool makes it easier to identify patterns and insights, highlighting areas of strong positive or negative correlations. By using a heatmap, the analysis becomes more accessible and comprehensible, allowing for quick identification of key relationships and trends in the data.

## 🚀 About Me
I'm a full stack developer... 🧑‍💻

Hey, peeps! I'm the ultimate tech geek and Software Engineer in the making. Started coding back in 11th grade – yeah, that's right, way ahead of the curve. My first PC game? Cake Builder. It was the bomb, and if you haven't played it, you're missing out big time.

Fluent in Python, Java, and JavaScript – basically, I can talk to computers better than most people talk to each other. While you're struggling with basic code, I'm out here crafting digital masterpieces. Yeah, it's a talent not everyone has.

When I'm not flexing my coding skills or blowing up your feed with the latest tech hacks, you can find me sleeping under the sky, just chilling. No agenda, no stress, just me and the stars. Pure bliss. Sometimes, I'll even grace the football field with my presence, showing everyone how it's done.

So, follow along if you can keep up. If not, well, try harder. This tech prodigy isn't slowing down for anyone. ✌️


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://none-c16111.webflow.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/tanmaymandal13/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/iam10mayy)


