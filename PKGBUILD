# Maintainer: Jan Boelsche <jan@lagomorph.de>
pkgname='fadein-windows'
pkgver=1.0
pkgrel=1
pkgdesc='compiz config that activates the fade plugin'
packager='Jan Boelsche'
arch=('any')
license=('GPL')
groups=()
depends=(
  'launch-compiz'
)

source=(
  'Default.ini'
)

sha256sums=('21311129f0e24825d03885f49e4341406b9280f229749bf9e4f5a4f5789eb261')

package() {
  home="${pkgdir}/home/auto-login"
  config_dir="${home}/.config/compiz/compizconfig"
	install -Dm 644 -t "${config_dir}" 'Default.ini'
}

