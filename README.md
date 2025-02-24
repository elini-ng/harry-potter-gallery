# harry-potter-gallery

harry-potter-gallery is a website to show pictures of characters or scenes in Harry Potter's movie.
<br/>

## How to Manage Images
1. Go to img/gallery_img directory.
2. Add or remove or replace image(s) in the directory.
3. Find img_list.json file under root directory and then edit the content accordingly.
   - Images are shown on website according to the sequence in the file.
   - Refer to below format and example of img_list.json file
<br/>

```
Format:

[
   {
      "name": [image_name 1],
      "keyword": [keyword 1]
   },
   {
      "name": [image_name 2],
      "keyword": [keyword 2]
   }
]
```

> - image_name is actual image name with extension in img/gallery_img directory.
> - keyword is the image information which is used for searching image by keyword.

<br/>

```
Example:

[
   {
      "name": "img1.jpg",
      "keyword": "Harry James Potter"
   },
   {
      "name": "img2.jpg",
      "keyword": "Hermione Granger"
   }
]
```
