# sneaky-eyes
<svg width="120" height="60" viewBox="0 0 120 60" xmlns="http://www.w3.org/2000/svg">
  <circle cx="40" cy="30" r="20" fill="white" stroke="black" stroke-width="3"/>
  <circle cx="80" cy="30" r="20" fill="white" stroke="black" stroke-width="3"/>
  <circle id="pupil1" cx="40" cy="30" r="8" fill="black"/>
  <circle id="pupil2" cx="80" cy="30" r="8" fill="black">
    <animate 
      attributeName="cx" 
      values="80;85;80;75;80" 
      dur="2s" 
      repeatCount="indefinite" />
  </circle>
  <animate 
    xlink:href="#pupil1" 
    attributeName="cx" 
    values="40;45;40;35;40" 
    dur="2s" 
    repeatCount="indefinite" />
</svg>