# *SimpleInsta*

**SimpleInsta** is a photo sharing app similar to Instagram but using Parse as its backend.

Time spent: **16** hours spent in total

## Part 2 

### User Stories

The following **required** functionality is completed:

- [x] User can view the last 20 posts submitted to "Instagram".
- [x] User can pull to refresh the last 20 posts submitted to "Instagram".
- [x] The user should switch between different tabs - viewing all posts (feed view), capture (camera and photo gallery view) and profile tabs (posts made) using fragments and a Bottom Navigation View. (2 points)

### Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://media.giphy.com/media/XEy7bTOyvH63VdfLD2/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Giphy](giphy.com).

### Notes

Implementing the pull-to-refresh feature was one challenge encountered while building the app to make sure to clear out old items before appending old ones, signaling when the refresh finishes, etc. Thinking through the logic and calling the methods at the right place helped to add this feature to the app.

## Part 1

### User Stories

The following **required** functionality is completed:

- [x] User can sign up to create a new account using Parse authentication.
- [x] User can log in and log out of his or her account.
- [x] The current signed in user is persisted across app restarts.
- [x] User can take a photo, add a caption, and post it to "Instagram".

### Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://media.giphy.com/media/fVItF9Pwrh9GecGsbQ/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Giphy](giphy.com).

### Notes

Implementing the dependency to use Parse as well as rotating the image taken so that it displays in the correct orientation were challenges encountered while building the app.

### Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

### License

    Copyright [2019] [Isha Kabra]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
