# An Teanga Sean: The Celtic Languages

![A flag representing the Celtic nations' six different flags](https://www.dropbox.com/pri/get/Dillinger/_images/hqdefault.jpg?_subject_uid=283917548&w=AAAD0DhoRodkZR7QJP8QRcQVvRT073HU6lJE_RY7qiRt_g)

In the study of European history, there are central and peripheral societies; the central societies lay claim to the Inheritance of Rome, or a progression of the flame of civilization from Cicero to the present day. The Celtic languages – Irish, Cornish, Welsh, Scots-Gaelic, Manx, and Breton – are languages of peripheral societies. These are not continental powerhouses like France or Germany, but small tribes of people on the British Isles. At least, that is the narrative told by the central societies, like the United Kingdom and France. Their legacy is one of oppression; whether it was Romans in antiquity, Vikings in the medieval period, or Norman Englishmen, the peoples of the Celtic languages have been oppressed and assaulted by foes for centuries. 

The Irish, with their monastic ecclesiastical orders and scriptoria brimming with the wisdom of the ancients, speak Gaelic, or Irish, as it is often called. This language has seen the hand of the English in action; the invading English tried to outlaw it, and when Ireland rose in resistance during the 19th and 20th centuries, Gaelic-speaking nationalists led the fight. 

Cornish, spoken mostly in academic interest in 21st century Cornwall in the south of England, died out in the 18th century, though there was a revival effort in the late 20th century. 

Welsh holds its standing in Wales as a governmentally recognized national language; Welsh citizens have the right to treat with the United Kingdom in Welsh. 

Scots-Gaelic, the language of the Celtic peoples in mostly Highland Scotland, bears subtle reminders of the common kinship of the Irish and the Scottish. 

Manx has little more than a well-attended fan club in the Isle of Man, one of the many small islands between Ireland and Britain. 

Breton died out in Brittany, France, though revival efforts are underway and children are increasingly attending bilingual schools where some instruction is in Breton. 

---

### Focus of my research

Rather than trying to compare data on all six Celtic languages, I decided to work with the two largest – Irish and Welsh – and one smaller one on which I have created a dataset of my own, Cornish. I was particularly interested in these languages because of the way they have been used to express, “Hey, we aren’t *all* English around here.” 

The Republic of Ireland has tried to push the Irish language as a key part of a national identity. Road signs have English and Irish on them, and any citizen of the Republic of Ireland has the right to treat with the Irish government in Irish. This movement began with the revolutionary nationalists of the 19th century and was realized by their 20th century descendants. However, even as the population of the Republic of Ireland moves toward pre-Famine level populations – and perhaps even a realization of the Good Friday Agreement’s allowances for reunification with Northern Ireland – the use of Irish is on the decline. I wanted to know a little bit more about that decline. 

Wales, on the other hand, does not have as bloody a recent history as the Republic of Ireland. Wales has been a part of the United Kingdom for centuries, with a devolved assembly and representatives in the Westminster Parliament. Their non-violent interactions with the English coupled with their Celtic identity are very intriguing.

Finally, Cornwall is a county of England, occupying the southwestern portion of the English coast. A Cornish identity has taken root there, and there is a movement to create a Cornish Assembly like the one in Wales. However, these efforts are slow to progress against the bureaucracy of the United Kingdom. I interned at the USF Special Collections department and got to interact with some primary source material on the Cornish literary revival, and I was able to create a small database from that interaction. It does not give a complete picture of the Cornish language revival of the 20th century, but it does serve as an interesting glimpse into what could be very stimulating future research. 

---

### What I am after
* Utilizing census data, I want to get a picture of how many people have some knowledge of these three Celtic languages. 
* Also, what kind of trends can be identified in their changes over time?
* How prevalent are non-English British languages in the United Kingdom?
* And finally, where do we see the most publications in the Cornish language revival?

---

### Methodology
Finding the data: Censuses
The United Kingdom and the Republic of Ireland perform censuses every ten years, and the Irish do another on the 6th year of every decade to commemorate the progress of the young nation since 1916. They both use services which host all the census data. There are two options for acquiring this data. The first is a bulk download; this method downloads a .csv file which can be several gigabytes worth of information. Further, this information is coded in a way that makes it difficult to read with the naked eye, and no program to accompany the data which could translate the codes into English. With that in mind, I acquired the data by the second route; the statistics websites allow the user to select data and build charts within the website and then export those data to a .csv file. As the census question change, it can take some interpretation to determine which census questions are polling for the same information. As such, census data from two distant years can be skewed by things like public education on the question, better phrasing, and more accurate digital recording. 

---

### Finding the data: building a dataset
The process of data entry from scratch becomes more complicated as one realizes which data is actually important; unfortunately, that realization can come several items into the list. Also, rare and interesting books are difficult to process without giving them a read. Consequently, the dataset I created from the Michael Krauss collection is only a small amount of the total collection of Cornish work, and a narrow glimpse of the available scholarship on the subject. It is nonetheless a good exercise to include this dataset.

---
### Data Manipulation
#### The census
The census data from the United Kingdom was so well-made within Excel that it could have been presented in its original format. The program which the UK uses utilized some functions of Excel to make the data very easy to manipulate and visualize. The main measurement I looked at was the main language of people in the United Kingdom. Obviously, I cared about the Celtic languages, so I quickly eliminated the dozens of rows dedicated to a dizzying array of international languages. The census even marked the type of area in which the census subjects lived; varying levels of urban and rural development made for a thought-provoking spread of the languages, but that was too far into the weeds. I eliminated all but the ‘total’, ‘rural total’, and ‘urban total’. This was just for England.

For Wales, I cared more about the proficiency of Welsh in the population. Again, the data was beautiful and accessible. I added a couple of lines to more clearly mark sums of important groupings of proficiency and eliminated the development markers.

The Republic of Ireland used a different service. Their service delivered the data in very simplistic terms and had to be organized a bit more efficiently into a compilation of data on one or two sheets. Their digitized census data was more widespread; I was able to acquire a population of speakers of Irish from 1861 to 1926. I used current census data from 2006 and 2011 to look at more recent trends.

#### The Michael Krauss Collection
I created an Excel document and began keying in publication information in a spreadsheet. After some patterns immerged, I was able to create drop down boxes and force a format on fields like year of publication. After collecting data on the books, which spanned all the Celtic languages and were in part written in English, I used OpenRefine to standardize spelling of author names and reorganize. I used the program to find everything Cornish in the collection, and I exported that out to a .csv. 

---

### What I found using Tableau
Since all my data were in formats I could understand but which Tableau could not necessarily figure out, I converted some data sets into simpler, reformatted versions specifically for Tableau. I was able to relatively easily create visualizations which demonstrated what I had hoped to demonstrate, and answer some questions.

---

### Visualizations

##### Celtic Languages in the United Kingdom
![Knowledge of Celtic Languages in England 2011](https://www.dropbox.com/pri/get/Dillinger/_images/Knowledge%20of%20Celtic%20Languages%20in%20England%202011.png?_subject_uid=283917548&w=AAC6Pj18HiIrIcuz1gvWSgUk5eIx2OKpMhxHwKSNRva30w)
Here only England is seen, and the numbers of people in each category of Celtic language numbers less than 10,000, some dramatically so. I would appear clearly here that Welsh is the predominant language aside from English in England, trailed by Irish, and then Cornish. It should be noted that due to the questionnaire, the Gaelic which is not otherwise specified may include people confused as to whether they speak Cornish, or Scots-Gaelic, or Irish, or even Breton. This is unclear, and a consequence of working with self-reported data.

---

#### Knowledge of Welsh in Wales

![Some Welsh vs No Welsh 2001](https://www.dropbox.com/pri/get/Dillinger/_images/2001newestKnowledge%20of%20Welsh%202001.png?_subject_uid=283917548&w=AABYdeTVxmCCjhUnP3uFzhWIjOyg7MD4JE_d1A4gy0u8aw)

![Some Welsh vs No Welsh 2011](https://www.dropbox.com/pri/get/Dillinger/_images/2011newestSome%20Welsh%20vs%20None%202011.png?_subject_uid=283917548&w=AACZ28xXRnVP8UVBu_0vnayk9Ef5UDNMNfJOOpbbMtuhLg)

Here are two pie charts which compare the proportion of people who have some skill in Welsh with the people in Wales who lack any skill. It is worth noting that this particular pie chart style allows us to see the nearly 25% portion of the total population which speaks, reads, or writes Welsh (or any combination thereof).

![Prevalence 2001](https://www.dropbox.com/pri/get/Dillinger/_images/Prevalence%20of%20Welsh%202001.png?_subject_uid=283917548&w=AADt10xmv8Rg0dQtoG9OAcfxOpABhWYAWNW5sTXqvGnTOw)

This chart explains basically the same information as the pies above, but it provides an opportunity to introduce the next graph. In 2001, the UK did not factor the concentration of Welsh between urban and rural settings. In 2011, we see more clearly the spread.

![Prevalence with Attention to Urban vs Rural Populations 2011](https://www.dropbox.com/pri/get/Dillinger/_images/Prevalence%20of%20Welsh%20Urban%20and%20Rural%202011.png?_subject_uid=283917548&w=AACf76uuIaMn-wUbHirUMBZ8WdjrgTdNYAC6-hoa4WiZcA)

In the left grouping of bars, the population without any skill in Welsh is displayed. Note that urban Welsh people dominate this scale; now compare it to the ones who have some skill in Welsh. There are nearly as many people skilled in Welsh as there are country folks who have no skill in Welsh. It would seem from this graph that urbanization may play a role in Anglicizing Welsh tongues.

---

#### Irish in Ireland
![Decline in Irish Speakers 1861-1926](https://www.dropbox.com/pri/get/Dillinger/_images/Decline%201861-1926.png?_subject_uid=283917548&w=AAD0erDHQorTAGTQK1zKewq6glOwV055ZqL5l4AVn3unGw)

In the period from 1861-1926, Ireland saw a surge of nationalism and the proliferation of Irish as a national tongue. However, the view from this graph does not seem to confirm this view. Let’s put it in context with a look at the overall population.

![Population Decline 1861-1926](https://www.dropbox.com/pri/get/Dillinger/_images/Population%20Decline%201861%20to%201926.png?_subject_uid=283917548&w=AAAEq0wiwb5m02wb09UZRR5jhA9DZ5S-Y4MmIto2JwJ60Q)

Here we see a steady decline as birth rates struggle to keep pace with crippling poverty and emigration to other nations. As seen below, the percentage of Irish speakers with relation to this overall decline remains relatively constant.

![Percentage of Speakers](https://www.dropbox.com/pri/get/Dillinger/_images/Irish%20Speakers%20as%20a%20Percentage%201861-1926.png?_subject_uid=283917548&w=AABScLNQCa845oIfxgq0LIRsn2ia9Wpg9btnnnDZvlg4tA)

![Irish speakers by Age Group 2006-2011](https://www.dropbox.com/pri/get/Dillinger/_images/Irish%20Speakers%20by%20Age%20Group%20in%20the%202006%20and%202011%20Census.png?_subject_uid=283917548&w=AABfhDTW5QC1GIROTyYvxYzsrvGprSC0V8MJpd-CmWDbMA)

Now to bring it into the modern term. In green are the numbers for 2006, ninety years after the Easter Uprising of 1916. Only five years later in 2011 (orange) we see a sharp increase in all but a certain age group: 15-34-year-old Irish people have not been visiting their grandmothers, it would seem. Or at least, they are insisting on English when they visit. It would be interesting to gain access to more information from the Republic of Ireland and see if this bubble exists in the 1990’s, and it will be interesting to see in twenty to thirty years if this trend holds. 

---

#### The Michael Krauss Collection and The Cornish Language Revival

![Number of Works on Cornish Published by Year](https://www.dropbox.com/pri/get/Dillinger/_images/Number%20of%20Works%20on%20Cornish%20Published%20by%20Year%20in%20MK%20Collection.png?_subject_uid=283917548&w=AABr5M7vCK5vsEpY7zl4n7CSZ4cLziYCly4Cjmii9ZI_CQ)

As for the Cornish dataset, I noticed a clear uptick in the 1970’s. This coincides with much of the efforts put forward by the Cornish people to see their ancient nation and language legitimized. It would certainly be interesting to utilize the rest of the collection to get an even better idea of the movement and identify more data points. With more data, the certainty with which we can infer trends increases, and as scholarship from this period is collected by archives as the scholars themselves retire, it would be immensely useful to see these kinds of collections digitized so we can ask bigger questions. 

---

### Conclusion
When conducting research, often every answer must be bought with one hundred more and new questions. This research proved no exception to that rule; where we saw a lack of urban engagement with Welsh language, could we demonstrate a disconnect with Welsh culture? Are the people of the mountains and coasts of Wales simply more *Welsh* than the city dwellers? Where we saw the Republic of Ireland bearing a language gap in the ‘millennial’ generation of people, could we infer a connection with digitization and globalization? On an internet that is largely monolingual, is it unsustainable to try and hold onto an old language like Irish, spoken by so few in the world? Will Celtic languages go the way of so many others and be casualties in the extinction-level disappearance of language in the world? And in the case of the Michael Krauss Collection on Cornish, how valuable can the digitization of these materials be? These questions are the best conclusion one could hope for; not an answer to end a project, but a prompt to begin many more. 

### Works Cited
* [“The Irish language.pdf.” 2017. Accessed May 5.](http://www.cso.ie/en/media/csoie/releasespublications/documents/population/2017/7._The_Irish_language.pdf)
* Ball, Martin J., and James Fife. 2002. The Celtic Languages. Routledge Language Family Descriptions. London: Routledge, 2002.
* [“Irish Speakers Aged 3 Years and Over 2011 - StatBank - Data and Statistics.” 2017. Accessed May 5.](http://www.cso.ie/px/pxeirestat/Statire/SelectVarVal/saveselections.asp)
* [“KS025 Welsh 2001- Nomis - Official Labour Market Statistics.” 2017. Accessed May 5.](https://www.nomisweb.co.uk/census/2001/KS025/view/2092957700?cols=measures)
* [“Percentage of Irish Speakers to Non-Irish Speakers between 1861 and 1926 by Province, CensusYear and Statistic - StatBank - Data and Statistics.” 2017. Accessed May 5.](http://www.cso.ie/px/pxeirestat/Statire/SelectVarVal/saveselections.asp)
* [“QS204EW (Main Language (Detailed)) - Nomis - Official Labour Market Statistics.” 2017. Accessed May 5.](https://www.nomisweb.co.uk/census/2011/qs204ew)
* [“QS207WA Welsh 2011 - Nomis - Official Labour Market Statistics.” 2017. Accessed May 5.](https://www.nomisweb.co.uk/census/2011/QS207WA/view/2092957700?rows=cell&cols=rural_urban)

