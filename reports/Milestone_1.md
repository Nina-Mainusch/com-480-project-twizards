## Milestone 1 (Friday 23rd April, 5pm)

**10% of the final grade**

In this project, we 

### Dataset
[Twitch.tv](https://www.twitch.tv/), a subsidiary of *Amazon.com Inc*, is a streaming service that is concentrated on video game live streaming, 
broadcasting of e-sport events, music and other creative content, and more recently "in real life" streams.
Each category represents either explicit video game titles or is more general like *Just Chatting* or *Music*. 
Since channels are also associated with languages, users are able select a certain category language in order to be presented with a list of fitting channels. 
Although Twitch.tv provides an official [API](https://dev.twitch.tv/docs/api/) which collects the number of current live viewers over the different channels, 
there is no official historical collection of these statistics. However, there are websites like [Sullygnome.com](https://sullygnome.com/) that sample such 
statistics every 15 minutes since august 2015 and make them publicly available. We use this sampled statistics for compiling a time series 
(each points representing one month) over different categories, each of which includes the following features:

- Watch Time: Total amount of time this category was watched.
- Stream Time: Total amount of time this category was streamed.
- Peak Viewers: Maximum number of viewers at a time, within one category.
- Peak Channels: Maximum number of channels at a time, within one category.
- Streamers: Total amount of channels that streamed at least once in this category.
- Average Viewers: Average total viewers within one category.
- Average Channels: Average total channels streaming withing one category.
- Average Viewer Ratio: Average number of viewers per channels withing one category. 

Note that this dataset is available over all channels and in respect to all streamed language.

### Problematic

### Exploratory Data Analysis

### Related Work

#### References  
