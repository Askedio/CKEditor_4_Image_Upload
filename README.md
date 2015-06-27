# CKEditor 4 Image Upload
Simple hidden iframe image upload button for CKEditor 4

```
  <script src="/js/plugins/ckeditor/ckeditor.js"></script>
  <script>
    CKEDITOR.plugins.addExternal('imageupload', '/js/plugins/ckeditor/plugins/imageupload/', 'plugin.js');
    var editor = CKEDITOR.inline('bodyi', { extraPlugins: 'imageupload' });
  </script>
  
```
