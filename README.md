# Front-End
All Visualizations of the Web Player

---

# Project Overview - Bare Minimum

### Front-End

- **Javascript**
  - General: raw, Jquery (easy mode), React (harder, but looks better on resume)
  - Data Handling: D3.js
- **Authentication & Accessibility**
  - Login or limit through location?
- **Interactions**
  - Adding Songs to Database / Playlists
  - Adding Songs to Queue
  - Playing Songs Immediately

### Back-End

- **Framework:** *(Python)*, Django or Flask
- **Database:** Postgresql, sqlite, MongDB
  - used to store playlists and statistics if needed
- **Server:** (local on rbp) Apache, 

### Audio Player

- somehow take song urls from playlist/database, then pull the video audio and play through raspberry pi
- **needs to be controllable:** pause, maybe half speed, double speed, etc..
- Useful Links:
  - http://unix.stackexchange.com/questions/229787/audio-only-youtube-player






#### Using D3.js to handle tables
- [Example: Basic Table](https://gist.github.com/gka/17ee676dc59aa752b4e6)
- [Example: Sortable Responsive Table](http://bl.ocks.org/AMDS/4a61497182b8fcb05906)
- [Helpful diagram](http://prcweb.co.uk/lab/selection/)
- [Fancy Ideas](http://bl.ocks.org/llimllib/841dd138e429bb0545df)
- [Create Table from Array (JSON data)](https://gist.github.com/LevelbossMike/2623382)

#### RBP Server ideas
- using apache and django
  - [Setting up an Apache Web Server with a Raspberry Pi and Ubuntu ](https://www.raspberrypi.org/documentation/remote-access/web-server/apache.md)
  - [How To Serve Django Applications with Apache and mod_wsgi on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-serve-django-applications-with-apache-and-mod_wsgi-on-ubuntu-14-04)
  - [How to use Django with Apache and mod_wsgi](https://docs.djangoproject.com/en/1.10/howto/deployment/wsgi/modwsgi/)

  ​
