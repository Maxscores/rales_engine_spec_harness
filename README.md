# RalesEngine Spec Harness

This gem contains an http-based spec harness for validating
functionality on student implementations of the 
[RalesEngine](https://github.com/turingschool/lesson_plans/blob/master/ruby_03-professional_rails_applications/rails_engine.md)
project at Turing.

## Installation

To use this repository, simply clone it onto your machine and bundle:

```
git clone https://github.com/turingschool/rales_engine_spec_harness.git
cd rales_engine_spec_harness
bundle
export BASE_URL=http://rales-engine-1710.herokuapp.com
```

## Usage

Run the tests with `bundle exec rake`:

```
bundle exec rake

2 runs, 112 assertions, 0 failures, 0 errors, 0 skips
```
