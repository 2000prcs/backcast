# Backcast
YouTube Video Player app using BackboneJS.

# Backbone is Interesting in a Few Key Ways

- Backbone was one of the first JavaScript MVC frameworks to gain substantial popularity and is used widely.
- Backbone is unopinionated and can be used in a variety of ways.
- Backbone model are designed for easy integration with RESTful APIs.

# App Organization
Here's how the app is organized:

<img src="https://s3-us-west-2.amazonaws.com/sprint.content/course.backcast/components.png">

1. AppView - The top level container for the entire application.
2. SearchView - Responsible for knowing and communicating information about the search input field
3. VideoPlayerView - Responsible for playing a single video and displaying information about it.
4. VideoListView - A container view responsible for populating video list entry views
5. VideoListEntryView - A view that shows information (thumbnail, title, description) for a single video. When the title of a video is clicked, that video will be shown in the VideoPlayerView view

# Demo

<img src="https://s3-us-west-2.amazonaws.com/sprint.content/course.backcast/video-player.gif">
