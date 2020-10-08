This is a research project on remote learning in the context of the COVID-19 pandemic.
A survey on experiences of remote learning was sent out in May 2020 by a group of researchers at Minerva Schools at KGI, and there were more than 10,000 responses, approximately half of which were from undergraduate students.
In this study, the focus was undergradute students' experiences with remote learning.

The repository has 6 Python notebooks:
- Quantitative_Online_Education_Analysis: I looked into factors that contributed to better remote learning experiences characterized by level of enjoyment, motivation, satisfaction, engagement, distraction, active participation.
Those factors could be primary mode of learning, teaching methods used in class, teaching methods used outside of class, etc. I used Mann-Whitney-U test to make pairwise comparisons among different groups.
- IBM_tone_analyzer and Tone_synthesis: I used IBM tone analyzer to look into the tones of the responses to the open-ended questions. These questions include:
+ Why do you prefer in person or remote classes?
+ Why do you prefer live classes, recorded lessons, uploaded materials, discussion forums?
+ What changes would you make to your current remote learning experiences?
+ What changes would you make to your previous learning experiences?
- PageRank: I used Page Rank algorithm to rank the main themes of the responses to the open-ended questions above.
- Wordcloud_V2: Word clouds of the responses
- TopicModellingLDA: Topic modeling is one of the most common ways to extract the main topics/themes of similar documents. Together with Jacob Puthipiroj, I used Latent Dirichlet Allocation to get the main themes of the responses.
