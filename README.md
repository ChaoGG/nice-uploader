## Uploader
Multiple file upload plugin with progress-bar.


### Usage
Include resources:
``` html
<link rel="stylesheet" href="path/to/jquery.uploader.css">
<script type="text/javascript" src="path/to/jquery.uploader.js"></script>
```

Initialization：
``` js
$(element).uploader({
    action: 'upload.php',
    onSuccess: function(){
        //do something..
    }
});
```

### Documention
[简体中文](http://niceue.com/uploader/)

### Dependencies
[jQuery 1.7+](http://jquery.com)

### Browser Support
  * IE6+
  * Chrome
  * Safari 4+
  * Firefox 3.5+
  * Opera


### Bugs / Contributions
- [Report a bug](https://github.com/niceue/uploader/issues)
- To contribute or send an idea, github message me or fork the project


### Build
Uploader use [UglifyJS2](https://github.com/mishoo/UglifyJS) 
you should have installed [nodejs](nodejs.org) and run `npm install uglify-js -g`.

  
### License
[MIT License](https://github.com/niceue/uploader/blob/master/LICENSE.txt).