<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
  <a href="https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai">
    <img src="assets/images/logo-sml.png" alt="Logo" width="200" height="200">
  </a>

  <h3 align="center">Mission Ready - Level 05 - Mission 01 - Research</h3>

  <p align="center">
    Turners Car Auctions - Insurance Premium Estimation with AI Vehicle Image Classification
    <br />
    <a href="https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai">View Demo</a>
    ·
    <a href="https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<div align="center">
  <a href="https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai">
    <img src="assets/images/logo-sml.png" alt="Logo" width="200" height="200">
  </a>
</div>


### The goal of this project is to prototype a solution that allows...

* A custom to upload the picture of a car 
* Identify the type of vehicle [and potentially make and model]
* Based on this information, calculate the appropriate insurance premium for the customer. 

### Propoesd implementation

* A cloud-based application that can recognise motor vehicles types (e.g. sedan vs SUV vs truck, or potentially recognise a few brands and/or models) using a cloud-based AI service on
  *  Microsoft Azure or,
  *  Amazon Web Services or,
  *  Google Cloud

  
* The solution does not need the business logic to calculate the insurance premium, as this will be handled by another team.

  You can use code from tutorials you find online, but make sure you read through the code so that you understand the code. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This project was built using these framewords/libraries/services ...

* [![Azure App Services][Azure-App-Services]][Azure-App-Services-url]
* [![Azure AI Vision][Azure-AI-Vision]][Azure-AI-Vision-url]
* [![Express][Express.js]][Express-url]
* [![React][React.js]][React-url]
* [![React Router][React-Router]][React-Router-url]
* [![Sweet Alert 2][Sweet-Alert2]][Sweet-Alert2-url]

