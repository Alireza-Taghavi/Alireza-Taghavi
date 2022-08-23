<style>
@import url(https://fonts.googleapis.com/css?family=Righteous);
body{
background-color: #181818;
}
*, *:before, *:after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  position: relative;
  }

h1 {
  display: inline-block;
  color: white;
  font-family: 'Righteous', serif;
  font-size: 8em; 
  text-shadow: .03em .03em 0 hsl(0,0%,20%);
  letter-spacing: .05em;
    text-align: center;
  }
  h1:after {
    content: attr(data-shadow);
    position: absolute;
    top: 0.65em; left: .06em;
    z-index: -1;
    text-shadow: none;
    background-image:
      linear-gradient(
        45deg,
        transparent 45%,
        hsla(48,20%,90%,1) 45%,
        hsla(48,20%,90%,1) 55%,
        transparent 0
        );
    background-size: .15em .15em;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  
    animation: shad-anim 15s linear infinite;
    }

@keyframes shad-anim {
  0% {background-position: 0 0}
  0% {background-position: 100% -100%}
  }
</style>
<h1 data-shadow='ALIREZA TAGHAVI'>ALIREZA TAGHAVI</h1>