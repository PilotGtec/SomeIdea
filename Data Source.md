# Data Source

We have two sets/sources of data: 

1. Twitter via its [Public API](http://dev.twitter.com/streaming/public)
2. Philippine Stock Exchange [(PSE) data via Dropbox] (http://www.dropbox.com/sh/1dluf0lawy9a7rm/fHREemAjWS)

For the Twitter data set, the streaming request parameter used was [follow](http://dev.twitter.com/streaming/overview/request-parameters#follow). The *follow* parameter is described in the Twitter site as follows. 


> A comma-separated list of user IDs, indicating the users whose Tweets should be delivered on the stream. Following protected users is not supported. For each user specified, the stream will contain:

> - Tweets created by the user.
> - Tweets which are retweeted by the user.
> - Replies to any Tweet created by the user.
> - Retweets of any Tweet created by the user.
> - Manual replies, created without pressing a reply button (e.g. “@twitterapi I agree”).

> The stream will not contain:

> - Tweets mentioning the user (e.g. “Hello @twitterapi!”).
> - Manual Retweets created without pressing a Retweet button (e.g. “RT @twitterapi The API is great”).
> - Tweets by protected users.
