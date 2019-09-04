
You need to display two sport flows on two pages/tabs: **Dernières vidéos** and **Top videos** by accessing to them via HTTP API <https://bitbucket.org/amandychev/lequipe-test/raw/4c23e6fbeb841a7501dfacea2f76e6b1443b201e/video-flux.json>

Each flow item must contain:

* title (onglets -> flux -> items -> titre)
* sport type (onglets -> flux -> items -> sport -> nom)
* icon (onglets -> flux -> items -> objet -> image -> url)

![Screen](./screen.png)

You must specify **width** and **hight** for the url to be able to download an image. For instance, the following url: <https://medias.lequipe.fr/img-video-cover/1500000000988715/{width}/{height}> must be formatted like this: <https://medias.lequipe.fr/img-video-cover/1500000000988715/320/280> to download an icon with 320x240 resolution.

The json file contains a real sample of L'Équipe video flow: <https://iphdata.lequipe.fr/iPhoneDatas/EFR/STD/ALL/V3/videos.json>. So there are lots of information inside the items. You may ignore it to simplify the application.

Good luck!
