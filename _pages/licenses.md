---
layout: page
title: Licenses
include_in_header: false
---

# Licenses

### JekyllEx

The app is licensed under the [MIT License](https://opensource.org/licenses/MIT).

```
MIT License

Copyright (c) 2021 Gourav Khunger

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Dependencies

#### [Compose Preference](https://github.com/zhanghai/ComposePreference)

```
Copyright 2023 Google LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

#### [Firebase](https://github.com/firebase/firebase-android-sdk)

```
Copyright 2018 Google LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

#### Other

The [`androidx.*` ecosystem](https://github.com/androidx/androidx) and [Material Components](https://github.com/material-components/material-components-android) are licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

```
Copyright 2008 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

### Bootstraped software

A bootstrap is a set of software bundled in a self-contained environment so that it can run without requiring additional configuration or setup.

A big thanks to the developers of the [Termux](https://github.com/termux) team who relentlessly maintain native packages and the environment for the Android platform. Building JekyllEx would not have been possible without their help with my numerous queries and bug reports that they promptly resolved.

The original termux patches are [licensed](https://github.com/termux/termux-packages/blob/master/LICENSE.md#license-for-package-patches) under [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0).

JekyllEx bundles the following software in its [`ruby-android`](https://github.com/jekyllex/ruby-android) bootstrap:

- [`git`](https://github.com/git/git): [GPL-2.0](https://github.com/git/git/blob/master/COPYING)
- [`libxml2`](https://gitlab.gnome.org/GNOME/libxml2): [MIT](https://gitlab.gnome.org/GNOME/libxml2#license)
- [`libxslt`](https://gitlab.gnome.org/GNOME/libxslt): [MIT](https://gitlab.gnome.org/GNOME/libxslt/-/blob/master/Copyright?ref_type=heads)
- [`ruby`](https://github.com/ruby/ruby): [Ruby License](https://www.ruby-lang.org/en/about/license.txt)
- [`github-pages`](https://github.com/github/pages-gem): [MIT](https://github.com/github/pages-gem/blob/master/LICENSE)
- [`coreutils`](https://github.com/coreutils/coreutils): [GPL-3.0](https://github.com/coreutils/coreutils/blob/master/COPYING)
- Dependencies: Respective licenses apply

The latest release of the bootstrap can be found [here](https://github.com/jekyllex/ruby-android/releases/latest).

The patches developed by Termux are maintained for < Android 10. The custom patches for ruby and bundled gems, build scripts and workflows to build the bootstrap for JekyllEx — to work on all Android versions — developed by [Gourav Khunger](https://github.com/gouravkhunger) are licensed under the MIT License.

```
MIT License

Copyright (c) 2022 Gourav Khunger

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
