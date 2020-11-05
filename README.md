# Ambulance Perambulation


|Date | Person |Zindi Submissions| Comments |
|---|---|---|---|
| 3/11-5/11 | Aseta | None |Looking for a way to predict accident locations so as to dynamically position the Ambulances |


1 Either cluster them according to time and day and predict probability of which class the belong

2 don't cluster them but predict whether an accident might occur or not 

3 predict 6 posible locations where the accident might occur


1 I've seen is wrong since the clustering isn't explicit road may change cluster
(But maybe gaussian clustering may work)

2 i only have data for accidents(YES) which means i have to add/create data for no accidents(NO), this might 
be alot of data and will definitely skew the algorithm ,most likely in the wrong direction, i'm not even sure 
where to begin when adding random accident data

3 seems easiest, but i have to find a way of getting 6 probable locations(like the softmax clustering[predict all 
locations with likelyhood of an accident at that time, but pick the top 6])) 
and i have to find a way of combining lat/long into a single variable , since predicting separately* seems 
wrong because lat/long are sort of dependent on each other , and i cant preditc tupples or geometries 

#### If you are able to come up with something email it to me as I try find a work around for this
