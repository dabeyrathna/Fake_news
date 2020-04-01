
# PHEME Dataset

PHEME[1], a dataset of potential rumors in Twitter and journalistic assessments of their accuracies. This is a curated data set of
conversation threads about rumors in Twitter replete with journalist annotations for truth [2]. 

## Original dataset

The original dataset can be found [here](https://figshare.com/articles/PHEME_dataset_for_Rumour_Detection_and_Veracity_Classification/6392078). The original format contains rumors and non-rumors original tweet collections and their reactions in JSON format. Each tweet has a seperate JSON file. 

```
{
   "contributors":null,
   "truncated":false,
   "text":"Omg Wow \"@FLOCKAfierce: WOW RT @AntonioFrench: Police have brought out the large gear in #Ferguson. http:\/\/t.co\/4t4RRtNWRk\"",
   "in_reply_to_status_id":null,
   "id":498250100079341568,
   "favorite_count":13,
   "source":"<a href=\"http:\/\/twitter.com\/download\/android\" rel=\"nofollow\">Twitter for Android<\/a>",
   "retweeted":false,
   "coordinates":null,
   "entities":{
      "symbols":[

      ],
      "user_mentions":[
         {
            "id":32402939,
            "indices":[
               9,
               22
            ],
            "id_str":"32402939",
            "screen_name":"FLOCKAfierce",
            "name":"Billionaire B"
         },
         {
            "id":14090948,
            "indices":[
               31,
               45
            ],
            "id_str":"14090948",
            "screen_name":"AntonioFrench",
            "name":"Antonio French"
         }
      ],
      "hashtags":[
         {
            "indices":[
               89,
               98
            ],
            "text":"Ferguson"
         }
      ],
      "urls":[

      ],
      "media":[
         {
            "source_status_id_str":"498248648699150336",
            "expanded_url":"http:\/\/twitter.com\/AntonioFrench\/status\/498248648699150336\/photo\/1",
            "display_url":"pic.twitter.com\/4t4RRtNWRk",
            "url":"http:\/\/t.co\/4t4RRtNWRk",
            "media_url_https":"https:\/\/pbs.twimg.com\/media\/BuoigYqIMAA11jo.jpg",
            "source_status_id":498248648699150336,
            "id_str":"498248648548167680",
            "sizes":{
               "large":{
                  "h":768,
                  "resize":"fit",
                  "w":1024
               },
               "small":{
                  "h":255,
                  "resize":"fit",
                  "w":340
               },
               "medium":{
                  "h":450,
                  "resize":"fit",
                  "w":600
               },
               "thumb":{
                  "h":150,
                  "resize":"crop",
                  "w":150
               }
            },
            "indices":[
               100,
               122
            ],
            "type":"photo",
            "id":498248648548167680,
            "media_url":"http:\/\/pbs.twimg.com\/media\/BuoigYqIMAA11jo.jpg"
         }
      ]
   },
   "in_reply_to_screen_name":null,
   "id_str":"498250100079341568",
   "retweet_count":103,
   "in_reply_to_user_id":null,
   "favorited":false,
   "user":{
      "follow_request_sent":false,
      "profile_use_background_image":true,
      "default_profile_image":false,
      "id":1921517718,
      "profile_background_image_url_https":"https:\/\/abs.twimg.com\/images\/themes\/theme1\/bg.png",
      "verified":false,
      "profile_text_color":"333333",
      "profile_image_url_https":"https:\/\/pbs.twimg.com\/profile_images\/577650273495175168\/4yRKm6Ql_normal.jpeg",
      "profile_sidebar_fill_color":"DDEEF6",
      "entities":{
         "description":{
            "urls":[

            ]
         }
      },
      "followers_count":384,
      "profile_sidebar_border_color":"C0DEED",
      "id_str":"1921517718",
      "profile_background_color":"C0DEED",
      "listed_count":2,
      "is_translation_enabled":false,
      "utc_offset":-10800,
      "statuses_count":21606,
      "description":"Living my life like Its GOLDEN with no care in the world",
      "friends_count":765,
      "location":"Whereever I wanna BE ",
      "profile_link_color":"0084B4",
      "profile_image_url":"http:\/\/pbs.twimg.com\/profile_images\/577650273495175168\/4yRKm6Ql_normal.jpeg",
      "following":false,
      "geo_enabled":false,
      "profile_banner_url":"https:\/\/pbs.twimg.com\/profile_banners\/1921517718\/1406746010",
      "profile_background_image_url":"http:\/\/abs.twimg.com\/images\/themes\/theme1\/bg.png",
      "screen_name":"Cassie_Xtassy",
      "lang":"en",
      "profile_background_tile":false,
      "favourites_count":151,
      "name":"#Justice4MikenEzell",
      "notifications":false,
      "url":null,
      "created_at":"Mon Sep 30 22:58:32 +0000 2013",
      "contributors_enabled":false,
      "time_zone":"Atlantic Time (Canada)",
      "protected":false,
      "default_profile":true,
      "is_translator":false
   },
   "geo":null,
   "in_reply_to_user_id_str":null,
   "possibly_sensitive":false,
   "lang":"en",
   "created_at":"Sat Aug 09 23:30:55 +0000 2014",
   "in_reply_to_status_id_str":null,
   "place":null,
   "extended_entities":{
      "media":[
         {
            "source_status_id_str":"498248648699150336",
            "expanded_url":"http:\/\/twitter.com\/AntonioFrench\/status\/498248648699150336\/photo\/1",
            "display_url":"pic.twitter.com\/4t4RRtNWRk",
            "url":"http:\/\/t.co\/4t4RRtNWRk",
            "media_url_https":"https:\/\/pbs.twimg.com\/media\/BuoigYqIMAA11jo.jpg",
            "source_status_id":498248648699150336,
            "id_str":"498248648548167680",
            "sizes":{
               "large":{
                  "h":768,
                  "resize":"fit",
                  "w":1024
               },
               "small":{
                  "h":255,
                  "resize":"fit",
                  "w":340
               },
               "medium":{
                  "h":450,
                  "resize":"fit",
                  "w":600
               },
               "thumb":{
                  "h":150,
                  "resize":"crop",
                  "w":150
               }
            },
            "indices":[
               100,
               122
            ],
            "type":"photo",
            "id":498248648548167680,
            "media_url":"http:\/\/pbs.twimg.com\/media\/BuoigYqIMAA11jo.jpg"
         }
      ]
   }
}
```



### Preprocessing

Whole dataset has converted in to incidant based single CSV format and labeled each and every instance in to a catagory of either rumor or not.

```
pheme_charliehebdo.csv
pheme_ferguson.csv
pheme_germanwings-crash.csv
pheme_ottawashooting.csv
pheme_sydneysiege.csv
```

### Attributes

Some of the importatnt attribtes extracted are,

```
is_rumor
tweet_length
text
created	has_smile_emoji
sensitive
has_quest_or_exclaim
user.time_zone
negativewordcount
positivewordcount	
contentlength	
sentimentscore	
has_url_in_text

etc
```

## References

[1] A. Zubiaga, G. W. S. Hoi, M. Liakata, R. Procter, and P. Tolmie, “Analysing How People Orient to and Spread Rumours in Social
Media by Looking at Conversational Threads,” PLoS ONE, pp. 1–33, 2015. [Online]. Available: http://arxiv.org/abs/1511.07487

[2] C. Buntain and J. Golbeck, "Automatically Identifying Fake News in Popular Twitter Threads," 2017 IEEE International Conference on Smart Cloud (SmartCloud), New York, NY, 2017, pp. 208-215.

