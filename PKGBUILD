# Maintainer: omame <me@omame.tech>

pkgname=cyberos-mirrorlist
pkgver=20210508
pkgrel=1
pkgdesc="CyberOS mirror list for use by pacman"
arch=('any')
url="https://github.com/cyberos/cyberos-mirrorlist"
license=('GPL')
backup=(etc/pacman.d/cyberos-mirrorlist)
source=(mirrorlist)
md5sums=('9f324d5cc952cb92456f1f30afc03b9c')

package() {
	mkdir -p "$pkgdir/etc/pacman.d"
	install -m644 "$srcdir/mirrorlist" "$pkgdir/etc/pacman.d/cyberos-mirrorlist"
}
