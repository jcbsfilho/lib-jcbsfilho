## <small>1.0.2 (2025-12-10)</small>

* fix: add repository field to package.json ([382eb54](https://github.com/jcbsfilho/lib-jcbsfilho/commit/382eb54))

## <small>1.0.1 (2025-12-10)</small>

* fix: clear npm auth token and disable setup-node default TOKEN in release workflow ([f0f33f3](https://github.com/jcbsfilho/lib-jcbsfilho/commit/f0f33f3))
* fix: move permissions to job level, remove npm update step ([c7e5f5c](https://github.com/jcbsfilho/lib-jcbsfilho/commit/c7e5f5c))
* fix: move permissions to workflow level and update npm to latest version in release workflow ([980d212](https://github.com/jcbsfilho/lib-jcbsfilho/commit/980d212))
* fix: remove global permissions and NPM_TOKEN from release workflow ([3964b7c](https://github.com/jcbsfilho/lib-jcbsfilho/commit/3964b7c))
* fix: remove npm OIDC configuration and auth token cleanup steps from release workflow ([11a084c](https://github.com/jcbsfilho/lib-jcbsfilho/commit/11a084c))
* fix: unset NODE_AUTH_TOKEN and NPM_TOKEN environment variables in release workflow ([70a60e6](https://github.com/jcbsfilho/lib-jcbsfilho/commit/70a60e6))
* fix: update Node.js version from 20 to 24 in release workflow ([a2ba922](https://github.com/jcbsfilho/lib-jcbsfilho/commit/a2ba922))

## 1.0.0 (2025-12-10)


### Bug Fixes

* add NODE_AUTH_TOKEN environment variable to release workflow ([c7db2cd](https://github.com/jcbsfilho/lib-jcbsfilho/commit/c7db2cd20496acebee17746f509a453583181665))
* configure npm OIDC authentication and update tokens ([cea5011](https://github.com/jcbsfilho/lib-jcbsfilho/commit/cea50112282c887017907bde9f0e6248d54a31b0))
* remove npm OIDC configuration step and reset version ([47f2879](https://github.com/jcbsfilho/lib-jcbsfilho/commit/47f287914ae8549da95af769295e41a1323016e6))
