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
    <img src="assets/images/logo.png" alt="Logo" width="200" height="200" style="border: 1px solid black; border-radius: 10px; padding: 0px;">
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

[![Product Name Screen Shot][product-screenshot]](https://example.com)

[product-screenshot]: assets/images/logo.png 


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

[Azure-AI-Vision]: https://img.shields.io/badge/Azure_AI_Vision-FF2D20?style=for-the-badge&logoColor=white&logo=data:image/svg%2bxml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzIwMTRfMTEwNTcpIj4KPHBhdGggZD0iTTAuNzg2Njc3IDYuNTIxMzNDMC41ODc1ODggNi41MjEzMyAwLjM5NjY1MyA2LjQ0MjI1IDAuMjU1ODc2IDYuMzAxNDdDMC4xMTUwOTkgNi4xNjA2OSAwLjAzNjAxMDcgNS45Njk3NiAwLjAzNjAxMDcgNS43NzA2N1YwLjc1MDY2N0MwLjAzNjAxMDcgMC41NTE1NzggMC4xMTUwOTkgMC4zNjA2NDMgMC4yNTU4NzYgMC4yMTk4NjVDMC4zOTY2NTMgMC4wNzkwODc5IDAuNTg3NTg4IDAgMC43ODY2NzcgMEg1LjQ4NjY4QzUuNjg1NzcgMCA1Ljg3NjcgMC4wNzkwODc5IDYuMDE3NDggMC4yMTk4NjVDNi4xNTgyNiAwLjM2MDY0MyA2LjIzNzM0IDAuNTUxNTc4IDYuMjM3MzQgMC43NTA2NjdDNi4yMzczNCAwLjk0OTc1NiA2LjE1ODI2IDEuMTQwNjkgNi4wMTc0OCAxLjI4MTQ3QzUuODc2NyAxLjQyMjI1IDUuNjg1NzcgMS41MDEzMyA1LjQ4NjY4IDEuNTAxMzNIMS41MzczNFY1Ljc2OEMxLjUzNzcgNS44NjY4IDEuNTE4NTQgNS45NjQ3IDEuNDgwOTcgNi4wNTYwOUMxLjQ0MzQgNi4xNDc0NyAxLjM4ODE2IDYuMjMwNTQgMS4zMTg0MiA2LjMwMDUzQzEuMjQ4NjggNi4zNzA1MiAxLjE2NTgxIDYuNDI2MDUgMS4wNzQ1NiA2LjQ2Mzk0QzAuOTgzMzEzIDYuNTAxODMgMC44ODU0ODEgNi41MjEzMyAwLjc4NjY3NyA2LjUyMTMzWk0yMy45NjQgNS43NzA2N1YwLjc1MDY2N0MyMy45NjM3IDAuNTUxNjg2IDIzLjg4NDUgMC4zNjA5NTUgMjMuNzQzOCAwLjIyMDI1NUMyMy42MDMxIDAuMDc5NTUzNiAyMy40MTIzIDAuMDAwMzUyNDkxIDIzLjIxMzMgMEwxOC41MTMzIDBDMTguMzE0MyAwIDE4LjEyMzMgMC4wNzkwODc5IDE3Ljk4MjUgMC4yMTk4NjVDMTcuODQxOCAwLjM2MDY0MyAxNy43NjI3IDAuNTUxNTc4IDE3Ljc2MjcgMC43NTA2NjdDMTcuNzYyNyAwLjk0OTc1NiAxNy44NDE4IDEuMTQwNjkgMTcuOTgyNSAxLjI4MTQ3QzE4LjEyMzMgMS40MjIyNSAxOC4zMTQzIDEuNTAxMzMgMTguNTEzMyAxLjUwMTMzSDIyLjQ2MjdWNS43NjhDMjIuNDYyNyA1Ljk2NzA5IDIyLjU0MTggNi4xNTgwMiAyMi42ODI1IDYuMjk4OEMyMi44MjMzIDYuNDM5NTggMjMuMDE0MyA2LjUxODY3IDIzLjIxMzMgNi41MTg2N0MyMy40MTI0IDYuNTE4NjcgMjMuNjAzNCA2LjQzOTU4IDIzLjc0NDEgNi4yOTg4QzIzLjg4NDkgNi4xNTgwMiAyMy45NjQgNS45NjcwOSAyMy45NjQgNS43NjhWNS43NzA2N1pNNi4yMzczNCAyMy4yNDkzQzYuMjM3MzQgMjMuMDUwMiA2LjE1ODI2IDIyLjg1OTMgNi4wMTc0OCAyMi43MTg1QzUuODc2NyAyMi41Nzc4IDUuNjg1NzcgMjIuNDk4NyA1LjQ4NjY4IDIyLjQ5ODdIMS41MzczNFYxOC4yMzJDMS41MzczNCAxOC4wMzI5IDEuNDU4MjYgMTcuODQyIDEuMzE3NDggMTcuNzAxMkMxLjE3NjcgMTcuNTYwNCAwLjk4NTc2NyAxNy40ODEzIDAuNzg2Njc3IDE3LjQ4MTNDMC41ODc1ODggMTcuNDgxMyAwLjM5NjY1MyAxNy41NjA0IDAuMjU1ODc2IDE3LjcwMTJDMC4xMTUwOTkgMTcuODQyIDAuMDM2MDEwNyAxOC4wMzI5IDAuMDM2MDEwNyAxOC4yMzJWMjMuMjUyQzAuMDM2NzE2MyAyMy40NTA2IDAuMTE2MTE2IDIzLjY0MDkgMC4yNTY4MTcgMjMuNzgxMUMwLjM5NzUxNyAyMy45MjEzIDAuNTg4MDQ5IDI0IDAuNzg2Njc3IDI0SDUuNDg2NjhDNS42ODU3NyAyNCA1Ljg3NjcgMjMuOTIwOSA2LjAxNzQ4IDIzLjc4MDFDNi4xNTgyNiAyMy42Mzk0IDYuMjM3MzQgMjMuNDQ4NCA2LjIzNzM0IDIzLjI0OTNaTTIzLjk2NCAyMy4yNDkzVjE4LjIyOTNDMjMuOTY0IDE4LjAzMDIgMjMuODg0OSAxNy44MzkzIDIzLjc0NDEgMTcuNjk4NUMyMy42MDM0IDE3LjU1NzggMjMuNDEyNCAxNy40Nzg3IDIzLjIxMzMgMTcuNDc4N0MyMy4wMTQzIDE3LjQ3ODcgMjIuODIzMyAxNy41NTc4IDIyLjY4MjUgMTcuNjk4NUMyMi41NDE4IDE3LjgzOTMgMjIuNDYyNyAxOC4wMzAyIDIyLjQ2MjcgMTguMjI5M1YyMi40OTZIMTguNTEzM0MxOC4zMTQzIDIyLjQ5NiAxOC4xMjMzIDIyLjU3NTEgMTcuOTgyNSAyMi43MTU5QzE3Ljg0MTggMjIuODU2NiAxNy43NjI3IDIzLjA0NzYgMTcuNzYyNyAyMy4yNDY3QzE3Ljc2MjcgMjMuNDQ1OCAxNy44NDE4IDIzLjYzNjcgMTcuOTgyNSAyMy43Nzc1QzE4LjEyMzMgMjMuOTE4MiAxOC4zMTQzIDIzLjk5NzMgMTguNTEzMyAyMy45OTczSDIzLjIxMzNDMjMuNDExOSAyMy45OTcgMjMuNjAyMiAyMy45MTgyIDIzLjc0MjggMjMuNzc4QzIzLjg4MzQgMjMuNjM3OSAyMy45NjMgMjMuNDQ3OSAyMy45NjQgMjMuMjQ5M1oiIGZpbGw9IiM1MEU2RkYiLz4KPHBhdGggZD0iTTExLjY4NjcgMjEuNDY2N0MxNi45NTQ3IDIxLjQ2NjcgMjEuMjI1MyAxNy4xOTYxIDIxLjIyNTMgMTEuOTI4MUMyMS4yMjUzIDYuNjYwMDEgMTYuOTU0NyAyLjM4OTQgMTEuNjg2NyAyLjM4OTRDNi40MTg2MiAyLjM4OTQgMi4xNDgwMSA2LjY2MDAxIDIuMTQ4MDEgMTEuOTI4MUMyLjE0ODAxIDE3LjE5NjEgNi40MTg2MiAyMS40NjY3IDExLjY4NjcgMjEuNDY2N1oiIGZpbGw9IiMwMDc4RDQiLz4KPHBhdGggZD0iTTExLjY4NjcgMjAuMzUzM0MxNi4yMzkgMjAuMzUzMyAxOS45MjkzIDE2LjY2MjkgMTkuOTI5MyAxMi4xMTA2QzE5LjkyOTMgNy41NTgyOSAxNi4yMzkgMy44Njc5MiAxMS42ODY3IDMuODY3OTJDNy4xMzQzNyAzLjg2NzkyIDMuNDQ0IDcuNTU4MjkgMy40NDQgMTIuMTEwNkMzLjQ0NCAxNi42NjI5IDcuMTM0MzcgMjAuMzUzMyAxMS42ODY3IDIwLjM1MzNaIiBmaWxsPSJ1cmwoI3BhaW50MF9saW5lYXJfMjAxNF8xMTA1NykiLz4KPHBhdGggZD0iTTExLjY4NjcgMTguNzAyNkMxNS40MDMyIDE4LjcwMjYgMTguNDE2IDE1LjY4OTcgMTguNDE2IDExLjk3MzJDMTguNDE2IDguMjU2NzIgMTUuNDAzMiA1LjI0MzkgMTEuNjg2NyA1LjI0MzlDNy45NzAxNiA1LjI0MzkgNC45NTczNCA4LjI1NjcyIDQuOTU3MzQgMTEuOTczMkM0Ljk1NzM0IDE1LjY4OTcgNy45NzAxNiAxOC43MDI2IDExLjY4NjcgMTguNzAyNloiIGZpbGw9IiM1RUEwRUYiLz4KPHBhdGggZD0iTTExLjY4NjcgMTYuNDkyMUMxNC4xNTcyIDE2LjQ5MjEgMTYuMTYgMTQuNDg5MyAxNi4xNiAxMi4wMTg3QzE2LjE2IDkuNTQ4MTkgMTQuMTU3MiA3LjU0NTQxIDExLjY4NjcgNy41NDU0MUM5LjIxNjEzIDcuNTQ1NDEgNy4yMTMzNSA5LjU0ODE5IDcuMjEzMzUgMTIuMDE4N0M3LjIxMzM1IDE0LjQ4OTMgOS4yMTYxMyAxNi40OTIxIDExLjY4NjcgMTYuNDkyMVoiIGZpbGw9IiMwMDVCQTEiLz4KPHBhdGggZD0iTTEwLjIxNDcgMTEuNzE0NkMxMC45NTY5IDExLjcxNDYgMTEuNTU4NyAxMS4xMTI5IDExLjU1ODcgMTAuMzcwNkMxMS41NTg3IDkuNjI4MzQgMTAuOTU2OSA5LjAyNjYxIDEwLjIxNDcgOS4wMjY2MUM5LjQ3MjQgOS4wMjY2MSA4Ljg3MDY3IDkuNjI4MzQgOC44NzA2NyAxMC4zNzA2QzguODcwNjcgMTEuMTEyOSA5LjQ3MjQgMTEuNzE0NiAxMC4yMTQ3IDExLjcxNDZaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMTEuNjg2NyAxMi42NkMxMi4wMTU4IDEyLjY2IDEyLjI4MjcgMTIuMzkzMiAxMi4yODI3IDEyLjA2NEMxMi4yODI3IDExLjczNDkgMTIuMDE1OCAxMS40NjggMTEuNjg2NyAxMS40NjhDMTEuMzU3NSAxMS40NjggMTEuMDkwNyAxMS43MzQ5IDExLjA5MDcgMTIuMDY0QzExLjA5MDcgMTIuMzkzMiAxMS4zNTc1IDEyLjY2IDExLjY4NjcgMTIuNjZaIiBmaWxsPSJ3aGl0ZSIvPgo8L2c+CjxkZWZzPgo8bGluZWFyR3JhZGllbnQgaWQ9InBhaW50MF9saW5lYXJfMjAxNF8xMTA1NyIgeDE9IjExLjY4NjciIHkxPSIyMC4zNTMzIiB4Mj0iMTEuNjg2NyIgeTI9IjMuODY3OTIiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIj4KPHN0b3Agc3RvcC1jb2xvcj0iIzVFQTBFRiIvPgo8c3RvcCBvZmZzZXQ9IjEiIHN0b3AtY29sb3I9IiMwMDc4RDQiLz4KPC9saW5lYXJHcmFkaWVudD4KPGNsaXBQYXRoIGlkPSJjbGlwMF8yMDE0XzExMDU3Ij4KPHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSJ3aGl0ZSIvPgo8L2NsaXBQYXRoPgo8L2RlZnM+Cjwvc3ZnPgo=
[Azure-AI-Vision-url]: https://azure.microsoft.com/en-us/products/app-service
[Azure-App-Services]: https://img.shields.io/badge/Azure_App_Sevices-0769AD?style=for-the-badge&logoColor=white&logo=data:image/svg%2bxml;base64,IDxzdmcgaWQ9ImI3MGFjZjBhLTM0YjQtNGJkZi05MDI0LTc0OTYwNDNmZjkxNSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB3aWR0aD0iMTgiIGhlaWdodD0iMTgiIHZpZXdCb3g9IjAgMCAxOCAxOCI+PGRlZnM+PHJhZGlhbEdyYWRpZW50IGlkPSJlMmNmODc0Ni1jOWE4LTRlZWUtODZjMi00OTUxOTgzYzYwMzIiIGN4PSIxMzQyOC44MSIgY3k9IjM1MTguODYiIHI9IjU2LjY3IiBncmFkaWVudFRyYW5zZm9ybT0idHJhbnNsYXRlKC0yMDA1LjMzIC01MTguODMpIHNjYWxlKDAuMTUpIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSI+PHN0b3Agb2Zmc2V0PSIwLjE4IiBzdG9wLWNvbG9yPSIjNWVhMGVmIiAvPjxzdG9wIG9mZnNldD0iMSIgc3RvcC1jb2xvcj0iIzAwNzhkNCIgLz48L3JhZGlhbEdyYWRpZW50PjxsaW5lYXJHcmFkaWVudCBpZD0iYmRkMjEzZGQtZDMxMy00NzNjLThmZjQtMDEzM2ZkM2E5MDMzIiB4MT0iNC40IiB5MT0iMTEuNDgiIHgyPSI0LjM3IiB5Mj0iNy41MyIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiPjxzdG9wIG9mZnNldD0iMCIgc3RvcC1jb2xvcj0iI2NjYyIgLz48c3RvcCBvZmZzZXQ9IjEiIHN0b3AtY29sb3I9IiNmY2ZjZmMiIC8+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImFmY2M2M2M1LTM2NDktNDQ3Ni1hNzQyLWJjYjUzYTU2OWYzYyIgeDE9IjEwLjEzIiB5MT0iMTUuNDUiIHgyPSIxMC4xMyIgeTI9IjExLjkiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIj48c3RvcCBvZmZzZXQ9IjAiIHN0b3AtY29sb3I9IiNjY2MiIC8+PHN0b3Agb2Zmc2V0PSIxIiBzdG9wLWNvbG9yPSIjZmNmY2ZjIiAvPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IGlkPSJiZDg3M2YwYi05OTU0LTRhYTUtYTNkZi05ZjRjNjRlODcyOWQiIHgxPSIxNC4xOCIgeTE9IjExLjE1IiB4Mj0iMTQuMTgiIHkyPSI3LjM4IiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSI+PHN0b3Agb2Zmc2V0PSIwIiBzdG9wLWNvbG9yPSIjY2NjIiAvPjxzdG9wIG9mZnNldD0iMSIgc3RvcC1jb2xvcj0iI2ZjZmNmYyIgLz48L2xpbmVhckdyYWRpZW50PjwvZGVmcz48dGl0bGU+SWNvbi13ZWItNDE8L3RpdGxlPjxwYXRoIGlkPSJlZTc1ZGQwNi0xYWNhLTRmNzYtOWQxMS1kMDVhMjg0MDIwYWQiIGQ9Ik0xNC4yMSwxNS43MkE4LjUsOC41LDAsMCwxLDMuNzksMi4yOGwuMDktLjA2YTguNSw4LjUsMCwwLDEsMTAuMzMsMTMuNSIgZmlsbD0idXJsKCNlMmNmODc0Ni1jOWE4LTRlZWUtODZjMi00OTUxOTgzYzYwMzIpIiAvPjxwYXRoIGQ9Ik02LjY5LDcuMjNBMTMsMTMsMCwwLDEsMTUuNiwzLjY1YTguNDcsOC40NywwLDAsMC0xLjQ5LTEuNDQsMTQuMzQsMTQuMzQsMCwwLDAtNC42OSwxLjFBMTIuNTQsMTIuNTQsMCwwLDAsNS4zNCw2LjEzLDIuNzYsMi43NiwwLDAsMSw2LjY5LDcuMjNaIiBmaWxsPSIjZmZmIiBvcGFjaXR5PSIwLjYiIC8+PHBhdGggZD0iTTIuNDgsMTAuNjVhMTcuODYsMTcuODYsMCwwLDAtLjgzLDIuNjIsNy44Miw3LjgyLDAsMCwwLC42Mi45MmMuMTguMjMuMzUuNDQuNTUuNjVBMTcuOTQsMTcuOTQsMCwwLDEsMy45LDExLjM3LDIuNzYsMi43NiwwLDAsMSwyLjQ4LDEwLjY1WiIgZmlsbD0iI2ZmZiIgb3BhY2l0eT0iMC42IiAvPjxwYXRoIGQ9Ik0zLjQ2LDYuMTFhMTIsMTIsMCwwLDEtLjY5LTIuOTQsOC4xNSw4LjE1LDAsMCwwLTEuMSwxLjQ1QTEyLjY5LDEyLjY5LDAsMCwwLDIuMjQsNywyLjY5LDIuNjksMCwwLDEsMy40Niw2LjExWiIgZmlsbD0iI2YyZjJmMiIgb3BhY2l0eT0iMC41NSIgLz48Y2lyY2xlIGN4PSI0LjM4IiBjeT0iOC42OCIgcj0iMi43MyIgZmlsbD0idXJsKCNiZGQyMTNkZC1kMzEzLTQ3M2MtOGZmNC0wMTMzZmQzYTkwMzMpIiAvPjxwYXRoIGQ9Ik04LjM2LDEzLjY3QTEuNzcsMS43NywwLDAsMSw4LjksMTIuNGExMS44OCwxMS44OCwwLDAsMS0yLjUzLTEuODYsMi43NCwyLjc0LDAsMCwxLTEuNDkuODMsMTMuMSwxMy4xLDAsMCwwLDEuNDUsMS4yOEExMi4xMiwxMi4xMiwwLDAsMCw4LjM4LDEzLjksMS43OSwxLjc5LDAsMCwxLDguMzYsMTMuNjdaIiBmaWxsPSIjZjJmMmYyIiBvcGFjaXR5PSIwLjU1IiAvPjxwYXRoIGQ9Ik0xNC42NiwxMy44OGExMiwxMiwwLDAsMS0yLjc2LS4zMi40MS40MSwwLDAsMSwwLC4xMSwxLjc1LDEuNzUsMCwwLDEtLjUxLDEuMjQsMTMuNjksMTMuNjksMCwwLDAsMy40Mi4yNEE4LjIxLDguMjEsMCwwLDAsMTYsMTMuODEsMTEuNSwxMS41LDAsMCwxLDE0LjY2LDEzLjg4WiIgZmlsbD0iI2YyZjJmMiIgb3BhY2l0eT0iMC41NSIgLz48Y2lyY2xlIGN4PSIxMC4xMyIgY3k9IjEzLjY3IiByPSIxLjc4IiBmaWxsPSJ1cmwoI2FmY2M2M2M1LTM2NDktNDQ3Ni1hNzQyLWJjYjUzYTU2OWYzYykiIC8+PHBhdGggZD0iTTEyLjMyLDguOTNhMS44MywxLjgzLDAsMCwxLC42MS0xQTI1LjUsMjUuNSwwLDAsMSw4LjQ3LDMuNzlhMTYuOTEsMTYuOTEsMCwwLDEtMi0yLjkyLDcuNjQsNy42NCwwLDAsMC0xLjA5LjQyQTE4LjE0LDE4LjE0LDAsMCwwLDcuNTMsNC40NywyNi40NCwyNi40NCwwLDAsMCwxMi4zMiw4LjkzWiIgZmlsbD0iI2YyZjJmMiIgb3BhY2l0eT0iMC43IiAvPjxjaXJjbGUgY3g9IjE0LjE4IiBjeT0iOS4yNyIgcj0iMS44OSIgZmlsbD0idXJsKCNiZDg3M2YwYi05OTU0LTRhYTUtYTNkZi05ZjRjNjRlODcyOWQpIiAvPjxwYXRoIGQ9Ik0xNy4zNSwxMC41NCwxNywxMC4zN2wwLDAtLjMtLjE2LS4wNiwwTDE2LjM4LDEwbC0uMDcsMEwxNiw5LjhhMS43NiwxLjc2LDAsMCwxLS42NC45MmMuMTIuMDguMjUuMTUuMzguMjJsLjA4LjA1LjM1LjE5LDAsMCwuODYuNDVoMGE4LjYzLDguNjMsMCwwLDAsLjI5LTEuMTFaIiBmaWxsPSIjZjJmMmYyIiBvcGFjaXR5PSIwLjU1IiAvPjxjaXJjbGUgY3g9IjQuMzgiIGN5PSI4LjY4IiByPSIyLjczIiBmaWxsPSJ1cmwoI2JkZDIxM2RkLWQzMTMtNDczYy04ZmY0LTAxMzNmZDNhOTAzMykiIC8+PGNpcmNsZSBjeD0iMTAuMTMiIGN5PSIxMy42NyIgcj0iMS43OCIgZmlsbD0idXJsKCNhZmNjNjNjNS0zNjQ5LTQ0NzYtYTc0Mi1iY2I1M2E1NjlmM2MpIiAvPjwvc3ZnPg==
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
  <img src="https://contrib.rocks/image?repo=othneildrew/Best-README-Template" alt="contrib.rocks image" />
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



