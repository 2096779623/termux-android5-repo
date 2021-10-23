# termux-android5-repo
## Foreign sources mirrors of Android 5~6 for termux

[![GitHub license](https://img.shields.io/badge/license-MIT-brightgreen)](https://github.com/2096779623/termux-android5-repo/blob/main/LICENSE) [![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2F2096779623%2Ftermux-android5-repo.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2F2096779623%2Ftermux-android5-repo?ref=badge_shield)


Chinese：[READMECN.md](https://github.com/2096779623/termux-android5-repo/blob/master/READMECN.md)



repo: [termux](http://termux.net)       [grimler](https://grimler.se/termux/)        [Termux 21 Version](https://github.com/termux?q=21&type=&language=&sort=)


## Usege:

1.rm $PREFIX/etc/apt/sources.list.d/*
2. pkg install git -y
3. git clone https://github.com/2096779623/termux-android5-repo.git
4. cd termux-android5-repo
5. chmod 777 -R *
6. move all files to $PREFIX/etc/apt
7. pkg update -n

##Simple installation
1.rm $PREFIX/etc/apt/sources.list.d/*
2.pkg install wget -y
3.wget -q https://raw.fastgit.org.org/2096779623/termux-android5-repo/main/install.sh
4.chmod 777 install.sh && ./install.sh



if your's mobile phone no rooted,please exec this order:
rm $PREFIX/etc/apt/sources.list.d/root.list

### Common Problem:

#### Can't connect to github?  Use mirror:[my mirror](https://github.2096779623.workers.dev)  [fastgit](https://hub.fastgit.org)





## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2F2096779623%2Ftermux-android5-repo.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2F2096779623%2Ftermux-android5-repo?ref=badge_large)