[Azure-AI-Vision]: https://img.shields.io/badge/Azure_AI_Vision-FF2D20?style=for-the-badge&logoColor=white&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAACXBIWXMAAAsTAAALEwEAmpwYAAAFB0lEQVRIiY2UW2wUVRjHf2due6PdLmzbLW1ZLaIgdwMRC0KkIFGRQJBieAATn3jAaOIlJgYBNUYMiSFiiMZ4wSdCEGMQAUEEQ63hoqHUIrctNHWp2267y+52Z3bm+NDtdgsF/CeTmfPN//y/y/nOJ3Z02/JwVukGtMFHFyi7Q6wCvuPemAO0NEZpsSSjADVvFxN16RXvxBwLWD/fIy7ogusCegMqiYcMnP8hfhuaMqgSjKNpKVstcU5sjjnZjWOE6w58BRh9tSs76WBL3/SuRG6az6XGpta6W5+c4j8NXAX67+RsTZSEdpdg5m3Z17lsU3O8AagD3IDI/7OhI/pc2HPy7Wer9k+u9hwDoiNoOFo+ymE40ZZcuXRXx4tJx6kHRmlCkBcfdCCBcXvaM7V7Pr5Sv+nRwPcbl4/9Bjh1i5StqUKIYsuJtuTKBV9d26AJUR9QVV1VoNylU+FzU+rWZb9li3jGFJGbGQWgN+fUbWqOr+3L2qXbVtduB/4Y1NIEtpBSLgEO5m1PKG+ef6NEURr8uqKVe1zU+L34PcaINYzEkkSSafodScyyYx8tDH760uLKrUBfnrJBAY7kF4EXPo88D8yvcGtazSgPk0NlBfFEoo9r1yPc6Boq9X3BEqZV+PHrKgFVDb58NLaMgbYdxC4NyOUXc76+lFoSMjSPoSjUBUsKws0tZ4imksOiXzBpOuNqwoz2uanKWEA/8bQ9ccu+zqUbl48drEimcMDbDtxYBNQEDI2qEg9K/miaW86wfc0UOrav5qlwWcHBL3/9WcimotSDV9MI6qq2pzWxqCiObMHBuc7M3KCuqm5NpSxflmsd7YR9sGrBBKpHu1hRf/+wLE6cPwOA19Dw6Sp+XaUladcWcwr3oDORG+/XVVyqgtcYMN/4N0pbLMlbXzQxvS5IKmMR9um0p6yB/HM5TMvE0A1KXDpZ24G0OaztCwsVqQFoRV1r59/vHblI42dNVJeXEPK5uRNc6m1XasjB+HLXBctxUFWFbG5Aemywchi58bMmmruGDtujaRj6QDltKQcygJsjOpgd9h7uzNqWoSpYOUcC1NSEKXXfOeLHHn4EANN2UIUgYVosqnBdHNHBuseDP+ekvBrPmJi2jSMlihAsmDqbkK/kNvG5D06hujI04MCypa4K2Z6xsiumlR4v5hUPu1OvzCg9sOt8amxVqcfXb9nSa2iirCzA4von6O2N09MXx+X2UlVRWWhj03awpeR6X0Z4hDi/vqHi0K0Z1OW/E9tW1+6OWfbRjr60CZDN2dKREoCysgB14TqqK0PF4tK0bNlv2eJcIt355fLQtwwfeDOUd7vl6V/TDA6bk5FXH9h5tjd15GrPzSwgLduRpu1IR8phTzZnSymljGdMfov2/vPh/ODeFbMDe4FCF6y9wQnNAWmCBzABxo1xHXDen2w3bG3r//FKpmFywOcPlXhymksTDIxpBXC6U9lce1+Ky2nz7y+erty37vHgbqC1uDw5iaLlN3kYmoAAh468PrHnk5+6Wnf+3rN4XyQ5KWRovnK3oaZzOedy2uwHLr8203/8g8YJPwBNt+wfREpsjjmxeR4xa6GXyAgEAXiB8P6zvZPiaXuMzyW6V8wa3QZEgHQ+wBGxJsolTQF5MiPdC71iJI4EUkDrMzPLWkci3AOK2NFt24ezSk9RJEIXOLtDTAcM4NpdBFRgHGA0RjlmDeXiBvSJunT9B65iESKwcVT9AAAAAElFTkSuQmCC
[Azure-AI-Vision-url]: https://azure.microsoft.com/en-us/products/app-service
[Azure-App-Services]: https://img.shields.io/badge/Azure_App_Sevices-0769AD.svg?style=for-the-badge&logoColor=white&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAACXBIWXMAAAsTAAALEwEAmpwYAAAFbUlEQVRIiY2VTWxcVxXHf+feN2/ezHhixx7HHge7NondhjZuSNo6kIi6UtUSKiEWiNIKVAlaIbFgA0gVQiLs+BASLIBNF2yKgCJoI1rR8pGqalRCQ5ImboLTfOI09tj1x9iejzfz7j0sJnGaOqGcxVvcd+//d8957/yPqCr/T1RjLxffi33cVFIWRopRexiY5Q87J/8LcPzCqp6YWuVnh5a5WHEECMnaW+XhgYgndnfy0PZ2I8JNhW4KOD8XP/uDl0qPO+d4/J42njta4c+XYowI3rf2eFUaQNN59vak+ckX+t7b2hN1f1Ar+ODCL/82q989uEDGCGEgPDDs+NxojgtLMF3xYBUHbMoYdhTT9OQDunKG45dqhVI50T0jbXLLDJ45WNJv/XWBbMqQEyFlDQMbAr59fxvluvKLN6rs3ByxvS9Nd96iCqqKqlJteFZjx+hAhl2DOVkHODS5rMcurfCjQ6tE1hBZQ2AtKSPs6Q95YiyDDSzTqwY81JrKubmYiek6J6YblBsJdedJW3jtG0PfL3aE+wEMQNz08urpMvm0oSeypKwhsIa0FbqzAWNbcqgEtEdQbFP+cb7Gz18v84eJKqdmExytbNPGsOLghy/Nfu+Gb/D80SV/uewY6Eyx+yMRhXyICJyedTy2K08+sizUYXalSXvaMbjR8MaUJR0IIoKIA1oli1R59t+rfGWqqqP9WQkAfvuvJSp1z9fH2/j8WEQYtEq4VHVMl5W5Zc9rZ+pMzDo+PWy5s2j48o6Q359ssBwreEMgHmuElAhWhN8cXmS0P9sq0aErMV+6r4PhYmZNHKAja9ncYTg10+TMvBKlLK9egGPvwmDB8ORYmt68ZbiQYnd/mnv7IrZ2BITAc6dWWyV6p1QvJcD9IxkVTSS52kmqioiQCZSPdgn/nBIUQUQ5PKUsVpXxrYavjkWAcN9QCoADx6s8/coCc7GjVG7uDxpN3WSMENmm1GrNdU0HUMi2YK3cWs/Tc7BYdezbBh/fLNTrDoBPbRH36LbIPnOyysJq8p2g6RTvYXa+QlferBNXVebLAaqpG9eBi2WlvBJTrepaxqpq84EDFGuEIJs2i8DGg2fqPPIxWQdoJPCXcxtadxfB6zWwR1U5XfLcVait7fceetvbGC960oF5OxgshF1O1f/4zYSRgtCba2KlpRI7y4rLUXdCnHgCY1DAeSXxDuc8x2cskQh3dMYkCpPzaTZsEB7ZlqG/EO4MwsDoZ4cynF1ISKJNXHGONydnyYQBg8UOrBEeHBYmpj0nS47R3hSBhfas4cW361QSOHA+4ndnQuqJp5YkqC7z2F05jKABwBfv2ciLJ5dRhQvzjhfOh4SBYWQhZs9QSFeb4c5e4cHbU9zd3/LHxEFkPL86UqHhPA3naXpHQz0rTc+uwRxw1So+s6Nddg5kUFWOXK7T9ErilLMLTX79Vo2JdxOcV3pyDWq1GrVajWajxgNbW8KJUxre01Cl7mEwZ9m3o8PC++x6z3AunpyJ04enqjRVcCgOQ0Ph5XM1jk1b7u5WKv66+6rCk/dGlKuexZpjvuJInOdr45sIrfgbAHf0ZaLJmbrOxJ6cFbyAKFijOGO4vJJwttRkS5dfA5RWLekgojtvKOSELV2WznzIrqGb2PW12P/HK/rTI2UypuWmgRUCBCPCeDFhrNigJ++YrRheOBux1LAEBpzzPPXJTh79RNetB861OHB0Sb/5pxJLiWJFCAEjgjHX/3WvileoeeXhgTRP7+thtD+7rpFuOfSX6y58+a1y/PyJMn//T0zNt2Bcne23ZQ3be9I8tbeLvbfn13fo+wDXT90iGk7NO9N110iUKCX12wrpvqsO8KHxX8prldq76f1xAAAAAElFTkSuQmCC
[Azure-App-Services-url]: https://azure.microsoft.com/en-us/products/app-service/
[Express.js]: https://img.shields.io/badge/Express-563D7C?style=for-the-badge&logo=express&logoColor=white
[Express-url]: https://expressjs.com/ 
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Sweet-Alert2]: https://img.shields.io/badge/Sweet_Alert_2-4A4A55?style=for-the-badge&logoColor=white&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjE1LjQgLTEyMC4zIDI2OS4zIDI2OS4zIj48Y2lyY2xlIGlkPSJsb3dlcl9jaXJjbGUiIGN4PSIxNjEuOCIgY3k9IjI3IiByPSIxMDAuMiIgZmlsbD0iI2ZkY2M4MCI+PC9jaXJjbGU+PGNpcmNsZSBpZD0iaW5uZXJfY2lyY2xlIiBjeD0iMTQ5LjQiIGN5PSIxNC4yIiByPSIzNi44IiBmaWxsPSIjZmZmIj48L2NpcmNsZT48cGF0aCBpZD0idXBwZXJfZnJvc3RpbmciIGQ9Ik0xMDguNyAxMDUuNWMtNi42LjMtMzEuOS0xMy40LTQyLjQtNDkuNS0xLjktNi42LTQuNS0xNi44LTQuNS0yOS42IDAtNTUgNDQuNi05OS42IDk5LjYtOTkuNiAxMy4xIDAgMjMuNSAyLjcgMjkuNiA0LjUgMzQuNCAxMC40IDQ4IDM0LjEgNDQuOSA0MC41cy0xMC42LTMuNC0yMi45LTIuNWMtMS40LjEtNC4yIDQtNC4yIDYuMiAwIDcuMiAxMy41IDEyLjcgMTQuNiAxNS45IDEuNyA1IDMuNCA2LjIgMi4zIDkuNS0xLjUgNC44LTIuOSAzLjYtNS4yIDUuOS0uOS45LTUuNi43LTE2LjYtMS43LTUuOS0xLjMtMTgtMTEuMi0xOC0xMS40IDAtLjQtMTYuMi0xMy4zLTMwLjItMTQuOC02LjYtLjctMjguMS0yLjgtMzkuMiAxOS4yLS41IDEuMS00LjQgMjAtNC4yIDIyLjUuOSAxMS45IDcgMjQuNyAxMi4xIDI3LjUgMTEuNyA2LjQgMTIuOSAxNC43IDEyLjggMTQuNC0uMS0uNCA3LjggMTQuNyA4LjIgMTcuMy4zIDIuMS0uOCA3LjQtMy43IDguNy0zLjUgMS41LTcuNy0xLjctOC40LTIuMS0uOC0uNS0xMC43LTE2LjMtMTkuNS0xMy4xLS44LjMtNiAzLjctNy42IDUtLjMuMiA0LjggMTUuNCA1LjYgMTguNS41IDEuOC0yLjMgOC43LTMuMSA4Ljd6IiBvcGFjaXR5PSIuNSIgZmlsbD0iI2ZhNzQ3MSI+PC9wYXRoPjxnIGlkPSJzcHJpbmtsZXMiPjxwYXRoIGQ9Ik0xMzUuMS02OS4zaC0uMmMtMi4zLjQtMy44IDIuNi0zLjQgNC45LjQgMi4zIDIuNiAzLjggNC45IDMuNC44LS4xIDEuNS0uNSAyLjEtMSAxLS45IDEuNi0yLjMgMS40LTMuNy0uMy0yLjMtMi41LTMuOS00LjgtMy42eiIgc3R5bGU9ImZpbGw6IHJnYigyNTAsIDExNiwgMTEzKTsiPjwvcGF0aD48cGF0aCBkPSJNMTgxLjctNjVjLTIuMy0uMS00LjMgMS43LTQuNSA0bC0uNSA4LjRjLS4xIDIuMyAxLjcgNC4zIDQgNC41IDEuMi4xIDIuMi0uMyAzLjEtMS4xLjgtLjcgMS4zLTEuNyAxLjQtMi45bC41LTguNGMuMS0yLjQtMS43LTQuNC00LTQuNXoiIHN0eWxlPSJmaWxsOiByZ2IoMjUwLCAxMTYsIDExMyk7Ij48L3BhdGg+PHBhdGggZD0iTTk0LjQgNDcuMWMtMi4zLS4xLTQuMyAxLjctNC41IDRsLS41IDguNGMtLjEgMi4zIDEuNyA0LjMgNCA0LjUgMS4yLjEgMi4yLS4zIDMuMS0xLjEuOC0uNyAxLjMtMS43IDEuNC0yLjlsLjUtOC40Yy4xLTIuNC0xLjctNC40LTQtNC41eiIgc3R5bGU9ImZpbGw6IHJnYigyNTAsIDExNiwgMTEzKTsiPjwvcGF0aD48cGF0aCBkPSJNNjUuNCAxLjdjLTIuMy0uMS00LjMgMS43LTQuNSA0bC0uNSA4LjRjLS4xIDIuMyAxLjcgNC4zIDQgNC41IDEuMi4xIDIuMi0uMyAzLjEtMS4xczEuMy0xLjcgMS40LTIuOWwuNS04LjRjLjEtMi4zLTEuNy00LjMtNC00LjV6IiBzdHlsZT0iZmlsbDogcmdiKDE2NSwgMTE3LCAxODMpOyI+PC9wYXRoPjxwYXRoIGQ9Ik0xNTcuMi02MS44bC02LjIgNS42Yy0xLjcgMS42LTEuOSA0LjItLjMgNiAxLjYgMS43IDQuMiAxLjkgNiAuM2w2LjItNS42YzEuNy0xLjYgMS45LTQuMi4zLTZzLTQuMy0xLjktNi0uM3oiIHN0eWxlPSJmaWxsOiByZ2IoMTY1LCAxMTcsIDE4Myk7Ij48L3BhdGg+PHBhdGggZD0iTTkzLjgtMjMuM2wtOC4zLS41Yy0yLjMtLjEtNC4zIDEuNy00LjUgNHMxLjcgNC4zIDQgNC41bDguMy41YzEuMi4xIDIuMi0uMyAzLjEtMS4xLjgtLjcgMS4zLTEuNyAxLjQtMi45LjEtMi40LTEuNy00LjQtNC00LjV6IiBzdHlsZT0iZmlsbDogcmdiKDI1MCwgMTE2LCAxMTMpOyI+PC9wYXRoPjxwYXRoIGQ9Ik0xODkuMS0zNS4xbC04LjMtLjVjLTIuMy0uMS00LjMgMS43LTQuNSA0czEuNyA0LjMgNCA0LjVsOC4zLjVjMS4yLjEgMi4yLS4zIDMuMS0xLjFzMS4zLTEuNyAxLjQtMi45Yy4xLTIuNC0xLjYtNC40LTQtNC41eiIgc3R5bGU9ImZpbGw6IHJnYigxNjUsIDExNywgMTgzKTsiPjwvcGF0aD48cGF0aCBkPSJNMTMyLjQtNDIuM2wtNy4xLTQuNGMtMi0xLjItNC42LS42LTUuOCAxLjQtMS4yIDItLjYgNC42IDEuNCA1LjhsNy4xIDQuNGMxIC42IDIuMS44IDMuMi41IDEuMS0uMiAyLS45IDIuNi0xLjkgMS4xLTIgLjUtNC42LTEuNC01Ljh6IiBzdHlsZT0iZmlsbDogcmdiKDI1MCwgMTE2LCAxMTMpOyI+PC9wYXRoPjxwYXRoIGQ9Ik04OC4yIDUuN2MtMi4xIDEuMS0yLjggMy43LTEuNyA1LjdsNCA3LjRjMS4xIDIuMSAzLjcgMi44IDUuNyAxLjcgMS4xLS42IDEuOC0xLjYgMi4xLTIuNy4zLTEgLjEtMi4xLS40LTNsLTQtNy40Yy0xLjEtMi0zLjctMi44LTUuNy0xLjd6IiBzdHlsZT0iZmlsbDogcmdiKDE2NSwgMTE3LCAxODMpOyI+PC9wYXRoPjwvZz48ZyBjbGFzcz0iaGFpciI+PHBhdGggZD0iTTIzMi41LTgzLjNjLTIuMiAzLjEtNC42IDYtNy4yIDguNy0xLjggMS45LTEuNyA0LjkuMSA2LjcgMS45IDEuOCA0LjkgMS43IDYuNy0uMSAyLjktMyA1LjYtNi4zIDgtOS43IDEuNS0yLjEgMS01LjEtMS4xLTYuNnMtNS0xLjEtNi41IDF6IiBzdHlsZT0iZmlsbDogcmdiKDE2NSwgMTE3LCAxODMpOyI+PC9wYXRoPjxwYXRoIGQ9Ik0xNDQuNy0xMTMuNGMuMiAzLjcuMiA3LjUtLjIgMTEuMi0uMiAyLjYgMS43IDQuOSA0LjMgNS4xIDIuNi4yIDQuOS0xLjcgNS4xLTQuMy40LTQuMi40LTguNC4yLTEyLjYtLjItMi42LTIuNC00LjYtNS00LjQtMi41LjEtNC41IDIuNC00LjQgNXoiIHN0eWxlPSJmaWxsOiByZ2IoMTY1LCAxMTcsIDE4Myk7Ij48L3BhdGg+PHBhdGggZD0iTTU5LjMtNzUuN2MzLjEgMi4yIDYgNC41IDguNyA3LjEgMS45IDEuOCA0LjkgMS43IDYuNy0uMnMxLjctNC45LS4yLTYuN2MtMy0yLjktNi4zLTUuNS05LjgtOC0yLjEtMS41LTUuMS0xLTYuNiAxLjFzLTEgNS4yIDEuMiA2Ljd6IiBzdHlsZT0iZmlsbDogcmdiKDE2NSwgMTE3LCAxODMpOyI+PC9wYXRoPjxwYXRoIGQ9Ik0yMi42IDExLjZjMy43LS4yIDcuNS0uMSAxMS4yLjMgMi42LjMgNC45LTEuNiA1LjItNC4ycy0xLjYtNC45LTQuMi01LjJjLTQuMi0uNC04LjQtLjUtMTIuNi0uMy0yLjYuMS00LjYgMi4zLTQuNSA0LjkuMSAyLjcgMi4zIDQuNyA0LjkgNC41eiIgc3R5bGU9ImZpbGw6IHJnYigxNjUsIDExNywgMTgzKTsiPjwvcGF0aD48cGF0aCBkPSJNNjAuMiAxMDIuMmMyLjItMyA0LjYtNS45IDcuMi04LjYgMS44LTEuOSAxLjgtNC45LS4xLTYuNy0xLjktMS44LTQuOS0xLjgtNi43LjEtMi45IDMtNS42IDYuMy04LjEgOS43LTEuNSAyLjEtMSA1LjEgMS4xIDYuNiAyLjEgMS40IDUgMSA2LjYtMS4xeiIgc3R5bGU9ImZpbGw6IHJnYigxNjUsIDExNywgMTgzKTsiPjwvcGF0aD48L2c+PGNpcmNsZSBjeD0iMTQ5LjEiIGN5PSIxNSIgcj0iOTkuNCIgc3R5bGU9InN0cm9rZS13aWR0aDogOC4yOyBzdHJva2U6IHJnYigxMzgsIDYxLCAxNTUpOyBmaWxsOiBub25lOyBzdHJva2UtbWl0ZXJsaW1pdDogMTA7Ij48L2NpcmNsZT48ZyBpZD0ic2lkZV9zd2lybCI+PHBhdGggZD0iTTE5Mi41IDUuNmM0LjItNC40IDkuNi41IDEzLjYgMi45IDQgMi4zIDcuOSAzLjQgMTIuNCAyLjMgOC43LTEuOSAxMy45LTkuOSAxMC4yLTE4LjUtMS45LTQuNC01LjUtNy40LTkuNS05LjgtMi4zLTEuNC01LjUtMi41LTctNC45LTIuNi00LjEgMi42LTUuNiA1LjctNC40IDQuNiAxLjcgOC4zIDMuMSAxMy4yIDEuNCAzLjUtMS4yIDcuNi0xLjYgOC4yLTYuMS43LTUuMy03LjQtNy42LTguMS0yLjItLjEuMi0uMS41LS4yLjcuOC0uNiAxLjctMS4zIDIuNS0xLjktMS42LjYtMy4zIDEtNC45IDEuNS0zLjIgMS01LjItLjEtOC0xLjMtNC4yLTEuNi04LjctMS42LTEyLjYuOS04LjkgNS45LTQuNiAxNi42IDIuOCAyMS4zIDMuOSAyLjUgMTAuMyA0LjcgMTAuNSAxMC4yLjIgNi4xLTcuNiA1LjctMTEuMiAzLjYtNy43LTQuNS0xNi4yLTkuMy0yMy43LTEuNi0zLjYgMy45IDIuMyA5LjggNi4xIDUuOXoiIHN0eWxlPSJmaWxsOiByZ2IoMTM4LCA2MSwgMTU1KTsiPjwvcGF0aD48cGF0aCBkPSJNMTMyLjUgNTYuMWMtLjkgMy44LS41IDcuNSAxLjMgMTEgMS44IDMuNiA3LjggOCA3LjYgMTIuMS0uMSAzLjEtMi44IDQuMS01LjUgMy41cy00LjItMi4zLTUuNy00LjVjLTIuMy0zLjMtNC41LTYuNi04LjItOC41LTYuNy0zLjUtMTUuOC0zLTE5LjQgNC40LTEuOCAzLjctMi4xIDguMS0uOSAxMi4xLjcgMi4zIDIgNC4zIDMuMyA2LjMuNyAxLjIgMS42IDIuMiAxLjMgMy43LS40IDEuNy0xLjMgMS42LTMuMSAxLjgtNS4zLjYtNS40IDkgMCA4LjQgNC0uNSA4LjItMS4zIDEwLjUtNC45IDIuMy0zLjcgMS40LTguMS0uNi0xMS43LTEuNC0yLjYtMy41LTQuOS0zLjctNy45LS4zLTQuMiAyLjItNi40IDYuMi01LjUgNS44IDEuMyA3LjIgNy4yIDExLjEgMTEgNS43IDUuNSAxNy40IDUuOSAyMS40LTEuNyAyLjEtMy45IDIuMi04LjcuMS0xMi42LTIuNS00LjYtOS04LjgtNy42LTE0LjYgMS4yLTUuNC02LjktNy43LTguMS0yLjR6IiBzdHlsZT0iZmlsbDogcmdiKDEzOCwgNjEsIDE1NSk7Ij48L3BhdGg+PHBhdGggZD0iTTEzOC4yLTIwYzEzLjQtMi45IDI3LjYtLjcgMzcuNSA5LjQgNy44IDggMTEuOCAxOS42IDEwLjIgMzAuNy0zLjkgMjcuNC0zNy41IDM5LjQtNTguNCAyMi0xMi4yLTEwLjItMTQuMi0yNS45LTEwLjQtNDAuNiAxLjQtNS42LTcuMi04LTguNy0yLjQtNC4yIDE2LjMtMi40IDMzLjcgOS42IDQ2LjQgOS4zIDkuOSAyMy42IDE1LjIgMzcuMSAxMy44IDE3LjUtMS44IDMyLjYtMTMuOSAzOC4xLTMwLjcgNC42LTEzLjkgMS40LTI5LjctNy40LTQxLjMtMTEuOS0xNS43LTMxLjMtMjAtNDkuOS0xNi01LjcgMS4yLTMuMyA5LjkgMi4zIDguN3oiIHN0eWxlPSJmaWxsOiByZ2IoMTM4LCA2MSwgMTU1KTsiPjwvcGF0aD48cGF0aCBkPSJNOTkuMy01NC44bC04IDIuNGMtMi4yLjctMy41IDMtMi45IDUuMi43IDIuMiAzIDMuNSA1LjIgMi45bDgtMi40YzEuMS0uMyAyLTEuMSAyLjUtMnMuNy0yLjEuMy0zLjJjLS41LTIuMi0yLjktMy41LTUuMS0yLjl6IiBzdHlsZT0iZmlsbDogcmdiKDE2NSwgMTE3LCAxODMpOyI+PC9wYXRoPjxwYXRoIGQ9Ik04MS44IDMwLjdoLS4yYy0zLjIuNi00LjkgNC43LTEuOCA3LjcgMi4xIDEuMiA0LjEuOCA1LjQtLjQgMS0uOSAxLjYtMi4zIDEuNC0zLjctLjQtMi4zLTIuNS0zLjktNC44LTMuNnoiIHN0eWxlPSJmaWxsOiByZ2IoMjUwLCAxMTYsIDExMyk7Ij48L3BhdGg+PHBhdGggZD0iTTEyNC4zLTIxLjdjLTMuMiAxLjctNi4xIDQuMy04LjMgNy4xLTEuNCAxLjgtMS4xIDQuOS44IDYuMyAyIDEuNSA0LjcgMS4xIDYuMy0uOC40LS41LjgtLjkgMS4yLTEuNGwuMS0uMWMuMi0uMy42LS41LjgtLjguNi0uNCAxLS45IDEuNi0xLjMuMy0uMy42LS40LjktLjYuOC0uNS0uNi4zLjEtLjEgMi0xLjEgMy41LTMuNiAyLjMtNi0uOS0yLTMuNS0zLjUtNS44LTIuM3oiIHN0eWxlPSJmaWxsOiByZ2IoMTM4LCA2MSwgMTU1KTsiPjwvcGF0aD48L2c+PC9zdmc+
[Sweet-Alert2-url]: https://sweetalert2.github.io/
[React-Router]: https://img.shields.io/badge/React_Router-FF2D20?style=for-the-badge&logo=react-router&logoColor=white
[React-Router-url]: https://reactrouter.com/



