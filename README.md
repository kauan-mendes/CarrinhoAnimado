# CarrinhoAnimado

html{
    box-sizing: border-box;

    --black :#1a1c20 ;
    --white : #fff ;
    --green : #00c380 ;
    --d-green : #019b66 ;
    --gray : #c1c1c1 ;
    --l-gray: #c4c4c4 ;
    --m-gray : #373838 ;
    --d-gray : #282724 ;
    --d-blue: #202428 ;
    --orange : #ef6206 ; 
    --yellow : #dfa500 ;
    --l-yellow: #deb953;
    --light: #fbfbfb ;
    --n-road : -4em;
    --p-road : 7em;

    background-color: var(--green) ;


}

html *,
html *::before,
html *::after{

    box-sizing: inherit ;

}

body::before,
body::after {

    content: " " ;
    position: absolute ;

}

body{

    margin: 0 ;
    height: 100vh ;
    display: flex ;
    overflow: hidden ;
    position: relative ;
    align-items: center ;
    justify-content: center ;
    background-repeat: no-repeat ;
    animation: car 3.5s cubic-bezier(0.57, 0.63, 0.49, 0.65) infinite ;


    background-image : 


    /* ===rubber-l */ 

        radial-gradient(circle at 49% 117%, var(--black) 37%, transparent 38%) ,
        radial-gradient(circle at -24% 50%, var(--white) 31%, transparent 49%) ,
        radial-gradient(2.95em 2.5em at 52% 1.2%, var(--black) 37%, transparent 38%) ,
        radial-gradient(2.95em 2.5em at 52% 1.2%, var(--black) 37%, transparent 38%) ,
        linear-gradient(var(--black) 100%, transparent 0) ,

    /* rubber-l=== */ 

    
    /* ===rubber-r */ 

        radial-gradient(circle at 49% 117%, var(--black) 37%, transparent 38%) ,
        radial-gradient(circle at 124% 50%, var(--white) 31%, transparent 49%) ,
        radial-gradient(2.95em 2.5em at 48% 1.2%, var(--black) 37%, transparent 38%) ,
        radial-gradient(2.95em 2.5em at 48% 1.2%, var(--black) 37%, transparent 38%) ,
        linear-gradient(var(--black) 100%, transparent 0) ,

    /* rubber-r=== */ 


    /* ===shadow */ 

        linear-gradient( var(--d-green) 100% , transparent 0) ;

    /* shadow=== */


    background-size : 


    /* ===rubber-l */ 

        2.5em 2.5em ,
        0.7em 0.6em ,
        2.5em .9em ,
        2.5em .9em ,
        1.95em 3.9em ,

    /* rubber-l=== */


    /* ===rubber-r */ 

        2.5em 2.5em ,
        0.7em 0.6em ,
        2.5em .9em ,
        2.5em .9em ,
        1.95em 3.9em ,

    /* rubber-r=== */ 


    /* ===shadow */ 

        13em .9em ;

    /* shadow=== */

   
    background-position : 


    /* ===rubber-l */ 

        calc(50% - 6.4em) calc(50% - 1.7em) ,
        calc(50% - 5.26em) calc(50% - -3.4em) ,
        calc(50% - 6.5em) calc(50% - -3.8em) ,
        calc(50% - 4.3em) calc(50% - -3.2em) ,
        calc(50% - 6.58em) calc(50% - -1.5em) ,

    /* rubber-l=== */ 

    
    /* ===rubber-r */ 

        calc(50% - -6.45em) calc(50% - 1.7em) ,
        calc(50% - -5.26em) calc(50% - -3.4em) ,
        calc(50% - -6.5em) calc(50% - -3.8em) ,
        calc(50% - -4.3em) calc(50% - -3.2em) ,
        calc(50% - -6.58em) calc(50% - -1.5em) ,

    /* rubber-r=== */ 


    /* ===shadow */ 

        center calc(50% - -3.8em) ;

    /* shadow=== */


}



body::before{
    
    width: 15.5em ;
    height: 62.9em ;
    top: calc(50% - 26.2em) ;
    background-size: 24.6% 491% ;
    background-repeat: no-repeat ;
    background-position: center 0 ;
    animation: line 1.5s infinite linear, move-road 3.5s infinite linear ;
    transform: perspective(311px) rotateX(83deg) translate3d(var(--n-road) ,-11.975em, 0) ;
    background-image: repeating-linear-gradient(to top, var(--white) , var(--white) 4.6%, transparent 0 , transparent 13.01%) ;

}





