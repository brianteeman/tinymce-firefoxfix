# tinymce-firefoxfix

For Joomla 5.4.3 and 6.0.3 users experiencing a _flashing_ problem when editing content using tinyMCE the files contained here will fix it for you. They are the same files that will be available in the next release of Joomla so they are safe to install.

Download the zip file and extract the contents `tinymce.js` and `tinymce.min.js` and upload them to your site int the `media\plg_editors_tinymce\js` folder to **replace** the two files with the same name.

Make sure you download the correct fix for your version of joomla

> [!IMPORTANT]
> If after replacing the two files and clearing the browser cache you still have problems then your site is using the gzipped version of the javascript which is NOT included in the update. You should delete the  file media/plg_editors/js/tinymce.min.js.gz to ensure that the correct hotfix files are being used by your site
