# zig-wlroots

Idiomatic [Zig](https://ziglang.org/) bindings for
[wlroots](https://github.com/swaywm/wlroots).

*Note: these bindings are early in development and should not be considered
as stable as wlroots*

## Dependencies

`zig-wlroots` of course depends on wlroots and all of its dependencies. In
addition the following zig bindings are required:

- [zig-wayland](https://github.com/ifreund/zig-wayland)
- [zig-xkbcommon](https://github.com/ifreund/zig-xkbcommon)
- [zig-pixman](https://github.com/ifreund/zig-pixman)

## Usage

See [tinwyl.zig][./tinywl/] for an example compositor using zig-wlroots and an example
of how to integrate zig-wlroots and its dependencies into your build.zig.

See the C headers of wlroots for documentation.

## TODO

- [x] Bind enough to port [tinwyl](https://github.com/swaywm/wlroots/tree/master/tinywl)
- [ ] Bind enough to port [river](https://github.com/ifreund/river)
- [ ] Complete bindings
