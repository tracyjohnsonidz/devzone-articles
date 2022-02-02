## Headers
Make sure you don't use the single # for any headers. 
Always start with the ##.


### Sub header level 3 (H3)
#### Sub header level 4 (H4)
##### Sub header Level 5 (rarely used) 

...
## General text styling

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

### Block quotes
This doesn't work that well
> We're living the future so
> the present is our past.
> 
{#note .greyHighlight}

**Notes**
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. {#note}

### Footnotes
Here's a sentence with a footnote. [^1]  
  
[^1]: This is the footnote.

### Task List
- [x] Write the press release  
- [ ] Update the website  
- [ ] Contact the media

H~2~O
X^2^


## Examples of math in .md

This expression $\sum_{i=1}^n X_i$ is inlined.

The Gamma function satisfying $\Gamma(n) = (n-1)!\quad\forall
n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

## Code on your page
Some `inline code` if you need to put inside a sentence.

If you have javascript:
```javascript
// An highlighted block
var foo = 'bar';
```

A very common one on the DevZone is bash
```bash
export I_MPI_ROOT=/opt/intel/oneapi/lib/intel64
export PATH=${I_MPI_ROOT}/libfabric/bin:${I_MPI_ROOT}/bin:$PATH
export LD_LIBRARY_PATH=${I_MPI_ROOT}/libfabric:${I_MPI_ROOT}:$LD_LIBRARY_PATH
export FI_PROVIDER_PATH=${I_MPI_ROOT}/libfabric
```

## Lists
### Creating an ordered list
1. First item  
2. Second item  
3. Third item  
4. Fourth item

This will also do the same thing
1. First item  
1. Second item  
1. Third item  
1. Fourth item

This will also do the same thing
1. First item  
8. Second item  
3. Third item  
5. Fourth item

Most of the time a MD editor will try to fix your list numbering
You can also indent by adding a few spaces.

An example of a horizontal rule
***

### Creating Unordered Lists
- First item  
- Second item  
- Third item  
- Fourth item

**Split Lists**
- list one - item 1
- list one - item 2
   - sub item 1
   - sub item 2
- list one - item 3
<!-- -->
- list two - item A
- list two - item B


## Tables

| Syntax | Description |  
| ----------- | ----------- |  
| Header | Title |  
| Paragraph | Text |


## A collapsible section with markdown
Not sure if this works. Testing in the template
<details>
  <summary>Click to expand!</summary>
  <br>
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>


## Videos
Also not sure if these will work in the editorial post. Will test.

Go to the youtube video and copy the embed code. 
<iframe width="424" height="238" src="https://www.youtube.com/embed/c7st0drv54U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


You can also use this embed code for brightcove videos. Just replace the videoid= #
To find the video ID, simply right click on the video on developer.intel.com and select **Player Information**. Video ID value is listed under Source.

<div style="position: relative; display: block; max-width: 900px;"><div style="padding-top: 56.25%;"><iframe src="https://players.brightcove.net/740838651001/default_default/index.html?videoId=6286027295001" allowfullscreen="" allow="encrypted-media" style="position: absolute; top: 0px; right: 0px; bottom: 0px; left: 0px; width: 100%; height: 100%;"></iframe></div></div>
