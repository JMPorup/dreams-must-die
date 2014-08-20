HOWTO
=====

Grab yourself a copy of dreams-must-die.html. This is the master
file. Then download Calibre:

    http://calibre-ebook.com/download
  
Run:

    ebook-convert dreams-must-die.html dreams-must-die.epub \
    --cover dreams-must-die-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "Dreams Must Die" \
    --title-sort "Dreams Must Die" \
    --preserve-cover-aspect-ratio
  
or if you're a Kindle user:

    ebook-convert dreams-must-die.html dreams-must-die.mobi \
    --cover dreams-must-die-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "Dreams Must Die" \
    --title-sort "Dreams Must Die" \
    --prefer-author-sort

or if you just want a PDF:

    ebook-convert dreams-must-die.html dreams-must-die.pdf \
    --cover dreams-must-die-cover.jpg \
    --author-sort "Porup, J.M." \
    --authors "J.M. Porup" \
    --language English \
    --title "Dreams Must Die" \
    --title-sort "Dreams Must Die" \
    --paper-size a4 \
    --pdf-add-toc \
    --pdf-page-numbers \
    --preserve-cover-aspect-ratio \
    --margin-bottom 72 \
    --margin-top 72 \
    --margin-left 72 \
    --margin-right 72
    
Calibre's full command-line interface is documented here:

    http://manual.calibre-ebook.com/cli/ebook-convert.html
