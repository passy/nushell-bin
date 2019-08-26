# Maintainer: Pascal Hartig <i@passy.me>
pkgname=nushell-bin
pkgver="0.2.0"
pkgrel=1
pkgdesc="A modern shell written in Rust"
arch=('x86_64')
url="https://github.com/nushell/nushell"
license=('MIT')
depends=()
options=()
source=("https://github.com/nushell/nushell/releases/download/${pkgver}/nu_${pkgver//./_}_linux.tar.gz")

build() {
    return 0
}

package() {
    ls "$srcdir/nushell/"
    install -D "$srcdir"/nushell/nu* -t "$pkgdir/usr/bin/"
}
md5sums=('e004d3d12af3b545f945d2dc7dfc261b')
