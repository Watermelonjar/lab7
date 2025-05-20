1. Within a Github action that runs whenever code is pushed, the biggest reason is the automation, since I will probably forget to do testing when I'm supposed to do it manually. If this project suddenly has another contributor the testing would be uniform
2. No, single functions shouldn't be tested using E2E test which is more for a full test for the user flow in the system
3. The main difference betwen navigation and snapshot is that, navigation is a mode to analyze page transitions throughout pages, where it analyzes accessibility for page transitions. Snapshot anlyzes the current state of a page, page accessibility, evaluate UI.
4. for one, the image sizes are really big, which really slows down image loading based on the network.  App does not have viewport tag which means that it is not that scalable properly on mobile devices, font and media would not scale properly. There is a delay with responsiveness of the button, it is because of css animations.




