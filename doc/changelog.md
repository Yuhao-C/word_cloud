# Changelog

This is the list of changes to wordcloud between each release. For full
details, see the commit logs at <https://github.com/amueller/word_cloud>

<!--next-version-placeholder-->

## v1.11.2 (2023-03-31)
### Documentation
* Update CONTRIBUTING.md python version ([`b7ca3c1`](https://github.com/Yuhao-C/word_cloud/commit/b7ca3c1bae433f4c18e038209e4e0f45deaff725))

## v1.11.1 (2023-03-31)
### Documentation
* Update CONTRIBUTING.md ([`5ef17d5`](https://github.com/Yuhao-C/word_cloud/commit/5ef17d530e11cd2c8afb74327714c7c57e450ced))

## v1.11.0 (2023-03-29)
### Feature
* Evalution test 222 ([`2dfbdea`](https://github.com/Yuhao-C/word_cloud/commit/2dfbdea6df57b38ddad428c75ac7b397903a521b))

## v1.10.0 (2023-03-29)
### Feature
* Evalution test111 ([`c5f802e`](https://github.com/Yuhao-C/word_cloud/commit/c5f802eb9a8576fdac062af4f30d812041b0634f))

## v1.9.1 (2023-03-28)
### Ci
* Replace test action with pre-commit ([`b1c2cc1`](https://github.com/Yuhao-C/word_cloud/commit/b1c2cc1000d4b1ac913709b88dce6f15ecbd3a41))

## v1.9.0 (2023-03-27)
### Feature
* Add commitzen-branch to check commit message syntax ([`9b523b9`](https://github.com/Yuhao-C/word_cloud/commit/9b523b9b0800ca40f0d87dcf77146c6a000eb14c))
* Add commitzen to check commit message syntax ([`2124df6`](https://github.com/Yuhao-C/word_cloud/commit/2124df660890f3ceeae006c720022416ed292ee4))
* Add commitzen to check commit message syntax ([`d4aa887`](https://github.com/Yuhao-C/word_cloud/commit/d4aa887f77c399f457b836cd00fcfca585f826d1))
*  add pre-commit yaml and actions ([`51f6afa`](https://github.com/Yuhao-C/word_cloud/commit/51f6afa0e7e53f1d600444fe8a73de75df0df6a1))

### Fix
* Add pip install to pytest and add to contributing.md ([`5f5985b`](https://github.com/Yuhao-C/word_cloud/commit/5f5985ba70afcc7b01806fede921480d013d1ae8))
* Add pre-commit to requirements-dev ([`ce5a420`](https://github.com/Yuhao-C/word_cloud/commit/ce5a4207083469f65d1d08756bc5235bb3b31863))
* Remove commitizen ([`423cba0`](https://github.com/Yuhao-C/word_cloud/commit/423cba07d4ef764a52749ac36dc59170c73b4a37))

### Documentation
* Update contributing guide ([`408b767`](https://github.com/Yuhao-C/word_cloud/commit/408b76752c6839f5ab2ef25cf3698c1ef5be0c7c))

### Chore
* Update pre-commit hooks version ([`4446640`](https://github.com/Yuhao-C/word_cloud/commit/44466404245925d1b7c2612d457e8d1840eda0ad))
* Install deps before pre-commit test ([`64a793d`](https://github.com/Yuhao-C/word_cloud/commit/64a793d0c877d27eb8210c2f8a6722b4bd73dadd))
* Exclude files from format fix ([`bcc3aaa`](https://github.com/Yuhao-C/word_cloud/commit/bcc3aaa5808694c0af9d33e2699fe75be61b80e7))
* Add commitizen to check commit msg ([`7ab490b`](https://github.com/Yuhao-C/word_cloud/commit/7ab490bdc00a3f2f78f71e0546a4cbb645e8b3d4))
* Exclude venv in flake8 check ([`628c7b4`](https://github.com/Yuhao-C/word_cloud/commit/628c7b4cb59fd86cc99273c8ef89ffecc8d9b67c))

### Style
* Fix EOF and trailing space ([`0da6930`](https://github.com/Yuhao-C/word_cloud/commit/0da69300770f0e4cd07cca8643ffc1fefd1cfae2))

## v1.8.6 (2023-03-21)
### Ci
* Fix semantic release ([`170c336`](https://github.com/Yuhao-C/word_cloud/commit/170c336380064d71b68605c5f1ad4cfbd1ae182e))
* Use semantic release ([`a3cf446`](https://github.com/Yuhao-C/word_cloud/commit/a3cf4467ca3a9a1125933d4ba11f14cd44466055))

## v1.8.5 (2023-03-20)
### Chore
* Update semantic-release changelog_sections ([`7cc70e9`](https://github.com/Yuhao-C/word_cloud/commit/7cc70e93b7037efc92b7d0ff5b0cbf9ea815583d))

### Ci
* Remove unnecessary unit test in workflow ([`da508dd`](https://github.com/Yuhao-C/word_cloud/commit/da508dd17856636126077a55f4ac26ae3ce3caa3))

## v1.8.4 (2023-03-20)

### Chore

- Replace versioneer with python-semantic-release ([`a486bbb`](https://github.com/Yuhao-C/word_cloud/commit/a486bbb9a03ec9e9d7eca88bd654aa1b5c1ca642))

## WordCloud 1.8.3

- Fix deprecated `numpy.int`.
- Fix styles.

## WordCloud 1.8.1

Release Date 11/11/2020

### Wheels

- Added wheels for Python 3.9.

## WordCloud 1.8.0

### Wheels

- Add support for building wheels for Python 3.8 for all platforms and
  32-bit wheels for windows **only**. See #547 and #549. Contributed
  by @amueller and @jcfr.

### Test

- Update CircleCI configuration to use
  [dockcross/manylinux1-x64](https://github.com/dockcross/dockcross#cross-compilers)
  image instead of obsolete [dockcross/manylinux-x64]{.title-ref} one.
  See #548. Contributed by @jcfr.

## WordCloud 1.7.0

### Features

- Add export of SVG files using `WordCloud.to_svg` by @jojolebarjos.
- Add missing options to the command line interface, [PR
  #527](https://github.com/amueller/word_cloud/pull/527) by
  @dm-logv.

### Bug fixes

- Make bigrams stopword aware, [PR
  #528](https://github.com/amueller/word_cloud/pull/529) by
  @carlgieringer.

## WordCloud 1.6.0

### Features

- Add support to render numbers and single letters using the
  `include_numbers` and `min_word_length` arguments.

### Examples

- Add `phx_glr_auto_examples_parrot.py` example showing another example of image-based coloring and masks.

## WordCloud 1.5.0

### Examples

- Add `sphx_glr_auto_examples_frequency.py` example for understanding how to generate a wordcloud using a dictionary of word frequency. Contributed by @yoonsubKim.
- Add `sphx_glr_auto_examples_wordcloud_cn.py` example. Contributed by @FontTian and improved by @duohappy.

### Features

- Add support for mask contour. Contributed by @jsmedmar.
  - Improve `wordcloud_cli` adding support for `--contour_width` and `--contour_color` named arguments.
  - Improve `wordcloud.WordCloud` API adding support for `contour_width` and `contour_color` keyword arguments.
  - Update `sphx_glr_auto_examples_masked.py` example.
- Update `wordcloud.WordCloud` to
  support `repeat` keyword argument. If set to True, indicates whether
  to repeat words and phrases until `max_words` or `min_font_size` is
  reached. Contributed by @amueller.

### Wheels

- Support installation on Linux, macOS and Windows for Python 2.7,
  3.4, 3.5, 3.6 and 3.7 by updating the Continuous Integration (CI)
  infrastructure and support the automatic creation and upload of
  wheels to [PyPI](https://pypi.org/project/wordcloud). Contributed by
  @jcfr`.
  - Use [scikit-ci](http://scikit-ci.readthedocs.io) to simplify and
    centralize the CI configuration. By having `appveyor.yml`,
    `.circleci/config.yml` and `.travis.yml` calling the scikit-ci
    command-line executable, all the CI steps for all service are
    described in one
    [scikit-ci.yml](https://github.com/amueller/word_cloud/blob/master/scikit-ci.yml)
    configuration file.
  - Use [scikit-ci-addons](http://scikit-ci-addons.readthedocs.io)
    to provide a set of scripts useful to help drive CI.
  - Simplify release process using
    [versioneer](https://github.com/warner/python-versioneer/).
    Release process is now as simple as tagging a release, there is
    no need to manually update version in `__init__.py`.
  - Remove use of miniconda and instead use
    [manylinux](https://www.python.org/dev/peps/pep-0571/) docker
    images.
- Fix installation of the cli on all platforms leveraging
  [entry_points](https://setuptools.readthedocs.io/en/latest/setuptools.html#automatic-script-creation).
  See #420. Contributed by @jcfr.

### Bug fixes

- `wordcloud.WordCloud` API
  - Fix coloring with black image. Contributed by
    @amueller.
  - Improve error message when there is no space on canvas.
    Contributed by @amueller.
- `wordcloud_cli`
  - Fix handling of invalid regexp parameter.
    Contributed by @jcfr.

### Documentation

- Update `wordcloud.WordCloud`
  `color_func` keyword argument documentation explaining how to create
  single color word cloud. Fix #185.
  Contributed by @maifeng.
- Simplify and improve
  [README](https://github.com/amueller/word_cloud#readme). Contributed
  by @amueller.
- Add `wordcloud_cli` document.
  Contributed by @amueller.
- Add `making_a_release` and
  `changelog` documents. Contributed by @jcfr.
- Improve sphinx gallery integration. Contributed by @jcfr.

### Website

- Setup automatic deployment of the website each time the
  master branch is updated. Contributed by
  @jcfr.
- Update [website](https://amueller.github.io/word_cloud) to use Read the Docs Sphinx Theme Contributed by @amueller.

### Test

- Update testing infrastructure. Contributed by
  @jcfr.
  - Switch testing framework from nose to
    [pytest](https://docs.pytest.org).
  - Enforce coding style by running
    [flake8](http://flake8.pycqa.org/en/latest/index.html) each time
    a Pull Request is proposed or the [master]{.title-ref} branch
    updated.
  - Support generating html coverage report locally running
    `pytest`, `coverage html` and opening `htmlcov/index.html`
    document.

## WordCloud 1.4.1

### Bug fixes

- Improve stopwords list. Contributed by @xuhdev.

### Test

- Remove outdated channel and use conda-forge. Contributed by
  @amueller.
- Add test for the command line utility. Contributed by
  @xuhdev.

## WordCloud 1.4.0

See <https://github.com/amueller/word_cloud/compare/1.3.3>\...1.4

## WordCloud 1.3.3

See <https://github.com/amueller/word_cloud/compare/1.3.2>\...1.3.3

## WordCloud 1.3.2

See <https://github.com/amueller/word_cloud/compare/1.2.2>\...1.3.2

## WordCloud 1.2.2

See <https://github.com/amueller/word_cloud/compare/1.2.1>\...1.2.2

## WordCloud 1.2.1

See <https://github.com/amueller/word_cloud/compare/4c7ebf81>\...1.2.1