body::after{

    width: 15.2em ;
    height: 13.2em ;
    top: calc(50% - 8.8em) ;
    left: calc(50% - 7.55em) ;
    background-repeat: no-repeat ;
    animation: light 1s linear infinite,  shake 3.5s linear infinite ;  
    


    background-image : 

    /* ===ceiling */ 

        radial-gradient(58em 20em at 50% 215% , transparent 20% , var(--white) 20.5% , var(--white) 20.8% , var(--green) 21.5%) ,

    /* ceiling=== */


    /* ===antenna */ 

        radial-gradient( circle at center 100% , var(--black)  30% , transparent 0) ,

    /* antenna=== */
    
    
    /* ===antenna */ 

        linear-gradient(var(--white) 100% , transparent 0) ,

    /* antenna=== */


    /* ===glass-l */ 

        radial-gradient( 17.8em 37em at 70% 240% , var(--black) 30% , transparent 30.5%) ,

    /* glass-l=== */


    /* ===glass-r */ 

        radial-gradient( 17.8em 37em at 31% 240% , var(--black) 30% , transparent 30.5%) ,

    /* glass-r=== */


    /* ===light */ 

        radial-gradient( circle , var(--light) 48% ,  var(--black) 52%, var(--black) 59% , transparent 62%) ,

    /* light=== */


    /* ===light */ 

        radial-gradient( circle , var(--light) 48% ,  var(--black) 52%, var(--black) 59% , transparent 62%) ,

    /* light=== */


    /* ===hood-ro */ 

        radial-gradient( 1em 1em at 102% 100% ,   var(--m-gray)  28%, #f3f3f3 30% ) ,

    /* hood-ro=== */


    /* ===hood-ro */ 

        radial-gradient( 1em 1em at 97% -7% ,  var(--m-gray)  28%, var(--l-gray)  30% ) ,

    /* hood-ro=== */


    /* ===hood-ro */ 

        radial-gradient( 1em 1em at -6% 102% ,  var(--m-gray)  28%, #efefef 30% ) ,

    /* hood-ro=== */


    /* ===hood-ro */ 

        radial-gradient( 1em 1em at -6% -1% ,  var(--m-gray)  28%, var(--l-gray)  30% ) ,

    /* hood-ro=== */


    /* ===hood-f */ 

        linear-gradient( to top , var(--m-gray) 50% ,  var(--d-gray) 0, var(--d-gray) 58% , var(--m-gray) 0) ,

    /* hood-f=== */


    /* ===hood-e */ 

        linear-gradient( to top , var(--l-gray) 30% , var(--white) 100% , transparent 0) ,

    /* hood-e=== */


    /* ===hood-l */ 

        radial-gradient( 16.4em 30.1em at 209% 333% , var(--white)  30% , transparent 30.2%) ,

    /* hood-l=== */


    /* ===hood-r */ 

        radial-gradient( 16.4em 30.1em at -109% 333% , var(--white) 30% , transparent 30.2%) ,

    /* hood-r=== */


    /* ===hood-o */ 

        linear-gradient(  var(--gray) 100% , transparent 0) ,

    /* hood-o=== */


    /* ===hood */ 

        linear-gradient( var(--white) 100% , transparent 0) ,

    /* hood=== */


    /* ===mirror */ 

        radial-gradient( 6.7em 2.5em at 154% 8% , var(--black) 30% , transparent 33%) ,

    /* mirror=== */


    /* ===mirror */ 

        radial-gradient( 6.7em 2.5em at -53% 8% , var(--black) 30% , transparent 33%) ,

    /* mirror=== */


    /* ===guide-l */ 

        linear-gradient( var(--orange) 100% , transparent 0) ,

    /* guide-l=== */


    /* ===guide-r */ 

        linear-gradient( var(--orange) 100% , transparent 0) ,

    /* guide-r=== */


    /* ===plaque */ 

        linear-gradient( var(--yellow) 100% , transparent 0) ,

    /* plaque=== */

    
    /* ===plaque */ 

        linear-gradient( var(--l-yellow) 100% , transparent 0) ,

    /* plaque=== */


    /* ===bumper */ 

        linear-gradient( var(--d-blue) 100% , transparent 0) ,

    /* bumper=== */


    /* ===bumper-l */ 

        radial-gradient( circle at 124% 39% , var(--d-blue) 60% , transparent 64%) ,

    /* bumper-l=== */


    /* ===bumper-r */ 

        radial-gradient( circle at -44% 39% , var(--d-blue) 60% , transparent 64%) ,

    /* bumper-r=== */


    /* ===bumper-d */ 

        radial-gradient(13.2em 2em at 50% 59% , var(--l-gray) 96% , transparent 100% ) ,

    /* bumper-d=== */
 
 
    /* ===bumper-l */ 
 
        radial-gradient( 1.6em 1.6em at 75% -9% , var(--l-gray) 60% , transparent 64%) ,

    /* bumper-l=== */


    /* ===bumper-r */ 
 
        radial-gradient( 1.6em 1.6em at 15% -9% , var(--l-gray) 60% , transparent 64%) ,

    /* bumper-r=== */


    /* ===floor */ 
 
        linear-gradient( var(--d-blue) 100% , transparent 0) ,

    /* floor=== */


    /* ===floor-l */ 

        radial-gradient( 6.9em 4.6em at 295% 3% , var(--d-blue) 30% , transparent 31%) ,

    /* floor-l=== */


    /* ===floor-r */ 

        radial-gradient( 6.9em 4.6em at -189% 3% , var(--d-blue) 30% , transparent 31%) ;

    /* floor-r=== */



    background-size : 

    /*=== ceiling */ 

        61.5% 20% ,

    /* ceiling=== */  


    /* ===antenna */ 

        5% 6% ,

    /* antenna=== */


    /*=== antenna */ 

        .4% 39% ,

    /* antenna=== */


    /* ===glass-l */ 

        60% 30% ,

    /* glass-l=== */


    /* ===glass-r */ 

        60% 30% ,

    /* glass-r=== */


    /* ===light */ 

        16% 16% ,

    /* light=== */


    /* ===light */ 

        16% 16% ,

    /* light=== */


    /* ===hood-ro */ 

        2.4% 2%  ,

    /* hood-ro=== */


    /* ===hood-ro */ 

        2.4% 2.3% ,

    /* hood-ro=== */


    /* ===hood-ro */ 

        2.4% 2.3% ,

    /* hood-ro=== */


    /* ===hood-ro */ 

        2.4% 2.3% ,

    /* hood-ro=== */


    /* ===hood-f */ 

        91% 12%  ,

    /* hood-f=== */


    /* ===hood-e */ 

        93.9% 17% ,

    /* hood-e=== */


    /* ===hood-l */ 

        12% 17.5% ,

    /* hood-l=== */


    /* ===hood-r */ 

        12% 17.5% ,

    /* hood-r=== */


    /* ===hood-o */ 

        38% 1.1% ,

    /* hood-o=== */


    /* ===hood */ 

        77% 25% ,

    /* hood=== */


    /* ===mirror */ 

        9% 30% ,

    /* mirror=== */


    /* ===mirror */ 

        9% 30% ,

    /* mirror=== */


    /* ===guide-l */ 

        8.4% 3% ,

    /* guide-l=== */


    /* ===guide-r */ 

        8.4% 3% ,

    /* guide-r=== */


    /* ===plaque */ 

        33% 6.5% ,

    /* plaque=== */


    /* ===plaque */ 

        36% 9% ,

    /* plaque=== */


    /* ===bumper */ 

        87% 30% ,

    /* bumper=== */


    /* ===bumper-l */ 

        10% 12% ,

    /* bumper-l=== */


    /* ===bumper-r */ 

        10% 12% ,

    /* bumper-r=== */


    /* ===bumper-d */ 

        78% 35% ,

    /* bumper-d=== */


    /* ===bumper-l */ 

        11% 8% ,

    /* bumper-l=== */


    /* ===bumper-r */ 

        11% 8% ,

    /* bumper-r=== */


    /* ===floor */ 

        68%  8% ,

    /* floor=== */


    /* ===floor-l */ 

        5% 7% ,

    /* floor-l=== */


    /* ===floor-r */ 

        5% 7% ;

    /* floor-r=== */


    background-position : 


    /*=== ceiling */ 

        50.5% 0 ,
        
    /* ceiling=== */ 


    /* ===antenna */ 

        90% 37% ,

    /* antenna=== */


    /*=== antenna */ 

        88% 1.2% ,
        
    /* antenna=== */ 


    /* ===glass-l */ 

        0 11.7% ,

    /* glass-l=== */


    /* ===glass-r */ 

        100% 11.7% ,

    /* glass-r=== */   


    /* ===light */ 

        5% 63% ,

    /* light=== */ 


    /* ===light */ 

        95% 63% ,

    /* light=== */ 


    /* ===hood-ro */ 

        4.1% 55.7% ,

    /* hood-ro=== */ 


    /* ===hood-ro */ 

        4.1% 65.9% ,

    /* hood-ro=== */ 


    /* ===hood-ro */ 

        95.8% 55.7% ,

    /* hood-ro=== */ 


    /* ===hood-ro */ 

        95.8% 65.8% ,

    /* hood-ro=== */ 


    /* ===hood-f */ 

        center 62% ,

    /* hood-f=== */ 


    /* ===hood-e */ 

        49% 63.6% ,

    /* hood-e=== */

 

    /* ===hood-l */ 

        3.4% 46.2% ,

    /* hood-l=== */ 


    /* ===hood-r */ 

        96.5% 46.2% ,

    /* hood-r=== */


    /* ===hood-o */ 

        center 40.9% ,

    /* hood-o=== */


    /* ===hood */ 

        center 50.3% ,

    /* hood=== */


    /* ===mirror */ 

        5.7% 48.6% ,

    /* mirror=== */ 


    /* ===mirror */ 

        95% 48.6% ,

    /* mirror=== */


    /* ===guide-l */ 

        5% 75.2% ,

    /* guide-l=== */


    /* ===guide-r */ 

        95% 75.2% ,

    /* guide-r=== */


    /* ===plaque */ 

        51% 86%  ,

    /* plaque=== */


    /* ===plaque */ 

        51.5% 87.3%  ,

    /* plaque=== */


    /* ===bumper */ 

        center 71.9% ,

    /* bumper=== */


    /* ===bumper-l */ 

        -0.8% 77.8% ,

    /* bumper-l=== */


    /* ===bumper-r */ 

        101.7% 77.8% ,

    /* bumper-r=== */


    /* ===bumper-d */ 

        center 80.2% ,

    /* bumper-d=== */


    /* ===bumper-l */ 

        4% 85.9% ,

    /* bumper-l=== */


    /* ===bumper-r */ 

        97% 85.9% ,

    /* bumper-r=== */


    /* ===floor */ 

        center 92.5% ,

    /* floor=== */


    /* ===floor-l */ 

        11.7% 92.6% ,

    /* floor-l=== */


    /* ===floor-r */ 

        88.3% 92.6% ;

    /* floor-r=== */

    
}


@keyframes line{

    100%{

        background-position: center 100% ;

    }

} 


@keyframes car{

    15%, 23%{

        transform: translate3d(-2.3em, 0, 0) ;

    }

    36% , 42%{

        transform: translate3d(-.8em, 0, 0) ;

    }

    61%, 71.5%{

        transform: translate3d(2.8em, 0, 0) ;

    }

    81%, 88%{

        transform: translate3d(1.5em, 0, 0) ;
    }

}

@keyframes move-road {

    5.5%{

        transform: perspective(311px) rotateX(83deg) translate3d(var(--n-road) ,-11.975em, 0) ;

    }

    27%, 51%{

        transform: perspective(311px) rotateX(83deg) translate3d(var(--p-road) ,-11.975em, 0) ;

    }

    73%, 100% {

        transform: perspective(311px) rotateX(83deg) translate3d(var(--n-road) ,-11.975em, 0) ;


    }

}

@keyframes light{

    0% , 37%{

        --light: #fbfbfb ;
    }

    50%{

        --light : #f1f1f1 ;
    }
    
    62%{

        --light : #fbfbfb ;
    }

    65%{

        --light: #f1f1f1 ;

    }

    95%{

        --light: #fbfbfb ;

    }

    100%{

         --light: #f1f1f1 ;

    }

}

@keyframes shake {

    5%, 26%{

        transform:  rotate(-1.5deg) ;

    }

    33%, 41%{

        transform:  rotate(-.5deg) ;

    }

    48%, 69%{

        transform: rotate(1.5deg) ;

    }

    80%, 95%{

        transform:  rotate(.5deg) ;
        
    }

}


@media screen and (max-width: 36em) {
    
    html{

        transform: scale(.5) ;

    }


    body::before{
      
        width: 11em ;
        --n-road: -4em ;
        --p-road: 4em ;
      
    }
    

}


