utmech-soft3
============

ROS pkgs used in the class "Software3".


How to use these ROS pkgs in your catkin workspace
---
このROSパッケージを自分の環境で使うときの設定。
```bash
# clone this repo to the src directory in your catkin workspace
$ mkdir -p ~/catkin_ws/soft3/src
$ cd ~/catkin_ws/soft3/src
$ git clone https://github.com/utmech-2014/utmech-soft3.git

# make it
$ cd ..
$ catkin_make
$ catkin_make install
$ source ~/catkin_ws/soft3/devel/setup.bash

# run samples
$ rosrun beginner_tutorials talker.py
$ rosrun my_keyop velocity.py
```

How to contribute to this repository
---
contributeの仕方。
* First, fork this repository.
* Setup the git remote target in your local workspace __like below__.
* Change the sources in the branch and send pull requests!
```bash
$ cd ~/catkin_ws/soft3/src/utmech-soft3
$ git branch YOUR-GITHUB-USERNAME
$ git checkout YOUR-GITHUB-USERNAME
$ git remote add YOUR-GITHUB-USERNAME git@github.com:YOUR-GITHUB-USERNAME/utmech-soft3
```

Information for git & GitHub
---
git の使い方 ドキュメント
* [Git -Book](http://git-scm.com/book/ja/v1)

Cheat Sheet
* [GitHub - GIT CHEAT SHEET](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)
* [Git Cheatsheet • NDP Software](http://ndpsoftware.com/git-cheatsheet.html)
