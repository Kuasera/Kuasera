
###
###

<br clear="both">

<img align="right" height="150" src="https://media1.tenor.com/m/DW7_R8EkhcgAAAAd/goat-creepy-scary-creepy-goat.gif"  />

###
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="30" alt="csharp logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="30" alt="cplusplus logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="30" alt="java logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="30" alt="nodejs logo"  />
</div>

###

<div align="left">
  <a href="https://discord.com/users/393444435079331860" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="discord logo"  />
  </a>
</div>

###

<br clear="both">

###
###

```cpp
#include <smallBrain.hpp>
//g++ tells me that it could not find "bigBrain.hpp"
#include <WorkCalendar.hpp>
//automatically updated list of works
#include <projects.hpp>
//automatically updated list of projects
//#include <luck.hpp>
//ran out of ^ a long time ago

int32_t main(){
  while(brain.alive){ 
    while(works.empty() && brain.work){
      brain.think(projects[rand() % projects.size()]); 
    }
    while(!works.empty() && brain.work){
      brain.think(works[0]);
    }
    //TODO: FIND ANOTHER THING TO DO
   }
  return 0;
}
```
