# TeachYourselfGameEngineering
<h1>Foreword</h1>
<p>Here is my personal roadmap on how to become a game engineer. I want to share it with you because I feel that the knowledge base should be available to anyone free of charge and the more people we get involved the better.

I use such phrasing as <strong>Game Engineering</strong> because I believe in a scientific approach and I think that a true developer is also an engineer. The ultimate goal is to build your own game engine with advanced features such as rendering system, UI, AI, physics and collision system, networking support etc. 

I'm certain that this roadmap may help you to understand a modern game development approach better as well as widen your technical expertise.</p>

<p>Don't be a spectator, be a participant."</p>
<h1>Contents</h1>
<ol start="0">
  <li><a href="#0-before-we-start">Before we start</a></li>
  <li><a href="#1-math-prerequisites">Math Prerequisites</a></li>
  <li>General Computer Science</li>
  <li>Software Engineering</li>
  <li>Advanced Game Math</li>
  <li>Game Programming</li>
  <li>Computer Graphics</li>
  <li>Game Physics</li>
  <li>User Interface</li>
  <li>Artifficial Intelligence</li>
  <li>Game Sound</li>
  <li>Multiplayer Games</li>
  <li>Some more advices</li>
  <li>Sources</li>
  <li><a href="#aknowledges">Aknowledges</a></li>
</ol>
<h2>0. Before we start</h2>
<h4> Мотивация и дисциплина </h4>
<p>On this journey  of learning a lot of new knowledge you need both a motivation and a proper approach to learn. I strongly suggest you to read <a href="https://www.calnewport.com/books/deep-work/">Deep Work by Cal Newport</a> and <a href="https://barbaraoakley.com/books/learning-how-to-learn/">Learning How To Learn by Barbara Oakley</a> books. These books help you prepare to the hard work and you will be studying much more efficiently. Дисциплина и настрой станут ключевыми оппонентами прокрастинации и фрустрации, которые будут очень часто возникать.
Хочу закончить эти слова сильной цитатой, которую следовать перечитывать каждый раз, когда опускаются руки:</p>
<p>"Никогда не останавливайся на полпути к цели. Ты мечтал, ты начал делать, прикладывать усилия, значит, это было важно для тебя и тебе этого очень сильно хотелось. Не бросай. Ты просто устаешь на пути к мечте, и это не значит, что тебе не хватает мотивации, просто те трудности, которые ты встречаешь на пути, заставляют тебя сомневаться, притормозить, угнетают и делают все, чтобы ты остановился. Но, прошу тебя, не останавливайся. Это одна из уловок. Ты пройди до конца и получи то, что так сильно хотел. Ведь ты это заслуживаешь."
  <h4> Почему книги? </h4>
  <p>Я считаю что лушчий источник знаний - другие люди. Но так как я не могу "прикрепить" к руководству людей, обойдемся самым комплексным способом аккумуляции людских знаний - книгами, в меньше степени статьями и видео, так как, по моему мнению, они более поверхностны (исключение это видео, где в первую очередь целью является визуализация сложно описуемых абстракций и явлений). Так же советую изучать каждую тему используя различные материалы и в различных комбинациях изложения (например, книга + видео). </p>
 <p>"Самое важное не то большое до чего додумались другие, а то маленькое до чего дошел ты сам." </p>
</p> 
<h4>Notation</h4>
<ul>
  <li><strong>Essential resource</strong></li>
  <li>Recommended resource</li>
  <li><em>Additional resource</em></li>
</ul>
 <p>I advise you not to skip recommended resources. Also if you want to become an outstanding game engineer you should deal with all additional resources and try to find any more!</p>
</p>
<h2>1. Math Prerequisites</h2>
<p> The question "Is math necessary for a software engineer?" is disscussed by experts all programming history, but for game engineer math surely is one of most important domains. If you want to work on rendering systems, or design AI systems, or implement physics systems, or develop gameplay features etc, the math will be either a helpful ally or a hateful enemy.
<h3>Contents</h3>
<ol start="1">
  <li><a href="#precalculus">Precalculus</a></li>
  <li><a href="#calculus">Calculus</a></li>
  <li><a href="#linear-algebra-basic">Linear Algebra: Basic</li>
  <li><a href="#probability-theory">Probability Theory</li>
