git clone https://github.com/enumivo/enumivo.git
cd enumivo
git fetch origin enumivo
git checkout -b enumivo origin/enumivo
git submodule update --init --recursive
./enumivo_build.sh
cd build
make install
