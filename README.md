netflixintro{
    display: block;
    position: relative;
    width: 300px;
    height: 300px;
    animation-name: zoom-in;
    animation-delay: .5s;
    animation-duracion: 3.5s;;
    animation-timing-function: ease-in;
    animation-fill-mode: forwards;
    background-size: 4000px;
    &[letter="N"]{
      transform-origin: 30% center;
      .helper-1{
          width: 19.5%;
          height: 100%;
          left: 22.4%;
          top: 0;
          transform: rotate(180deg);
          animation-name: fading-lumieres-box;
      }
    }
}
