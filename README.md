# mousezoom
I didn't write this, I just need it in a repo

### usage
- Arguments are optional
- I'm assuming arguments for `on` are pointer-type events
- `magnify` refers to to the pixel-size of the original image. Meaning `1.5` will make a 1000px image display as 1500px. **This is the file pixel size, NOT the size that is rendered on the page**

```
    $('#zoom').zoom({ 
      on: 'grab',
      magnify: 1.5
    });
```
    
### Other Methods (and their default values) I found in the code but have not tested

- `destroy` (n/a)
- `url` (!1)
- `callback` (!1)
- `target` (!1)
- `duration` (120)
- `on` ("mouseover")
- `touch` (!0)
- `onZoomIn` (!1)
- `onZoomOut` (!1)
- `magnify` (1.33)

Have Fun!
