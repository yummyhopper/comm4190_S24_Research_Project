# Automated Email Marketing Using LLMs

In this project I use AI to generate highly personalized email marketing messages for a host of sample customers. The program integrates with a test Shopify development store and Klaviyo an email marketing campaign management software to incorporate real-time customer data to the program. I then add several variable attributes to the customer data such a CLV, up-sales propensity, and recommended incentive. I did this randomly, but any of these attributes could be projects in themselves. Next, I created a function to scrape all this data from Klaviyo and deliver it in a python dictionary from which I could pull these variables into my LangChain prompt. Finally, I was able to integrate unique customer data to generate 14 highly personalized emails for each sample customer. 

### The Contents of This Repo

- Blogs: Contains four blog posts outlining my journey from beginning to end in this project. Go here if you're most interested in my thought process and direction throughout the project
- Essay: Contains a mini white paper summarizing the opportunities for this sort of LLM use case and analyzing how this might be integrated. Go here if your most interested in the theoretical propositions of this project and a consideration of the scope of the opportunity
- Project: Contains the final simplified Python code used in this project. If you're most interested in a python template or evaluating my programming skills this is the one for you.
