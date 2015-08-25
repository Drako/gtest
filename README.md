# Google Test

## VERSION

version 1.6

## DESCRIPTION

This is a fork of the [Google testing framework](https://github.com/google/googletest).
I use it for my personal testing needs and it turned out 1.6 worked best for me.

## SYNOPSIS

Put this repo as a submodule in your cmake based project.
Then just `target_link_library` against `contrib::gtest` or just `gtest`
