# :newspaper: The Spanish Fake News Corpus
![GitHub](https://img.shields.io/github/license/jpposadas/FakeNewsCorpusSpanish)
![GitHub repo size](https://img.shields.io/github/repo-size/jpposadas/FakeNewsCorpusSpanish)
![GitHub last commit](https://img.shields.io/github/last-commit/jpposadas/FakeNewsCorpusSpanish)
![GitHub stars](https://img.shields.io/github/stars/jpposadas/FakeNewsCorpusSpanish)


## :loudspeaker: The Spanish Fake News Corpus Version 2.0 [[ FakeDeS Task @ Iberlef 2021 ]] :metal:
 
### :page_facing_up: Corpus Description
The Spanish Fake News Corpus Version 2.0 contains pairs of fake and true publications about different events (all of them were written in Spanish) that were collected from **November 2020 to March 2021**. Different sources from the web were used to gather the information, but mainly of two types: 1) newspapers and media companies websites, and 2) fact-cheking websites. Most of the revised fact-checking sites used follow the recommendations of the International [Fact-Checking Network (IFCN)](https://ifcncodeofprinciples.poynter.org/) that seeks to promote good practice in fact-checking.
  
The assembled corpus has **572 instances** and the instances were labeled using two classes, true or fake. The test corpus is balanced with respect to these two classes. To compile the true-fake news pair of the test corpus, the following guidelines were followed:
- A fake news is added to the corpus if any of the selected fact-checking sites determines it.
- Given a fake news, its true news counterpart is added if there is evidence that it has been published in a reliable site (established newspaper site or media site).

The topics covered in the corpus are: **Science, Sport, Politics, Society, COVID-19, Environment, and International**.The corpus includes mostly news articles, however, on this occasion social media posts were also included in the category of fake news. Exactly 90 posts were included as fake news (15.73\% of the total). This posts were recovered mainly from Facebook and WhatsApp. The use of the various fact-checking sites involved consulting pages from different countries that offer content in Spanish in addition to Mexico, so different variants of Spanish are included in the test corpus. These sites included countries like Argentina, Bolivia, Chile, Colombia, Costa Rica, Ecuador, Spain, United States, France, Peru, Uruguay, England and Venezuela.

The corpus is concentrated in the file test.xlsx. The meaning of the columns is described next:
<ul>
  <li><b>Id</b>: assign an identifier to each instance.</li>
  <li><b>Category</b>: indicates the category of the news (true or fake).</li>
  <li><b>Topic</b>: indicates the topic related to the news.</li>
  <li><b>Source</b>: indicates the name of the source.</li>
  <li><b>Headline</b>: contains the headline of the news.</li>
  <li><b>Text</b>: contains the raw text of the news.</li>
  <li><b>Link</b>: contains the URL of the source.</li>
</ul>

Note that some instances have an empty header intentionally because the source omitted it.

### :pencil: How to cite
If you use the corpus please cite the following articles:

1) Gómez-Adorno, H., Posadas-Durán, J. P., Enguix, G. B., & Capetillo, C. P. (2021). Overview of FakeDeS at IberLEF 2021: Fake News Detection in Spanish Shared Task. Procesamiento del Lenguaje Natural, 67, 223-231.
2) Aragón, M. E., Jarquín, H., Gómez, M. M. Y., Escalante, H. J., Villaseñor-Pineda, L., Gómez-Adorno, H., ... & Posadas-Durán, J. P. (2020, September). Overview of mex-a3t at iberlef 2020: Fake news and aggressiveness analysis in mexican spanish. In Notebook Papers of 2nd SEPLN Workshop on Iberian Languages Evaluation Forum (IberLEF), Malaga, Spain.
3) Posadas-Durán, J. P., Gómez-Adorno, H., Sidorov, G., & Escobar, J. J. M. (2019). Detection of fake news in a new corpus for the Spanish language. Journal of Intelligent & Fuzzy Systems, 36(5), 4869-4876.


