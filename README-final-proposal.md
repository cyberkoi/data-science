## Capstone Project Final Idea

### What is the problem you want to solve?
What constitutes a helpful review for electronic products?

Sort into 3 review groups:
- Helpful (>=8), an unhelpful review (<=4), and a review in-between (5-7)

Plot (x / y):
- Avg review length (n) / helpfulness (0-10)
- Avg review rating (0-5) / helpfulness (0-10)

and how have characteristics of helpfulness (helpful, unhelpful, in-between) changed over time?

Plot (x / y): 
- Avg review length (n) of reviews in review group / time (1995-2013)
- Avg review rating (0-5) of reviews in review group / time (1995-2013)


### Who is your client and why do they care about this problem? 
(In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?)

- Multiple studies have found that consumers are increasingly reliant upon online reviews when making decisions regarding purchase. According to [Entrepreneur](http://www.entrepreneur.com/article/253361), industry experts expect further increase in coming years.
- Amazon has recognised that review helpfulness is a good indicator for bringing certain reviews up to the 'Top'. This has shifted away from chronologically sorting reviews according to 'Recent' posts or 'Highest Ratings'. 
- By giving greater weight to "legitimate" reviews, the product will likely be given a more accurate picture, as opposed to fake or unhelpful reviews.
- Moreover, improved user experience by minimising discovery time for best reviews.
- Reviews are a source of valuable market intelligence. Customers rely on it, and merchants use feedback to make strategic placement decisions.


This project will play a role in understanding how to overcome the bias for older reviews. Older reviews have more exposure and are deemed more helpful, as such newer reviews might not be given much of a chance.


### What data are you going to use for this? How will you acquire this data?

- J. McAuley and J. Leskovec. Hidden factors and hidden topics: understanding rating dimensions with review text. RecSys, 2013.
- Web data: [https://snap.stanford.edu/data/web-Amazon.html](https://snap.stanford.edu/data/web-Amazon.html)

#### Data files to be used:

- **Electronic products**: Electronics.txt.gz	- Electronics product reviews (1,241,778 reviews)
- **Possible product duplicates**: possible_dupes.txt.gz	- List of possible duplicate products

#### Data variables used:

- product/productId: asin, e.g. amazon.com/dp/B00006HAXW
- review/helpfulness: fraction of users who found the review helpful
- review/score: rating of the product
- review/time: time of the review (unix time)
- review/text: text of the review


### In brief, outline your approach to solving this problem 
(know that this might change later)

- Data Cleaning and Wrangling
- Exploratory Data Analysis: Descriptive statistics and visualisations
- Data story and further analysis
- Lastly, final result covering requirements listed in the deliverables below

(Learn more about NLP. Learn how to R and find words that seemingly indicate helpfulness and words that indicate uselessness)

### What are your deliverables? 
1. **Code** for the project documented on github.
2. **A final paper** explaining the problem, approach and findings (+ ideas for further research, and three concrete recommendations for client on how to use my findings).
3. **A slide deck** for Springboard’s technical blog. 


*Note: All code and further documentation you write will be added to this repository.*
*Once your mentor has approved your proposal, please share the github repository URL on the community and ask for feedback*
