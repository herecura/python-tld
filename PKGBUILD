# Maintainer: Anton Grensjö <anton@grensjo.se>
pkgname=python-tld
_realname=tld
pkgver=0.11.9
pkgrel=1
pkgdesc="Extracts the top level domain (TLD) from the URL given"
arch=('any')
url="https://github.com/barseghyanartur/tld"
license=('GPL')
depends=('python' 'python-six')
makedepends=('python-setuptools')
options=(!emptydirs)
source=("https://github.com/barseghyanartur/tld/archive/${pkgver}.tar.gz")
sha256sums=('5df05695e06492a2c40c89229d352c25728ee6c04a647cbbe8e745f32957667f')

package() {
  cd "$srcdir/$_realname-$pkgver"
  python setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
