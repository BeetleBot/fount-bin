# Maintainer: BeetleBot <nikarabilla@gmail.com>
pkgname=fount-bin
pkgver=0.8.3
pkgrel=1
pkgdesc="A terminal-based Fountain screenplay editor (Binary)"
arch=('x86_64')
url="https://github.com/BeetleBot/FountTUI"
license=('GPL3')
provides=('fount')
conflicts=('fount')
# We point to the Fount-Linux-x64.tar.gz from your GitHub release
source=("${pkgname}-${pkgver}.tar.gz::${url}/releases/download/v${pkgver}/Fount-Linux-x64.tar.gz")
sha256sums=('0287a95e42e9525d4b34a8d589a15807d32819b5c6cdb43804160552793fca6a')
package() {
  install -Dm755 "${srcdir}/fount" "${pkgdir}/usr/bin/fount"
  install -Dm644 "${srcdir}/assets/linux/fount.desktop" "${pkgdir}/usr/share/applications/fount.desktop"
  install -Dm644 "${srcdir}/assets/icons/Dark-Fount.png" "${pkgdir}/usr/share/icons/hicolor/256x256/apps/fount.png"
}
