# Compilers (Stanford CS143)

## Setup

Fuck to download ~2Gig WM with ~6M of actual project resources. So Directly
install it on Linux

1. Download course resources

```bash
wget https://courses.edx.org/asset-v1:StanfordOnline+SOE.YCSCS1+1T2020+type@asset+block@student-dist.tar.gz -O resources.tar.gz
```

2. Install packages. For Ubuntu:

```bash
$ sudo apt-get install flex-old bison build-essential csh libxaw7-dev
```

NOTE: if flex-old not a thing, use flex. Key point flex should be 2.5.x to
work with course assignments examples.

Also if u do file bin/.i686/spim, u will notice it's 32-bit LSB executable,
dynamically linked
So some sort of 32-libs required
For Ubuntu > 16.04 -

```bash
$ sudo apt install lib32z1
```

3. Activate env - just add binaries to your $PATH

```bash
$ source env.sh
```

## Links
- [Stanford site](https://web.stanford.edu/class/cs143/)
- [Course ad edx](https://learning.edx.org/course/course-v1:StanfordOnline+SOE.YCSCS1+3T2020/home)
- [youtube lectures](https://www.youtube.com/playlist?list=PLoCMsyE1cvdUZRe1udlyjpzTww1U5olL2)
- [Cool syntax hl for vim](https://alfix.gitlab.io/coding/2018/04/03/vim-syntax-highlight-cool.html)
