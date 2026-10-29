# Homebrew tap for markdbenson

Homebrew formulas for tools by Mark Benson.

## Dapper

[Dapper](https://github.com/markdbenson/dapper) is a static site generator:
Markdown in, plain HTML out.

    brew install markdbenson/tap/dapper

The formula installs the single-file build of `dapper` attached to each
[GitHub release](https://github.com/markdbenson/dapper/releases). It runs
with the Perl that comes with macOS.

## Updating a formula

For a new Dapper release, from a checkout of the dapper repository:

    packaging/homebrew/update-formula.sh <version> > ../homebrew-tap/Formula/dapper.rb

Then commit and push here.
