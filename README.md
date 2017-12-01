# An anonymized dataset of 60+ million Foursquare users with a focus on cross-site linking

Understanding Cross-site Linking in Online Social Networks (full citation below)

Licensed under [Creative Commons Attribution Share Alike 4.0](http://choosealicense.com/licenses/cc-by-sa-4.0/).

## Description
This dataset covers 61.39 million Foursquare users, including all their profile information fields shown on their Foursquare homepage, the statistical counts of their activities, and the lists of their followers and followings.

## Files
 
* profile.gz: the profile information and activity statistics of all Foursquare users.

Each line in profile.txt is an entry of user's information, including her demographic information fields, and the statistics of her activities. 

The format of the ***.txt file is 

UID followings followers tips  checkins  photos  gender  has_lastname  bio_length has_photo superuser_info fb tw location

For example, an entry

5956 8 51 20 4 m y 0 0 0 1472822320 jakub_cer Shanghai 

shows that the user with a Foursquare ID as 5965, has 8 followings and  5 followers, has left 1 tips and conducted 20 check-ins, and published 4 photos. He is a male user, and has filled his lastname into the information field. He writes no bio, no profile photo, and not a superuser of Foursquare. He has linked his Facebook and Twitter accounts, with the user IDs on these two websites are 1472822320  and jakub_cer respectively. He shows his location as Shanghai on Foursquare. 

* graph.gz: the follower and following list of all Foursquare users 

## BibTex Entry
```
@inproceedings{Chen_CrossOSN_SNAKDD14,
author={Yang Chen and Chenfan Zhuang and Qiang Cao and Pan Hui},
title={ Understanding Cross-site Linking in Online Social Networks},
booktitle={Proc. of the 8th ACM Workshop on Social Network Mining and Analysis (SNAKDD'14)},
year={2014},
}
```
