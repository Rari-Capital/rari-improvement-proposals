# RIPs [![Discord](https://img.shields.io/discord/763219451905704026?color=7289da&label=discord)](https://discord.gg/Y6Zy7c2aat) [![Telegram](https://img.shields.io/badge/chat-on%20Telegram-blue.svg)](https://t.me/RariCapitalChat) [![Twitter Follow](https://img.shields.io/twitter/follow/raricapital.svg?label=RariCapital&style=social)](https://twitter.com/raricapital)

Rari Improvement Proposals (RIPs) describe standards for the Rari Capital platform, including core protocol specifications, client APIs, and contract standards.
 
## Contributing

 1. Review [RIP-0](RIPS/RIP-0.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your RIP to your fork of the repository. There is a [template RIP here](rip-X.md).
 4. Submit a Pull Request to Rari’s [RIPs repository](https://github.com/Rari-Capital/Rari-Improvement-Proposals-RIPS-).

Your first PR should be a first draft of the final RIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new RIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a new thread on [gov.yearn.finance](https://gov.yearn.finance/) where people can discuss the RIP as a whole.

If your RIP requires images, the image files should be included in a subdirectory of the `assets` folder for that RIP as follow: `assets/rip-X` (for rip **X**). When linking to an image in the RIP, use relative links such as `../assets/rip-X/image.png`.

When you believe your RIP is mature and ready to progress past the WIP phase, you should ask to have your issue added to the next governance call where it can be discussed for inclusion in a future platform upgrade. If the community agrees to include it, the RIP editors will update the state of your RIP to 'Approved'.

## RIP Statuses

* **WIP** - a RIP that is still being developed.
* **Proposed** - a RIP that is ready to be reviewed in a governance call.
* **Approved** - a RIP that has been accepted for implementation by the Rari community.
* **Implemented** - a RIP that has been released to mainnet.
* **Rejected** - a RIP that has been rejected.
* **Withdrawn** - a RIP that has been withdrawn by the author(s).
* **Deferred** - a RIP that is pending another RIP/some other change that should be bundled with it together.
* **Moribund** - a RIP that was implemented but is now obsolete and requires no explicit replacement.

## Validation

RIPs must pass some validation tests.  The RIP repository ensures this by running tests using [html-proofer](https://rubygems.org/gems/html-proofer) and [yip_validator](https://rubygems.org/gems/yip_validator).

It is possible to run the RIP validator locally:
```
gem install rip_validator
rip_validator <INPUT_FILES>
```

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

