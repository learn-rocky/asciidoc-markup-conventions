# Red Hat Documentation Asciidoc Mark-up Conventions

The Asciidoc-markup-conventions initiative tries to identify the best practises and styles for the Asciidoc Mark-up that is to be used in Red Hat documents. The matter was discussed heavily across all Red Hat documentation teams to reach an agreement on marking up various elements used in the documentation.

Finally, we have come up with a quick reference of the AsciiDoc markup. You can find the latest results at https://redhat-documentation.github.io/asciidoc-markup-conventions. Build status: [![Build Status](https://travis-ci.org/redhat-documentation/asciidoc-markup-conventions.svg?branch=master)](https://travis-ci.org/redhat-documentation/asciidoc-markup-conventions)

## Fedora install

```
[x220@ipa01 asciidoc-markup-conventions]$ sudo dnf install rubygem-asciidoctor rubygem-asciidoctor-pdf
[x220@ipa01 asciidoc-markup-conventions]$ asciidoctor --version
Asciidoctor 2.0.10 [https://asciidoctor.org]
Runtime Environment (ruby 2.7.2p137 (2020-10-01 revision 5445e04352) [x86_64-linux]) (lc:UTF-8 fs:UTF-8 in:UTF-8 ex:UTF-8)
[x220@ipa01 asciidoc-markup-conventions]$

rubygem-asciidoctor-doc.noarch : Documentation for rubygem-asciidoctor
rubygem-asciidoctor-pdf-doc.noarch : Documentation for rubygem-asciidoctor-pdf
rubygem-asciidoctor.noarch : A fast, open source AsciiDoc implementation in Ruby
rubygem-asciidoctor-pdf.noarch : Converts AsciiDoc documents to PDF using Prawn

```

