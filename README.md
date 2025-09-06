<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML TUTORIAL</title>
</head>
<body>
    <header>                                        <!--shows that is it heading-->
        <h1 align="center">this is a demo page</h1>
    </header>
    <main>                                          <!--contains main content-->
    <!--04/09/2025-->
    <section>                                       <!--makes separate section-->
    <h1>this is most important line</h1>            <!--heading tag -->
    <h6>this is least important line</h6>
    <p>this is a paragraph</p>                      <!--paragraph tag-->
    </section>
    <hr />                                          <!--line maker-->
    <section>
    <a href="https://google.com">Google</a>     <!--anchor tag = to add a link-->
    <br />                                          <!--line changer-->
    <a href="https://google.com" target="_main">Google</a>      <!--to open the link in next tab-->
    <br />
    <a href="https://google.com"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Google_%22G%22_logo.svg/1200px-Google_%22G%22_logo.svg.png" alt="Google" height="100"></a>                     <!--clickable image link-->
    <br />
    <a href="https://google.com" target="_main"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Google_%22G%22_logo.svg/1200px-Google_%22G%22_logo.svg.png" alt="Google" height="100"></a>              <!--clickable image link in next tab-->
    <br />
    <a href="https://github.com/dashboard">github</a>
    <br />
    <a href="/portfolio.html">my portfolio</a>      <!--relative link-->
    </section>
    <hr />
    <section>
    <!--image adding-->
    <img src="https://avatars.githubusercontent.com/u/215622497?v=4" alt="my photo">    <!--web link-->  
    <br />      
    <img src="/my photo.jpg" alt="my photo" >            <!--local file link-->
    <br />
    <img src="/my photo.jpg" alt="my photo" height="300">   <!--adjust size by height-->
    <br />
    <img src="/my photo.jpg" alt="my photo" width="400">   <!--adjust size by width-->
    <br />
    <img src="/my photo.jpg" alt="my photo" height=300px>   <!--adjust size by height in px-->
    <br />
    <img src="/my photo.jpg" alt="my photo" width=400px>   <!--adjust size by width in px-->
    </section>
    <hr />
    <section>
    <b>to bold a text</b>
    <br />
    <i>to style a text in italic</i>
    <br />
    <u>to underline a text</u>
    <br />
    <b><u>bold and underlined text</u></b>
    </section>
    <hr />
    <!--05/09/2025-->
    <section>
    <big>this makes the text appear big</big>
    <br />
    this is normal text size
    <br />
    <small>this makes the text appear small</small>
    </section>
    <hr />
    <section>
    <p>H<sub>2</sub>O</p>                               <!--subscript tag to shift up-->
    <p>C<sub>6</sub>H<sub>12</sub>O<sub>6</sub></p>
    <p>3<sup>2</sup>=9</p>                              <!--superscript tag to shift down-->
    <p>A<sup>2</sup>+B<sup>2</sup></p>
    </section>
    <hr />
    <section>
    <pre>
        Lorem ipsum         dolor sit, amet consectetur adipisicing elit.
        Impedit voluptatum fugit est dolorum facilis. Dicta, voluptatum eligendi? Quibusdam dicta ullam provident, quaerat qui corrupti optio perspiciatis. Ab accusantium ex debitis.rem
    </pre>
    <!--this makes the text appear as it is writtren,without ignoring spaces and line changing-->
    <!--06/09/2025-->
    </section>
    <hr />
    <section>
        <article>                                   <!--for articles-->
            my story.
        </article>
    </section>
    <hr />
    <aside>                                         <!--dosen't affect ranking of web page-->   
    <img src="https://digitalsynopsis.com/wp-content/uploads/2023/12/creative-ads.jpg" alt="Advertisement image" align="right" height="200">
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <br />
    <h2 align="right" style="font-size: 20px;"><b>25 Genius Ads That Will Make You Look Twice</b></h2>
    </aside>
    <div>                       <!--block element-->
        <p>hello</p>
        <p>what's going on.</p>
    </div>
    <hr />
    <section>
        <h2 align="center">LIST OF BLOCK TAGS</h2>
        <pre align="center" style="font-size: 20px;"><b>
        address         dt          hr          section
      article         fieldset    l           table
      aside           figcaption  main        tfoot
   blockquote      figure      nav         ul
      canvas          footer      noscript    video
    dd              form        ol          div
       h1-h6           p           dl          header
                                             pre </b>
        </pre>
    </section>
    <hr />
    <section>
        <h2 align="center">LIST OF INLINE TAGS</h2>
        <pre align="center" style="font-size: 20px;"><b>
    a         cite         label         script
    abbr      code         map           select
   acronym   dfn          object        small
  b         em           tt            span
    bdo       i            var           strong
 big       img          output        sub
 br        input        q             sup
      button    kbd          samp          textarea
                                       time
        </pre>
    </section>
    <hr />
    </main>
    <footer>                                        <!--makes foot of page-->
        <h3 align="center">contact me at:</h3>
        <pre align="center"> <b>
         demo@gmail.com      9876543210      www.linkedin.com/in/demo
    </b>    </pre>
    </footer>
</body>
</html>
