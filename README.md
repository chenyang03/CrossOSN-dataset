# An anonymized dataset of 60+ million Foursquare users with a focus on cross-site linking

**Publication:**
Qingyuan Gong, Yang Chen, Jiyao Hu, Qiang Cao, Pan Hui, Xin Wang. Understanding Cross-site Linking in Online Social Networks. ACM Transactions on the Web (TWEB), 2018, 12(4):25:1-25:29. 
(full citation below)

Licensed under [Creative Commons Attribution Share Alike 4.0](http://choosealicense.com/licenses/cc-by-sa-4.0/).

## Description
This dataset covers 61.39 million Foursquare users, including all their profile information fields shown on their homepages, the statistical counts of their activities, and the social graph.

## Files
 
* [profile.tar.gz](https://drive.google.com/open?id=1blb5SLM9kL8U_YfDZsBDW-FwZrYfelRl): the profile information and activity statistics of all Foursquare users.

Each line in ``Foursquare_profile.txt`` is an entry of user's information, including her demographic information fields, and the statistics of her activities. For each line, the format is:

[Anonymized UID,  number of followings,  number of followers,  number of tips,  number of checkins, gender  (m: male, f: female,  -: none), has_lastname (1: yes, 0: no), has_bio (1:yes, 0: no), has_photo (1: yes, 0: no), is_superuser  (1: yes, 0: no), linked to Facebook  (1: yes, 0: no), linked to Twitter (1: yes, 0: no), is_early_user (1:early user, 0: non-early user), location]

For example, an entry

[358, 12, 14, 1, 185, "m", 1, 0, 1, 0, 1, 1, 1, "New York, NY"]

shows that the user has an anonymized ID of 358, has 12 followings and 14 followers, has left 1 tips and conducted 185 check-ins. He is a male user, and has filled his lastname into the information field. He has not filled in the biography field. He has uploaded a photo. He is not a superuser of Foursquare. He has linked to Facebook and Twitter accounts. He is an early user. Finally, his location is New York, NY.


* [Foursquare_Graph.tar.gz](https://www.dropbox.com/s/xusf3knnqkqs9zk/Foursquare_Graph.tar.gz?dl=0): the social graph of all Foursquare users 

There are two files in ``Foursquare_Graph.tar.gz``. One is ``node.csv``, the other is ``edges.csv``.

Each line of ``node.csv`` represents an anonymized user ID of a Foursquare user.

Each line in ``edges.csv`` represents a directed edge of the Foursquare network.

For example, in a line 

23,24 

We can conclude that user 23 follows user 24. 23 and 24 are the anonymized IDs of the two users.

## BibTex Entry
```
@article{Gong_CrossOSN18,
author={Qingyuan Gong and Yang Chen and Jiyao Hu and Qiang Cao and Pan Hui and Xin Wang},
title={{Understanding Cross-site Linking in Online Social Networks}},
journal={ACM Transactions on the Web},
year={2018},
volume = {12},
number = {4},
pages = {25:1--25:29},
}

```
