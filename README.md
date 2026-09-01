# Awesome Homomorphic Encryption with stars

> A curated list of amazing Homomorphic Encryption libraries, software and resources.

## Contents

* [Libraries](#libraries)
* [Toolkits](#toolkits)
* [Applications](#applications)
* [Databases](#databases)
* [Resources](#resources)

## Libraries

Libraries that can be used to implement applications using (Fully) Homomorphic Encryption.

* [fhEVM](https://github.com/zama-ai/fhevm) ⭐ 24,818 | 🐛 128 | 🌐 Rust | 📅 2026-09-01 - Solidity library that enables confidential smart contracts on the Ethereum VM using FHE.
* <a name="SEAL">[Microsoft SEAL](https://github.com/microsoft/SEAL) ⭐ 4,024 | 🐛 113 | 🌐 C++ | 📅 2026-08-28 - C++ FHE library implementing BFV and CKKS schemes.</a>
* <a name="HElib">[HElib](https://github.com/HomEnc/HElib) ⭐ 3,249 | 🐛 194 | 🌐 C++ | 📅 2024-08-01 - BGV scheme with bootstrapping and the Approximate Number CKKS scheme.
* [TFHE-rs](https://github.com/zama-ai/tfhe-rs) ⭐ 1,648 | 🐛 64 | 🌐 Rust | 📅 2026-09-01 - Rust implementation of the TFHE scheme for boolean and integers FHE arithmetics by [Zama](https://github.com/zama-ai).
* <a name="lattigo">[lattigo](https://github.com/ldsec/lattigo) ⭐ 1,441 | 🐛 10 | 🌐 Go | 📅 2026-06-16 - Go library for lattice-based crypto that implements various schemes.
* <a name="tfhe">[tfhe](https://github.com/tfhe/tfhe) ⭐ 1,326 | 🐛 46 | 🌐 C++ | 📅 2025-09-17 - Faster fully HE: Bootstrapping in less than 0.1 seconds.</a>
* <a name="OpenFHE">[OpenFHE](https://github.com/openfheorg/openfhe-development) ⭐ 1,193 | 🐛 95 | 🌐 C++ | 📅 2026-09-01 - C++ FHE library implementing all major schemes along with bootstrapping and scheme switching.
* [TenSEAL](https://github.com/OpenMined/TenSEAL) ⭐ 1,032 | 🐛 138 | 🌐 C++ | 📅 2026-08-22 - Library for HE operations on tensors, built on [Microsoft SEAL](#SEAL), with a Python API.
* [python-paillier](https://github.com/data61/python-paillier) ⭐ 640 | 🐛 23 | 🌐 Python | 📅 2023-08-04 - Partially HE based on Paillier scheme.
* [Pyfhel](https://github.com/ibarrond/Pyfhel) ⭐ 552 | 🐛 7 | 🌐 Cython | 📅 2026-08-31 - A Python wrapper for [SEAL](#SEAL), [HElib](#HElib), and [PALISADE](#PALISADE).
* [NuFHE](https://github.com/nucypher/nufhe) ⚠️ Archived - GPU-accelerated HE library, faster than cuFHE, that implements the [tfhe](#tfhe) algorithms.
* [Cupcake](https://github.com/facebookresearch/Cupcake) ⚠️ Archived - Facebook's Rust library for the (additive version of the) Fan-Vercauteren scheme.
* [blyss](https://github.com/blyssprivacy/sdk) ⭐ 350 | 🐛 8 | 🌐 Rust | 📅 2024-03-21 - Rust FHE library specialized for private information retrieval. Includes bindings to JS & Python.
* [SEAL-python](https://github.com/Huelse/SEAL-Python/) ⭐ 349 | 🐛 0 | 🌐 C++ | 📅 2026-08-03 - Python binding for the [Microsoft SEAL](#SEAL) library.
* [Sunscreen](https://github.com/Sunscreen-tech/Sunscreen) ⭐ 308 | 🐛 16 | 🌐 Rust | 📅 2025-08-31 - Rust compiler for the BFV fully homomorphic encryption scheme.
* [cuFHE](https://github.com/vernamlab/cuFHE) ⭐ 240 | 🐛 8 | 🌐 Cuda | 📅 2021-07-07 - CUDA-accelerated Fully Homomorphic Encryption Library.
* [FHEW](https://github.com/lducas/FHEW) ⭐ 238 | 🐛 5 | 🌐 C++ | 📅 2019-01-03 - A Fully HE library based on [*FHEW: Bootstrapping Homomorphic Encryption in less than a second*](https://eprint.iacr.org/2014/816).
* [Λ ○ λ](https://github.com/cpeikert/Lol) ⭐ 236 | 🐛 12 | 🌐 Haskell | 📅 2021-03-22 - "Lol" Haskell library for ring-based lattice cryptography that supports FHE.
* [node-seal](https://github.com/morfix-io/node-seal) ⭐ 217 | 🐛 0 | 🌐 TypeScript | 📅 2025-11-09 - JavaScript/WebAssembly port of [Microsoft SEAL](#SEAL).
* [cuHE](https://github.com/vernamlab/cuHE) ⭐ 212 | 🐛 4 | 🌐 Cuda | 📅 2017-06-08 - GPU-accelerated HE library for NVIDIA CUDA-Enabled GPUs.
* [NFLlib](https://github.com/quarkslab/NFLlib) ⭐ 181 | 🐛 10 | 🌐 C++ | 📅 2022-10-14 - NTT-based Fast Lattice library specialized on power-of-two polynomials.
* <a name="OpenFHE-Python">[OpenFHE-Python](https://github.com/openfheorg/openfhe-python) ⭐ 161 | 🐛 13 | 🌐 C++ | 📅 2026-05-19 - Python wrapper for [OpenFHE](#OpenFHE).
* [PhantomFHE](https://github.com/encryptorion-lab/phantom-fhe) ⭐ 160 | 🐛 8 | 🌐 Cuda | 📅 2025-01-01 - A CUDA-Accelerated Fully Homomorphic Encryption Library.
* [HEonGPU](https://github.com/Alisah-Ozcan/HEonGPU) ⭐ 138 | 🐛 7 | 🌐 Cuda | 📅 2026-05-11 -  CUDA-accelerated FHE library on GPUs (BFV, CKKS, MPC).
* [petlib](https://github.com/gdanezis/petlib) ⭐ 136 | 🐛 12 | 🌐 Python | 📅 2022-10-26 - Python library that implements a number of Privacy Enhancing Technologies.
* [LightPHE](https://github.com/serengil/LightPHE) ⭐ 105 | 🐛 0 | 🌐 Python | 📅 2026-08-29 - A Python wrapping Partially HE library (RSA, ElGamal, Paillier, Damgard-Jurik, Benaloh, and more).
* [FV-NFLlib](https://github.com/CryptoExperts/FV-NFLlib) ⭐ 62 | 🐛 2 | 🌐 C++ | 📅 2016-07-26 - A header-only library implementing the Fan-Vercauteren scheme.
* <a name="OpenFHE-Rust">[OpenFHE-Rust](https://github.com/fairmath/openfhe-rs) ⭐ 61 | 🐛 8 | 🌐 C++ | 📅 2025-02-26 - Rust wrapper for [OpenFHE](#OpenFHE).
* [krypto](https://github.com/kryptnostic/krypto) ⭐ 52 | 🐛 0 | 🌐 C++ | 📅 2016-10-26 - C++ implementation of multivariate quadratic FHE.
* [FINAL](https://github.com/KULeuven-COSIC/FINAL) ⭐ 51 | 🐛 0 | 🌐 C++ | 📅 2024-09-26 - C++ FHE library based on [NTRU and LWE scheme](https://eprint.iacr.org/2022/074).
* [libScarab](https://github.com/hcrypt-project/libScarab) ⭐ 45 | 🐛 2 | 🌐 Mathematica | 📅 2015-08-26 - C library implementing a FHE scheme using large integers.
* [HEMat](https://github.com/K-miran/HEMat) ⭐ 43 | 🐛 3 | 🌐 C++ | 📅 2019-08-07 - C++ implementation of matrix computation (addition, multiplication, and transposition) using [HEANN](#HEAAN).
* [HEAAN-Python](https://github.com/Huelse/HEAAN-Python) ⭐ 33 | 🐛 5 | 🌐 C++ | 📅 2020-08-27 - Python binding for the [HEANN](#HEAAN) library.
* [libshe](https://github.com/bogdan-kulynych/libshe) ⭐ 27 | 🐛 0 | 🌐 C++ | 📅 2017-08-08 - Symmetric somewhat HE library based on DGHV scheme.
* [cuYASHE](https://github.com/cuyashe-library/cuyashe) ⭐ 9 | 🐛 3 | 🌐 Cuda | 📅 2026-04-06 - Based on leveled fully HE scheme YASHE for GPGPUs.
* [SparkFHE](https://github.com/SpiRITlab/spark) ⭐ 3 | 🐛 0 | 🌐 Scala | 📅 2020-09-30 - Apache Spark with an add-on for FHE computations. See [:page\_facing\_up:](https://homomorphicencryption.org/wp-content/uploads/2019/08/poster_5.pdf).
* <a name="HEAAN">[HEAAN](https://github.com/snucrypto/HEAAN) -  Scheme with native support for fixed point approximate arithmetic.
* <a name="PALISADE">[PALISADE](https://palisade-crypto.org/software-library) - lattice encryption library (superseded by [OpenFHE](#OpenFHE)).

## Toolkits

* [Google's FHE Repository](https://github.com/google/fully-homomorphic-encryption) ⭐ 3,753 | 🐛 2 | 🌐 Starlark | 📅 2026-08-31 - A compiler that converts a subset of C++ programs into FHE circuits implemented in various backend libraries (superseded by [HEIR](#HEIR)).
* [Concrete](https://github.com/zama-ai/concrete) ⭐ 1,574 | 🐛 57 | 🌐 C++ | 📅 2025-12-19 - TFHE compiler for converting Python programs into FHE equivalents.
* [Concrete-ML](https://github.com/zama-ai/concrete-ml) ⭐ 1,448 | 🐛 21 | 🌐 Python | 📅 2026-08-04 - Python-based toolkit for data scientists w/o prior FHE knowledge (using sklearn, pyTorch, XGBoost models).
* <a name="HEIR">[HEIR](https://github.com/google/heir) ⭐ 885 | 🐛 388 | 🌐 MLIR | 📅 2026-09-01 - Google's MLIR-based toolchain for FHE compilers.
* [Cingulata](https://github.com/CEA-LIST/Cingulata) ⭐ 411 | 🐛 4 | 🌐 C++ | 📅 2025-06-13 - Compiler toolchain and RTE for running C++ programs over encrypted data.
* [EVA](https://github.com/microsoft/EVA) ⭐ 261 | 🐛 32 | 🌐 C++ | 📅 2024-07-03 - A compiler and optimizer for the CKKS scheme (targeting [Microsoft SEAL](#SEAL)).
* [E3](https://github.com/momalab/e3) ⭐ 98 | 🐛 1 | 🌐 Pascal | 📅 2023-03-03 - Encrypt-Everything-Everywhere framework for compiling C++ programs with encrypted operands.
* [AWS HE toolkit](https://github.com/awslabs/homomorphic-implementors-toolkit) ⭐ 72 | 🐛 14 | 🌐 C++ | 📅 2024-12-05 - Simplifies the process of designing circuits for the CKKS scheme.
* [ALCHEMY](https://github.com/cpeikert/ALCHEMY) ⭐ 68 | 🐛 4 | 🌐 Haskell | 📅 2020-06-01 - Haskell-based DSLs and interpreters/compilers, build on top of the lattice crypto library Lol.
* [SHEEP](https://github.com/alan-turing-institute/SHEEP) ⚠️ Archived - HE evaluation platform with a set of native benchmarks and a library agnostic language.
* [IBM HElayers](https://github.com/IBM/helayers) ⭐ 48 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2026-06-30 - IBM's FHE SDK for practical and efficient execution of encrypted workloads.
* [T2](https://github.com/TrustworthyComputing/T2-FHE-Compiler-and-Benchmarks) ⭐ 40 | 🐛 0 | 🌐 Java | 📅 2023-12-29 - A cross compiler and standardized benchmarks for FHE computation that targets [lattigo](#lattigo), [HElib](#HElib), [PALISADE](#PALISADE), [Microsoft SEAL](#SEAL), and [tfhe](#tfhe).
* [Marble](https://github.com/MarbleHE/Marble) ⚠️ Archived - C++ framework that translates between nearly plaintext-style user programs and FHE computations.

## Applications

* [tf-encrypted](https://github.com/tf-encrypted/tf-encrypted) ⭐ 1,242 | 🐛 144 | 🌐 Python | 📅 2024-09-25 - Bridge between TensorFlow and the [Microsoft SEAL](#SEAL) library.
* [OpenFHE demo applications](https://github.com/openfheorg/openfhe-development) ⭐ 1,193 | 🐛 95 | 🌐 C++ | 📅 2026-09-01 - Several demo applications that demonstrate some of the capabilities of OpenFHE
  * [logreg-training-examples](https://github.com/openfheorg/openfhe-logreg-training-examples) ⭐ 32 | 🐛 3 | 🌐 C++ | 📅 2025-05-21 - Logistic Regression Training Examples.
  * [genomic-examples](https://github.com/openfheorg/openfhe-genomic-examples) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2026-07-07 - Prototypes for secure genome-wide association studies using homomorphic encryption.
  * [boolean-circuit-evaluator](https://github.com/openfheorg/openfhe-boolean-circuit-evaluator) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2023-10-26 - Demonstration application to read in boolean circuits using multiple formats and execute them in encrypted form based on binfhe module for encrypted boolean logic.
* [Rosetta](https://github.com/LatticeX-Foundation/Rosetta) ⭐ 550 | 🐛 6 | 🌐 C++ | 📅 2022-04-26 - A privacy-preserving framework based on TensorFlow.
* [nGraph-HE](https://github.com/IntelAI/he-transformer) ⚠️ Archived - Deep Learning (DL) with HE through Intel’s DL graph compiler nGraph based on [SEAL](#SEAL).
* [crypto-geofence](https://github.com/Georeactor/crypto-geofence) ⭐ 38 | 🐛 3 | 🌐 JavaScript | 📅 2019-04-10 - Geo-fencing demo application based on Paillier scheme.
* [lattigo-polls](https://github.com/ldsec/lattigo-polls-demo) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2022-09-02 - Web-application for scheduling meetings using [lattigo](#lattigo).
* [Morfix.io](https://morfix.io/sandbox) - Web-based UI to play around with the [Microsoft SEAL](#SEAL) library.
* [OpenMined](https://github.com/OpenMined) - Decentralized data ownership & intelligence based on HE and deep / federated learning.
  * [PySyft](https://github.com/OpenMined/PySyft) ⭐ 10,021 | 🐛 20 | 🌐 Python | 📅 2026-08-28 - Python library for the server/IoT part of the OpenMined's open-source ecosystem.
  * [syft.js](https://github.com/OpenMined/syft.js) ⭐ 150 | 🐛 79 | 🌐 JavaScript | 📅 2023-01-07 - JavaScript library for the web part of the OpenMined's open-source ecosystem.
  * [KotlinSyft](https://github.com/OpenMined/KotlinSyft) ⭐ 89 | 🐛 75 | 🌐 Kotlin | 📅 2021-08-20 - Kotlin library for the Android part of the OpenMined's open-source ecosystem.
  * [SwiftSyft](https://github.com/OpenMined/SwiftSyft) ⭐ 51 | 🐛 55 | 🌐 Swift | 📅 2021-09-06 - Swift library for the iOS part of the OpenMined's open-source ecosystem.
* [Zama's Hugging Face spaces](https://huggingface.co/zama-fhe) - Demo apps showing the power of FHE for real-world use cases.

## Databases

* [ZeroDB](https://github.com/zerodb/zerodb) ⚠️ Archived - E2E encrypted database using proxy re-encryption.
* [CryptDB](https://github.com/CryptDB/cryptdb) ⭐ 520 | 🐛 9 | 🌐 PHP | 📅 2016-12-15 - Protecting confidentiality with encrypted query processing.
* [TimeCrypt](https://github.com/TimeCrypt/timecrypt) ⭐ 48 | 🐛 0 | 🌐 Java | 📅 2020-08-03 - Encrypted time-series database using homomorphic encryption-based access control.
* [Prisma/DB](https://github.com/PrismaDB/PrismaDB) ⭐ 33 | 🐛 10 | 🌐 PowerShell | 📅 2020-08-24 - Security layer for relational database systems.
* [encrypted-mongodb](https://github.com/pdroalves/encrypted-mongodb) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2018-01-15 - Wrapper on MongoDB's Python driver that enables to query encrypted data.

## Resources

* [Barak, Boaz](https://intensecrypto.org/public/lec_15_FHE.html). Chapter about FHE in Barak's introductory book to Cryptography, used for Harvard CS 127.
* [Barthelemy, Lucas](https://blog.quarkslab.com/a-brief-survey-of-fully-homomorphic-encryption-computing-on-encrypted-data.html). Brief survey of Fully HE. 2016.
* [Chen, Zhigang](https://zhigang-chen.github.io/A%20List%20of%20FHE%20Papers.html). A continuously updated list of FHE papers.
* [FHE.org](https://fhe.org). A community of researchers and developers interested in advancing homomorphic encryption.
* [Gentry, Craig](https://crypto.stanford.edu/craig/craig-thesis.pdf). A fully homomorphic encryption scheme. Stanford University, 2009.
* [HomomorphicEncryption.org](https://homomorphicencryption.org). An open industry, government & academic consortium working on standardization of FHE.
* [KU Leuven](https://www.esat.kuleuven.be/cosic/tag/cosic-guide-to-crypto/). An introduction to homomorphic encryption.
* [Micciancio, Daniele](http://cseweb.ucsd.edu/~daniele/LatticeLinks/FHE.html). Links to papers and implementations of Lattice Cryptography schemes.
* [Microsoft Research](https://www.youtube.com/playlist?list=PLD7HFcN7LXRef-eTSGt_XOUJLZNoDINUn). Videos from SEAL/CKKS talks at Microsoft's Private AI Bootcamp.
* [OpenFHE](https://www.openfhe.org). Webinars about the foundations of applied FHE, the latest advances in the OpenFHE project and applications of FHE.
* [Vaikuntanathan, Vinoid](https://people.csail.mit.edu/vinodv/FHE/FHE-refs.html). A list of references about FHE, covering top papers in the field.
* [Zhigang Chen](https://zhigang-chen.github.io/FHE%20Resources.html). A list of English and Chinese FHE and Machine Learning references.

## Related awesome lists

* [awesome-cryptography](https://github.com/sobolevn/awesome-cryptography) ⭐ 7,099 | 🐛 73 | 📅 2026-07-15
* [awesome-crypto-papers](https://github.com/pFarb/awesome-crypto-papers) ⭐ 2,093 | 🐛 4 | 📅 2024-10-17
* [awesome-mpc](https://github.com/rdragos/awesome-mpc) ⭐ 1,995 | 🐛 8 | 📅 2026-07-24 - Multi-Party Computation.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## Like this work?

✨ Star this project on GitHub [![GitHub Repo stars](https://img.shields.io/github/stars/jonaschn/awesome-he?style=social)](https://github.com/jonaschn/awesome-he) ⭐ 1,255 | 🐛 9 | 📅 2025-03-25

🚀 Contribute further [awesome HE](https://github.com/jonaschn/awesome-he/edit/master/README.md) ⭐ 1,255 | 🐛 9 | 📅 2025-03-25 projects

💸 Spare me some ~~coffee~~ tea 🍵 via [Paypal](https://www.paypal.me/JonathanSchneiderDE/3)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Jonathan Schneider has waived all copyright and
related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
