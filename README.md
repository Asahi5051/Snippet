# Snippet for beginner
```
{
    "report":{
        "prefix": "report",
        "body": [
        "\\documentclass[a4paper,11pt]{ltjsarticle}",
        "",
        "% 数式",
        "\\usepackage{amsmath,amsfonts}",
        "\\usepackage{bm}",
        "% 画像",
        "\\usepackage{graphics}",
        "\\usepackage{graphicx}",
        "\\usepackage{here} %画像の表示位置調整用",
        "\\usepackage{type1cm}",

        "",
        "%A4: 21.0 x 29.7cm",
        "${4}",
        "",
        "\\begin{document}",
        "",
        "\\title{${5}}",
        "\\author{${6}}",
        "\\date{${7:\\today}}",
        "\\maketitle",
        "\\section{}",
        "\\subsection{}",
        "",
        "",
        "$0",
        "",
        "",
        "\\end{document}"
        ],
        "description": "授業レポート用テンプレート"
    },
    "slide":{
        "prefix":"slide",
        "body": [
        "\\documentclass[unicode,11pt]{beamer}",
        "\\usepackage{luatexja}",
        "\\usepackage{amsmath,amsfonts,amssymb}",
        "\\usepackage{mathtools}",
        "\\usepackage{bm}",
        "\\usepackage{graphics}",
        "\\usepackage{graphicx}",
        "\\usepackage{here} %画像の表示位置調整用",
        "\\usepackage{type1cm}",
        "\\renewcommand{\\kanjifamilydefault}{\\gtdefault} %既定をゴシック体に",
        "\\usepackage{ascmac}",
        "\\usepackage{fancybx}",
        "\\usetheme[numbering=fraction]{metropolis}",
        "\\definecolor{Purple}{HTML}{911146}",
        "\\definecolor{Orange}{HTML}{CF4A30}",
        "%...Theme colors are derived from these two elements",
        "\\setbeamercolor{alerted text}{fg=Orange}",
        "%...however you can of course override styles of all elements",
        "\\setbeamercolor{frametitle}{bg=Purple}",
        "",
        "\\title{}",
        "\\subtitle{}",
        "\\date{\\today}",
        "\\author{名前}",
        "\\institute{所属}",
        "\\begin{document}",
        "\\maketitle",
        "\\section{}",
        "\\begin{frame}{}",
        "",
        "\\end{frame}",
        "\\end{document}"
        ],
        "description": "スライド用テンプレート"
    },
    "gazou":{
        "prefix":"gazou",
        "body" : [
        "\\begin{figure}[H]",
        "\\centering",
        "\\includegraphics[scale=]{}",
        "\\caption{}",
        "\\end{figure}",
        "\\vspace{-5mm}"
        ],
        "description": "画像挿入"
    },
    "hyou":{
        "prefix":"hyou",
        "body": [
        "\\begin{table}[H]",
        "\\caption{}",
        "\\label{}",
        "\\centering",
        "\\begin{tabular}{lcr}",
        "\\hline",
        "  &  &  \\\\\\\\",
        "\\hline \\hline",
        "  &  &  \\\\\\\\",
        "  &  &  \\\\\\\\",
        "  &  &  \\\\\\\\",
        "\\hline",
        "\\end{tabular}",
        "\\end{table}"
        ],
        "description": "図表挿入"
    }
}
```
