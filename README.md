# NLPforSHINE
List of scripts to scrape data from SHINE UKWA and analyse results (NLTK + Wordcloud)

Data Analysis:
1. NLTK for trends UK (excel): https://docs.google.com/spreadsheets/d/16Fya8-HTyokX412cV0glGYrargcapmLR305czxY26SY/edit?usp=sharing
2. NLTK for trends BR (excel): https://docs.google.com/spreadsheets/d/1IfFhFSkce0HjBgsX3MQX0JYTfc_PNhXHFcNFmvJEX_s/edit#gid=1372954454

```
NewsArticlesStorage
├─ Data
└─ Event (Eg. London)
   ├─ Google
   │    ├─ News
   │    │  └─ News outlet (Eg. BBC) 
   │    │     ├─ full-articles
   │    │     └─ olympic-articles
   │    ├─ Government
   │    │  └─ Goverment webiste (Eg. UKSport) 
   │    │     ├─ full-articles
   │    │     └─ olympic-articles
   │    └─ Activist
   │       └─ Activist blog (Eg. Games Monitor) 
   │          ├─ full-articles
   │          └─ olympic-articles
   └─ UKWA
        └─ Domain (Eg. Guardian)
              ├─ full-articles
              └─ olympic-articles          
```
SA
```
Sub-DatasetStorage
├─ Data
└─ Event (Eg. London)
   ├─ English
   │   └─ Brisith News outlet (Eg. BBC) 
   │      ├─ full-articles
   │      ├─ olympic-articles   
   │      └─ curated-articles
   └─ Portuguese
       └─ Brazilian News outlet (Eg. Globo) 
          ├─ full-articles
          ├─ olympic-articles
          └─ curated-articles

```

