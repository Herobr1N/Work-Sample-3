# Corporate intranet discussion forums Project using Keras, Tensorflow, NLTK and Scikit-Learn

Corporate intranet discussion forums are a valuable tool for software development companies.  
The discussion forums enable employees to facilitate content creation, customer support, community-based support, project management, project collaboration, 
and knowledge base creation. We used Stack Overflow as a proxy for a corporate intranet forum because we could not gain access to a private company’s proprietary intranet forum.  
Stack Overflow data can be scraped from the internet, has a question and answer section, and tags for questions categorization.  
Private intranet forums would be structurally different with far fewer users, but Stack Overflow is a suitable proxy to compare a question content and tagging system.  
Stack Overflow’s robust tagging system predicts tags based on inputs and user history. 
For the purposes of our analysis we identify a use case where it is necessary for the tagging system to predict tags based on the question content.
Sorting through the categories of these questions both internally and externally is time consuming and AI categorization based on tags would be a time saver for askers and answers.
In this analysis we will test Fully Connected Feed Forward (FCFN) networks and identify the network with the highest accuracy.
