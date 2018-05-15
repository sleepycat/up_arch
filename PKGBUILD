# Maintainer: Mike Williamson <mike at korora dot ca>
pkgname=up
pkgdesc="Deploy infinitely scalable serverless apps, apis, and sites in seconds to AWS."
pkgver=0.6.4
pkgrel=1
arch=('x86_64')
license=('GPL3')
url="https://up.docs.apex.sh"
provides=('up')
makedepends=('binutils')
source=("https://github.com/apex/up/releases/download/v0.6.4/up_0.6.4_linux_amd64.tar.gz")
sha256sums=('1140e480688c313fea63e6ac3f322c5435a70f10e040566a1b8109e97a2f3f87')

package() {
  mkdir -p "$pkgdir"/usr/bin
  install -Dm0755 "$srcdir"/up "$pkgdir"/usr/bin
  install -D -m0755 "$srcdir"/LICENSE "${pkgdir}/usr/share/licenses/up/LICENSE"
}

