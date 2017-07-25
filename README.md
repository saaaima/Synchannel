# Synchannel
This file will be a part of data cleaning platform
It switches utc time to local eastern or pacific time due to the status of channel. 
Syn channel will be given eastern local time no matter it is a pacific channel or an eastern channel.
Offset channel will be given local time corresponding to their channel status. 
Syn channels are determined and matched by utc time. For instantce, if channel A EAST and channel B Pacific aired about the same
time,i.e the difference is between 3 mins. Then we say channel A is a syn channel.
Similalry, if channel A Pacific aired 3 hours later than channel A EAST, then we say channel A is a offset channel. Since
it assures that channel A Pacific and channel A East airing at the same local time. 
