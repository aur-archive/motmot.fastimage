#Automatically generated by pip2arch on 2012-06-20

pkgname=motmot.fastimage
pkgver=0.5.5
pkgrel=1
pkgdesc="Pythonic API for the framewave SIMD library"
url="http://code.astraw.com/projects/motmot"
depends=('python2' 'framewave')
makedepends=('python2-distribute' )
license=('BSD')
arch=('any')
source=('http://pypi.python.org/packages/source/m/motmot.FastImage/motmot.FastImage-0.5.5.zip')
md5sums=('5d58e639e3a739f5bb44989ba6bc1a61')

build() {
    cd $srcdir/motmot.FastImage-0.5.5
    python2 setup.py build
}

package() {
    cd $srcdir/motmot.FastImage-0.5.5
    python2 setup.py install --root="$pkgdir" --optimize=1 
}
