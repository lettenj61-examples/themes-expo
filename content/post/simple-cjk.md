+++
title = """Simple Cjk"""
date  = "2018-10-03T23:29:45+09:00"
draft = true
+++

# ようこそ

さりとて……

```rust
extern crate serde;

use serde_json::Value;

pub struct Msg {
    lineno: usize,
    comment: Option<String>,
}

impl Msg {
    pub fn relay(&self) -> bool {
        unimplemented!()
    }
}

```
