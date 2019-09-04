For the following frame

![preview](assets/template-part.png)

use the following code snippet

```tex
  \begingroup
    \setbeamertemplate{footline}{}
    \setbeamercolor{background}{}
    \setbeamercolor{background canvas}{bg=blue}
    \begin{frame}
      \begin{tikzpicture}[remember picture,overlay]
        \draw [color=blue,ultra thick, fill] ($(current page.north east)$) rectangle  ($(current page.north east)+(-5cm,-2cm)$) ;
      \end{tikzpicture}
      \center\Large\textcolor{white}{A Dedicated Part}
    \end{frame}
  \endgroup
```