# Maintainer: Rinat Sabitov <me@false.org.ru>
pkgname=fortune-mod-ulysses
pkgver=1.0
pkgrel=1
pkgdesc="Fortune mod module for Ulysses quotes"
arch=('any')
url="https://github.com/histrio/ulysses-fortune-mod"
license=('GPL')
depends=('fortune-mod')
source=("$pkgname-$pkgver.tar.gz::https://github.com/histrio/ulysses-fortune-mod/archive/refs/heads/main.tar.gz")
sha256sums=('SKIP')

package() {
    cd "$srcdir/ulysses-fortune-mod-main"
    install -Dm644 ulysses -t "$pkgdir/usr/share/fortune"
}
