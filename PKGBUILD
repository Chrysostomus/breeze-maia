# Maintainer : Chrysostomus

pkgname=breeze-maia-gtk3
pkgver=1
pkgrel=1
pkgdesc="Breeze theme with maia colors, gtk3-only version"
arch=('any')
url="https://www.gnome.org/"
license=('LGPL')
source=("https://rawgit.com/Chrysostomus/breeze-maia/master/chrome.tar.gz")
sha256sums=('SKIP')
options=('!strip')

package() {
	find Breeze* -type f -exec install -Dm644 '{}' "$pkgdir/usr/share/themes/{}"
}
