# Overview #
PoseMan is a tool to manage characters (any objects) poses in Maya (2011) writed in Python

With PoseMan you could create poses and organize them in projects, sections and groups. A project could be several characters divided into parts (sections) and use groups to organize poses. For example:

ProjectName: MyShortFilm
Sections (tabs): Nemo, Bruce, Merlin
Groups: Inside each section: Head, Body, Face, Hands, etc..

You can use project, sections and group however you want, another example or a little more big PoseMan project, using a poseman project for each character

ProjectName: Nemo
Sections: Face, Body, Arms, Hands
Groups: Inside Face for example you can have several groups like: Eyes, Nose, Tonge, LeftEye, RightEye, etc..

PoseMan files are all XML's, if you want, you can edit the files with a text editor and change names, create new sections, etc.. or you can batch-script and create a bunch of project, sections, etc.., for example to create a base for a bunch of characters, etc..



# Install, Launch and Use PoseMan #
Go to the download page and get the last PoseMan version. Inside a .zip there is a install&launch.txt file with instructions.

Basically you have to copy PoseMan.pyc into a maya script directory and make a button or type this code into the script editor (python tab)

**import PoseMan as PM**
**reload(PM)**
**PoseManUI = PM.PoseMan\_UI()**

# Support the Project #
<a href='https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=KKYG7CRU2V4GE&lc=ES&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHostedGuest'><img src='http://www.inartx.com/poseman/donate-button.png' /></a>

# Screens #
![http://a5.sphotos.ak.fbcdn.net/hphotos-ak-snc7/s720x720/394668_483240285037484_1459682309_n.jpg](http://a5.sphotos.ak.fbcdn.net/hphotos-ak-snc7/s720x720/394668_483240285037484_1459682309_n.jpg)

![http://sphotos.ak.fbcdn.net/hphotos-ak-snc3/hs488.snc3/26688_135880499773466_133201926707990_296675_1584697_n.jpg](http://sphotos.ak.fbcdn.net/hphotos-ak-snc3/hs488.snc3/26688_135880499773466_133201926707990_296675_1584697_n.jpg)

![http://sphotos.ak.fbcdn.net/hphotos-ak-snc4/hs063.snc4/34517_137690786259104_133201926707990_305870_7202807_n.jpg](http://sphotos.ak.fbcdn.net/hphotos-ak-snc4/hs063.snc4/34517_137690786259104_133201926707990_305870_7202807_n.jpg)