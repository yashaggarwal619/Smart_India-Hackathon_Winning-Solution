# Smart_India-Hackathon_Winning-Solution
We have to create a model that takes in a word document explaining a problem and identifies the root cause of the problem.
This will save the factory staff to go through all the documents to find the root causes. We will first need to collect data 
having problems and root causes associated with it, specific to the factory. Then we will pre-process our doc files which 
would include cleaning the text using NLTK functions, removing stop-words and shifting all the words to their root words. 
After the text is cleaned, we will use the word embedding to vectorize the documents and retrieve relevant words out of our corpus. 
Subsequently, a supervised learning technique will be used to map the documents to the root causes using an __Attentive LSTMs__ model 
which will take embedded words as input and give the root causes as output. Since there are different types of attention mechanisms, 
we will experiment with them to see which gives the best results. Some of the examples are __Gaussian, Multi-hop and Hierarchical attention__. 
After the root causes of the problems are found, the results will be updated on the website. Description of the website: 
We will make a dashboard that will have all the root causes listed in decreasing order of their frequencies, with these frequencies 
mentioned alongside. On clicking the root cause, the list of all the instances of that root cause will be shown. 
We will develop a portal where the factory staff can upload the word files containing problems. An authentication system will also 
be devised so that only authorized personnel can access the information.


### Note:
__Can't share the solution publically due to nda signed with the organisation.Only the presentation can be shown.__