### FakeDeS @ IberLef 2021 
>> The corpus was used for the **Fake News Detection in Spanish (FakeDeS)** shared task at the IberLEF 2021 congress. The details of the competition can be viewed in the main page of the [competition](https://sites.google.com/view/fakedes).

### Organizers
- Helena Montserrat Gómez Adorno (IIMAS - UNAM)
- Juan Pablo Francisco Posadas Durán (ESIME Zacatenco - IPN)
- Gemma Bel Enguix (IINGEN - UNAM)
- Claudia Porto Capetillo (IIMAS - UNAM)

## :books: The Spanish Fake News Corpus Version 1.0 (@ MEXLEF 20)
### :page_facing_up: Corpus Description
<p style='text-align: justify;'>
The Spanish Fake News Corpus contains a collection of news compiled from several resources on the Web: established newspapers websites, media companies’ websites, special websites dedicated to validating fake news and websites designated by different journalists as sites that regularly publish fake news. The news were collected from **January to July of 2018** and all of them were written in Spanish. The process of tagging the corpus was manually performed and the method followed is described in the paper.
aspects were considered: 1) news were tagged as true if there was evidence that it has been published in reliable sites, i.e., established newspaper websites or renowned journalists websites; 2) news were tagged as fake if there were news from reliable sites or specialized website in detection of deceptive content for example VerificadoMX (https://verificado.mx)  that contradicts it or no other evidence was found about the news besides the source; 3) the correlation between the news was kept by collecting the true-fake news pair of an event; 4) we tried to trace the source of the news.
</p>
The corpus contains 971 news divided into 491 real news and 480 fake news. The corpus covers news from 9 different topics: **Science, Sport, Economy, Education, Entertainment, Politics, Health, Security, and Society**. The corpus was split into train and test sets, using around the 70\% of the corpus for train and the rest for test. We performed a hierarchical distribution of the corpus, i.e., all the categories keep the 70\%-30\% ratio.

The corpus is concentrated in the files train.xlsx and development.xlsx. The meaning of the columns is described next:
<ul>
  <li><b>Id</b>: assign an identifier to each instance.</li>
  <li><b>Category</b>: indicates the category of the news (true or fake).</li>
  <li><b>Topic</b>: indicates the topic related to the news.</li>
  <li><b>Source</b>: indicates the name of the source.</li>
  <li><b>Headline</b>: contains the headline of the news.</li>
  <li><b>Text</b>: contains the raw text of the news.</li>
  <li><b>Link</b>: contains the URL of the source.</li>
</ul>

### :pencil: How to cite
If you use the corpus please cite the following articles:

1) Gómez-Adorno, H., Posadas-Durán, J. P., Enguix, G. B., & Capetillo, C. P. (2021). Overview of FakeDeS at IberLEF 2021: Fake News Detection in Spanish Shared Task. Procesamiento del Lenguaje Natural, 67, 223-231.
2) Aragón, M. E., Jarquín, H., Gómez, M. M. Y., Escalante, H. J., Villaseñor-Pineda, L., Gómez-Adorno, H., ... & Posadas-Durán, J. P. (2020, September). Overview of mex-a3t at iberlef 2020: Fake news and aggressiveness analysis in mexican spanish. In Notebook Papers of 2nd SEPLN Workshop on Iberian Languages Evaluation Forum (IberLEF), Malaga, Spain.
3) Posadas-Durán, J. P., Gómez-Adorno, H., Sidorov, G., & Escobar, J. J. M. (2019). Detection of fake news in a new corpus for the Spanish language. Journal of Intelligent & Fuzzy Systems, 36(5), 4869-4876.

### Fake News Detection Task at MEX-A3T 
>> The Fake News Corpus in Spanish was used for the **Fake News Detection Task** in the **MEX-A3T** competition at the IberLEF 2020 congress. The details of the competition can be viewed in the main page of the [competition](https://sites.google.com/view/mex-a3t/).

### Authors of the corpus
Juan Manuel Ramírez Cruz (ESIME Zacatenco - IPN), Silvia Úrsula Palacios Alvarado (ESIME Zacatenco - IPN), Karime Elena Franca Tapia (ESIME Zacatenco - IPN), Juan Pablo Francisco Posadas Durán (ESIME Zacatenco - IPN), Helena Montserrat Gómez Adorno (IIMAS - UNAM), Grigori Sidorov (CIC - IPN)

### Aknowledgments
The work was done with partial support of Red Temática de Tecnologías del Lenguaje,  CONACYT project 240844 and SIP-IPN projects 20181849 and 20171813
## License
[CC-BY-4.0](https://choosealicense.com/licenses/cc-by-4.0/).
