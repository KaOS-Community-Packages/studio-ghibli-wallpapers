pkgname=studio-ghibli-wallpapers
_pkgname=Studio-ghibli-wallpapers
pkgver=f99039a
pkgrel=1
pkgdesc="Wallpapers from Studio Ghibli movies"
url="https://studioghiblimovies.com/"
arch=('x86_64')
license=('CCPL:by-sa')
depends=('')
install=${pkgname}.install
source=("git+https://github.com/bison-paolo/Studio-ghibli-wallpapers.git")
sha1sums=('SKIP')
 
package() {
   cd "${_pkgname}"

   install -dm755 "${pkgdir}/usr/share/wallpapers"
   cp -dpr --no-preserve=ownership "${pkgname}" "${pkgdir}/usr/share/wallpapers/"
}
