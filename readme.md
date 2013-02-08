Retina Spacer GIF
==================================================

The retina spacer gif should be used in all your legacy projects to upgrade for
high pixel density displays. 

## Usage

To use, replace your gifs with:

``` html 
<img src="spacer@2x.gif" style="height:1px;width:1px;" />
``` 

It's as easy as that!

## FAQ

### But I can't see it!

Exactly! By optimizing the image for high-density displays, your old site will
look as intended on all screens.

### Will it affect performance?

Yes. This spacer may be as much as 9 bytes larger than non-retina spacers. Also,
the additional HTML required could add as much as 33 bytes per usage. For this 
reason, it is recommended to use deflate or other compression on your markup. 
Contact AngelFire, GeoCities, or other host if you have further needs.

### Is it HTML5 compatible?

You may be in the wrong place. However, to ensure your project will continue to 
render properly, we suggest using the PUBLIC HTML5 doctype (if your project uses
 a doctype):

``` html 
<!DOCTYPE html PUBLIC>
``` 

It is advisable to also include an X-UA-Compatible meta tag to ensure compliance:
``` html 
<meta http-equiv="X-UA-Compatible" content="IE=5,chrome=?" />
```

This will ensure your site is compatible with IE5 and greater.


## Contributing

Please file bugs and contribute pull requests. Specifically, we could use a
transparent spacer, and perhaps one in SVG.
