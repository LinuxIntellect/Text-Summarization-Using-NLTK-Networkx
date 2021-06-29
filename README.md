### Text-Summarization-Using-NLTK-Networkx

<h1>A Quick Introduction to Text Summarization in Machine Learning</h1></br>
<center><img src="https://github.com/AHAMMADMEJBAH/Text-Summarization-Using-NLTK-Networkx/blob/main/maxresdefault.jpg" alt="Text Summerization"></center>
Text summarization refers to the technique of shortening long pieces of text. The intention is to create a coherent and fluent summary having only the main points outlined in the document.</br>

<h3>Automatic text summarization is a common problem in machine learning and natural language processing (NLP).</h3></br>

Skyhoshi, who is a U.S.-based machine learning expert with 13 years of experience and currently teaches people his skills, says that “the technique has proved to be critical in quickly and accurately summarizing voluminous texts, something which could be expensive and time consuming if done without machines.”
Machine learning models are usually trained to understand documents and distill the useful information before outputting the required summarized texts.
<h3>What’s the need for text summarization?</h3></br>
Propelled by the modern technological innovations, data is to this century what oil was to the previous one. Today, our world is parachuted by the gathering and dissemination of huge amounts of data.</br>
In fact, the International Data Corporation (IDC) projects that the total amount of digital data circulating annually around the world would sprout from 4.4 zettabytes in 2013 to hit 180 zettabytes in 2025. That’s a lot of data!<br>
With such a big amount of data circulating in the digital space, there is need to develop machine learning algorithms that can automatically shorten longer texts and deliver accurate summaries that can fluently pass the intended messages.</br>
Furthermore, applying text summarization reduces reading time, accelerates the process of researching for information, and increases the amount of information that can fit in an area.</br>
<h3>What are the main approaches to automatic summarization?</h3>
There are two main types of how to summarize text in NLP:
<h3>Extraction-based summarization</h3></br>
The extractive text summarization technique involves pulling keyphrases from the source document and combining them to make a summary. The extraction is made according to the defined metric without making any changes to the texts.
<h4>Here is an example:</h4>
<b>Source text:</b></br>
Joseph and Mary rode on a donkey to attend the annual event in Jerusalem. In the city, Mary gave birth to a child named Jesus.</br>
<b>Extractive summary:</b></br>
Joseph and Mary attend event Jerusalem. Mary birth Jesus.</br>
As you can see above, the words in bold have been extracted and joined to create a summary — although sometimes the summary can be grammatically strange.
<h3><u>Abstraction-based summarization</u></h3></br>
The abstraction technique entails paraphrasing and shortening parts of the source document. When abstraction is applied for text summarization in deep learning problems, it can overcome the grammar inconsistencies of the extractive method.</br>
The abstractive text summarization algorithms create new phrases and sentences that relay the most useful information from the original text — just like humans do.
Therefore, abstraction performs better than extraction. However, the text summarization algorithms required to do abstraction are more difficult to develop; that’s why the use of extraction is still popular.
<b>Here is an example:</b></br>
Abstractive summary: Joseph and Mary came to Jerusalem where Jesus was born.
How does a text summarization algorithm work?
Usually, text summarization in NLP is treated as a supervised machine learning problem (where future outcomes are predicted based on provided data).
<h1>Typically, here is how using the extraction-based approach to summarize texts can work:</h1>

<ol type = "1">
  <li>Introduce a method to extract the merited keyphrases from the source document. For example, you can use part-of-speech tagging, words sequences, or other linguistic patterns to identify the keyphrases.</li>
  <li>Gather text documents with positively-labeled keyphrases. The keyphrases should be compatible to the stipulated extraction technique. To increase accuracy, you can also create negatively-labeled keyphrases.</li>
  <li>Train a binary machine learning classifier to make the text summarization. Some of the features you can use include:
    <ol type = "1">
      <li>Length of the keyphrase</li>
      <li>Frequency of the keyphrase</li>
      <li>The most recurring word in the keyphrase</li>
      <li>Number of characters in the keyphrase</li>
      </ol>
    
   <li>Finally, in the test phrase, create all the keyphrase words and sentences and carry out classification for them.<li>
  
<h4>Summary</h4></br>
Text summarization is an interesting machine learning field that is increasingly gaining traction. As research in this area continues, we can expect to see breakthroughs that will assist in fluently and accurately shortening long text documents. [<a href="https://towardsdatascience.com/a-quick-introduction-to-text-summarization-in-machine-learning-3d27ccf18a9f" Source </a>]
