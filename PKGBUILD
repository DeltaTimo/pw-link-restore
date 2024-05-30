pkgname=pw-link-restore
pkgver=1.0
pkgrel=1
pkgdesc="Simple utility script that loads links from a config."
arch=(any)
url=""
depends=(pipewire)
source=(
        "pw-link-restore"
       )
b2sums=(
        "SKIP"
       )
license=('Unlicense')

package() {
  install -d "$pkgdir/usr/bin/"
  install -m755 "$srcdir/pw-link-restore" "$pkgdir/usr/bin/"
} 
