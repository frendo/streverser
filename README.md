# streverser
bundle gem <name>
# Building, testing and releasing your gem
$ rake build      # Build the gem locally
$ rake install    # Build and install locally
$ rake release    # Build and push to Rubygems
$ rake spec       # Run test files inside gem

# Bump your gem version from the command line
# NOTE: This is for the most recent `bump` version:
$ gem bump patch  # bumps to the next patch version
$ gem bump minor  # bumps to the next minor version
$ gem bump major  # bumps to the next major version

# This is the syntax for the older `bump` version:
$ gem bump --to minor # bumps to the next minor version
$ gem bump --to major # bumps to the next major version
$ gem bump --to 1.1.1 # bumps to the specified version
