# Contributor: Gustavo A. Gomez Farhat <gustavo_dot_gomez_dot_farhat at gmail_dot_com>
pkgname=cgprof
pkgver=1.2
pkgrel=2
pkgdesc="Generates colored graphs for profiled executables using gcc and gprof"
url="http://mvertes.free.fr"
arch=('any')
license=('GPL')
depends=('bash' 'graphviz')
source=($url/$pkgname/$pkgname)
md5sums=('5dd4a2be676bc542a29057967c1cbef2')

build() {
  install -m 755 -D $srcdir/$pkgname $pkgdir/usr/bin/$pkgname
}