</ol>
<ol>
  <li> <h3>Precalculus</h3>
     <h4>Goal</h4>
        <p>Understanding basic math concepts such as:</p>
        <ul>
          <li> Basis of the number theory
          <li> Polynomial, rational, radical, exponential, and logarithmic functions and be able to solve corresponding equations
          <li> Basis of trygonometry
          <li> Plane and solid geometry
          <li> Basis of probability theory
        </ul>
     <h4>Theory</h4>
     <ul> 
        <li>
          <p><strong>Precalculus 7th Edition by James Stewart</strong></p>
          <img src="https://user-images.githubusercontent.com/31415381/143224298-4032932c-a08e-43f9-a0ca-68380ad5b25e.png" width="200" height="230"/>
        </li>
        <li>
          <p><em>How to Solve It: A New Aspect of Mathematical Method by G. Polya, John H. Conway</em></p>
          <img src="https://user-images.githubusercontent.com/31415381/143228072-f9dbbddd-56fb-4447-bb61-2089e09a5799.png" width="200" height="230"/>
        </li>
     </ul>
     <h4>Practice</h4>
     <ul>
        <li> 
          <p><strong>Pre-Calculus For Dummies: 1,001 Practice Problem by Mary Jane Sterling</strong></p>
          <img src="https://user-images.githubusercontent.com/31415381/148806112-acfa667d-d9a1-4a0c-971c-191afe5c828f.png"  width="200" height="230"/>
        </li>
     </ul>
    <h4>Additional resources</h4>
     <ul>
        <li><a href="https://www.khanacademy.org/math/precalculus">"Precalculus Course" by Khan Academy</a> (recommended)</li>
        <li><a href="https://www.youtube.com/playlist?list=PLl-Np5U6u5E4sv_fgOyo6nsHMWhf3P-6T">"Precalculus: Video Lectures" by Professor V</a>  (<em>additional</em>)</li>
     </ul>
  </li>   
  <li> <h3>Calculus</h3>
     <h4>Goal</h4>
        <p>Understanding math concepts such as:</p>
        <ul>
          <li> Limits
          <li> Derivatives
          <li> Integrals
          <li> Analyzing functions
          <li> Differential equations
        </ul>
     <h4>Theory</h4>
     <ul> 
        <li>
          <p><strong>Calculus 8th Edition by James Stewart</strong></p>
          <img src="https://user-images.githubusercontent.com/31415381/148810039-0e69e056-e075-4e74-a5da-79beec2494eb.png" width="200" height="230"/>
        </li>
        <li>
          <p> Calculus 4th edition by Michael Spivak </p>
          <img src="https://user-images.githubusercontent.com/31415381/150311356-6259ab3a-d89f-4697-a649-a5e10b19230c.png" width="200" height="230"/>
        <li>
          <a href="https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr">"Essence of Calculus" by 3Blue1Brown</a> <strong>(essential)</strong>
        </li>
     </ul>
     <h4>Practice</h4>
     <ul>
        <li> 
          <p><strong>Essential Calculus Skills Practice Workbook with Full Solutions by Chris McMullen</strong></p>
          <img src="https://user-images.githubusercontent.com/31415381/150313504-fe0309f4-d557-45ee-81fc-ccd89d30ac80.png" width="200" height="230"/>
        </li>
        <li>
          <a href="https://tutorial.math.lamar.edu/Problems/CalcI/CalcI.aspx">"Calculus I: Problems" by Paul's Online Notes</a> (recommended)
        </li>
     </ul>
    <h4>Additional resources</h4>
     <ul>
        <li><a href="https://ocw.mit.edu/courses/mathematics/18-01-single-variable-calculus-fall-2006/video-lectures/">"Single Variable Calculus: Video Lectures" by MIT </a>(recommended)</li>
     </ul>
  </li>
    <li> <h3>Linear Algebra: Basic</h3>
     <h4>Goal</h4>
        <p>Understanding math concepts such as:</p>
        <ul>
          <li> Vectors and Vector Space
          <li> Dot and cross product
          <li> Matrices
          <li> System of linear equation
        </ul>
     <h4>Theory</h4>
     <ul> 
        <li>
          <p><strong>Linear Algebra by Serge Lang</strong></p>
          <img src="https://user-images.githubusercontent.com/31415381/150317227-4e3b0872-dd12-4661-8f79-25c809c800e5.png" width="200" height="230"/>
        </li>
        <li>
          <p><em>Linear Algebra by D. Cherney, T. Denton, R. Thomas, A. Waldron</em></p>
          <img src="https://user-images.githubusercontent.com/31415381/150316398-acf1df8b-314b-42b3-93fa-0ce759854f10.png" width="200" height="230"/>
        </li>
        <li>
          <a href="https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab">"Essence of Linear Algebra" by 3Blue1Brown</a> <strong>(essential)</strong>
        </li>
     </ul>
     <h4>Practice</h4>
     <ul>
        <li> 
          <p><strong>Exercises And Problems In Linear Algebra by John M. Erdman</strong></p>
          <img src="https://user-images.githubusercontent.com/31415381/150316981-5bf1fac2-5d2f-46c6-81bb-f47f1dc3e649.png" width="200" height="230"/>
        </li>
     </ul>
  </li>
  <li> <h3>Probability Theory</h3>
     <h4>Goal</h4>
        <p>Understanding math concepts such as:</p>
        <ul>
          <li> Basic Probability
          <li> Compound Probability
          <li> Probability Distributions
          <li> Frequentist Inference
          <li> Bayesian Inference
          <li> Regression Analysis
        </ul>
     <h4>Theory</h4>
     <ul> 
        <li>
          <p><strong>Introduction To Probability by Dimitri P. Bertsekas</strong></p>
          <img src="https://user-images.githubusercontent.com/31415381/150323958-561807a5-a2ff-4622-baad-139ecfd5c152.png" width="200" height="230"/>
        </li>
        <li>
          <p><em>The Nature Of Code by Daniel Shiffman</em></p>
          <img src="https://user-images.githubusercontent.com/31415381/150324594-e6d56a56-3617-4080-8ec6-f97f88d0a769.png" width="200" height="230"/>
        </li>
        <li>
          <a href="https://www.youtube.com/playlist?list=PLZHQObOWTQDOjmo3Y6ADm0ScWAlEXf-fp">"Probabilities of probabilities" by 3Blue1Brown</a> <strong>(essential)</strong>
        </li>
     </ul>
     <h4>Practice</h4>
     <ul>
        <li> 
          <p><strong>Problems in Probability Theory, Mathematical Statistics and Theory of Random Functions by A. A. Sveshnikov</strong></p>
          <img src="https://user-images.githubusercontent.com/31415381/150324839-58a34eca-9624-4d7c-a745-9d511a0fa581.png" width="200" height="230"/>
        </li>
     </ul>
     <h4>Additional resources</h4>
     <ul>
        <li><a href="https://seeing-theory.brown.edu/index.html">"Seeing Theory"</a>(recommended)</li>
     </ul>
  </li>
</ol>

<h2>Aknowledges</h2>
<ul>
  <li>kzolozhkov</li>
  <li>KovarnaKocici</li>
  <li>LuiGiodd</li>
</ul>
