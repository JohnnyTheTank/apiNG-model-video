Universal **_VIDEO_** [model](https://aping.readme.io/docs/models) for [apiNG](https://github.com/JohnnyTheTank/apiNG)

# Supported apiNG Plugins
- [x] **Youtube** ([apiNG-plugin-youtube](https://github.com/JohnnyTheTank/apiNG-plugin-youtube))
- [x] **Instagram** ([apiNG-plugin-instagram](https://github.com/JohnnyTheTank/apiNG-plugin-instagram))
- [x] **Facebook** ([apiNG-plugin-facebook](https://github.com/JohnnyTheTank/apiNG-plugin-facebook))
- [x] **Vimeo** ([apiNG-plugin-vimeo](https://github.com/JohnnyTheTank/apiNG-plugin-vimeo))
- [x] **Dailymotion** ([apiNG-plugin-dailymotion](https://github.com/JohnnyTheTank/apiNG-plugin-dailymotion))
- [x] **Tumblr** ([apiNG-plugin-tumblr](https://github.com/JohnnyTheTank/apiNG-plugin-tumblr))


# JavaScript
```JavaScript
var video = {
    platform: undefined, //NAME of platform ( "youtube" / "facebook", "instagram" , ...)
    blog_name: undefined, //NAME of blog (channel / page / instagram account / ...)
    blog_id: undefined, //ID of blog (channel / page / account, ...)
    blog_link: undefined, //link to blog (channel / uploader / page / account, ...)
    timestamp: undefined, //timestamp of created_at
    date_time: undefined, //datetime of created_at
    post_url: undefined, //url to the video
    intern_id: undefined, //INTERN ID of video (facebook id, youtube id, ...)
    caption: undefined, //video title
    text: undefined, //video description
    img_url: undefined, //preview image url (best case 700px)
    thumb_url: undefined, // best case 200px (min)
    source: undefined, //url to .mp4 file
    markup: undefined, //markup to embed video
    duration: undefined, //video duration in seconds
    width: undefined, //width in pixels
    height: undefined, //height in pixels
    comments: undefined, //comments_count
    likes: undefined, //likes_count
    shares: undefined, //shares_count
    position: undefined //position in playlist
};
```

# JSON

```JSON
{
  "platform": false,
  "blog_name": false,
  "blog_id": false,
  "blog_link": false,
  "timestamp": false,
  "date_time": false,
  "post_url": false,
  "intern_id": false,
  "caption": false,
  "text": false,
  "img_url": false,
  "thumb_url": false,
  "source": false,
  "markup": false,
  "duration": false,
  "width": false,
  "height": false,
  "comments": false,
  "likes": false,
  "shares": false,
  "position": false
}
```