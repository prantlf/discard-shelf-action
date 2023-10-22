# Changes

# [3.0.0](https://github.com/prantlf/discard-shelf-action/compare/v2.1.1...v3.0.0) (2023-10-22)

## Features

* Run only in specified branches ([0442f58](https://github.com/prantlf/discard-shelf-action/commit/0442f58f3b9dcbdfe9fc5a2ba252d7e107d26acc))

## BREAKING CHANGES

If you used this action for branches `main` or `master`, your configuration will continue working, because those branches are enabled by default. If you used it for other branches, specify all their names in the input `branches`. If you used this action on all branches, set the input `branches` to `*`.

# [2.1.1](https://github.com/prantlf/discard-shelf-action/compare/v2.1.0...v2.1.1) (2023-10-21)

## Bug Fixes

* Correct inputs for choosing the platfoms to discard ([5cc2e1d](https://github.com/prantlf/discard-shelf-action/commit/5cc2e1d6d878ff9e586c8961244d3b84e94a41aa))

# [2.1.0](https://github.com/prantlf/discard-shelf-action/compare/v2.0.0...v2.1.0) (2023-10-21)

## Features

* Add inputs for choosing the platfoms to unshelve ([7fff944](https://github.com/prantlf/discard-shelf-action/commit/7fff94408b91d2c433956c3349c246463f6c7b0d))

# [2.0.0](https://github.com/prantlf/discard-shelf-action/compare/v1.1.0...v2.0.0) (2023-10-21)

## Chores

* Bump Node.js version from 16 to 20 ([81c80b9](https://github.com/prantlf/discard-shelf-action/commit/81c80b974d6815e36c0e83d34c438338b43628e0))

## BREAKING CHANGES

Although I do not know what could break, because this action runs with its own Node.js version, such change in the build environment might break something unexpectedly. For example, Node.js prefers IPV6 to IPV4 since 17. However, there are no known problems or migration steps necessary.

# [1.1.0](https://github.com/prantlf/discard-shelf-action/compare/v1.0.0...v1.1.0) (2023-10-21)

## Features

* Add input "enable" to optionally skip this action ([aaa5267](https://github.com/prantlf/discard-shelf-action/commit/aaa5267be94d7cfec282604deb44a8dbf3be1388))

# 1.0.0 (2023-10-19)

Initial release
