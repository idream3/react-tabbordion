## v0.2.3 - 2015-07-05

- Allow Panel props to override ones set by Tabbordion [issue #2](https://github.com/Merri/react-tabbordion/issues/2)
- Add support for shorthand BEM modifier syntax
- Fix a bug where checked prop passed to Panel could be incorrect


## v0.2.2 - 2015-06-30

- Fix crashes with undefined or null children


## v0.2.1 - 2015-06-30

- Make isomorphic rendering possible
- More tests


## v0.2.0 - 2015-06-27

- Set up environment: linting, tests, Travis
- Add first set of tests
- Add support for animators (using height and marginTop)
- Change names of properties passed to non-Panel children of Tabbordion.
- Fix bug in Panel where between, first and last modifiers were applied when not visible.
- Fix incorrect order of merging classNames in Panel.
- Improve documentation.


## v0.1.1 - 2015-06-26

- Fix critical issue where not working with minified React due to differences in React's internals.


## v0.1.0 - 2015-06-26

- Initial release