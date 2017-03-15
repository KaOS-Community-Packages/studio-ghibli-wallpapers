pkgname=studio-ghibli-wallpapers
_pkgname=Studio-ghibli-wallpapers
pkgver=9ee8ba1
pkgrel=1
pkgdesc="Wallpapers from Studio Ghibli movies"
url="https://studioghiblimovies.com/"
arch=('x86_64')
license=('CCPL:by-sa')
depends=('kservice')
source=("git+https://github.com/mrpable/Studio-ghibli-wallpapers.git")
sha1sums=('SKIP')
 
package() {
   cd "${_pkgname}"

   install -dm755 "${pkgdir}/usr/share/wallpapers"
   cp -dpr --no-preserve=ownership "${pkgname}" "${pkgdir}/usr/share/wallpapers/"
}
