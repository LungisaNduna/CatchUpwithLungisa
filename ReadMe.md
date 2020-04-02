Hey guys. Welcome to my attempt at doing something heart felt with code.
I've been terrible with keeping my family up to speed with where my life is so I have 
decided to work on a simple webpage to keep them up to date with where I am in life.

I am going to use this page as documentation I guess. Yah that is a good idea.

So here we go.
The first thing I wanted to do was to add some interesting styling for a navigation bar.
I am using the following tutorial for most of the first part
https://www.youtube.com/watch?v=biOMz4puGt8
I like it and so might you.

First things first the reason I have chosen to do this is because: 
    1. My Mom asked me to inform some of my uncles about how my life is going.
        in fairness they helped to support me in becoming a Software Developer
        both financially and the other ways that count. My response to Her was that 
        I would do so as a coder would.
    2. I saw this interesting video this morning while doing my random coding video session. 
        Every morning I check out the first coding video suggested by YouTube, broadens my horizons.
    3. I really need to improve my github activity, It's one of my new years resolutions and goals.

Okay lets start coding.
If I randomly stop coding I might just have lost myself in the music playing, I'll try edit those out.
This will be the worst readme file ever.

Sorry Using windows to capture screenshots on the other side

Lack of planning just hit me. I need to think about the navigation items I want.
Which means I need to consider the things I want to place in the site.

    1.  Career and Vocation.
    2.  Family and Friends (going to have to throw my sister under the bus here and talk about her life. Mine is not that interesting)
    3.  a personal thank you based on who they are.

I think I can get all of that done.
I need need to go find some icons to use. this man in the video swears by font awesome.
I'm going to stop the recording here and come back when I do

Found a few Icons I liked. lets see them in action.
Sorry it's been a while since last I looked at this project. Time to move forward.

Had to do some searching to find the paths. I don't know what the prescribed method is but this is how I did it
    1.  find the icon you are looking for
    2.  inspect the icon by right clicking on it and selecting inspect
    3.  the svg tag should show and you can copy the d value which is a long string

Also I copied the code from the repo that Fireship has and pasted that in.

Okay it's looking good so far. Back to the tutorial video to see the next steps
First lets commit and push these changes. Such bad habits

Great its working out so far
We no longer need the file

Really looking good. Just following the steps without any changes really. Reallllly Nice

Moving onto mobile

Okay so we are done with the video and now it's time for me to move forward on my own. Thinking I should have an about section maybe though. let me add that in.

Welcome back guys. It has been a while due to some fustrations of not being able to find a solution to a problem

The core problem is trying to load html pages dynamically.
First thing I did was create some mark up I would like to use. All these are in the folder pages.
This makes up the content, then I want to load it the content dynamically. Sounds like fun right so lets go ahead.

I will be using the .load function which loads content from another file.
Well that was easy why did I get frustrated for 3 days. Because of testing
When you try run that code locally there may be some issues with the functionality and you may get a CORS error.
    This is because .load() uses AJAX and for security reasons most browsers (in my case firefox, chrome and Edge) 
        will not allow local content to be called in this fashion.
    I fixed it by first closing all instances of Chrome running on my computer
    Then you need to open chrome in the command line with the following tag -–allow-file-access-from-files
    Found this out at https://github.com/BsAtHome/atpack/issues/2. They have more information check it out if you are having the same issues.

Anyway that complete I found a new tutorial on creating information cards so I want to try it out for displaying the content on the individual pages. So far I have placed most of the content in a way that is somewhat good but lets go forth with a new tutorial.

