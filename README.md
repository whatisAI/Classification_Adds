# Classification_Adds
Job add classification

In this notebook, I am classifying job postings from Indeed.com.uk.

The structure is as follows :


1. Create a corpus from a number of job postings.
    - This implies scraping the web. For this I used the notebook by https://jessesw.com/Data-Science-Skills/  , which uses the package BeautifulSoup.
       
2. Create bag-of-word features using Tf-idf. I have used 1,2 and 3-gram bag of words. This is done using TfidfVectorizer from sklearn.feature_extraction.text

3. Perform an un-supervised classification of the job-postings with kmeans++ from sklearn.cluster
