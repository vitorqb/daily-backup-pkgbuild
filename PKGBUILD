# Maintainer: Vitor Barbosa <vitorqb@gmail.com>
pkgname=daily-backup
pkgver=0.3.0
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
source=("$pkgname-$pkgver.tar.gz::https://github.com/vitorqb/daily-backup/archive/$pkgver.tar.gz")
noextract=()
md5sums=('f0c4805a4f624f1d60c4921813b9e816')
validpgpkeys=()

package() {
    cd $pkgname-$pkgver
    ./install --prefix "$pkgdir"
}
