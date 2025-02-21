# harry-potter-gallery

harry-potter-gallery is a website to show pictures of characters or scene in Harry Potter's movie.

## Manage Image
1. Add or remove or replace image in img/gallery_img directory. 

2. Find img_list.json file under root directory and edit the content accordingly.
   - Images are shown on website according to the sequence in the file.


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

> - image_name is actual image name with extension in img/gallery_img directory.
> - keyword is the image information which is used for searching image by keyword.

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