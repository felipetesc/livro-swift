# A Linguagem de Programação Swift

Esse repositório contém o código fonte para *A Linguagem de Programação Swift*
(algumas vezes é abreviada como TSPL, do inglês "The Swift Programming Language"), a qual é publicada em inglês originalmente no endereço elêtronico [docs.swift.org][published]
e que é construída usando [Swift-DocC][docc].

# Nota sobre essa tradução à língua portuguesa

Optou-se pela escolha de uma tradução semântica e interpretativa, pois é usual perder o sentido das ideias e fluídez ao realizar-se traduções. O objetivo não é oferecer apenas a tradução do original, mas garantir que o leitor adquira conhecimento da linguagem de programação, da mesma maneira que o seu original escrito em inglês. Isto é, o original em inglês é percebido como uma "trilha e não um trilho".

Além disso, sempre que possível, tentar-se-á empregar a língua escrita portuguesa objetivando os leitores de Portugal, do Brasil, de Ângola, Moçambique, dentre outros. Sinta-se convidado e bem vindo a solicitação de mudanças, perguntas e també as críticas se espressas com respeito e cordialidade.  

## Contribuições

Para realizar pequenas modificações, tais como, correções de tipos de dados e a modificação de alguns poucos parágrafos, crie uma forca desse repósitorio e solicite uma requisição de [pull](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

O processo formal de contribuição para esse documento ainda está sendo desenvolvido.
Enquanto isso, podes inicar um novo tópico na sessão de discussões, solicitar mudaças mais significativas discutindo sua abordagem e identificar possíveis problemas antes de utilizar muito do seu tempo na escrita da documentação. 

Os conteúdos desse livro sem o [Guia de Estilo Apple][asq]
e do [guia do estilo desse livro][tspl-style]

Arquivos de bugs sobre o conteúdo que usam a [página de problemas][issue], estão no repositório Github.  

Discussões e contribuições seguem o [Código de Conduta Swift][conduct].


Para obteres maiores informações, veja [Contribuindo com a Linguagem de Programação Swift][contributing].

[asg]: https://help.apple.com/applestyleguide/
[bugs]: https://github.com/apple/swift-book/issues
[conduct]: https://www.swift.org/code-of-conduct
[contributing]: /CONTRIBUTING.md
[forum]: https://forums.swift.org/c/swift-documentation/92
[tspl-style]: /Style.md
[published]: https://docs.swift.org/swift-book/documentation/the-swift-programming-language/
[docc]: https://github.com/apple/swift-docc

## Construindo a documentação

Clone esse repositório,
abra o seu emulador de terminal
navegue até a pasta raiz livro-swift, e
execute `docc preview TSPL.docc`

Após algum tempo de espera ao executar o comando acima,
abra  pelo seu explorador de arquivos o link que `ddoc` gerará, na raiz desse novo diretório/ficheiro,
abra o arquivo usando o teu navegador preferido.

> Nota:
>
> If you installed DocC by downloading a toolchain from Swift.org,
> `docc` is located in `usr/bin/`,
> relative to the installation path of the toolchain.
> Make sure your shell's `PATH` environment variable
> includes that directory.
>
> If you installed DocC by downloading Xcode,
> run `xcrun docc preview TSPL.docc` instead.

