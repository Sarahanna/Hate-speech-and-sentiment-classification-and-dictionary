#READ ME

In the context of the DFG Financed project Tubework, we created a hate speech and sentiment dataset. For more information you can visit our website here: https://www.uni-potsdam.de/de/sozialstrukturanalyse/index/forschung/tubework
  

# Ger-Eng-YouTube-Comments

One issue of classifying hate speech comments is to find enough, of a big variety in the comments you are scraping. We opt for filtering half of the comments in our dataset by using a hate speech dictionary as described below. 

The material includes: 
1.) A hate speech dictionary of German and English YouTube comments
2.) A data set of 7268 German and English classified YouTube comments for sentiment and hate speech

## 1.) Hate Speech Dictionary

Existing dictionaries often cover a limited range of topics and may not be available in both German and English. Additionally, internet language evolves rapidly and is context-sensitive. To address these issues, we aimed to create a comprehensive dictionary by gathering terms from diverse sources. Our goal was to achieve a balanced representation of topics such as Sexism, LGBTIA+, Race/Ethnicity, Religion, political opinion and Class. The dictionary was developed in several stages: incorporating new terms, testing their relevance and effectiveness to capture hate speech, their meaning was reflected and in a last step it was decided whether to retain or remove them based on their appropriateness. We also focused on including region-specific contexts of hate speech, such as terms used against groups like Turkish people in Germany. We included previously existing dictionaries as well as information from NGOs, but also internet sources like Wikipedia, as seen below.

##  2.) Dataset YouTube Comments

These comments were drawn from a sample of 5000 content creators from German-speaking countries. Half of the comments were randomly selected, and the other half was filtered using the custom hate speech dictionary to capture a larger amount of hate speech. These comments have been classified by students from the University of Potsdam, which had received an extensive introduction to the annotation process. Every comment has a double coverage and if the coders disagreed, an expert from the project decided on the classification to achieve majority decisions. The annotation guidelines can be found here.

The file *ger-eng-youtube-comments* is structured as follows:
- sentiment: negative, neutral, positive
- hate_speech: none, off, hate
- language: emoticon, English, German
- content: raw YouTube comment

**Hate speech** is defined as: “Any behaviour that incites violence or hatred against (i) individuals or (ii) a group of individuals or a member defined by reference to race, colour, religion, descent or national or ethnic origin,  gender, sexual orientation, political opinion or makes false allegations.”

**Offensive language**: 
On the other hand, we defined offensive language as “Comments which are insulting, toxic or hostile but are not exclusively directed towards protected groups.” 

Examples: 
“You are an Idiot” Offensive
“I despise refugees” Hate Speech
“I hate this” None

##  Sources 
The following sources were used to create the hate speech and offensive language dictionary. The basis was the hate speech dictionary Hurtlex which was available in both German and English and featured both offensive terms and hate speech:
https://github.com/valeriobasile/hurtlex 

Further terms were included from:
    - https://hatebase.org/
 - https://www.noswearing.com/dictionary/x
 - https://weaponizedword.org/lexicons 
 - https://github.com/uds-lsv/lexicon-of-abusive-words 
 - https://github.com/bgmartins/hate-speech-lexicons

Topic-specific terms:
- Right-wing terms:https://de.wikipedia.org/wiki/Rechtsextreme_Symbole_und_Zeichen; https://www.belltower.news/rechtsextreme-sprachcodes-31230/; https://www.belltower.news/rechtsextreme-sprachcodes-31230/; https://www.bpb.de/themen/rechtsextremismus/dossier-rechtsextremismus/500822/zahlencodes/
  - Digital platform terms: https://www.belltower.news/tiktok-und-algospeak-wie-gartenzwerge-die-grenzen-des-sagbaren-verschieben-154217/
  -https://lifehacker.com/all-the-social-media-algospeak-you-don-t-understand-1849841027

- Anti-queer terms: https://www.belltower.news/symbole-und-codes-queerfeindliche-narrative-und-dogwhistles-134233/
-https://rationalwiki.org/wiki/TERF_glossary#
-https://en.wikipedia.org/wiki/Category:LGBT-related_slurs 
https://en.wikipedia.org/wiki/Category:Homophobic_slurs 
https://itg.nls.uk/wiki/LGBTQIA%2B_Slurs_and_Slang 

- Antisemitic terms: https://www.amadeu-antonio-stiftung.de/antisemitismus/deconstruct-antisemitism-2/
-https://en.wikipedia.org/wiki/Antisemitic_trope 
-https://www.jewishtimes.com/the-etymology-of-hate-jewish-slurs/ 

- Racism:https://en.wikipedia.org/wiki/List_of_ethnic_slurs
-https://www.vielfalt-mediathek.de/wp-content/uploads/2020/12/jugendschutz.net_report_antiziganismus_online_vielfalt_mediathek.pdf
-https://www.buergerundstaat.de/1_2_18/antiziganismus.pdf
- Political topics/opinion: https://kompetenznetzwerk-hass-im-netz.de/wp-content/uploads/2023/09/Report_Hass_gegen_junge_Klimaaktivist_innen.pdf
https://en.wikipedia.org/wiki/List_of_political_slogans
- Swearwords: https://www.freewebheaders.com/german-swear-words-list-and-bad-words-free-download/
https://www.freewebheaders.com/youtube-blacklist-words-free-and-youtube-comment-moderation/
https://vidalingua.com/englische-schimpfworter
- Class-related terms: https://en.wikipedia.org/wiki/Category:Class-related_slurs
https://www.merriam-webster.com/wordplay/10-words-for-the-elitists-in-your-life
https://www.reddit.com/r/dndnext/comments/dbj5ut/insults_for_wealthy_characters/
Religious Slurs: https://en.wikipedia.org/wiki/List_of_religious_slurs 



further material:https://hatespeechdata.com/
https://www.amadeu-antonio-stiftung.de/digitale-zivilgesellschaft/was-ist-hate-speech/ 
https://www.urbandictionary.com/ 





