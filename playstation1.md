command:

git clone https://github.com/notaz/pcsx_rearmed
cd pcsx_rearmed
git submodule &&  git submodule update



export CFLAGS="-mcpu=cortex-a7 -mfpu=neon-vfpv4 -mfloat-abi=hard -O3"
export CXXFLAGS=$CFLAGS
./configure --platform=libretro
make -j





https://github.com/neilmunday/pes/blob/master/setup/arch-rpi2/install-psx_rearmed.sh
