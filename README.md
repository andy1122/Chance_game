# Asaphus_challenge


git clone https://github.com/andy1122/Asaphus_challenge.git


mkdir build

cmake -S . -B build

cmake --build build



To check if test case passed

./build/test/unit_tests 

All tests passed (4 assertions in 4 test cases)


Get more comprehensive view of the test case

cd build

ctest

