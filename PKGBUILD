# Maintainer: name    <mail@domain.org>
pkgname=endeavouros-ce-WM
pkgver=1.0
pkgrel=1
pkgdesc='Default EndeavourOS Community Edition WM config files'
arch=('any')
url='https://www.endeavouros.com'
license=('GPL3')
source=("${pkgname}-${pkgver}.${pkgrel}.tar.gz::https://github.com/EndeavourOS-Community-Editions/${pkgname}/archive/${pkgver}.${pkgrel}.tar.gz")
sha512sums=('')

package() {
    install -dm 755 $pkgdir/etc/skel
    cp -r --no-preserve=ownership ${pkgname}-${pkgver}.${pkgrel}/etc/skel $pkgdir/etc/
}

