# Maintainer: omame <me@omame.tech>

pkgname=cyberos-mirrorlist
pkgver=20210511
pkgrel=1
pkgdesc="CyberOS mirror list for use by pacman"
arch=('any')
url="https://github.com/cyberos/cyberos-mirrorlist"
license=('GPL')
backup=(etc/pacman.d/cyberos-mirrorlist)
source=(mirrorlist)
md5sums=('58d45334d02a6870460438d97b1e7e09')

package() {
	mkdir -p "$pkgdir/etc/pacman.d"
	install -m644 "$srcdir/mirrorlist" "$pkgdir/etc/pacman.d/cyberos-mirrorlist"
}
