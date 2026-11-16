# Fuzzing set up

This folder contains fuzzers for blazingmq

- `s_bmqfuzz_eval.cpp` targets `BNP_Paribas::bmqeval::SimpleEvaluator::compile`
- `s_bmqfuzz_parseutil.cpp` targets `BNP_Paribas::mqbcmd::ParseUtil::parse`
- `s_bmqfuzz_bmqt_uri.cpp` targets `BNP_Paribas::bmqt::UriParser::parse`
