cmake_minimum_required(VERSION 2.8)
include(cmake/rust.cmake)

project(rust-core-foundation)
rust_library(lib.rs)
rust_test(lib.rs)
