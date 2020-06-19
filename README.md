# PresentationJa
[Presentation Template](https://github.com/m12watanabe1a/PresentationJa/blob/master/presentation.pdf) for Student of Materials Engineering Dep.

## Setup

* Open [info.sty](https://github.com/m12watanabe1a/PresentationJa/blob/master/assets/tex/info.sty)
* Type in your personal information

```bash
 $ git clone https://github.com/m12watanabe1a/PresentationJa.git 
 $ cd ./PresentationJa
 $ vim assets/tex/info.sty
```

```tex
\newcommand{\myname}{
    <first_name> <family_name>
}

\newcommand{\mymail}{
    <your-email>
}

\newcommand{\myorg}{
    <your-organization>
}

\newcommand{\myorgshort}{
    <your-organization-in-short>
}
```

## Compile

```bash
 $ latexmk presentation.tex
```
