ekumachidi.gitlab.io
=======
<p>This my personal website powered by Jekyll.</p>

Table of Contents
-----------------

*   [Features](#features)
*   [Deployment](#deployment)
*   [Posts](#posts)
*   [Other Authors](#authors)
*   [Disqus Comments](#disqus)
*   [Google Analytics](#analytics)
*   [Update favicon](#favicon)
*   [Credits](#credits)
*   [License](#license)

* * *

### Features

* 100% responsive
* Optimized for mobile devices
* Minimal design
* Valid HTML5 code
* Included site search
* Contact Page
* Post sharing
* Supports Mail Chimp Subscriber
* Supports Disqus Comments
* Social Media Profiles
* Formspree form
* Font Awesome fonts
* Google Fonts

* * *

### Deployment

To run this site locally, navigate to the app directory and run `bundle install` to install the dependencies, then run `jekyll serve` or `bundle exec jekyll serve` to start the Jekyll server.

Please check the [Deployment Methods](https://jekyllrb.com/docs/deployment-methods/) page on Jekyll website.

* * *

### Posts

To create a new post, you can create a new markdown file inside the _posts directory by following the [recommended file structure](https://jekyllrb.com/docs/posts/#creating-post-files).

```sh
  ---
  layout: post
  title: 10 Best books of all time
  date: 2017-10-27 18:09:50 +0300
  img: 17.jpg
  tags: [Books, C#]
  author: Ekuma_Chidi # Optional
  ---
```        

You can set the tags, author and the post image.

Add post images to **/images/pages/** directory.

For tags, try to not add space between two words, for example, `Ruby on Rails`, could be something like (`ruby-on-rails`, `Ruby_on_Rails`, or `Ruby-on-Rails`).

* * *

### Authors

You can add other authors for your posts. In the beginning, create the author in the file `_config.yml`

**For example:**

```sh
  # Other Authors - here you can add Other authors. For example Natali_Braxton
  authors:
    Example_Author:
      author-name: Example Author
      author-image: 111.jpg
      about-author: My name is Example Author. I love walking, I play the guitar in my spare time. And also write articles about different technologies.
      author-email: example@gmail.com
      author-twitter: https://twitter.com/
      author-facebook: https://twitter.com/
      author-instagram: https://www.instagram.com/
      author-pinterest: https://pinterest.com/
```

Then add the author in a post. Save and you are done.

```sh
  ---
  layout: post
  title: 10 Best books of all time
  date: 2017-10-27 18:09:50 +0300
  img: 17.jpg
  tags: [Books, Hobby]
  author: Example_Author
  ---
```

* * *

### Disqus

Disqus comments are enabled.

Open `_config.yml` file, and change the `mr-brown` value on line 52 with your [Disqus account shortname](https://help.disqus.com/customer/portal/articles/466208).

```sh
  # Comment Section (Disqus)
  disqus-identifier: mr-brown # Add your shortname for Disqus Comment. For example mr-brown
```     

That’s all you need to setup Disqus from the theme side. If you get any issue regarding that comments are unable to load. First, make sure you have [registered your website with Disqus (Step 1)](https://help.disqus.com/customer/portal/articles/466182-publisher-quick-start-guide).

And also check [Disqus troubleshooting guide](https://help.disqus.com/customer/portal/articles/472007-i-m-receiving-the-message-%22we-were-unable-to-load-disqus-%22) if you still have issues.

* * *

### Analytics

To integrate Google Analytics, open `_config.yml`, and add your Google Analytics identifier.
```sh
  # Google Analytics
  google-analytics: # Add your identifier. For example UA-99631805-1
```     

* * *

### Favicon

You can find the current favicon (favicon.ico) inside the theme root directory, just replace it with a new favicon.

* * *

### Credits

We have used the following scripts, fonts or other files as listed.

*   [Google Fonts](https://fonts.google.com/) (Dancing+Script, PT+Serif, Lato, Roboto).
*   [Font Awesome](https://fontawesome.com/v4.7.0/)
*   [FitVids.js](http://fitvidsjs.com/)
*   [jQuery-viewport-checker](https://github.com/dirkgroenen/jQuery-viewport-checker)
*   [Zoom](https://github.com/fat/zoom.js)
*   [Transition](http://getbootstrap.com/javascript/#transitions)
*   [jQuery.com](https://jquery.com/)
*   [Simple-Jekyll-Search](https://github.com/christian-fei/Simple-Jekyll-Search)
*   Preview Images [unsplash.com](https://unsplash.com/), [pexels.com](https://www.pexels.com/)

* * *

### License

MIT License
