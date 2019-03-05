# Contributing

There are three phases to the Not Yet Awesome Embedded Rust List:

* Adding an item to the list
* Marking an item as a work in progress
* Removing an item from the list

## Adding an item to the list

Anyone can submit an item that they think is not yet awesome to the list. To do this, just [edit the README] for this repo, and add your item to the list.

[edit the README]: https://github.com/rust-embedded/not-yet-awesome-embedded-rust/edit/master/README.md

In order to help people make this thing awesome, your item should meet all of the following criteria:

1. You request is clearly stated, linking to relevant documentation, such as a whitepaper, protocol definition, datasheet, etc.
    * This lets someone know how to implement this request, and make Embedded Rust more awesome.
2. "Success Criteria" for your request are defined, such as "Add PWM support to the iMXRT1050 HAL"
    * This lets the reviewer know when the work is done, so they can remove this item from the list
3. Possible using today's Rust (not blocked by LLVM impl, rustc impl, etc.)
    * For now, we can't accept anything in this list that is not possible with today's (preferrably stable) version of Rust. This keeps items from staying on the list for too long.
4. Your request should be broken into reasonable work packages, such as "Create HAL for XYZ chip", not "support all boards from ABC vendor"
    * This also keeps items from staying on the list for too long

Once you've submitted a PR by editing the README, someone from the WG will review your suggestion to make sure that it meets the criteria above. They'll help you fix any issues with your request. Once the review checklist is complete, and any fixes are made, the item will be added to the list!

## Marking an item as WIP

If you've started addressing one of the items on the Not Yet Awesome Embedded Rust list, you can add your project here, even if you aren't finished yet! This is to help you find contributors who are willing to help you make things awesome.

You can let people know you are working on something by [editing the readme][edit the README], and adding a link to your project. Before adding your project, you should make sure that it meets all the following criteria:

1. You should link to the source project on GitHub/GitLab/etc. Your project must be open source
2. You should state whether outside contributions are welcome
3. Your project must be relevant to the TODO item it addresses
4. Your project must be more than just an empty repo or a placeholder (e.g. just a "hello world" `bin.rs`/`lib.rs` is not enough!)

Once you've submitted a PR by editing the README, someone from the WG will review your suggestion to make sure that it meets the criteria above. They'll help you fix any issues with your request. Once the review checklist is complete, and any fixes are made, the item will be added to the list!

## Removing the item from the TODO list

Once you have made something on the list awesome, we can remove the item from this list! You can do this by [editing the README][edit the README], and removing the item.

When you remove a list from the item, you should let us know what project "fixes" this in your pull request. We'll make sure all of the following criteria are true:


1. Your project addresses the original request fully
2. The crate that addresses the request has been added to the [Awesome Embedded Rust] list
3. The crate has been published on crates.io (or somewhere else where other people can consume it)

Once the above items are complete, the Not Yet Awesome item and all WIP crates are removed from the list. :confetti_ball: :tada:

[Awesome Embedded Rust]: https://github.com/rust-embedded/awesome-embedded-rust
