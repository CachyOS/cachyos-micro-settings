# Maintainer: Vladislav Nepogodin <nepogodin.vlad@gmail.com>

pkgname=cachyos-micro-settings
pkgdesc='CachyOS micro settings'
pkgver=1.0.0
pkgrel=1
arch=('any')
url="https://github.com/cachyos/$pkgname"
license=('GPL')
source=("$pkgname-$pkgver.tar.gz::$url/archive/$pkgver.tar.gz")
sha512sums=('SKIP')
depends=('micro')
install=$pkgname.install
provides=('cachyos-micro-settings')

package() {
    install -d $pkgdir/etc
    cp -rf $srcdir/$pkgname-$pkgver/etc $pkgdir
}
