# Copyright 2016 Google Inc.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#
################################################################################
#
package(
    default_testonly = 1,
    default_visibility = ["//browsers:__subpackages__"],
)

load("//web:web.bzl", "web_test_archive")

licenses(["reciprocal"])  # MPL 2.0

exports_files(["LICENSE"])

web_test_archive(
    name = "geckodriver",
    archive = "@org_mozilla_geckodriver//file",
    named_files = {
        "GECKODRIVER": "geckodriver",
    },
)
