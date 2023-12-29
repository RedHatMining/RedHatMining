<svg fill="none" viewBox="0 0 300 120" width="300" height="120" xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">
        <head>
          <style>
            @keyframes glitch {
              0% {
                color: black;
                text-shadow: 0 0 5px purple, 0 0 10px purple;
                transform: none;
              }
              25% {
                color: pink;
                text-shadow: 0 0 5px purple, 0 0 10px purple;
                transform: skew(5deg);
              }
              50% {
                color: purple;
                text-shadow: 0 0 5px pink, 0 0 10px pink;
                transform: skew(-5deg);
              }
              75% {
                color: black;
                text-shadow: 0 0 5px pink, 0 0 10px pink;
                transform: skew(3deg);
              }
              100% {
                color: pink;
                text-shadow: 0 0 5px purple, 0 0 10px purple;
                transform: none;
              }
            }
        
            .glitch-text {
              font-size: 48px;
              font-family: 'Arial', sans-serif;
              animation: glitch 1s infinite;
            }
          </style>
        </head>
        <body>
          <div class="glitch-text">ZAREM Eternity</div>
        </body>
    </foreignObject>
</svg>
