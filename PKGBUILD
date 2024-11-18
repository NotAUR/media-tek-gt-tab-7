pkgname=("media-tek-gt-tab-7-udev-rules")
pkgrel=1
pkgver=0.0.1
arch=('any')

source+=("99-media-tek-gt-tab-7.rules")
sha512sums+=('b447ebaf9e493f35d39b62ed172287f5f8b6d1a70cff0d51007e8ce7c354b5225257c1a92a5fdbc557d81dcfcf904a04f5f4588cc1574218a46bc42cfd3b143a')

package_media-tek-gt-tab-7-udev-rules() {
  pkgdesc="MediaTek GT Tab 7 udev rules" 

  install -Dm644 99-media-tek-gt-tab-7.rules "${pkgdir}/etc/udev/rules.d/99-media-tek-gt-tab-7.rules"
}
