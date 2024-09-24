# social-listening-system
A social listening system developed using aspect-based sentiment analysis.

ABSA is a more advanced and specific form of SA. While SA aims to determine the overall polarity (positive, negative, or neutral) of a given text, ABSA goes beyond this by analyzing the sentiment towards specific aspects or features of the product or service being discussed.

ABSA provides a more granular and detailed view of the sentiment expressed in the text. This information can be very valuable for businesses, as it can help them understand what specific aspects of their products or services are being praised or criticized by customers. This knowledge can be used to improve the quality of the product or service, address customer concerns, and ultimately increase customer satisfaction and loyalty.

To parse the reviews posted by various customers, natural language processing techniques need to be applied. Review data can be collected from e-commerce websites like Amazon, Flipkart or from social media websites like Twitter.

Even though Bi-LSTM can be used to perform ABSA, it is not always guaranteed that every review extracted will contain information in the same format and same aspects.

The proposed model parses all reviews related to the given mobile phone model and generates a report as illustrated. Based on the number of positive and negative reviews, the user is advised whether or not to buy the product. Splitting the reviews into various aspects helps customers as well as business owners to make informed choices.
