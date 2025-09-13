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
            <a href="https://github.com/dashboard"  target="_main">github</a>
            <br />
            <a href="/portfolio.html" target="_main">my portfolio</a>      <!--relative link-->
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
                Impedit voluptatum fugit est dolorum facilis. Dicta, voluptatum eligendi? 
                Quibusdam dicta ullam provident, quaerat qui corrupti optio perspiciatis. Ab accusantium ex debitis.rem
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
    <!--13/09/2025-->
        <section>
            <ol>                                            <!--to make an ordered list-->
                <li>Apple</li>                              <!--to write list element-->
                    <ul>                                    <!--to make an unordered list-->
                        <li>Color:red</li>
                        <li>season:winter</li>
                    </ul>
                <li>Mango</li>
                <li>Banana</li>
            </ol>
            <ol type="a">                                            <!--ordered list in lowercase letters-->
                <li>Apple</li>
                <li>Mango</li>
                <li>Banana</li>
            </ol>
            <ol type="A">                                            <!--ordered list in uppercase letters-->
                <li>Apple</li>
                <li>Mango</li>
                <li>Banana</li>
            </ol>
            <ol type="i">                                            <!--ordered list in lowercase romans-->
                <li>Apple</li>
                <li>Mango</li>
                <li>Banana</li>
            </ol>
            <ol type="I">                                            <!--ordered list in uppercase romans-->
                <li>Apple</li>
                <li>Mango</li>
                <li>Banana</li>
            </ol>
            <ol type="1">                                            <!--ordered list in numbers-->
                <li>Apple</li>
                <li>Mango</li>
                <li>Banana</li>
            </ol>
        </section>
        <hr color="blue" size="10">                                <!--hr attribut-->
        <table>                                                    <!--to form a table-->
            <thead>                                                <!--to wrap table head (not visible)-->
                <caption>STUDENT DATA</caption>                    <!--to add caption of table-->
                <tr>                                               <!--to add a row in table-->
                    <th>NAME</th>                                  <!--to add a table head-->
                    <th>ROLL NO</th>
                </tr>
            </thead>
            <tbody>                                                <!--to wrap table body (not visible)-->
                <tr>
                    <td>Sujal</td>                                 <!--to add table data-->
                    <td>2277</td>
                </tr>
                <tr>
                    <td>harsh</td>
                    <td>1256</td>
                </tr>
            </tbody>
        </table>
        <br />
        <table>
            <thead>
                <caption>STUDENT DATA</caption>
                <tr>
                    <th colspan="2">INFORMATION</th>               <!--to equally hover single head on desired number of columns-->
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Sujal</td>
                    <td>2277</td>
                </tr>
            </tbody>
        </table>
        <hr />
        <form action="/action.php">     <!--to collect data from use-->    <!--action defines action to be performe-->    <!--php is for backend-->
            <input type="text" placeholder="TYPE YOUR NAME">    <!--text type is for text-->    <!--placeholder contains the text which will appear when box is empty-->
            <br />
            <br />
            <input type="password" placeholder="PASSWORD">  <!--password type shows only dots on screen,text is hidden-->
            <br />
            <br />
            <input type="radio" value="class XI" name="class">class XI  <!--radio type shows options , but only one can be clicked of same name-->
            <input type="radio" value="class XII" name="class">class XII
            <br />
            <br />
            <label for="11">                    <!--label makes the displayed option clickable-->
                <input type="radio" value="class XI" name="class1" id="11">class XI
            </label>
            <label for="21">
                <input type="radio" value="class XII" name="class1" id="21">class XII
            </label>
            <br />
            <br />
            <h3>SELECT YOUR CLASS</h3>
            <label for="110">
                <input type="radio" value="class XI" name="class2" id="110">class XI
            </label>
            <label for="210">
                <input type="radio" value="class XII" name="class2" id="210">class XII
            </label>
            <br />
            <br />
            <h3>SELECT YOUR SUBJECTS</h3>
            <label for="102">
                <input type="checkbox" value="math" name="subject" id="102">MATH    <!--checkbox is for multiple option selection-->
            </label>
            <br />
            <br />
            <label for="103">
                <input type="checkbox" value="physics" name="subject" id="103">PHYSICS
            </label>
            <br />
            <br />
            <label for="104">
                <input type="checkbox" value="chemistry" name="subject" id="104">chemistry
            </label>
            <br />
            <br />
            <label for="105">
                <input type="checkbox" value="biology" name="subject" id="105">BIOLOGY
            </label>
            <br />
            <br />
            <div id="id1" class="group1">THIS IS FIRST OF G1</div>       <!--can assign group and id-->
            <div id="id2" class="group1">THIS IS SECOND OF G1</div>
            <br />
            <br />
            <textarea name="feedback" id="203" placeholder="PLEASE GIVE YOUR feedback HERE" rows=5></textarea>      <!--typing space for user-->
        </form>
    </main>
    <footer>                                        <!--makes foot of page-->
        <h3 align="center">contact me at:</h3>
        <pre align="center"> <b>
         demo@gmail.com      9876543210      www.linkedin.com/in/demo
    </b>    </pre>
    </footer>
      <header>
    <h1 align="center">MY EDUCATION</h1>
    </header>
    <main>
    <section>
    <h2><pre>
        <img src="https://bser-exam.in/img/boserlogo.png" height="200">
        <p style="font-size: 30px;">    <b>Board of Secondary Education Rajasthan
    PCMB</b></p>
    </pre></h2>
    </section> 
    <hr />
    <hr />
    <section>
    <h2><pre>
        <img src="https://mbmec.weebly.com/uploads/1/3/0/0/130049266/editor/mbm-logo-1.png?1662674703">
        <p style="font-size: 30px;">    <b>M.B.M. Engineering College, Jodhpur
    Bachelor of Engineering, Mining and Mineral Engineering.
    2024 - 2028</b></p>
    </pre></h2> 
    </section>
    </main>
      <header>
   <h1 align="center">MY EXPERIENCES</h1>
   </header>
   <main>
    <section>
   <h2><pre>
        <img src="https://media.licdn.com/dms/image/v2/D4D0BAQGN3Vcm0FCAMg/img-crop_100/B4DZiK0rwWH8AQ-/0/1754675731439?e=1759968000&v=beta&t=GQLDle4V6Oqc4GwH1qiyjEJC1L8R4byzatpizAUSdM4" height="200">
        <p style="font-size: 30px;">    <b>
Project Team Lead
<a href="https://www.linkedin.com/company/spark-mbm/posts/?feedView=all">SPARK MBM</a> 
Jun 2025 - Present ·
Jodhpur, Rajasthan, India
I am leading my team in spark project 1.</b></p>
    </pre></h2>
    </section>
    </main>
      <header>
    <h1 align="center">MY PROJECTS</h1>
    </header>
    <main>
    <section>
    <h2><pre>
        <img src="https://media.licdn.com/dms/image/sync/v2/D4E27AQH3aeZrtyDA-A/articleshare-shrink_160/B4EZjxe3fsGUAs-/0/1756398057729?e=1758384000&v=beta&t=rtN9MRfH3qTZVv_7mpYSA7FTdGBDF7ho2Bkjpar235g" alt="PROJECT LOGO" height="100">
        <p style="font-size: 20px;">    <b>
<a href="https://github.com/sujal-gupta1/Spark-project-1" >spark project 1</a>/ Travel booking system
Jun 2025 - Present
        </b>
    </pre>
    </section>
    </main>
</body>
</html>
