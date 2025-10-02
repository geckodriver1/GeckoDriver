#  Geckodriver

Proxy for using W3C [WebDriver] compatible clients to interact with
Gecko-based browsers like Firefox.

Geckodriver provides the HTTP API described by the [WebDriver protocol], acting
as a bridge between clients and the Gecko browser engine.

 Official Site: [geckodriver.com](https://geckodriver.com/)

[WebDriver protocol]: https://geckodriver.com/blog/
[WebDriver]: https://geckodriver.com/blog/

---

##  Installation

You can install Geckodriver in two ways:

* **Download binaries** for Windows, macOS, and Linux from our official  
   [Geckodriver Download Page](https://geckodriver.com/download/)

* **Build from source** with the Rust toolchain:  
  - `cargo install geckodriver`, or  
  - Clone the release branch and build manually.

For release notes and version updates, check the  [Geckodriver Changelog](https://geckodriver.com/blog/).

---

##  Documentation

Full documentation and guides are available here:  
 [Geckodriver Documentation](https://geckodriver.com/blog/)

Key resources:  
* WebDriver overview  
* Supported platforms  
* Firefox capabilities  
* Usage examples  
* Debugging and crash analysis  
* Building, testing, and contributing  

---

##  Source Code

Geckodriver is open-source and available under the **Mozilla Public License**.  

 [View Source](https://geckodriver.com/)  

---

##  Custom Builds

If a binary is not available for your platform, you can build Geckodriver manually:  

1. Install the [Rust toolchain](https://geckodriver.com/blog/).  
2. Clone the repository.  
3. Run:  

```sh
cargo build
