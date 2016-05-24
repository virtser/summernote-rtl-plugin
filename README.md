# summernote-rtl-plugin
Summernote RTL plugin/extension to be used with Super simple WYSIWYG editor - http://summernote.org

This extensions allows to add two new buttons to Summernote editor toolbar. 
Those buttons let user change text direction to either LTR (left to right) or RTL (right to left).
This is especially useful in right to left languages like Hebrew or Arabic.

Note: developed and tested with Summernote v0.7.3

## How to use it

* Include the summernote-ext-rtl.js script file along with summernote editor in your html file.

```<script src="scripts/libs/summernote-ext-rtl.js"></script>```

* Add *['insert',['ltr','rtl']]* setting into your summernote toolbar options like this:
```
var options =  {
  height: 300,                
  placeholder: 'Start typing your text...',
  toolbar: [
      ['style', ['bold', 'italic', 'underline', 'clear']],
      ['fontsize', ['fontsize']],
      ['color', ['color']],
      ['para', ['ul', 'ol', 'paragraph']],
      ['insert',['ltr','rtl']],
      ['insert', ['link','picture', 'video', 'hr']],
      ['view', ['fullscreen', 'codeview']]
  ]
};
summernote.summernote(options);
```

Enjoy and start using it. ;)

![](http://i.imgur.com/9ajdjdn.png)
