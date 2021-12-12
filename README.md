# How to build Custom Pallets with Substrate
# Introduction
In this tutorial, we will be building a custom pallet using FRAME. We will glance a look at the Substrate pallet template, using it to build our custom pallet, write test cases and finally publish it.

# Pre-requisite
This blog assumes that you are kind of familiar with the Rust and have a basic understanding of Substrate.

To get started with substrate,  [check out this link](https://docs.substrate.io/v3/getting-started/overview/)

# About FRAME

FRAME (The Framework for Runtime Aggregation of Modularized Entities) is a framework used for runtime development. In substrate, we refer to these modules as Pallets. You can also check out some prebuilt Pallets  [here](https://substrate.dev/docs/en/knowledgebase/runtime/frame#prebuilt-pallets).

# How to Use

Simply fork this project and start your runtime development in `lib.rs`.

## Update Your Package Information

In the `Cargo.toml` file of this template, you should update the name and authors of this pallet:

```rust
[package]
name = "<YOUR_PALLET_NAME>"
version = "0.1.0"
description = '<YOUR_PALLET_DESCRIPTION>'
authors = ["<YOUR_NAME>"]
edition = '2018'
homepage = '<YOUR_HOMEPAGE>'
license = 'Unlicense'
```