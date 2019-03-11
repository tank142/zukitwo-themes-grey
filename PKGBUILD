# Maintainer: Chiku < chirantan dot mitra at gmail dot com >

pkgname=zukitwo-themes-grey
pkgver=1
pkgrel=1
pkgdesc="A theme for GTK3, GTK2, Metacity, xfwm4, Gnome Shell and Unity - git version"
arch=('any')
url="http://gnome-look.org/content/show.php/Zukitwo?content=140562"
license=('GPL3')
depends=('gtk-engines' 'gtk-engine-murrine')
optdepends=('gnome-themes-standard: Required for the GTK3 theme'
            'ttf-roboto: Font family for the Gnome Shell theme')
makedepends=('git')
provides=('zukitwo-themes')
conflicts=('zukitwo-themes')
replaces=('zukitwo-themes')
source=("git://github.com/tank142/zukitwo-themes-grey.git")
sha256sums=('SKIP')
package() {
  mkdir -p "$pkgdir/usr/share/themes/"
  cp -r "$srcdir"/zukitwo-themes-grey/Zukitwo "$pkgdir/usr/share/themes/Zukitwo"
  chmod -R +644 "$pkgdir/"
}

# vim:set ts=2 sw=2 et:
