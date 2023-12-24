# Dioxus Retrouter

> code copied from [Dioxus 0.3.2 Router](https://github.com/DioxusLabs/dioxus/tree/v0.3.2/packages/router)



## Overview

This repoistory use for maintain retro-style Dioxus router (before 0.4), I think the old version of router is more friendly to dynamic router.

```rust, ignore
fn app() {
    cx.render(rsx! {
        Router {
            Route { to: "/", Component {} },
            Route { to: "/blog", Blog {} },
            Route { to: "/blog/:id", BlogPost {} },
        }
    })
}
```

You need to enable the right features for the platform you're targeting since these are not determined automatically!

## Contributing

- Report issues on our [issue tracker](https://github.com/dioxuslabs/dioxus/issues).
- Join the discord and ask questions!

## License
This project is licensed under the [MIT license].

[mit license]: https://github.com/DioxusLabs/dioxus/blob/master/LICENSE-MIT

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in Dioxus by you shall be licensed as MIT without any additional
terms or conditions.

