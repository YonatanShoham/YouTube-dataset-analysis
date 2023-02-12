# YouTube-dataset-analysis
YouTube dataset analysis, the data was analyzed from and an excel xls file, and the analysis was done with the aid of phyton matplotlib library.
Eleven matplotlib graphs were analyzed to reach some productive conclusions to aid YouTube channel owners to expand or maintain their user base.

The main purpose of this data analyzation is to aid YouTube channel owners to expand or maintain their user base by providing them with useful information regarding YouTube video usage.
A secondary purpose can be to aid YouTube common users to find the best quality or most popular channels or videos. 

The given dataset contain 27 different columns, of which the first column is the index column the index number is unique to every row thus it can be defined as the primary key every row has a unique number identifying it. 
The other 26 remaining columns contain YouTube related data, the channel id column is the unique id of every channel.
The following columns are divided by categories: positive correlation in which the YouTube channel owners will want to maximize the amount to gain success, negative correlation in which the YouTube channel owners will want to minimize the amount to gain success, unknown correlation in which the effect on the channel success of changing the amount or type of the factor is yet unknown and unrelated correlation in which the column data is unrelated to the channel success.

Positive correlation : subscriberCount, channelViewCount, channelCommentCount, videoViewCount, likes/dislikes, videoLikeCount.

Negative correlation: dislikes/subscriber, dislikes/views, videoDislikeCount.
Unknown correlation: videoCategoryId, videoCount, views/subscribers, channelelapsedtime, videoId, totalviews/channelelapsedtime comments/views, comments/subscriber, likes/subscriber, likes/views, totvideos/videocount, elapsedtime, totviews/totsubs, views/elapsedtime, videoPublished, VideoCommentCount.
Unrelated correlation: Index, channelId.

To achieve the main objective a comparison will be made between factors with known correlation outcome to factors with unknow correlation outcome. This method will help draw conclusions about the factors with the unknown correlation to success.
This comparison will give results that will hopefully aid the YouTube channel owner improve his channel success.

The main objective is to aid the YouTube channel owner to improve or maintain it’s users base, to achieve this various factors will be considered.
The logical assumption is that a channel owner will want to maximize his number of subscriptions, views, likes and will want o minimize his number of dislikes. 
A big amount of likes and views for a specific video can be seen as a short term success and a big amount of subscriptions or a big amount of likes and views per channel can be seen as a long term success.

The raw number of for example likes per videos will give us partial information because a video can get a big amount of likes compared to another video, but the amount of subscribers and viewers can vary greatly between them.
For example, a video that got 100 likes but have been watched a million times compared to a video that got 100 likes but have been watched only a thousand times, it can be assumed that both videos got very different reactions from the audience.
To amend this problem more substantial usage will be made with data that is divided by values which represents the channel popularity for example number of subscriptions, views.
The channel that got the most subscriptions or the video that got the most likes\views divided by a factor that represents the video\channel popularity for example number of subscriptions will give a scale of the video\channel success.

