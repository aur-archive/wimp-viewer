# Maintainer: Trizen <echo dHJpemVueEBnbWFpbC5jb20K | base64 -d>

pkgname=wimp-viewer
pkgver=0.32
pkgrel=1
pkgdesc="List and play videos from wimp.com"
arch=('any')
url="https://github.com/trizen/perl-scripts/blob/master/Visualisators/wimp-viewer"
license=('GPLv3')
depends=('perl-libwww' 'perl-xml-fast' 'youtube-viewer' 'universal-streamer' 'perl-www-mechanize')
source="https://raw.githubusercontent.com/trizen/perl-scripts/master/Visualisators/wimp-viewer"
md5sums=('b4bdc6afbd2b706fa6dddd20463f7cf3')

package() {
  install -Dm 755 "$srcdir/$pkgname" "$pkgdir/usr/bin/$pkgname"
}
