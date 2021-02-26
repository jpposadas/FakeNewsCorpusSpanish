# :newspaper: The Spanish Fake News Corpus
![GitHub](https://img.shields.io/github/license/jpposadas/FakeNewsCorpusSpanish)
![GitHub repo size](https://img.shields.io/github/repo-size/jpposadas/FakeNewsCorpusSpanish)
![GitHub last commit](https://img.shields.io/github/last-commit/jpposadas/FakeNewsCorpusSpanish)
![GitHub stars](https://img.shields.io/github/stars/jpposadas/FakeNewsCorpusSpanish)


## :loudspeaker: Call for Participation in Fake News Detection in Spanish Shared Task (FakeDeS) 2021
We invite the entire github community to participate in the second edition of the fake news detection task (FakeDeS). For more details and to register, visit the official event website https://sites.google.com/view/fakedes

### :calendar: Important dates
- March 1th 2021: training data available to participants
- April 19th 2021: test data available to participants
- April 30th 2021:  system results due to organizers
- May 15th 2021: assessment returned to participants 
- Jun 7th 2021: working notes submission
- June 21th 2021: working notes reviewed (peer-reviewed)
- June 28th 2021: camera ready papers due to the organizers
- September 2021: IberLEF@SEPLN 2021 Workshop
- October 2021: Presentation of results at a workshop in Mexico

## :page_facing_up: Corpus Description
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

## :pencil: How to cite
If you use the corpus please cite the following articles:

1) Posadas-Durán, J. P., Gómez-Adorno, H., Sidorov, G., & Escobar, J. J. M. (2019). Detection of fake news in a new corpus for the Spanish language. Journal of Intelligent & Fuzzy Systems, 36(5), 4869-4876.

2) Aragón, M. E., Jarquín, H., Gómez, M. M. Y., Escalante, H. J., Villaseñor-Pineda, L., Gómez-Adorno, H., ... & Posadas-Durán, J. P. (2020, September). Overview of mex-a3t at iberlef 2020: Fake news and aggressiveness analysis in mexican spanish. In Notebook Papers of 2nd SEPLN Workshop on Iberian Languages Evaluation Forum (IberLEF), Malaga, Spain.

>> The fake news corpus in Spanish was used for the **Fake News Detection Task** in the **MEX-A3T** competition at the IberLEF 2020 congress. The details of the competition can be viewed in the main page of the [competition](https://sites.google.com/view/mex-a3t/).

## Authors of the corpus
Juan Manuel Ramírez Cruz (ESIME Zacatenco - IPN), Silvia Úrsula Palacios Alvarado (ESIME Zacatenco - IPN), Karime Elena Franca Tapia (ESIME Zacatenco - IPN), Juan Pablo Francisco Posadas Durán (ESIME Zacatenco - IPN), Helena Montserrat Gómez Adorno (IIMAS - UNAM), Grigori Sidorov (CIC - IPN)

## Aknowledgments
The work was done with partial support of Red Temática de Tecnologías del Lenguaje,  CONACYT project 240844 and SIP-IPN projects 20181849 and 20171813
## License
[CC-BY-4.0](https://choosealicense.com/licenses/cc-by-4.0/).
