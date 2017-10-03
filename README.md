# Scrawl: A fully responsive theme for Ghost

![Scrawl on a tablet](https://dl.dropboxusercontent.com/s/xhdbn5q9o8k7nnd/scrawlCoverImage.png?dl=0)

Features include:

* Fully responsive, mobile first design
* Automatic estimated reading times for each post
* Easily configurable social links, without messing around with the server
* For dev blogs: includes [Prism](http://prismjs.com/) to style your code snippets
* [Inbuilt search for the blog](#user-content-inbuilt-search-for-blog)
* [Alert and notification through backtick code block](#user-content-alerts-and-notes)


[See the screenshots below.](#scrawl-in-action)


## How to install

Get the .zip file for the latest version from original author [here](https://github.com/ktweeden/scrawl/archive/master.zip) or this modified version with search and other added enhancements [here](https://github.com/pubmania/scrawl/archive/master.zip)

Ghost(Pro) users can upload this [.zip](https://github.com/ktweeden/scrawl/archive/master.zip) file via the Pro dashboard. See the [official guide](http://support.ghost.org/upload-theme-ghostpro/).
Self-hosted Ghost users should upload the [.zip](https://github.com/ktweeden/scrawl/archive/master.zip) file to Ghost's `content/themes/` directory and extract it with `unzip -o scrawl-master.zip`


## Configuration

Scrawl adheres to the [Ghost Theme Configuration Approach](https://github.com/unwitting/gtca), allowing you to add your own social media links to pre-formatted buttons without touching your website's server.

The configuration for Scrawl uses the code injection interface, which you will find at yourwebsite.address/ghost. Each social network or profile that you want to add, requires only one line adding to the blog header code injection.

This configuration approach is designed to be as easy for the user as possible, but if you have any problems then please don't hesitate to get in touch with me!

### Social media links

Scrawl supports a range of social media platforms. When configured, a button will appear for each platform in the footer that appears on each page of the theme.

Below is the list of the social media platforms currently supported. Choose the ones that you would like to include on your blog and copy the code. Then, replace the ... with your username for that platform. Remember to keep the speech marks!

For example, if I wanted to add a link to my twitter profile to a blog using scrawl I would simply put

`<script>window.__themeCfg.twitterUsername = 'ktweeden';<script>`

---

Copy and paste the relevant links to the blog header code injection box:

bitbucket: `<script>window.__themeCfg.bitbucketUsername = '...';</script>`

codepen: `<script>window.__themeCfg.codepenUsername = '...';</script>`

facebook: `<script>window.__themeCfg.facebookUsername = '...';</script>`

github: `<script>window.__themeCfg.githubUsername = '...';</script>`

instagram: `<script>window.__themeCfg.instagramUsername = '...';</script>`

pinterest: `<script>window.__themeCfg.pinterestUsername = '...';</script>`

tumblr: `<script>window.__themeCfg.tumblrUsername = '...';</script>`

twitter: `<script>window.__themeCfg.twitterUsername = '...';</script>`

vine: `<script>window.__themeCfg.vineUsername = '...';</script>`

youtube: `<script>window.__themeCfg.youtubeUsername = '...';</script>`

linkedin: `<script>window.__themeCfg.linkedinUsername = '...';</script>`

googleplus: `<script>window.__themeCfg.gplusUsername = '...';</script>`

### Disqus

Scrawl comes with the [Disqus](https://www.disquss.com) commenting platform so that you can easily manage interactions with your readers.

To enable commenting:
* make sure that you have an account on Disqus.
* Create a "channel" for your blog using Disqus's website. This channel will hold all of the comments for your blog.
* Copy the following code into the blog header code injection, replacing ... with your channel's name (no spaces!).

`<script>window.__themeCfg.disqusUsername = '...';</script>`

## Scrawl in action

Enough talk, here are some pictures.


### Home page

![Scrawl home page example](https://dl.dropboxusercontent.com/s/k2nvu6u9uilhyo0/scrawFpFull.png?dl=0)


### Post

![Scrawl post example](https://dl.dropboxusercontent.com/s/62ia4v64y298mh1/A%20long%20article%20example.png?dl=0)

![Scraw formatting](https://dl.dropboxusercontent.com/s/apkw7s3e96zu08m/Scrawls%20formatting.png?dl=0)


### Tablet

![Scrawl home page example](https://dl.dropboxusercontent.com/s/ew5skbpisd2gra3/scrawlTabletIndex.png?dl=0)


### Mobile

![Scrawl home page example](https://dl.dropboxusercontent.com/s/9i3eo9pl5taq5tu/scrawlPhoneIndex.png?dl=0)

### Inbuilt Search for blog
![Scrawl inbuilt search](https://github.com/pubmania/scrawl/blob/master/ScrawlSearch.PNG?raw=true)

The above search box will be enabled by default on the theme but for it to work, on the Ghost admin go to "Labs" under Setting on left hand side navigation and then scroll down to  "Enable Beta Features". Here make sure Public API is enabled like so:

![EnablePublicAPI](https://github.com/pubmania/scrawl/blob/master/EnableSearch.PNG?raw=true)

### Alerts and Notes

![Scrawl Alerts and Notes examples](https://raw.githubusercontent.com/pubmania/scrawl/master/Alert_and_Notes.PNG)

Theme has inbuilt CSS which allows to have alert and note boxes as shown in above screenshot using the simple backtick wraparound. For example above boxes were created using the following markdown:

![Scrawl Alerts and Notes markdown usage examples](https://github.com/pubmania/scrawl/blob/master/AlertNoteExample.PNG?raw=true)
