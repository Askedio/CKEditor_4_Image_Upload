# CKEditor 4 Image Upload
Simple hidden iframe image upload button for CKEditor 4


```
<script src="/js/plugins/ckeditor/ckeditor.js"></script>
<script>
  CKEDITOR.plugins.addExternal('imageupload', '/ckeditor/plugins/imageupload/', 'plugin.js');
  var editor = CKEDITOR.inline('editable', { extraPlugins: 'imageupload' });
</script>
  
```

Configurable options in plugin.js
```
var action = '/admin/create/upload';
var field  = 'upload';
```

Form action = action
Form file field = field
Form response should be the url to the image
