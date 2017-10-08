# Feature Matrix of Native Build Systems

| Tool | License | URL | Source | Community | Example |
| - | - | - | - | - | - | 
| Make | [![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) | [URL](https://www.gnu.org/software/make/) | [Source](https://git.savannah.gnu.org/cgit/make.git/) | | [Example](https://github.com/Praqma/native-example-make/) |
| Bazel | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) | [URL](https://bazel.build/) | [Source](https://github.com/bazelbuild/bazel) | Google | [Example](https://github.com/Praqma/native-example-bazel/) |
| Buck | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) | [URL](https://buckbuild.com) | [Source](https://github.com/facebook/buck) | Facebook | [Example](https://github.com/Praqma/native-example-buck/) |
| Gradle | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) | [URL](https://gradle.org) | [Source](https://github.com/gradle/gradle) | | [Example](https://github.com/Praqma/native-example-bazel/) |
| Conan | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) | [URL](https://conan.io/) | [Source](https://github.com/conan-io/conan) | | [Example](https://github.com/Praqma/native-example-conan/) |
| SCons | [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) | [URL](http://scons.org/) | [Source](https://bitbucket.org/scons/scons) | | [Example](https://github.com/Praqma/native-example-scons/) |

<!-- | Pants | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) | [URL](https://www.pantsbuild.org/) | [Source](https://github.com/pantsbuild/pants) | Twitter, Foursquare, Square, Medium | |
| Please | [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) | [URL](https://please.build/) | [Source](https://github.com/thought-machine/please) | | | -->

<ul>
{% for member in site.data.tool %}
  <li>
    <a href="https://github.com/{{ tool.github }}">
      {{ tool.name }}
    </a>
  </li>
{% endfor %}
</ul>

## Prerequisites / Requirements / Dependencies

| Tool | Java | Python | - | - | - |
| - | - | - | - | - | - |
| Make | - | - | - | - | - |
| Bazel | - | - | - | - | - |
| Buck | - | - | - | - | - |
| Gradle | - | - | - | - | - |
| Conan | - | - | - | - | - |
| SCons | - | - | - | - | - |

## Supported Builds

| Tool | Java | C++ | Android | iOS | Go |
| - | - | - | - | - | - |
| Make | - | - | - | - | - |
| Bazel | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Buck | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | - |
| Gradle | - | - | - | - | - |
| Conan | - | - | - | - | - |
| SCons | - | - | - | - | - |

## Performance

| Tool | Incremental Builds | Task Output Caching | Incremental Subtasks | Compiler Daemon | Parallel Execution | Parallel Download of Dependencies |
| - | - | - | - | - | - | - |
| Make | | - | - | - | - | - |
| Bazel | - | - | - | - | - | - |
| Buck | - | - | - | - | - | - |
| Gradle | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Conan | - | - | - | - | - | - |
| SCons | - | - | - | - | - | - |

## Build Scans

| Tool | Collaborative Debugging | Compare Builds | Extend and Customize | Track and Export History Across all Builds | - |
| - | - | - | - | - | - |
| - | - | - | - | - | - |
| Make | - | - | - | - | - |
| Bazel | - | - | - | - | - |
| Buck | - | - | - | - | - |
| Gradle | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | - |
| Conan | - | - | - | - | - |
| SCons | - | - | - | - | - |

## Command-Line Interface

| Tool | Task Exclusion | Continuous build | Composite builds | Dry Run | Continue Execution After Failures | Sync Dependency Cache with Repository |
| - | - | - | - | - | - | - |
| - | - | - | - | - | - | - |
| Make | - | - | - | - | - | - |
| Bazel | - | - | - | - | - | - |
| Buck | - | - | - | - | - | - |
| Gradle | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| Conan | - | - | - | - | - | - |
| SCons | - | - | - | - | - | - |

## IDE Support

| Tool | - | - | - | - | - |
| - | - | - | - | - | - |
| Make | - | - | - | - | - |
| Bazel | - | - | - | - | - |
| Buck | - | - | - | - | - |
| Gradle | - | - | - | - | - |
| Conan | - | - | - | - | - |
| SCons | - | - | - | - | - |

## Syntax Highlighting

| Tool | - | - | - | - | - |
| - | - | - | - | - | - |
| Make | - | - | - | - | - |
| Bazel | - | - | - | - | - |
| Buck | - | - | - | - | - |
| Gradle | - | - | - | - | - |
| Conan | - | - | - | - | - |
| SCons | - | - | - | - | - |
