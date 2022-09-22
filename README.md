# VistaPanel Demo,but with features
- [x] CNAME RECORDS
- [x] PHP Version Changer
- [x] MySQL
- [x] PHPInfo
- [ ] PMA
- [ ] More.

This repository contains a working demo of VistaPanel, a web hosting panel used in MyOwnFreeHost.  
It has been ripped directly from the browser display files, and customized to function as a demo.

Currently, aside from the working index, almost all pages/features are disabled (as "demo mode" restrictions). In the future, more pages may be added, for the demo to be complete.

# Customization
Using a search and replace function, you are encouraged to customize the following attributes to your own:  
```YOURDOMAIN```: replace with the domain you want to appear in the sidebar. This can be your host's domain, an example domain, or any domain you prefer.  
```YOURPREFIX```: replace with your host's username prefix. This is what comes before the numbers in your panel username, for example ```mofh_12345678```.  
```YOURSQL```: replace with your host's MySQL hostname. You can obtain it from your client panel. As it is not the same for all accounts, you can set it to something similar to ```sqldemo.yourdomain.com```.  

Additionally, as this is, in a way, a working VistaPanel, you can inject your own customizations, such as themes, scripts, and anything you can use in the panel's HTML advertisements.  
Currently, the footer ad area is available, and can be located by searching for this text: ```Add your themes and scripts```. Make sure to follow the instructions there.  
Because the index is the only page available right now, there is no need for other areas. Feel free to customize the code and add your modifications wherever you want, though.

Some areas have been manually disabled by me as they're no longer available. You can search for the ```<!-- DISABLED``` comment, and uncomment the lines to add them back.

You can replace the VistaPanel logo with your own by changing the [vplogo.png](elements/vplogo.png) file.

In the future, these may be rewritten as PHP files to allow you to customize attributes via a config file, similar to the way it's implemented in [MOFH Material Template](https://github.com/MOFHDevs/mofh-material-template/blob/master/config.php).  
If you want to implement it yourself, free feel to do so and make a PR to add it back here.

# Use a CDN
If you do not want to host the files yourself, you can use the following files:
* [jsdelivr.html](jsdelivr.html): the demo index configured to use the assets via jsDelivr's CDN.
* [ourCDN.html](ourCDN.html): the demo index configured to serve assets via our CDN.

You'll still have to host the HTML file, obviously. You could point to [our demo](https://vpd.cdn.wybenetwork.com), however it will be using the default configuration.

# Copyright Info and Credits
Copyright 2022 Wybe Network. No Rights Reserved, check the [LICENSE](LICENSE.md) for more details.

The idea for this project was conceived by [SmallHost](https://smallhost.us.to), in this forum post: [Demo Hosting Account](https://www.byet.net/index.php?/topic/24001-demo-hosting-account/)

All files included are licensed under their own terms, with the copyrights to their owners retained.
