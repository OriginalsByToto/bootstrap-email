# Upcoming

**BREAKING CHANGES:** `.row-fluid`, `.row-fluid-lg` and `.row-inset` removed
- Margin- & Padding-logic updated
- Grids logic updated. No spacing errors, when rows are used inside other elements
- Bugfix: Preview tag can contain more than 100 characters now

# 1.0.9 (2019-07-12)

- Added border attributes to container IE/MSO fallback
- Set `font-size` and `line-height` to zero on `hr`-tags
- Outlook bugfix, causing random stripes to appear when using margins  

# 1.0.8 (2019-06-23)

- Added `containerWidthFallback` setting to container template

# 1.0.7 (2019-06-20)

- Updated node-sass dependency

# 1.0.6 (2019-04-22)

- Added `content` option to constructor
- Documentation updated

# 1.0.5 (2019-04-21)

- `.row-inset`- and `.row-fluid{-lg}`-class added
- Better padding handling. Block-elements keep full width
- Enhanced sass variables usage
- Attribute inheriting
- Add `text-{sm|lg}-{left|right|center}` classes for responsive text align
- Typography extended
- Other improvments

# 1.0.4 (2019-04-20)

- Fixed bug caused by cheerio (https://github.com/cheeriojs/cheerio/issues/1301)

# 1.0.3 (2019-04-18)

- Make rows fit seamlessly into containers (also fluid containers)
- Enhanced class inheritation into table templates