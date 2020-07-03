# live555
add live555,2020.06.25 version

compiler step;
export PREFIX=`pwd`/_install;
./genMakefiles cwm-linux-with-shared-libraries;
make;
make install;

