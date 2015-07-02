# Sonitus Ex

## Desciption
Currently, the best way to play music via the SoundCloud site is through their web site. However, this is a bit restrictive because it means you must keep a browser 'window/tab' open to stream audio. If you use the web daily for work and utilize many tabs and browser windows in can become a pain to try and find the open SoundCloud page.

Enter Sonitus Ex. The plan is to create a Google Chrome Web Extension that utilizes the SoundCloud API to import and play a logged in user's playlists. This should eliminate the need for a user to keep a browser window or tab open to stream audio from SoundCloud.

Sonitus Ex should primarily utilize javascript, jQuery and React.js for handling the web extensions framework and the SoundCloud API integration. While the UI will be handled using SASS and web standard HTML5 elements. The logo, style tiles and some of the layout will be handled by a professional designer.

Finally, the first iteration of Sonitus Ex will mainly integrate to a user's playlists on SoundCloud. However, future iterations will include other options including searching of the SoundCloud song library as well as the ability to add and create playlists directly in Sonitus Ex.

## User Stories

Trello with preliminary user stories (still needs to be further vetted): https://trello.com/b/eUVc3w3D/sonitus-ex

## Wireframes

Links to wireframes of your project. Ideally embed them in this README.

## Models
```
UserModel -
userId: "",
username: "",
password: "",
email: ""

PlaylistModel -
playlistId: ""
```

## APIs, Plugins, Libraries and Frameworks
google knowledge base: https://developer.chrome.com/extensions/getstarted

soundcloud: https://developers.soundcloud.com/docs/api/html5-widget

soundcloud: https://developers.soundcloud.com/docs/api/guide