<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Disclaimer

This project is a concept demo and is for informational and educational purposes only. It references and uses the trade name of [Turners Car Auctions] as a conceptual basis. However, this project is not affiliated with, endorsed by, or officially connected to [Turners Car Auctions] in any way. All trademarks, service marks, trade names, and logos used in this demo are the property of their respective owners. The inclusion of the business name and any associated references are solely for illustrative purposes and do not imply any official association or representation of [Turners Car Auctions].

<!-- GETTING STARTED -->
## Project Log

* Created README.md, project logo (ChatGPT/Photoshop)
* Created GitHub repository - Mission Ready, Level 5, Mission 01, AI 
  * [mr-level-05-fsd-mission-01-ai](https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/)

  ```
  cd ~/mission-ready
  mkdir -p /level-05/mission-01/research && cd /level-05/mission-01/research
  nano README.md
  git init
  git add .
  git commit -m "repo - mr-level-05-fsd-mission-01-ai - first commit"
  git branch -M main
  git remote add origin https://[ghp_access_token]@github.com/Astrotope/mr-level-05-fsd-mission-01-ai.git
  git push -u origin HEAD
  ```


<!-- ROADMAP -->
## Delvelopment Micro-Sprints (1.5 hours)

- [x] [Sprint-01] Create this README.md
- [ ] [Sprint-02] Research Azure Vision Service
- [ ] [Sprint-03] 


See the [open issues](https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Top contributors:

<a href="https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Astrotope/mr-level-05-fsd-mission-01-ai" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Astrotope - [Astrotope](https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai)

Project Link: [https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai](https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/

[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 



