# Project Title

DSC160 Data Science and the Arts - Midterm Project Repository - Spring 2020

Project Team Members: 
- Nicholas Kho, nikho@ucsd.edu
- Brian Qian, brqian@ucsd.edu
- Emma Logomasini, elogomas@ucsd.edu
- Siqi Huang, name4@ucsd.edu


## Abstract

(10 points) 

The Korean music industry is often seen as a bright and fresh representation of East-Asian creativity that has captured the world’s attention. In this project, we will be taking a look at numerous decades of popular music in Korea from the 1910s to the 2010s to understand the connection between distinctive musical styles and major political events that coincide with them. Part of what makes this possible analysis intriguing is that Korea has been under the cultural influence of two major powers in the last century in addition to dealing with oppressive regimes. Our goal is to try to measure the influence of these events in the difference of genres. Our research question is that do we see similar features in time periods that dealt with similar historical issues, in this case, political repression or economic growth? Our hypothesis is that we will see similarities in periods of great political conflict, particularly that of Japanese Occupation and the 1970s. To further cognize the influence of political changes, we will be extracting information in forms of features such as Fourier Transforms, MFCCs, temporal, and spectral statistics on a dataset of representative music of each major political era in recent Korean history. Thus we will be able to further attribute certain characteristics towards the political and cultural events, whether positive or negative, that occured within the same timeframe. 
As for the technical process, we will be utilizing jupyterhub and numerous libraries such as Seaborn, matplotlib, and LibROSA to extract and display the features we will be taking into consideration. Our results will be formatted among graphs and charts to give a visual perception of each distinct era of political change to demonstrate if the popular music at that time shared specific elements among each other. We feel like we can make a “timeline” to represent the different features of each area.  We feel as this project will give us further insight into the history of Korean music which has become a global genre in today’s world. Overall, we want to see if there is a correlation between the characteristics of popular Korean music and major political events throughout time, and whether or not the relationship is substantial. 
In terms of dataset, we will be utilizing suggested important songs of each era as outlined in the Sogang University's Professor Huikyong Pang’s class “The Mediums of Korean Cultural Modernity.” In addition, we plan to look at Melon [Korean’s music chart ranking since 2004] chart data for recent popular singles. Below are the compiled songs list and the events that took place in that period. 
 
 
 
1910-1945(Japanese Colonization):
Events:
1920s: 
mass media emergence, papers 
TROT music introduced from Japan (there it was called Enka music), typically had very sad lyrics 
1920s-1930s: the recording industry develops (phonographs available)
Japan often censored “troublesome” recordings 
 
Early Trot Songs:
“My Brother is a Street Musician” (오빠는 풍각쟁이야 ) -Park Hyang-rim (1938)
“Tears of Mokpo” Yi Nan-yeong (1935)
“Serenade of Pathos” Nam In-su
Changga Songs (anti-Japan songs):
Huimangga (The Song of Hope)
Western Style Songs:
Glorification of Death - Yun Sim-deok (1926)
 
late 1940s-1950s: 
Events:
The Korean War (1950-1953)
Syngman Rhee (1948-1960)
A right-wing government, killed/arrested leftist opponents, political oppression, took away term limit 
1956: first tv station 
1950s: linked to urbanization, popular culture boom, Americanization (through American performers, listening salons, clubs/bars, and military radio) 
Trot Music Songs:
Go Away 38th Parallel (1946)   https://www.youtube.com/watch?v=jqkh26uaMAU  
I Miss My Hometown Even in My Dreams (1953)
Farewell in Busan Station (1953)
Be Strong! Keumsun (1953)
Heartbreak Pass Miari (1956)   
Missing the Daedong River (1959)
Dance music (basically, Western-style songs):
Daejeon Blues
Nilniri Mambo 
The Rain Tango
Time for Cha-Cha-Cha
Guitar Boogie
 
 
1960s:
Events:
The April Revolution! (1960) Mass protests, Syngman Rhee resigns
	GET A DEMOCRATIC ELECTION… Yun Bo-soen is elected but….. 
May 14, 1960. Park Chung-hee coup d’etat.
1961, KBS, 1st government tv broadcasting station. Used by Park Chung-hee (very anti-communist, material from US) 
Better economy, more TVs, American music played on TV
 
American Standard Pop Songs (popular amongst upper/middle class):
The Boy in the Yellow Shirt (1961) --Han Myeong-suk
	Soul Music: 
	A Cup of Coffee -- Pearl Sisters
