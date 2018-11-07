# FakeNewsCorpusSpanish

The Spanish Fake News Corpus contains a collection of news compiled from several resources on the Web: established newspapers websites, media companies’ websites, special websites dedicated to validating fake news and websites designated by different journalists as sites that regularly publish fake news. The news were collected from January to July of 2018 and all of them were written in Spanish.
The process of tagging the corpus was manually performed and the method followed is described in the paper.
aspects were considered: 1) news were tagged as true if there was evidence that it has been published in reliable sites, i.e., established newspaper websites or renowned journalists websites; 2) news were tagged as fake if there were news from reliable sites or specialized website in detection of deceptive content for example VerificadoMX (https://verificado.mx)  that contradicts it or no other evidence was found about the news besides the source; 3) the correlation between the news was kept by collecting the true-fake news pair of an event; 4) we tried to find the source of the news.

The corpus contains 971 news divided into 491 real news and 480 fake news. The corpus covers news from 9 different topics: Science, Sport, Economy, Education, Entertainment, Politics, Health, Security, and Society. The corpus was split into train and test sets, using around the 70\% of the corpus for train and the rest for test. We performed a hierarchical distribution of the corpus, i.e., all the categories keep the 70\%-30\% ratio.

The corpus is concentrated in the files train.xlsx and test.xlsx. The meaning of the columns is described next:
<ul>
  <li><b>Category</b>: indicates the category of the news (true or fake).</li>
  <li><b>Topic</b>: indicates the topic related to the news.</li>
  <li><b>Source</b>: indicates the name of the source.</li>
  <li><b>Headline</b>: contains the headline of the news.</li>
  <li><b>Text</b>: contains the raw text of the news.</li>
  <li><b>Link</b>: contains the URL of the source.</li>
</ul>

If you use the corpus please cite the following article:

Posadas-Durán, J., Gómez-Adorno, H., Sidorov, G., Moreno, J. (2018). Detection of Fake News in a New Corpus for the Spanish Language. Journal of Intelligent & Fuzzy Systems, In Press.

<h2>Authors of the corpus</h2>
Juan Manuel Ramírez Cruz (ESIME Zacatenco - IPN), Silvia Úrsula Palacios Alvarado (ESIME Zacatenco - IPN), Karime Elena Franca Tapia (ESIME Zacatenco - IPN), Juan Pablo Francisco Posadas Durán (ESIME Zacatenco - IPN), Helena Montserrat Gómez Adorno (IIMAS - UNAM), Dr. Grigori Sidorov (CIC - IPN)

<h2>Aknowledgments</h2>
The work was done with partial support of Red Temática de Tecnologías del Lenguaje,  CONACYT project 240844 and SIP-IPN projects 20181849 and 20171813
