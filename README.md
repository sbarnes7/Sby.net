# Sby.net
## How to add files to the Intranet site
- Go to the page where the file needs to be added
- Find the letter header that matches the first letter of the file you are naming
    - If letter header doesn't exist create a new one in the proper location by copying and pasting new one replacing old letter with your new one
    - Keep track of your div tags and ensure you aren't forgetting any and not embedding tags
- href the new link into the correct location by following the format of the other links on the page
- Go to links.js file and also add the new file to this location anywhere on the page using the same formatting as the other links
    - It is important to make sure the formatting of this link is correct because it is in JS document.write and need toi consider special characters
    - This part will update all other files under the site wide search section

## How to delete files from the Intranet Site
- Go to file where the link resides
- Find the link and delete the href from the page
    - If the file being deleted is the only file under the section header, delete the section header and be sure to delete all corresponding tags along with it
- Go to the links.js file
- Find the link associated to the file being deleted
- Delete the ENTIRE LINE of code to delete all corresponding JS formatting    

