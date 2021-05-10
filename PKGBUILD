# Maintainer: omame <me@omame.tech>

pkgname=cyberos-mirrorlist
pkgver=20210510
pkgrel=3
pkgdesc="CyberOS mirror list for use by pacman"
arch=('any')
url="https://github.com/cyberos/cyberos-mirrorlist"
license=('GPL')
backup=(etc/pacman.d/cyberos-mirrorlist)
source=(mirrorlist)
md5sums=('f5579f265ded7f4841f9086e08c5c958')

package() {
	mkdir -p "$pkgdir/etc/pacman.d"
	install -m644 "$srcdir/mirrorlist" "$pkgdir/etc/pacman.d/cyberos-mirrorlist"
}
