# SharingTime
"making my own card project", lesson4, Google Developer Challenge Scholarship: Android Basics 

My own card / lesson 4, Google Developer Challenge Scholarship: Android Basics 

Code explanation

Making my own card took three steps: drawing, positioning and styling views.
To begin I drew the desired output on paper, highlighting the area occupied by the views.
The root view is a RelativeLayout View, so that I can position the children views relative to the parent view and they can overlap.
It contains an ImageView and two TextViews, one aligned to the top left of the parent view, and the other to the center bottom of it.
In the code the ImageView is the first child of the parent view, so that each of the textviews can overlap with it.
I set its layout_width and layout_height to match_parent, so the image can take up all the screen.
I used a picture that I took last year during summer, I scaled it to centerCrop and I also provided it with a content description for accessibility.
Both of the Text Views has the attributes layout_width and layout_height set to wrap_content, the first is aligned to the top left of the screen, so I didn't have to change the default values of its alignment.
For the second TextView I set the attributes layout_alignParentBottom and layout_centerHorizontal to value true.
I didn't hardcode the text attribute directly in the xml layout file, instead I used an @string resource.
I styled the text changing size, color and font-family and I added a padding of 20dp, so that the text isn't squashed to the edges of views.
I aligned the text of the second textview to the centre of it.
This is a simple card, and it wasn't particularly difficult to make, though I had two issues running it on my phone.
First I considered changing the ADB driver, chosing a more recent than the previous one.
This made the upload quicker.
The second problem, I found out, was due to the dimensions of the picture , which caused the app to close immediately.
resizing the image solved the issue.

