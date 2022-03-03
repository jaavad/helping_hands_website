# [Helping hands website](https://helpinghandslab.netlify.app/)

[![Screenshot](./assets/media/logo.png)](https://helpinghandslab.netlify.app/)

The helping hands lab website is now deployed [here.](https://helpinghandslab.netlify.app/)
* It often need about 5 min for website to update after git push. 

* Please add/modify/delete files in the *content* folder. :)

## Publication
* **Add publication**: 

  Create a folder, e.g. '/content/publication/$YOURNAME', copy a template _index.md and cite.bib from '/content/publication/my_conference_paper' folder and modify it. You can save a feature picture as 'featured.jpg' in your folder.
* **Change publication category**: 
  
  Modify publication_types in '/content/authors/$YOURPAPER/_index.md'
* **Modify your own page**

  Modify in '/content/authors/$YOURNAME/_index.md'
* **Redirect it to your personal project website**: find your folder and append the following in '/content/authors/$YOURNAME/_index.md'. Substitude 'yourURL'.
    ```
    <meta http-equiv = "refresh" content = " 0 ; url = yourURL"/>
    ```
* **Internal link**

  If you want to link to some files in your folder, the path should be like '/publication/my_conference_paper/FILENAME'

## People
* **Add people**: 

  Create a folder, e.g. '/content/authors/$YOURNAME', copy a _index.md from other's folder and modify it. Your avatar must be saved as 'avatar.jpg' in your folder.
* **Change people category**: 
  
  Modify user group in '/content/authors/$YOURNAME/_index.md'
* **Modify your own page**

  Modify in '/content/authors/$YOURNAME/_index.md'
* **Redirect it to your personal website**: find your folder and append the following in '/content/authors/$YOURNAME/_index.md'
    ```
    <meta http-equiv = "refresh" content = " 0 ; url = yourURL"/>
    ```



## Advanced option for real-time preview & debugging
[Offcial document](https://wowchemy.com/docs/getting-started/install-hugo-extended/)


## To-do list
* add side feature pic on publication page
* link the to-be launched lab twitter account

## Website major updates
* Mar 3, 2022: Support dark mode!
* Mar 2, 2022: HH website launched!