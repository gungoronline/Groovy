# Groovy
An Wordpress Plugin for Create Mobile Application with Restful API

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
