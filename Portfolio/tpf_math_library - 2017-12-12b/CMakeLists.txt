cmake_minimum_required(VERSION 3.20)
project(tpf_math_library___2017_12_12b)

set(CMAKE_CXX_STANDARD 14)

include_directories(include)
include_directories(TPF_Math_Library/SHA256)

add_executable(tpf_math_library___2017_12_12b
        include/tpf_detect_leak.h
        include/tpf_enum_combi.h
        include/tpf_enum_permu.h
        include/tpf_gcd_lcm.h
        include/tpf_ncr_npr.h
        include/tpf_prime_factorization.h
        include/tpf_prime_numbers.h
        include/tpf_random.h
        include/tpf_rational_number.h
        include/tpf_set_operation.h
        include/tpf_smart_output.h
        include/tpf_split_range.h
        include/tpf_stop_watch.h
        include/tpf_string.h
        include/tpf_term.h
        include/tpf_traits.h
        include/tpf_types.h
        include/tpf_unsigned_rational.h
        TPF_Math_Library/000-Traits/TraitsSource.cpp
        TPF_Math_Library/001-StopWatch/StopWatchSource.cpp
        TPF_Math_Library/002-Random/RandomSource.cpp
        TPF_Math_Library/003-String/StringSource.cpp
        TPF_Math_Library/004-DetectMemoryLeak/DetectMemoryLeakSource.cpp
        TPF_Math_Library/005-SplitRange/SplitRangeSource.cpp
        TPF_Math_Library/006-PrimeNumbers/PrimeNumbersSource.cpp
        TPF_Math_Library/007-SmartOutput/SmartOutputSource.cpp
        TPF_Math_Library/008-EuclideanAlgorithm/EuclideanAlgorithmSource.cpp
        TPF_Math_Library/009-SetOperation/SetOperationSource.cpp
        TPF_Math_Library/010-PrimeFactorization/PrimeFactorizationSource.cpp
        TPF_Math_Library/011-RationalNumber/RationalNumberSource.cpp
        TPF_Math_Library/012-nCr-nPr/nCr-nPr-Source.cpp
        TPF_Math_Library/013-CombinationPermutation/CombinationPermutationSource.cpp
        TPF_Math_Library/014-ChineseRemainderTheorem/ChineseRemainderTheoremSource.cpp
        TPF_Math_Library/015-FastModuloComputation/FastModuloComputationSource.cpp
        TPF_Math_Library/016-RSA-Algorithm/RSA-Algorithm-Source.cpp
        TPF_Math_Library/017-RSA-Demo/RSA-Demo-Source.cpp
        TPF_Math_Library/SHA256/main.cpp
        TPF_Math_Library/SHA256/sha256.cpp
        TPF_Math_Library/SHA256/sha256.h)
