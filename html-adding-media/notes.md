
# Adding Media: Images,Audios, and Videos to our Webpage
- < img>: tag represtent an image
- < audio>: tag represents a sound or audio stream
- < viedo>: tag represents video footage
- < src="">: can either a file path or a url address

# Attributes for images
- src= : file path 
- alt= "[  media description ]"
- width= : size 
<br/>
Example: < img src=/home/rosexalba/html-lessons/html-semantics/imgCathedral.jpg alt= "picture of inside cathedral" width= "300" > 

# Attributes for Audios 
- < audio>
- < controls > -makes contnet visible
- < source>
- < src=""> : insert 'mp3 file path
- < type=""> : insert 'audio/mpeg'
<br/>
Example: < audio control> < source src="./brain_stew.mp3" type="audio/mpeg" /> < /audio>

# Attributes for Video
- < video>
- < width>
- < Source>
- < contorl>
- < src= ""> : file path
- < type=""> : 
<br/>
Example:  < video controls width="400"> < source src="./video.mp4" type="video/mp4"> < /video>

# Embedding Youtube Videos
- Youtube videos use < iframe: portal to a different website within your page

1. go to youtube.com 
2. find desired video
3. click "share" button
4. slect and copy "embed" <>
5. paste on vscode: this will give you the code with attributes included
<br/>
Example: < iframe width="491" height="872" src="https://www.youtube.com/embed/NbV080vu2Jk" title="Guys I found a walkie talkie circuit in an old book. I immediately made a schema it looks cool." frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>< /iframe>