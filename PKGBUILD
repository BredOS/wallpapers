# Maintainer: Bill Sideris <bill88t@bredos.org>
pkgname=bredos-wallpapers
pkgver=1.0
pkgrel=1
pkgdesc="Custom backgrounds and properties for GNOME"
arch=('any')
license=('MIT')
source=("w0_bred_dp.png" "w0_bred_lp.png" "w0_bred.xml")
md5sums=("SKIP" "SKIP" "SKIP")

package() {
    install -d "$pkgdir/usr/share/backgrounds"
    install -d "$pkgdir/usr/share/gnome-background-properties"

    install -m644 "$srcdir/"*.png "$pkgdir/usr/share/backgrounds/"
    install -m644 "$srcdir/"*.xml "$pkgdir/usr/share/gnome-background-properties/"
}
