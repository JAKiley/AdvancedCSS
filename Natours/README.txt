Jonas Web page of resources https://codingheroes.io/resources/

jonas uses BEM (Block Element Modifier) nameing for classes http://getbem.com/

prior to 4/24
Live Server
    Start gtibash terminal in VS Code or can start in Gitbash
    get into directory
    live-Server
---- add instructions on how to install live-server for other Jonas projects


Auto Recompile of Scss
    Start gitbatch terminal in VS Code
    get into directory
    npm run compile:sass

after 4/24 - this will do all of the above
    npm run start 
    remember to uncomment font-icon in HTML when in development


Sass folder uses 7-1 Css
    main.scss pulls all the scss together - compiled is stylesheet.css
    folders
        abstracts
            variables - colors standard one line reusables
            mixiims - reusable multi line code
        base
            animations
            base - html, body (excluding typography)
            typography - headings 
            utiliies - common classes (in HTML)
        components - Butons etc
        layout
            header, footers, nav etc
        pages
        themes
        vendors - third parties like bootstrap

easing.net - transitions for -bezier