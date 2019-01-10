# Maintainer: Anton Grensjö <anton@grensjo.se>
pkgname=python-tld
_realname=tld
pkgver=0.9.2
pkgrel=1
pkgdesc="Extracts the top level domain (TLD) from the URL given"
arch=('any')
url="https://github.com/barseghyanartur/tld"
license=('GPL')
depends=('python' 'python-six')
makedepends=('python-setuptools')
options=(!emptydirs)
source=("https://github.com/barseghyanartur/tld/archive/${pkgver}.tar.gz")
sha256sums=('41ff73ad932055e54df50536bd0a9207eeb86076597dd4f8f6a8894c0f6ce1ac')

package() {
  cd "$srcdir/$_realname-$pkgver"
  python setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
