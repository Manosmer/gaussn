# gaussn

A test project for simple Go code.

### Gaussian Noise for png

The code creates an executable that produces a PNG image with noise, following the Gaussian Distribution

#### Instructions
Open your Go workspace, defined by `$GOPATH`.

```
$ cd src
$ mkdir github.com/litarhis // if github.com already exists just create a directory named litarhis in it
$ git clone https://github.com/Litarhis/gaussn.git
$ cd gaussn
$ go install
$ gaussn.exe // if you haven't added $GOPATH/bin as an environment variable, navigate to $GOPATH/bin and execute gauss.exe
```
Pass the width and height of your preference.

Good! Now the only thing you need to do is to apply gaussianNoise.png as an overlay of your picture.