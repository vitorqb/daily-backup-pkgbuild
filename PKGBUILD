# Maintainer: Vitor Barbosa <vitorqb@gmail.com>
pkgname=daily-backup
pkgver=0.2.1
pkgrel=1
epoch=
pkgdesc="Daily backup utilities for vitor"
arch=(any)
url=""
license=('GPL')
groups=()
depends=("python3" "curl" "gnupg")
makedepends=()
checkdepends=()
optdepends=("backblaze-b2" "openssh")
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("https://f000.backblazeb2.com/file/daily-backup-releases/$pkgname-$pkgver.tar.gz")
noextract=()
md5sums=('8cbce04d22fb726b95b77fb08418f8e7')
validpgpkeys=()

package() {
    ./install --prefix "$pkgdir"
}
