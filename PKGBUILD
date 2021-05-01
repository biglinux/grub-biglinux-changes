# Maintainer: Bruno Goncalves <bigbruno@gmail.com>

pkgname=grub-biglinux-changes
pkgver=1.0.0
pkgrel=0
arch=('any')
license=('GPL')
url="https://github.com/biglinux/grub-biglinux-changes"
pkgdesc="Change configurations of grub"
depends=('grub')
source=("git+https://github.com/biglinux/grub-biglinux-changes.git")
md5sums=(SKIP)

package() {
    cp -r "${srcdir}/grub-biglinux-changes/grub-biglinux-changes/usr/" "${pkgdir}/"
}


