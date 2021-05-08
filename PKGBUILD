# Maintainer: omame <me@omame.tech>

pkgname=cyberos-mirrorlist
pkgver=20210508
pkgrel=2
pkgdesc="CyberOS mirror list for use by pacman"
arch=('any')
url="https://github.com/cyberos/cyberos-mirrorlist"
license=('GPL')
backup=(etc/pacman.d/cyberos-mirrorlist)
source=(mirrorlist)
md5sums=('0c39e82ebda159d3f5200dc5063a7445')

package() {
	mkdir -p "$pkgdir/etc/pacman.d"
	install -m644 "$srcdir/mirrorlist" "$pkgdir/etc/pacman.d/cyberos-mirrorlist"
}
