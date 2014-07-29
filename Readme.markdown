#Throwback Trovebox - a trovebox timemachine


### What is this?

I loved everpix and was really sad to see it go. And after switching to Trovebox i missed the feature that showed you photos from that day, a year, month, week ago etc. So i hacked togheter this simple page to recreate a simple version of that feature. 

It just loads photos from the specified trovebox account x days ago from today (default a year, a month and a week). Nothing fancy for now :)


### TODO
* Add ability to look for photos if none are found, for example if no photos is found 1 year ago we could search 1year ago +-1 one day etc
* Add gui to discover photos (so you could show photos from x weeks/years/days ago without editing the source)


### Usage

Edit the openphoto.js line
    <script src="js/OpenPhoto.js" data-site="http://photo.example.com"></script>

and change data-site to your trovebox installation.

If you want to edit the template you have to compile it using hulk (hogan.js)
    
    npm install hogan.js -g

    cd /path/to/download/Throwback_Trovebox/templates

    hulk photos.mustache > ../js/templates.js (Or run the bash script from this dir)

