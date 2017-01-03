# Today I Learned
A chat bot to close the day.

### Ideation
The concept for this chat bot evolved from [this Medium article] covering an evening ritual that helps wind down the mind, reduce decision fatigue and prepare for the next day. These subjects interest me since I often have trouble shutting down the buzzing of things in my mind, I have working towards a growth rather than goal oriented mindset, and I work well when I have established routines for work and productivity.

[this Medium article]: https://medium.com/art-of-practicality/this-30-minute-evening-ritual-will-help-you-to-kick-life-in-the-ass-fb2c2625f757#.1q8v6ikqv

### Goals
The intended execution of the idea is a Slack chat bot that, at a given time each evening, will ask three questions, similar to how many development teams run stand up meetings.
1. What progress did you make today?
2. What did you learn today?
3. What progress or learning opportunites are you looking forward to tomorrow?

A potential greeting message in the morning could reiterate the items in #3.

Additionally, I would like to support a few [slash commands] to be able to add things on the fly:
1. `TIL` - immediately add something to today's list of learned things
2. `YIL` - add something that was learned yesterday but forgotten

[slack commands]: https://api.slack.com/slash-commands
