Developed by Kaushal Kishore <br>
Email : kaushal.rahuljaiswal@gmail.com<br>
Website : http://www.kaushalkishore.com<br>

<h2>About Drupal Media Sitemap</h2>
This module is used for creating the image sitemap for Google. It uses the media module for generating the sitemap of all images. It creates the image sitemap in given format:

This is the drupal full project. You can also download it from drupal site. 
<a href="https://www.drupal.org/project/media_sitemap" target="_blank">Media Sitemap</a>

```
<?xml version="1.0" encoding="UTF-8"?>
 <urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"
  xmlns:image="http://www.google.com/schemas/sitemap-image/1.1">
 <url>
   <loc>http://example.com/sample.html</loc>
   <image:image>
     <image:loc>http://example.com/image.jpg</image:loc>
   </image:image>
   <image:image>
     <image:loc>http://example.com/photo.jpg</image:loc>
   </image:image>
 </url>
```
