![Image of Groovy](groovy.jpg)

# Groovy
An Wordpress Plugin for Create Mobile Application with Restful API

## How it works ?
- No setup is required when you install this plugin. It contains pages for updating settings.
- Within the Linker Mobile application, your website is added to the application and listed in the search results. Quickly share the contents of your web page with your visitors.
- It is the best and free way to turn your Wordpress website into a mobile application.

## What does it support?
- Read your blogs on webview
- Lists your blogs
- Lists your today's organic search referance website adress and visit counts
- Shows total comment counts
- Shows total member counts
- Shows total category counts
- Lists your categories and publish count
- Lists your pages
- Read your pages on webview
- The blog of the day can be selected and you can get ahead in the SEO ranking. You can rise on Alexa.

## Benefits
- You can show the ads on your website pages to more people.
- You can bring organic visitors to your site.
- You can ensure that the pages of your own website are found in instant search results.
- You can enable your own pages to be found in word-based search results.
- You can get into their top rankings. (Most visit, Most search count etc.)
- You can have thousands of people come to your web page with instant application notifications. (* This service is paid.)
- Heyy! Do we have a little dream? If you think that there are 50,000 people using this plugin and there are 25 blog articles on each blog site, we enable searches from 1,250,000 blog titles. this is crazy :)
- You can see, Your website pages and blogs adding automatically on [Filterexp Search](http://filterexp.com). 

## Installation
- Please visit https://github.com/gungoronline/Groovy/tree/master/Plugin-versions page and download latest version and upload zip into plugins.

## After to Installation
- Please download Android app https://play.google.com/store/apps/details?id=com.serifgungor.linker and send mail to contact@serifgungor.com your website adress and 241x120px logo. You can see your website in this application after the website adress added.

## Restful API's response examples
### content/api/post/images.php
{"images":[{"image_name":"wp-content/uploads/2020/07/a.jpg","image_created_time":""},{"image_name":"wp-content/uploads/2020/07/b.jpg","image_created_time":""},{"image_name":"wp-content/uploads/2020/07/c.jpg","image_created_time":""}]}

### content/api/post/blogs.php
{
    "blogs": [
        {
            "id": "1",
            "sharetime": "2020-07-14 19:00:28",
            "updatetime": "2020-07-14 19:07:22",
            "blog_do_viewcount": "11",
            "url": "http:\/\/localhost\/wordpress\/?p=1",
            "image": "http:\/\/localhost\/wordpress\/wp-content\/uploads\/2020\/07\/a.jpg",
            "blog_seo_title": "Merhaba d\u00fcnya!"
        }
    ]
}

### content/api/post/categories.php
{
    "categories": [
        {
            "id": "1",
            "parent": 0,
            "ranking_id": 0,
            "category_name": "Genel",
            "category_link": "genel"
        }
    ]
}

### content/api/post/pages.php
{
    "pages": [
        {
            "id": "2",
            "page_share_time": "2020-07-14 19:00:28",
            "page_lastview": "2020-07-14 19:00:28",
            "page_view_count": "11",
            "page_url": "http:\/\/localhost\/wordpress\/?page_id=2",
            "page_title": "\u00d6rnek sayfa"
        }
    ]
}

### content/api/post/todayOrganicSearch.php
{
    "todayOrganicSearch": [
        {
            "cnt": "1",
            "visitor_refer_domain": "localhost"
        }
    ]
}

### content/api/post/permission.php
{
    "permission": [
        {
            "indexId": "1",
            "codeName": "statistics"
        },
        {
            "indexId": "2",
            "codeName": "blogs"
        },
        {
            "indexId": "3",
            "codeName": "pages"
        },
        {
            "indexId": "4",
            "codeName": "microblogs"
        }
    ]
}

## Version History
### 16.08.2020 (Version 1.0.1)
- Mobile Application's get "404 Page Not Found" problem fixed.
- Problem fixeds and Updates for Wordpress
### 16.08.2020 (Version 1.0.2)
- Show Wordpress Categories count & listing problem fixed.
### 20.08.2020 (Version 1.0.3)
- Bug fixed.

