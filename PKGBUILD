# Maintainer: Ecmel Ercan <ecmel.ercan@gmail.com>
pkgname=groff-doc
pkgver=1.21
pkgrel=2
pkgdesc="GNU troff text-formatting system documentation."
url="http://www.gnu.org/software/groff/groff.html"
arch=('any')
license=('GPL')
depends=('groff')
optdepends=()
makedepends=()
conflicts=()
replaces=()
backup=()
install=
source=("ftp://ftp.gnu.org/gnu/groff/groff-$pkgver.tar.gz")
md5sums=('8b8cd29385b97616a0f0d96d0951c5bf')

package() {
  cd "${srcdir}/groff-$pkgver/contrib/mom/"
  install -d "$pkgdir/usr/share/doc/groff/html"
  cp -rf examples "$pkgdir/usr/share/doc/groff/"
  cp -rf momdoc "$pkgdir/usr/share/doc/groff/html/"
}

