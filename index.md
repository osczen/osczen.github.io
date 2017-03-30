## About Me
Hello world! I am currently a Master student at Cambridge University in the Machine Learning, Speech, and Language Technologies course. Before that, I was an undergraduate CS specialist at the University of Toronto, St. George with a focus in artificial intelligence. My main interests in AI are problems in reinforcement learning/machine learning, natural language processing and planning under uncertainty. I also like to dabble in topics in programming languages from time to time. Generally speaking, I am interested in the interplay between general artificial intelligence and human psychology, and how advances in AI can be made by drawing from observations of how the human mind operates; moreover, I am interested in how these "intelligent processes" can be described using concrete computational models.

## Research
### Decision Making via POMDP with Alternative Rewards, with Prof. Sheila McIlraith, Alberto Camacho</li>
                        
The reward function of a Partially Observable Markov Decision Process is Markovian under classical settings, relying only on the previous state of the system. This project investigates both modeling and algorithmic issues associated with different methods of encoding rewards in POMDPs.

### POMDP in Picture Description Task, NSERC-USRA Research Intern, with Prof. Sheila McIlraith and Prof. Frank Rudzicz

Developed a POMDP model as part of a communicative, intelligent system that guides a person in a picture description task. The project used symbolicPerseus by Pascal Poupart as the primary POMDP-solver.
 
### Network Visualizer for Graph Algorithms (work in progress)

### Teaching
                        <li>CSC324H1: Principles of Programming Languages, Fall 2015</li>
                        <p>
                        Assisted in the teaching of a third-year course covering topics on the principles of programming languages. Course materials covered programming in Racket and Haskell. Held weekly lab tutorials where students can work on lab assignments and ask questions related to the course material.
                        </p>

                        <li>CSC108H1: Intro to Computer Programming, Winter 2015</li>
                        <p>
                        Assisted in the teaching of a first-year intro course to programming as an inverted-classroom TA. Course materials covered programming in Python. Elementary data types, lists, maps. Program structure: control flow, functions, classes, objects, methods. Algorithms and problem solving. Searching, sorting, and complexity. Unit testing.
                        </p>
                    </ul>
                </div>
                <div class ="left">
                    <h1 id="aboutme">About Me</h1>
                    <p>
                    I can be reached by email at oscar[at]cs[dot]toronto[dot]edu
                    </p>
                </div>
            </middle>

            <!-- scroll back to top button-->
            <a href="#" class="scrollup">Top</a>
		</div><!-- /container -->

		<script src="js/toucheffects.js"></script>
        <script type="text/javascript" src="jquery-1.3.2.js"></script>
<!--         <script type="text/javascript">
            $(function() {
                // $('#nav').stop().animate({'opacity':'0'},1000);
                // $('#nav').opacity = 0;
                $(window).scroll(function(){
                    var scrollTop = $(window).scrollTop();

                    /* this variable below defines when the bar should show*/
                    if(scrollTop > 800)
                        /*the number at the very end controls the speed of fadein and fadeout. smaller means faster*/
                        $('#nav').stop().animate({'opacity':'1'},200);
                    else
                        $('#nav').stop().animate({'opacity':'0'},200);
                });

                the code snippet below is unneccsary
                $('#nav').hover(
                    function (e) {
                        var scrollTop = $(window).scrollTop();
                        if(scrollTop > 800){
                            $('#nav').stop().animate({'opacity':'0'},200);
                        }
                    },
                    function (e) {
                        var scrollTop = $(window).scrollTop();
                        if(scrollTop > 0){
                            $('#nav').stop().animate({'opacity':'1'},200);
                        }
                    }
                );
            });
        </script> -->
    <script type="text/javascript">
        $(document).ready(function () {
            $('.scrollup').fadeOut(0);
        $(window).scroll(function () {
            if ($(this).scrollTop() > 100) {
                $('.scrollup').fadeIn();
            } else {
                $('.scrollup').fadeOut();
            }
        });

        $('.scrollup').click(function () {
            $("html, body").animate({
                scrollTop: 0
            }, 400);
            return false;
            });
        });
    </script>
<!--     <script>
var timeOnSlide = 3,
timeBetweenSlides = 1,
animationstring = 'animation',
animation = false,
keyframeprefix = '',
domPrefixes = 'Webkit Moz O Khtml'.split(' '),
pfx = '',
slidy = document.getElementById("slidy");
if (slidy.style.animationName !== undefined) { animation = true; }
if ( animation === false ) {
for ( var i = 0; i < domPrefixes.length; i++ ) {
if ( slidy.style[ domPrefixes[i] + 'AnimationName' ] !== undefined ) {
pfx = domPrefixes[ i ];
animationstring = pfx + 'Animation';
keyframeprefix = '-' + pfx.toLowerCase() + '-';
animation = true;
break;
} } }
if ( animation === false ) {
// animate using a JavaScript fallback, if you wish
} else {
var images = slidy.getElementsByTagName("img"),
firstImg = images[0],
imgWrap = firstImg.cloneNode(false);
slidy.appendChild(imgWrap);
var imgCount = images.length,
totalTime = (timeOnSlide + timeBetweenSlides) * (imgCount - 1),
slideRatio = (timeOnSlide / totalTime)*100,
moveRatio = (timeBetweenSlides / totalTime)*100,
basePercentage = 100/imgCount,
position = 0,
css = document.createElement("style");
css.type = "text/css";
css.innerHTML += "#slidy { text-align: left; margin: 0; font-size: 0; position: relative; width: " + (imgCount * 100) + "%; }";
css.innerHTML += "#slidy img { float: left; width: " + basePercentage + "%; }";
css.innerHTML += "@"+keyframeprefix+"keyframes slidy {";
for (i=0;i<(imgCount-1); i++) {
position+= slideRatio;
css.innerHTML += position+"% { left: -"+(i * 100)+"%; }";
position += moveRatio;
css.innerHTML += position+"% { left: -"+((i+1) * 100)+"%; }";
}
css.innerHTML += "}";
css.innerHTML += "#slidy { left: 0%; "+keyframeprefix+"transform: translate3d(0,0,0); "+keyframeprefix+"animation: "+totalTime+"s slidy infinite; }";
document.body.appendChild(css);
}
</script> -->

	</body>
</html>
