# Atom Lustre extension

This extension provides syntax highlighting and snippets for the LUSTRE language on Atom.

Atom is now abandonned, this pckage is not maintained anymore, for VSCode use [https://github.com/MercierCorentin/vscode-lustre](https://github.com/MercierCorentin/vscode-lustre)

## Installation

- Go to `Edit`-> `Preferences`. 
- On the opened tab, go to `Install` on the left menu.
- In the search box search `language-lustre`.
- Install the package `language-lustre`.


## Lustre

Lustre is a "synchronous language based on the dataflow model and designed for the description and verification of real-time systems"[1].

This extension implements Lustre Core syntax highlight and snippets. Lustre Core is described in [1].

[1] The Lustre V6 Reference Manual, Erwan Jahier, Pascal Raymond, Nicolas Halbwachs, [http://www-verimag.imag.fr/DIST-TOOLS/SYNCHRONE/lustre-v6/doc/lv6-ref-man.pdf](http://www-verimag.imag.fr/DIST-TOOLS/SYNCHRONE/lustre-v6/doc/lv6-ref-man.pdf)

## Snippets
| Prefix | Snippet |
|---|---|
| node | Node Header + Body |
| function | Function header + Body |
| node_a | Node Header + Local Variables and Constants declaration +  Body |
| let    | Body |
| extern_n | External node |
| extern_f | External function |
| var | Variable declaration |
| const | Constants declaration |
| type | User type definition |
| struct | Structure definition |
| enum | Enum type definition |

## Issues

For issues you can either create a Github issue or send an email to the maintainer (corentin.mercier(at)irsn.fr).
