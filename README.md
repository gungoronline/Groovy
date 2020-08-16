# Groovy
An Wordpress Plugin for Create Mobile Application with Restful API

## How it works ?
- No setup is required when you install this plugin. There is no page for the setting.
- Within the Linker Mobile application, your website is added to the application and listed in the search results. Quickly share the contents of your web page with your visitors.
- It is the best and free way to turn your Wordpress website into a mobile application.

## Installation
- Please visit https://github.com/gungoronline/Groovy/tree/master/Plugin-versions page and download any version and upload zip into plugins.

## Response examples
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

## Special Thanks
- Furkan Kalkan - Github @furkan9595 
