Oicana is a toolset for PDF templating using [Typst].

Features:
* Every Oicana template is a valid [Typst] project. This means you can work on the template using the [Typst web app] or other Typst editors.
* Define inputs for your templates. This is the data that can be changed for every compilation of the template.
  * `json` inputs for structured data like invoice items.
  * `blob` inputs for binary data like images.
* Integrations for multiple tech stacks.
  * .NET/C# integration.
  * Typescript/Javascript integration for the browser.
  * Rust and Node.js integrations are work in progress.
* Typst's incremental PDF compilation leads to document compilation in single-digit milliseconds.


[Typst]: https://typst.app/home/
[Typst web app]: https://typst.app/
