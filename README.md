# Myers-Briggs-Personalitity-Test
This is a school project and won't be posted publically. This project aims to mimic the myers-briggs personality test as well as other personality tests to see if you're similar in personality to a celebrity or fantasy character. Depending on user input, it can put you through the standard "lite" version of the myers briggs personality test, or tell you how similar you are to a celebrity or fantasy character. The way it works is through a scoring system for each attribute in OCEAN. (O is for Openness; C is for Conscientiousness; E is for Extraversion; A is for Agreeableness; N is for Neuroticism). A question has a fixed factor of 1 or -1 or 0 for every attribute. The majority of questions have two attributes max that it can affect depending on the user input. The user has their own score for each attribute, and they are all initalized to 0. The user has 5 answers to however many questions they want: strongly agree, agree, neutral, disagree, strongly disagree. Each of these answers has a weight to it, so if a question had a +1 in O and a -1 in C and 0 in everything else, that number would be multiplied by their answer and added on to the user's score. Then based on the score, we compare that to fixed data and find the delta to see which is the most similar to either a personality type, celebrity or fantasy character. 
