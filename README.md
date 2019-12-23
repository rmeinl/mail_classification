# mail_classification

Modern Enterprises have to deal with constant flows of information and customer en- quiries from all different sources such as Email, Chat and Call.
Recently, automated solutions such as Chatbots have become a popular way to deal with the most frequently asked questions which saved a lot of resources and manual labor. These solutions have been able to take over many tasks from classification, to labelling and even fully-automated answering of the enquiry.
Most of these systems are considered somewhat intelligent as they draw their knowl- edge from a Knowledge Base with which they interact through a set of predefined rules. Through Pattern Matching using Regular Expressions, information such as the cus- tomers intent can be extracted and used for the task of classifying the request into a set of categories.
The problem is that it takes a long time to properly implement and refine these rules. They also have a fair amount of problems when dealing with unseen requests.
The goal is to develop a solution that can learn from a large corpus of data (e.g. email conversations) about how to handle customer requests that are often encountered. Such a solution consists of two parts:
The first part is the automated classification of incoming requests into categories. The second part then looks at the request, knowing the intent based on the category and tries to generate an answer based on the what it learned from the data it has seen.
At this point in time the first part is accomplished by the Pattern Matching approach which matches a request to an answer from the knowledge base. The goal of this work is to propose a Deep Learning approach for this first part, which will lay the foundation for further research and can be a first estimator for the feasibility of the whole 2-part project.
In order to evaluate our approach, a corpus of about 150k emails, which have been pre- labelled and divided into 28 categories, was extracted from novominds product ‘novom- ind iMAIL’.
