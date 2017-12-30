# BearLibTerminal.rs [![TravisCI build status](https://travis-ci.org/nabijaczleweli/BearLibTerminal.rs.svg?branch=master)](https://travis-ci.org/nabijaczleweli/BearLibTerminal.rs) [![AppVeyorCI build status](https://ci.appveyor.com/api/projects/status/33799jdins9rctlo/branch/master?svg=true)](https://ci.appveyor.com/project/nabijaczleweli/bearlibterminal-rs/branch/master) [![Licence](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE) [![Crates.io version](http://meritbadge.herokuapp.com/bear-lib-terminal)](https://crates.io/crates/bear-lib-terminal)
[BearLibTerminal](https://bitbucket.org/cfyzium/bearlibterminal) FFI for Rust.

# Requirements
You need to compile/get a precompiled version of [BearLibTerminal](https://bitbucket.org/cfyzium/bearlibterminal) yourself and put it somewhere, where it'll be linkable with `-lBearLibTerminal`.

They can also be found in the [releases](https://github.com/nabijaczleweli/BearLibTerminal.rs/releases).

# Docs
Autoupdated docs can be found [here](https://cdn.rawgit.com/nabijaczleweli/BearLibTerminal.rs/doc/bear_lib_terminal/index.html).

# Recently added feature
The ability to set multiple bitmap fonts by assigning them an alias has been added. This can be done by specifying a bitmap font as described in the above docs then use .font_name("example") to assign that font a alias.  Which can be refered to by wrapping text in the [font=] tags when using the put funcitons.

example: terminal::put_xy(10, 10, "[font=example]@[/font]"); 
