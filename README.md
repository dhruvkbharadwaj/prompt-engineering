# prompt-engineering
1. Problem Statement: Customer Query Classification Using Prompt Engineering
An e-commerce company receives numerous customer queries related to orders,
deliveries, payments, refunds, cancellations, and product defects. Your task is to design
an effective prompt that classifies each customer query into the appropriate predefined
category.
Input: A customer query in natural language.
Output: A single word representing the category of the query.
Categories:
• Delivery
• Shipping
• Refund
• Payment
• Cancellation
• Defect
• Return
• Account
• Unknown
Examples:

Input Query Expected Output

My order has not arrived yet. Delivery
My package is stuck in transit. Shipping
I haven't received my money back. Refund
Money was deducted twice from my account. Payment
I want to cancel my order. Cancellation
The product I received is broken. Defect
I want to send this product back. Return
I cannot log in to my account. Account
What is the capital of India? Unknown

Constraint: The output must contain exactly one category word, without explanations,
punctuation, or additional text.

2. Problem Statement: Sentiment Analysis
An online shopping company wants to analyze customer reviews automatically to
understand customer satisfaction. Your task is to design a prompt that identifies the
sentiment expressed in a customer review.
Classify each review into one of three categories based on the customer's overall
sentiment.
Input: A customer review in natural language.
Output: A single word representing the sentiment.
Allowed Outputs:
• Positive
• Negative
• Neutral

Examples:
Input Review Expected Output
The product is excellent, and I love its quality. Positive
The delivery was late, and the product was damaged. Negative
The product arrived yesterday. Neutral
The customer support team was extremely helpful. Positive
The product is not worth the money. Negative
The package contained two items. Neutral
The phone is good, but the battery life is terrible. Negative

Constraint: The output must contain exactly one word: Positive, Negative, or Neutral.
Do not provide explanations or additional text.
