# Maintainer: Jerome Leclanche <jerome.leclanche+arch@gmail.com>
# Contributor: twa022 <twa022 (at) gmail (dot) com>

pkgname=simple-icon-theme
_pkgname=Simple
pkgver=2.7
pkgrel=3
pkgdesc="The Simple icon theme from the Simplicity desktop theme."
arch=('any')
license=('CCPL' 'GPL' 'LGPL')
url="https://code.google.com/p/simplicity-desktop-theme/"
source=("http://simplicity-desktop-theme.googlecode.com/files/$_pkgname-$pkgver.tar.bz2")
sha256sums=('e28c2b8a52ff3dd223b7ea5965b2fa5f8a7c6abf9d6efd2059e93f499a9c3f74')

package() {
	cd "$srcdir"
	install -d "$pkgdir/usr/share/icons/"
	rm "$_pkgname/"{AUTHORS,GPL,LGPL}
	cp -r "$_pkgname/" "$pkgdir/usr/share/icons/"
}

