# Copyright 2017 Google Inc.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

licenses(["notice"])  # BSD

exports_files(["LICENSE"])

py_library(
    name = "mock",
    srcs = ["mock/mock.py"],
    visibility = ["//visibility:public"],
    deps = [
        "@funcsigs_1_0_2//:funcsigs",
        "@pbr_1_10_0//:pbr",
        "@six_archive//:six",
    ],
)
