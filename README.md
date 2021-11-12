# PHP EMAIL TRACKER

## Simple pixel based email tracker with PHP.

### This script allows you to track opens of HTML emails.

#### How to:
1. Set-up a local environment in order to test and run the PHP script.
2. Once you've run the script, each time you open the email in your browser your IP address will be logged on the log.txt file.
3. When you're satisfied with the script, you can host the script on the server. However don't forget to change the local path of the tracking pixel to the actual URL. 
4. When properly set-up each time a person opens the email, his IP-address should be logged on the log.txt file. 

```HTML
<img src="tracker.php?image=tracking.gif" alt="">
```

##### Replace local path by your URL path

```HTML
<img src="http://yourpath/tracker.php?image=tracking.gif" alt="">
```





#### Useful Tips:
1. You can use geo-location services like [http://ip-api.com/docs/](http://ip-api.com/docs/) to return the actual location of the IP-address.
2. Additionally you could use the [MAPBOX API](https://www.mapbox.com/) to visualize the locations on a map. 

<a href="https://heroku.com/deploy" rel="nofollow"><img src="https://camo.githubusercontent.com/6979881d5a96b7b18a057083bb8aeb87ba35fc279452e29034c1e1c49ade0636/68747470733a2f2f7777772e6865726f6b7563646e2e636f6d2f6465706c6f792f627574746f6e2e737667" alt="Deploy" data-canonical-src="https://www.herokucdn.com/deploy/button.svg" style="max-width: 100%;"></a>