My Beloved Is Far Away; Before Being Late -- Kim Choo-ja
 
More Trot Songs (popular amongst populace):
Lee Mi-ja’s “Camelia Lady”(1964)
 
 
1970s:
Events:
Yushin Regime! (1972-1978) Park Chunghee made legal dictatorship.
Curfew, could get arrested for short skirts, etc.  
Youth Culture: tension between younger and older generations, youth were social intellectuals influenced by American values
(10/26/1979)“10.26 Incident” Park Chung-hee was killed by Korean CIA
Coup-de-tat of December Twelfth: Meet your new dictator Cheon Doo-Hwan!
 
Folk Music Songs(mostly by youths, American influence, themes of wanting freedom):
Han Dae-su “To a Happy World,” “  The Sorrow of the Oki”, “Give me water”
Kim Min-gi 


1980s:
Events:
Gwangju Democracy Movement 1980-- Massive protests, many protesters killed by the government, the government blamed the communists for the protests
1987-- announced Roh Tae-woo as the successor, let to MAJOR protests → FINALLY PRESIDENTIAL ELECTIONS INSTATED 
Media under state control BUT new 3S policy---> 
	Distract people from politics with SPORTS! SEX! SCREEN! 
Teens as a consumer group
Dance Music Artists (target teens, dance/costumes on TV):
Nami, Kim Wan-sun, Park Nam-jung, a dance trio Sobangcha 
Pop Ballad Songs:
Cho Yong-pil 
Protest Songs (songs against the regime):
The March for My love (lyrics from the poem by Paik Ki-wan and set to music by Kim Jong-ryul)
 
1990s:
Events:
Neoliberalism → made things more competitive, especially for students 
	Music as release
Culture as a commodity
Record label shift into inhouse training, recording, managing by label  
	Focus on all-round entertainer over just musician  
	Similar j-pop model at time
Economic collapse (1997), hurt indie music 
1995, SM entertainment founded
Big artists:
seo taiji and boys
H.O.T. 
S.E.S.
 
2000s(Hallyu):
Korean music market expansion slowed, starting to go to new markets
Winer Sonata(2002): kdrama that first captivated other Asian countries 
Some big Artists:
BoA, Rain, SE7EN, TVXQ
 
2010s:
Sewol ferry incident (2014)
THADD missile system (2016)
President Park Geun-hye impeachment and imprisonment (2017)
Burning Sun Scandal (2019) 
Artists: 
EXO
BTS
TWICE
SEVENTEEN


## Data

(10 points) 

This section will describe your data and its origins. Each item should contain a name of the data source, a link to the source, and any necessary background information such as:
- What is your cultural data source? 
- When was it made? 
- Who created the works? 
- Is it digital native, or is it some kind of scan, recording, photo, etc., of an analog form? 

## Code

(20 points)

This section will link to the various code for your project (stored within this repository). Your code should be executable on datahub, should we choose to replicate your result. This includes code for: 

- data acquisition/scraping
- cleaning
- analysis
- generating results. 

Link each of your notebooks or .py files within this section, and provide a brief explanation of what the code does. Reading this section we should have a sense of how to run your code.

## Results

(30 points) 

This section will contain links to documentation of your results. This can include figures, sound files, videos, bitmaps, as appropriate to your domain of analysis. Each result should include a brief textual description, and all should be listed below: 

- image files (`.jpg`, `.png` or whatever else is appropriate)
- audio files (`.wav`, `.mp3`)
- written text as `.pdf`

## Discussion

(30 points, three to five paragraphs)

The first paragraph should be a short summary describing your results.

The subsequent paragraphs could address questions including:
- Why is this culturally relevant?
- How does your computational approach differ from the traditional art historical, musicological, manuel/subjective approach to analyzing your cultural subject? 
- How do you think the original artists/musicians would respond to this type of analysis? Would it change/inform their practice in some way?
- How do your results relate to broader social, cultural, economic political, etc., issues? 
- In what future directions could you expand this work?

## Team Roles

Provide an account of individual members and their efforts/contributions to the specific tasks you accomplished.

## Technical Notes and Dependencies

Any implementation details or notes we need to repeat your work. 
- Additional libraries you are using for this project
- Does this code require other pip packages, software, etc?
- Does this code need to run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:
- Papers
- Repositories
- Blog posts
