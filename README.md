### Purpose

To create a standard json file, placed at the root of a conference's website, that can then be scrapped by a hubot.

### Background

Trying to remember dates and other generic information about a multitude of conferences can get frustrating.  Combine this with meetups and it gets downright hard.

Leveraging a [hubot][1] and [ChatOps][2] principles it should be possible to automatically gather specific details about a conference from their site.  [Meetup.com][3] has an api that can be easily leveraged, there is no reason that the same thing could not be done with conferences, after all they are just giant meetups and the ability to scale is a widely talked about tenet of the DevOps culture.

This spec attempts to bridge the gap between creating a generic api for a conference site that would most likely have a low adoption rate and our desire to automate low-level manual tasks.

[1]: https://hubot.github.com/
[2]: https://www.pagerduty.com/blog/what-is-chatops/
[3]: http://www.meetup.com/
