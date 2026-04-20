# Maintainer: BeetleBot <nikarabilla@gmail.com>
pkgname=fount-bin
pkgver=0.8.2
pkgrel=1
pkgdesc="A terminal-based Fountain screenplay editor (Binary)"
arch=('x86_64')
url="https://github.com/BeetleBot/Fount"
license=('GPL3')
provides=('fount')
conflicts=('fount')
# We point to the Fount-Linux-x64.tar.gz from your GitHub release
source=("${pkgname}-${pkgver}.tar.gz::${url}/releases/download/v${pkgver}/Fount-Linux-x64.tar.gz")
sha256sums=('24caed7476762a246977c58baf340bca13ad48ed8c7747acc793d3d4b6c6dc30')
package() {
  install -Dm755 "${srcdir}/fount" "${pkgdir}/usr/bin/fount"
}
