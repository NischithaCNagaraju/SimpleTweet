# Project 2 - *Nischitha Chottanahalli Nagaraju*

**SimpleTweet** is an android app that allows a user to view his Twitter timeline. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **12** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can **sign in to Twitter** using OAuth login
- [x]	User can **view tweets from their home timeline**
  - [x] User is displayed the username, name, and body for each tweet
  - [ ] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [x] User can refresh tweets timeline by pulling down to refresh


#  *Twitter Client - Part 2*
## User Stories

The following **required** functionality is completed:

- [x] User can **compose and post a new tweet**
  - [x] User can click a “Compose” icon in the Action Bar on the top right
  - [x] User can then enter a new tweet and post this to twitter
  - [x] User is taken back to home timeline with **new tweet visible** in timeline
  - [x] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
  

The following **optional** features are implemented:

[x] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.


**GIF WALKTHROUGH  Twitter part 2- Required**  <img src='https://user-images.githubusercontent.com/61173798/108665092-f59ccb80-7488-11eb-9297-5f6e763e8c16.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />




**GIF LINK Twitter part 2 - required** [Twitter-part2](https://user-images.githubusercontent.com/61173798/108665092-f59ccb80-7488-11eb-9297-5f6e763e8c16.gif)



**GIF WALKTHROUGH  Twitter part 2- optional (Existence of database in airplane mode) **  <img src='https://user-images.githubusercontent.com/61173798/108676545-3c94bc00-749d-11eb-8d38-002b579ba0ef.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />




**GIF LINK Twitter part 2 - required** [Twitter-part2-2](https://user-images.githubusercontent.com/61173798/108676545-3c94bc00-749d-11eb-8d38-002b579ba0ef.gif)





The following **optional** features are implemented:

- [x] User can view more tweets as they scroll with infinite pagination - GIF included
## Video Walkthrough

Here's a walkthrough of implemented user stories:

**GIF WALKTHROUGH - Required**  <img src='https://user-images.githubusercontent.com/61173798/107914425-43f51c00-6f17-11eb-9611-7225699a9367.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />




**GIF LINK 1**  [Twitter1](https://user-images.githubusercontent.com/61173798/107914425-43f51c00-6f17-11eb-9611-7225699a9367.gif)


**GIF WALKTHROUGH - Optional- Infinite scroll**  <img src='https://user-images.githubusercontent.com/61173798/107918489-9ab22400-6f1e-11eb-82c6-49de047f90ab.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

**GIF LINK 2** [Twitter2](https://user-images.githubusercontent.com/61173798/107918489-9ab22400-6f1e-11eb-82c6-49de047f90ab.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
