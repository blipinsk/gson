# gson-annotations

This is a repackaging of Google's Gson annotations. Just annotations. Nothing else.

_The only code change that has been made is removing of the `com.google.gson.*` references from `JsonAdapter`'s javadoc._

### Download

*(Download using jitpack.io* ***For version, use the Gson version prefixed with `annotations-`.*** *)*

---

1. Add it in your root `build.gradle` at the end of repositories:

```gradle
repositories {
  //...
  maven { url 'https://jitpack.io' }
}
```

2. Add the dependency
```gradle
dependencies {
  implementation 'com.github.blipinsk:gson-annotations:annotations-2.8.8'
}
```

### License

Gson is released under the [Apache 2.0 license](LICENSE).

```
Copyright 2008 Google Inc.

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

### Disclaimer

This is not an officially supported Google product.
