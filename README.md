Oicana is a work in progress toolset for PDF templating using [Typst].

Features:
* Every Oicana template is a valid [Typst] project. This means you can, for example, work on the template using the [Typst web app].
* Define input datasets for your templates. This is the data that can be changed for every rendering of the template.
  * "json datasets" for structured data like invoice content
  * "blob datasets" for binary data like logos or other images
* Integrations for multiple tech stacks
  * .NET/C# integration
  * Typescript/Javascript integration for the browser
  * Rust and Node.js integrations are work in progress
* Leverage the incremental PDF compilation of Typst for blazingly fast (down to single digit ms!) document creation


[Typst]: https://typst.app/home/
[Typst web app]: https://typst.app/
