# LIDET (Laboratory of Interactivity and Digital Entretainment Technology)

This is the repository of files used by the LIDET team at the University of Sao Paulo (Brazil). It includes LaTeX templates, image sources, and similar resources.

The LIDET website can be reached through this URL:
http://www.ime.usp.br/~lidet

## Information on Contents

### LaTeX Beamer Presentation Template

This template is prepared to be generated either in a full screen (4:3) or wide screen (16:9) aspect ratio. Just use the proper target in the Makefile:

- The target *full* generates the PDF with the full screen (4:3) aspect ratio.
- The target *wide* generates the PDF with the wide screen (16:9) aspect ratio.
- The target *all* is configured to use the target *wide*.

So, for example, if you want to produce a PDF to use in a presentation with a wide screen projector, compile like this:

```
make wide
```

or simply:

```
make
```

If you want to produce a PDF for regular (old) projectors, compile like this:

```
make full
```

## References:

- The LIDET logo is based on the ChessType true type font created by Carl Krull (http://www.dafont.com/pt/chesstype.font).
