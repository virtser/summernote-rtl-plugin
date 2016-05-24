# summernote-rtl-plugin
Summernote RTL plugin/extension to be used with Super simple WYSIWYG editor - http://summernote.org

## How to use it

1. Include the summernote-ext-rtl.js script file along with summernote editor in your html file.

2. Add ['insert',['ltr','rtl']] setting into your summernote toolbar options like this:

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
