[![GitHub license](https://img.shields.io/github/license/microsoft/Web-Dev-For-Beginners.svg)](https://github.com/microsoft/Web-Dev-For-Beginners/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/Web-Dev-For-Beginners.svg)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/Web-Dev-For-Beginners.svg)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/Web-Dev-For-Beginners.svg)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/Web-Dev-For-Beginners.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/Web-Dev-For-Beginners.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/Web-Dev-For-Beginners.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/microsoft/Web-Dev-For-Beginners/stargazers/)


# തുടക്കക്കാർക്കുള്ള വെബ് വികസനം - ഒരു പാഠ്യപദ്ധതി

മൈക്രോസോഫ്റ്റിലെ അസുർ ക്ലൗഡ് അഡ്വക്കേറ്റ്സ് ജാവാസ്ക്രിപ്റ്റ്, സിഎസ്എസ്, എച്ച്ടിഎംഎൽ അടിസ്ഥാനകാര്യങ്ങൾ എന്നിവയെക്കുറിച്ച് 12-ആഴ്ച, 24-പാഠ പാഠ്യപദ്ധതി വാഗ്ദാനം ചെയ്യുന്നതിൽ സന്തോഷമുണ്ട്. ഓരോ പാഠത്തിലും പാഠത്തിന് മുമ്പും ശേഷവുമുള്ള ക്വിസുകൾ, പാഠം പൂർത്തിയാക്കാനുള്ള രേഖാമൂലമുള്ള നിർദ്ദേശങ്ങൾ, ഒരു പരിഹാരം, ഒരു അസൈൻമെന്റ് എന്നിവയും അതിലേറെയും ഉൾപ്പെടുന്നു. ഞങ്ങളുടെ പ്രോജക്റ്റ് അധിഷ്‌ഠിത അദ്ധ്യാപനം പുതിയ കഴിവുകൾ 'എത്തിപ്പിടിക്കാൻ' തെളിയിക്കപ്പെട്ട ഒരു മാർഗം നിർമ്മിക്കുമ്പോൾ പഠിക്കാൻ നിങ്ങളെ അനുവദിക്കുന്നു. 

**ഞങ്ങളുടെ രചയിതാക്കളായ ജെൻ ലൂപ്പർ, ക്രിസ് നോറിംഗ്, ക്രിസ്റ്റഫർ ഹാരിസൺ, ജാസ്മിൻ ഗ്രീൻവേ, യോഹാൻ ലസോർസ, ഫ്ലോർ ഡ്രീസ്, സ്കെച്ച്നോട്ട് ആർട്ടിസ്റ്റ് ടോമിമി ഇമുറ എന്നിവർക്ക് ഹൃദയം നിറഞ്ഞ നന്ദി!**

# ആമുഖം

> **അദ്ധ്യാപകർ**, ഞങ്ങൾ [ചില നിർദ്ദേശങ്ങൾ ഉൾപ്പെടുത്തിയിട്ടുണ്ട്](for-teachers.md) ഈ പാഠ്യപദ്ധതി എങ്ങനെ ഉപയോഗിക്കാം എന്നതിനെക്കുറിച്ച്. നിങ്ങളുടെ ഫീഡ്‌ബാക്ക് ഞങ്ങൾ ഇഷ്ടപ്പെടുന്നു [ഞങ്ങളുടെ ചർച്ചാ ഫോറത്തിൽ](https://github.com/microsoft/Web-Dev-For-Beginners/discussions/categories/teacher-corner)!

> **വിദ്യാർത്ഥികൾ**, ഈ പാഠ്യപദ്ധതി സ്വന്തമായി ഉപയോഗിക്കുന്നതിന്, മുഴുവൻ റിപ്പോയും ഫോർക്ക് ചെയ്ത് സ്വന്തമായി വ്യായാമങ്ങൾ പൂർത്തിയാക്കുക, പ്രീ-ലെക്ചർ ക്വിസിൽ തുടങ്ങി, പ്രഭാഷണം വായിച്ച് ബാക്കി പ്രവർത്തനങ്ങൾ പൂർത്തിയാക്കുക. പരിഹാര കോഡ് പകർത്തുന്നതിനുപകരം പാഠങ്ങൾ മനസിലാക്കിക്കൊണ്ട് പ്രോജക്ടുകൾ സൃഷ്ടിക്കാൻ ശ്രമിക്കുക; എന്നിരുന്നാലും ആ പ്രോജക്റ്റ് അധിഷ്ടിതം  പാഠത്തിലെ /സൊല്യൂഷൻസ് ഫോൾഡറുകളിൽ ആ കോഡ് ലഭ്യമാണ്. മറ്റൊരു ആശയം സുഹൃത്തുക്കളുമായി ഒരു പഠന ഗ്രൂപ്പ് രൂപീകരിച്ച് ഒരുമിച്ച് ഉള്ളടക്കം പരിശോധിക്കുക എന്നതാണ്. കൂടുതൽ പഠനത്തിന്, ഞങ്ങൾ ശുപാർശ ചെയ്യുന്നു [മൈക്രോസോഫ്റ്റ് ലേൺ](https://docs.microsoft.com/users/jenlooper-2911/collections/jg2gax8pzd6o81?WT.mc_id=academic-13441-cxa) കൂടാതെ താഴെ സൂചിപ്പിച്ചിരിക്കുന്ന വീഡിയോകൾ കണ്ടുകൊണ്ട്.

[![Promo video](screenshot.png)](https://youtube.com/watch?v=R1wrdtmBSII "Promo video")

> 🎥 പ്രോജക്റ്റിനെക്കുറിച്ചും അത് സൃഷ്ടിച്ചവരെക്കുറിച്ചും ഒരു വീഡിയോയ്ക്കായി മുകളിലുള്ള ചിത്രത്തിൽ ക്ലിക്കുചെയ്യുക!

## അദ്ധ്യാപനo

ഈ പാഠ്യപദ്ധതി നിർമ്മിക്കുമ്പോൾ ഞങ്ങൾ രണ്ട് പെഡഗോഗിക്കൽ സിദ്ധാന്തങ്ങൾ തിരഞ്ഞെടുത്തു: ഇത് പ്രോജക്റ്റ് അടിസ്ഥാനമാക്കിയുള്ളതാണെന്നും അതിൽ പതിവ് ക്വിസുകൾ ഉൾപ്പെടുന്നുവെന്നും ഉറപ്പാക്കുന്നു. ഈ പരമ്പരയുടെ അവസാനത്തോടെ, വിദ്യാർത്ഥികൾ ഒരു ടൈപ്പിംഗ് ഗെയിം, ഒരു വെർച്വൽ ടെറേറിയം, ഒരു 'ഗ്രീൻ' ബ്രൗസർ എക്സ്റ്റൻഷൻ, ഒരു 'സ്പെയ്സ് ഇൻവേഡേഴ്സ്' ടൈപ്പ് ഗെയിം, ഒരു ബിസിനസ്-ടൈപ്പ് ബാങ്കിംഗ് ആപ്പ് എന്നിവ നിർമ്മിക്കുകയും ജാവാസ്ക്രിപ്റ്റിന്റെ അടിസ്ഥാനകാര്യങ്ങൾ പഠിക്കുകയും ചെയ്യും , ഇന്നത്തെ വെബ് ഡെവലപ്പറിന്റെ ആധുനിക ടൂൾചെയിനിനൊപ്പം HTML, CSS എന്നിവയും. 

> 🎓 ഈ പാഠ്യപദ്ധതിയിലെ ആദ്യ കുറച്ച് പാഠങ്ങൾ നിങ്ങൾക്ക് മൈക്രോസോഫ്റ്റ് ലേൺ നെ കുറിച്ചുള്ള ഒരു[പഠന പാത](https://docs.microsoft.com/learn/paths/web-development-101?WT.mc_id=academic-13441-cxa) ആയി എടുക്കാം.

പ്രോജക്റ്റുകളുമായി ഉള്ളടക്കം യോജിക്കുന്നുവെന്ന് ഉറപ്പുവരുത്തുന്നതിലൂടെ, ഈ പ്രക്രിയ വിദ്യാർത്ഥികളെ കൂടുതൽ ആകർഷകമാക്കുകയും ആശയങ്ങൾ നിലനിർത്തുന്നത് വർദ്ധിപ്പിക്കുകയും ചെയ്യും. ആശയങ്ങൾ അവതരിപ്പിക്കാൻ ഞങ്ങൾ ജാവാസ്ക്രിപ്റ്റ് അടിസ്ഥാനത്തിൽ നിരവധി സ്റ്റാർട്ടർ പാഠങ്ങൾ എഴുതി, paired with video from the "[Beginners Series to: JavaScript](https://channel9.msdn.com/Series/Beginners-Series-to-JavaScript?WT.mc_id=academic-13441-cxa)" വീഡിയോ ട്യൂട്ടോറിയലുകളുടെ ശേഖരം, ചില എഴുത്തുകാർ ഈ പാഠ്യപദ്ധതിക്ക് സംഭാവന നൽകി.
ഇതുകൂടാതെ, ഒരു ക്ലാസിന് മുമ്പുള്ള ഒരു കുറഞ്ഞ ക്വിസ് ഒരു വിഷയം പഠിക്കുന്നതിനുള്ള വിദ്യാർത്ഥിയുടെ ഉദ്ദേശ്യം സജ്ജമാക്കുന്നു, അതേസമയം ക്ലാസിന് ശേഷമുള്ള രണ്ടാമത്തെ ക്വിസ് കൂടുതൽ നിലനിർത്തൽ ഉറപ്പാക്കുന്നു. ഈ പാഠ്യപദ്ധതി രൂപകൽപ്പന ചെയ്തിരിക്കുന്നത് വഴക്കമുള്ളതും രസകരവുമാണ്, ഇത് മുഴുവനായോ ഭാഗികമായോ എടുക്കാം. പദ്ധതികൾ ചെറുതായി ആരംഭിച്ച് 12 ആഴ്ച ചക്രത്തിന്റെ അവസാനത്തോടെ കൂടുതൽ സങ്കീർണമാകുന്നു.

ഒരു ചട്ടക്കൂട് സ്വീകരിക്കുന്നതിന് മുമ്പ് ഒരു വെബ് ഡെവലപ്പർ എന്ന നിലയിൽ ആവശ്യമായ അടിസ്ഥാന കഴിവുകളിൽ ശ്രദ്ധ കേന്ദ്രീകരിക്കുന്നതിന് ഞങ്ങൾ ജാവാസ്ക്രിപ്റ്റ് ചട്ടക്കൂടുകൾ അവതരിപ്പിക്കുന്നത് മനപ്പൂർവ്വം ഒഴിവാക്കിയിട്ടുണ്ടെങ്കിലും, ഈ പാഠ്യപദ്ധതി പൂർത്തിയാക്കുന്നതിനുള്ള ഒരു നല്ല അടുത്ത ഘട്ടം വീഡിയോകളുടെ മറ്റൊരു ശേഖരത്തിലൂടെ Node.js- നെക്കുറിച്ച് പഠിക്കുക എന്നതാണ്: "[Beginner Series to: Node.js](https://channel9.msdn.com/Series/Beginners-Series-to-Nodejs?WT.mc_id=academic-13441-cxa)".

> Find our [Code of Conduct](CODE_OF_CONDUCT.md), [Contributing](CONTRIBUTING.md), and [Translation](TRANSLATIONS.md) guidelines. We welcome your constructive feedback!
>
## ഓരോ പാഠവും ഉൾപ്പെടുന്നു:

- optional sketchnote
- optional supplemental video
- pre-lesson warmup quiz
- written lesson
- for project-based lessons, step-by-step guides on how to build the project
- knowledge checks
- a challenge
- supplemental reading
- assignment
- post-lesson quiz

> **ക്വിസുകളെക്കുറിച്ചുള്ള ഒരു കുറിപ്പ്**: All quizzes are contained [in this app](https://happy-mud-02d95f10f.azurestaticapps.net/), for 48 total quizzes of three questions each. They are linked from within the lessons but the quiz app can be run locally; follow the instruction in the `quiz-app` folder. They are gradually being localized.

## പാഠങ്ങൾ

|       |                       പദ്ധതിയുടെ പേര്                    |                          പഠിപ്പിച്ച ആശയങ്ങൾ                            | പഠന ലക്ഷ്യങ്ങൾ                                                                                                                |                                                       Linked Lesson                                                          |         രചയിതാവ്         |
| :---: | :------------------------------------------------------: | :--------------------------------------------------------------------: | ----------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------: | :---------------------: |
|  01   |                     ആമുഖം                   |           പ്രോഗ്രാമിംഗിന്റെയും ട്രേഡിന്റെ ഉപകരണങ്ങളുടെയും ആമുഖം         | മിക്ക പ്രോഗ്രാമിംഗ് ഭാഷകളുടെയും പ്രൊഫഷണൽ ഡെവലപ്പർമാരെ അവരുടെ ജോലികൾ ചെയ്യാൻ സഹായിക്കുന്ന സോഫ്റ്റ്വെയറിനെക്കുറിച്ചും അടിസ്ഥാനപരമായ അടിസ്ഥാനങ്ങൾ പഠിക്കുക | [Intro to Programming Languages and Tools of the Trade](/1-getting-started-lessons/1-intro-to-programming-languages/README.md) |         Jasmine         |
|  02   |                     Getting Started                      |             Basics of GitHub, includes working with a team             | How to use GitHub in your project, how to collaborate with others on a code base                                                    |                            [Intro to GitHub](/1-getting-started-lessons/2-github-basics/README.md)                             |          Floor          |
|  03   |                     Getting Started                      |                             Accessibility                              | Learn the basics of web accessibility                                                                                               |                       [Accessibility Fundamentals](/1-getting-started-lessons/3-accessibility/README.md)                       |       Christopher       |
|  04   |                        JS Basics                         |                         JavaScript Data Types                          | The basics of JavaScript data types                                                                                                 |                                       [Data Types](/2-js-basics/1-data-types/README.md)                                        |         Jasmine         |
|  05   |                        JS Basics                         |                         Functions and Methods                          | Learn about functions and methods to manage an application's logic flow                                                             |                              [Functions and Methods](/2-js-basics/2-functions-methods/README.md)                               | Jasmine and Christopher |
|  06   |                        JS Basics                         |                        Making Decisions with JS                        | Learn how to create conditions in your code using decision-making methods                                                           |                                 [Making Decisions](/2-js-basics/3-making-decisions/README.md)                                  |         Jasmine         |
|  07   |                        JS Basics                         |                            Arrays and Loops                            | Work with data using arrays and loops in JavaScript                                                                                 |                                   [Arrays and Loops](/2-js-basics/4-arrays-loops/README.md)                                    |         Jasmine         |
|  08   |       [Terrarium](/3-terrarium/solution/README.md)       |                            HTML in Practice                            | Build the HTML to create an online terrarium, focusing on building a layout                                                         |                                 [Introduction to HTML](/3-terrarium/1-intro-to-html/README.md)                                 |           Jen           |
|  09   |       [Terrarium](/3-terrarium/solution/README.md)       |                            CSS in Practice                             | Build the CSS to style the online terrarium, focusing on the basics of CSS including making the page responsive                     |                                  [Introduction to CSS](/3-terrarium/2-intro-to-css/README.md)                                  |           Jen           |
|  10   |            [Terrarium](/3-terrarium/solution)            |                 JavaScript Closures, DOM manipulation                  | Build the JavaScript to make the terrarium function as a drag/drop interface, focusing on closures and DOM manipulation             |                  [JavaScript Closures, DOM manipulation](/3-terrarium/3-intro-to-DOM-and-closures/README.md)                   |           Jen           |
|  11   |          [Typing Game](/4-typing-game/solution)          |                          Build a Typing Game                           | Learn how to use keyboard events to drive the logic of your JavaScript app                                                          |                                [Event-Driven Programming](/4-typing-game/typing-game/README.md)                                |       Christopher       |
|  12   | [Green Browser Extension](/5-browser-extension/solution) |                         Working with Browsers                          | Learn how browsers work, their history, and how to scaffold the first elements of a browser extension                               |                               [About Browsers](/5-browser-extension/1-about-browsers/README.md)                                |           Jen           |
|  13   | [Green Browser Extension](/5-browser-extension/solution) | Building a form, calling an API and storing variables in local storage | Build the JavaScript elements of your browser extension to call an API using variables stored in local storage                      |                [APIs, Forms, and Local Storage](/5-browser-extension/2-forms-browsers-local-storage/README.md)                 |           Jen           |
|  14   | [Green Browser Extension](/5-browser-extension/solution) |          Background processes in the browser, web performance          | Use the browser's background processes to manage the extension's icon; learn about web performance and some optimizations to make   |             [Background Tasks and Performance](/5-browser-extension/3-background-tasks-and-performance/README.md)              |           Jen           |
|  15   |           [Space Game](/6-space-game/solution)           |             More Advanced Game Development with JavaScript             | Learn about Inheritance using both Classes and Composition and the Pub/Sub pattern, in preparation for building a game              |                      [Introduction to Advanced Game Development](/6-space-game/1-introduction/README.md)                       |          Chris          |
|  16   |           [Space Game](/6-space-game/solution)           |                           Drawing to canvas                            | Learn about the Canvas API, used to draw elements to a screen                                                                       |                                [Drawing to Canvas](/6-space-game/2-drawing-to-canvas/README.md)                                |          Chris          |
|  17   |           [Space Game](/6-space-game/solution)           |                   Moving elements around the screen                    | Discover how elements can gain motion using the cartesian coordinates and the Canvas API                                            |                           [Moving Elements Around](/6-space-game/3-moving-elements-around/README.md)                           |          Chris          |
|  18   |           [Space Game](/6-space-game/solution)           |                          Collision detection                           | Make elements collide and react to each other using keypresses and provide a cooldown function to ensure performance of the game    |                              [Collision Detection](/6-space-game/4-collision-detection/README.md)                              |          Chris          |
|  19   |           [Space Game](/6-space-game/solution)           |                             Keeping score                              | Perform math calculations based on the game's status and performance                                                                |                                    [Keeping Score](/6-space-game/5-keeping-score/README.md)                                    |          Chris          |
|  20   |           [Space Game](/6-space-game/solution)           |                     Ending and restarting the game                     | Learn about ending and restarting the game, including cleaning up assets and resetting variable values                              |                                [The Ending Condition](/6-space-game/6-end-condition/README.md)                                 |          Chris          |
|  21   |         [Banking App](/7-bank-project/solution)          |                 HTML Templates and Routes in a Web App                 | Learn how to create the scaffold of a multipage website's architecture using routing and HTML templates                             |                            [HTML Templates and Routes](/7-bank-project/1-template-route/README.md)                             |          Yohan          |
|  22   |         [Banking App](/7-bank-project/solution)          |                  Build a Login and Registration Form                   | Learn about building forms and handing validation routines                                                                          |                                           [Forms](/7-bank-project/2-forms/README.md)                                           |          Yohan          |
|  23   |         [Banking App](/7-bank-project/solution)          |                   Methods of Fetching and Using Data                   | How data flows in and out of your app, how to fetch it, store it, and dispose of it                                                 |                                            [Data](/7-bank-project/3-data/README.md)                                            |          Yohan          |
|  24   |         [Banking App](/7-bank-project/solution)          |                      Concepts of State Management                      | Learn how your app retains state and how to manage it programmatically                                                              |                                [State Management](/7-bank-project/4-state-management/README.md)                                |          Yohan          |

## Offline access

You can run this documentation offline by using [Docsify](https://docsify.js.org/#/). Fork this repo, [install Docsify](https://docsify.js.org/#/quickstart) on your local machine, and then in the root folder of this repo, type `docsify serve`. The website will be served on port 3000 on your localhost: `localhost:3000`.

## പിഡിഫ് 

A PDF of all of the lessons can be found [here](pdf/readme.pdf)

## മറ്റ് പാഠ്യപദ്ധതികൾ

Our team produces other curricula! Check out:

- [Machine Learning for Beginners](https://aka.ms/ml-beginners)
- [IoT for Beginners](https://aka.ms/iot-beginners)
