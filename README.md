# A Linguagem de Programação Swift

Esse repositório contém o código fonte para *A Linguagem de Programação Swift*
(algumas vezes é abreviada como TSPL, do inglês "The Swift Programming Language"),
a qual é publicada em inglês originalmente no endereço elêtronico [docs.swift.org][published]
e que é construída usando [Swift-DocC][docc].

# Nota sobre essa tradução à língua portuguesa
Optou-se pela escolha de uma tradução semântica e interpretativa, pois é usual perder o sentido das ideias e fluídez ao realizar-se traduções. O objetivo não é oferecer uma tradução, mas grantir que o leitor adquira conhecimento da linguagem de programação, da mesma maneira que o seu original escrito em inglês. Isto é, o original em inglês é percebido como uma "trilha e não um trilho".
Além disso, sempre que possível, tentar-se-á empregar a língua escrita portuguesa objetivando os leitores de Portugal, do Brasil, de Ângola, Moçambique, dentre outros. Sinta-se convidado e bem vindo a solicitação de mudanças, perguntas e també as críticas se espressas com respeito e cordialidade.  

## Contribuições

Para realizar modificações pequenas, 
como correções de tipos de dados e a modificação de alguns poucos parágrafos,
crie uma forca desse repósitorio e solicite uma requisição de [pull][https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request].

A formal contribution process for this document is still in development.
In the meantime,
start a pitch thread in the [Swift forums][forum] for larger changes
to discuss your approach and identify possible issues
before you invest a lot of time in writing.

Content in this book follows [Apple Style Guide][asg]
and [this book’s style guide][tspl-style].

File bugs about the content using the [issues page][bugs] on Github.

Discussions and contributions follow the [Swift Code of Conduct][conduct].

For more information, see [Contributing to The Swift Programming Language][contributing].

[asg]: https://help.apple.com/applestyleguide/
[bugs]: https://github.com/apple/swift-book/issues
[conduct]: https://www.swift.org/code-of-conduct
[contributing]: /CONTRIBUTING.md
[forum]: https://forums.swift.org/c/swift-documentation/92
[tspl-style]: /Style.md
[published]: https://docs.swift.org/swift-book/documentation/the-swift-programming-language/
[docc]: https://github.com/apple/swift-docc

## Building

Run `docc preview TSPL.docc`
in this repository's root directory.

After running DocC, open the link that `docc` outputs
to display a local preview in your browser.

> Note:
>
> If you installed DocC by downloading a toolchain from Swift.org,
> `docc` is located in `usr/bin/`,
> relative to the installation path of the toolchain.
> Make sure your shell's `PATH` environment variable
> includes that directory.
>
> If you installed DocC by downloading Xcode,
> run `xcrun docc preview TSPL.docc` instead.

