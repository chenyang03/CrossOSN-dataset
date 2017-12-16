# An anonymized dataset of 60+ million Foursquare users with a focus on cross-site linking

Understanding Cross-site Linking in Online Social Networks (full citation below)

Licensed under [Creative Commons Attribution Share Alike 4.0](http://choosealicense.com/licenses/cc-by-sa-4.0/).

## Description
This dataset covers 61.39 million Foursquare users, including all their profile information fields shown on their Foursquare homepage, the statistical counts of their activities, and the lists of their followers and followings.

## Files
 
* [profile.gz](https://drive.google.com/open?id=1blb5SLM9kL8U_YfDZsBDW-FwZrYfelRl): the profile information and activity statistics of all Foursquare users.

Each line in profile.txt is an entry of user's information, including her demographic information fields, and the statistics of her activities. For each line, the format is:

[Anonymized UID,  number of followings,  number of followers,  number of tips,  number of checkins, gender  (m: male, f: female,  -: none), has_lastname (1: yes, 0: no), has_bio (1:yes, 0: no), has_photo (1: yes, 0: no), is_superuser  (1: yes, 0: no), linked to Facebook  (1: yes, 0: no), linked to Twitter (1: yes, 0: no), is_early_user (1:early user, 0: non-early user), location]

For example, an entry

[358, 12, 14, 1, 185, "m", 1, 0, 1, 0, 1, 0, 1, "New York, NY"]

shows that the user has an anonymized ID of 358, has 12 followings and 14 followers, has left 1 tips and conducted 185 check-ins. He is a male user, and has filled his lastname into the information field. He has no filled in the biography field.
He has uploaded a photo photo. He is not a superuser of Foursquare. He has linked Facebook and Twitter accounts. He is an early user. Finally, his location is New York, NY.


* [graph.gz](https://drive.google.com/open?id=1N8nd3_vzIGR89XWprJ8jovB4VprCtMKl): the follower and following list of all Foursquare users 

## BibTex Entry
```
@inproceedings{Chen_CrossOSN_SNAKDD14,
author={Yang Chen and Chenfan Zhuang and Qiang Cao and Pan Hui},
title={{Understanding Cross-site Linking in Online Social Networks}},
booktitle={Proc. of the 8th ACM Workshop on Social Network Mining and Analysis (SNAKDD'14)},
year={2014},
}

```
