# How Styles is setup

Currently we like using LESS as our CSS preprocesser. app.less is currently the "master" file that is used to compile all the different CSS pieces into one, compressed file for production. You may add whatever additional .less files you need, just make sure you add them to app.less to make sure they are included in your production CSS.
