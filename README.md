<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<br />
<div align="center">
  <a href="https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai">
    <img src="assets/images/logo-sml.png" alt="Logo" width="350" height="350">
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


## Companion Repositories

- ML Models, Training and Deployment Code
	- [GitHub Repo](https://github.com/Astrotope/mr-level-05-fsd-mission-01-models)
- ML Traning/Validation Datasets
	- [GitHub Repo](https://github.com/Astrotope/mr-level-05-fsd-mission-01-datasets)
- POC Frontend/Backend Code
	- [GitHub Repo](https://github.com/Astrotope/mr-level-05-fsd-mission-01-backend-frontend)


<!-- ABOUT THE PROJECT -->
## About The Project
<div align="center">
  <a href="https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai">
    <img src="assets/images/logo-sml.png" alt="Logo" width="200" height="200">
  </a>
</div>

### Key Stakeholders

#### The key stakeholders and their interests include:

- **Product Owners/Business Leaders** (Turners Cars - Insurance Division Management):

  - **Interest**: 
    - They want the project to deliver business value by streamlining customer acquisition and improving conversion rates.

  - **Engagement**: 
    - Provide regular updates on progress and demo key features. Engage them early to align technical goals with business objectives and ensure you're building a solution that meets their expectations.

- **Technical Team Members/Developers** (Turners Website Production Team, and POC Developers):

  - **Interest**: 
    - Ensure the system is robust, scalable, and easy to integrate with other services. Technical Team Members/Developers will be directly involved in implementing, testing, and troubleshooting the system.

  - **Engagement**: 
    - Collaborate closely on design decisions, address technical challenges together, and maintain open communication channels for efficient problem-solving.

- **Data Scientists/AI Specialists** (Machine Learning Specialists that will train the ML Models):

  - **Interest**: 
    - Data Scientists/AI Specialists will focus on model performance, training data quality, and optimizing the computer vision algorithm to meet accuracy and speed requirements.

  - **Engagement**: 
    - Regularly review and iterate on the data models and algorithms. Schedule knowledge-sharing sessions to leverage their expertise and gain feedback on model performance metrics.

- **Legal/Compliance Teams** (Regulatory Compliance Team, Legal):

  - **Interest**: 
    - Legal/Compliance Teams are concerned with data privacy, adherence to regulations, and ethical use of AI, especially if sensitive data is involved.

  - **Engagement**: 
    - Consult them during the design phase to ensure compliance requirements are embedded in the system. Schedule review checkpoints to stay aligned with legal standards and preempt any regulatory hurdles.

- **Customer Service, Marketing and Sales Teams** (At corporate, and at branch level)

  - **Interest**: 
    - Customer Service, Marketing and Sales Teams are interested in how the solution will impact their workflows and enhance the customer experience. These teams may also provide valuable insights into common customer concerns and expectations.

  - **Engagement**: 
     - Host feedback sessions to gather insights on how the automated system will integrate into their processes. Share user stories and test cases to ensure the system meets practical use cases and improves the overall customer journey.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Project Launch Meeting Questions

- **What are the primary objectives and goals for this specific project?** 
  - Understanding the overarching and specific goals, that will define the technical requirements for the computer vision system. This will ensure the project stays focused on providing value, and clarify the expected outcomes, such as accuracy levels (of computer vision predictions) and user experience (response time).

- **What are the main timelines, dates, and milestones?** 
  - Knowing that schedule is crucial for the planning the development, testing, and deployment phases of the computer vision model. It will also allow for prioritization of tasks, such as data collection, model training, and integration with existing systems, to meet deadlines.

- **What are the most critical obstacles or constraints, and what happens if the project isn’t successful?** 
  - Identifying potential hurdles, like limited data for training the model or regulatory challenges (privacy, legal requirements for accuracy of quotations), can help to proactively develop risk mitigation strategies. Understanding the consequences of failure will also inform the level of risk acceptable and shape contingency planning.

- **What are the best assets to leverage for this project?** 
  - Identify useful resources, such as existing image datasets, pre-trained models, or expertise within the project team that could accelerate development and improve the system's performance.

- **What technologies and tools can the team use to complete this project?** 
  - Knowing the available tools, such as frameworks for computer vision (e.g., Azure Custom Vision, TensorFlow, Keras) and cloud platforms for processing, ensures the team is equipped to deliver an efficient and scalable solution. It also aligns development efforts with the organization’s tech stack.

- **Is there anything else?** 
  - Use the Johari window to identify project aspects that haven’t been uncovered, and establish processes for communicating new information that may be discovered as the project proceeds.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Project Specfication

- Upgrade Insurance Quotation System for Turner Car Auctions, Insurance Division
- The upgrade will include

  - The ability for a customer to upload an image of their vehicle
  - A machine learning model trained to identify a vehicle's class from an image.
  - An web API endpoint to wrap the machine learning model. 
  - A backend serve the API endpoint/s, to a frontend while securing API access details.
  - A web frontend, that will 
    - allow a customer to upload an image of their vehicle.
    - identify the class of their vehicle.
    - provide an insurance quote based on the class of their vehicle, to the user either through the web interface, or via email.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Implementation Specification

- The solution provide be a cloud-based, web-accessible, machine learning model prediction API endpoint that can accept images, and return vehicle class predictions.
- The service should use a cloud service provider like...
  - Microsoft Azure or,
  - Amazon Web Services or,
  - Google Cloud
- The solution does not need the business logic to calculate the insurance premium, as this will be handled by another team.
- Third party code from online sources can be used for the P.O.C., as long as the developer understands how it works. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Proof of Concept Solution

- ML web API Endpoints, and ML Models
  - Models [GitHub Repo](https://github.com/Astrotope/mr-level-05-fsd-mission-01-models)
    - Solution 01: Azure Custom Vision Service. Models General [A1] & General (compact) [S1]. Served on a Custom Vision Prediction Endpoint.
    - Solution 02: Azure ML Endpoint, using Keras Model (EfficientNet B1) wrapped with FastAPI in a Docker container.
- ML Model Training/Validation Datasets
  - Datasets [GitHub Repo](https://github.com/Astrotope/mr-level-05-fsd-mission-01-datasets)
- Backend/Frontend [Express.js Node.js]/[React, Semantic UI, Tailwind CSS]
  - Backend/Frontend [GitHub Repo](https://github.com/Astrotope/mr-level-05-fsd-mission-01-backend-frontend)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This project was built using these framewords/libraries/services ...

* [![GitHub][GitHub]][GitHub-url]
* [![Azure App Services][Azure-App-Services]][Azure-App-Services-url]
* [![Azure Custom Vision][Azure-Custom-Vision]][Azure-AI-Vision-url]
* [![Express][Express.js]][Express-url]
* [![React][React.js]][React-url]
* [![Semantic UI][Semantic-UI]][Semantic-UI-url]
* [![Tailwind CSS][Tailwind-CSS]][Tailwind-CSS-url]
* [![TensorFlow][TensorFlow]][TensorFlow-url]
* [![Keras][Keras]][Keras-url]

[Tailwind-CSS]: https://img.shields.io/badge/Tailwind_CSS-E50E31?style=for-the-badge&logo=tailwind-css&logoColor=61DAF
[Tailwind-CSS-url]: https://tailwindcss.com/
[Keras]: https://img.shields.io/badge/Keras-D23585?style=for-the-badge&logo=keras&logoColor=61DAF
[Keras-url]: https://keras.io/
[TensorFlow]: https://img.shields.io/badge/TensorFlow-2D3CB0?style=for-the-badge&logo=tensorflow&logoColor=61DAF
[TensorFlow-url]: https://www.tensorflow.org/
[Semantic-UI]: https://img.shields.io/badge/Semantic_UI-852DB0?style=for-the-badge&logo=semantic-ui&logoColor=61DAF
[Semantic-UI-url]: https://semantic-ui.com/
[GitHub]: https://img.shields.io/badge/GitHub-DD0031?style=for-the-badge&logo=github&logoColor=61DAF
[GitHub-url]: https://github.com/
[Azure-Custom-Vision]: https://img.shields.io/badge/Azure_Custom_Vision-FF2D20?style=for-the-badge&logoColor=white&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAACXBIWXMAAAsTAAALEwEAmpwYAAAFB0lEQVRIiY2UW2wUVRjHf2due6PdLmzbLW1ZLaIgdwMRC0KkIFGRQJBieAATn3jAaOIlJgYBNUYMiSFiiMZ4wSdCEGMQAUEEQ63hoqHUIrctNHWp2267y+52Z3bm+NDtdgsF/CeTmfPN//y/y/nOJ3Z02/JwVukGtMFHFyi7Q6wCvuPemAO0NEZpsSSjADVvFxN16RXvxBwLWD/fIy7ogusCegMqiYcMnP8hfhuaMqgSjKNpKVstcU5sjjnZjWOE6w58BRh9tSs76WBL3/SuRG6az6XGpta6W5+c4j8NXAX67+RsTZSEdpdg5m3Z17lsU3O8AagD3IDI/7OhI/pc2HPy7Wer9k+u9hwDoiNoOFo+ymE40ZZcuXRXx4tJx6kHRmlCkBcfdCCBcXvaM7V7Pr5Sv+nRwPcbl4/9Bjh1i5StqUKIYsuJtuTKBV9d26AJUR9QVV1VoNylU+FzU+rWZb9li3jGFJGbGQWgN+fUbWqOr+3L2qXbVtduB/4Y1NIEtpBSLgEO5m1PKG+ef6NEURr8uqKVe1zU+L34PcaINYzEkkSSafodScyyYx8tDH760uLKrUBfnrJBAY7kF4EXPo88D8yvcGtazSgPk0NlBfFEoo9r1yPc6Boq9X3BEqZV+PHrKgFVDb58NLaMgbYdxC4NyOUXc76+lFoSMjSPoSjUBUsKws0tZ4imksOiXzBpOuNqwoz2uanKWEA/8bQ9ccu+zqUbl48drEimcMDbDtxYBNQEDI2qEg9K/miaW86wfc0UOrav5qlwWcHBL3/9WcimotSDV9MI6qq2pzWxqCiObMHBuc7M3KCuqm5NpSxflmsd7YR9sGrBBKpHu1hRf/+wLE6cPwOA19Dw6Sp+XaUladcWcwr3oDORG+/XVVyqgtcYMN/4N0pbLMlbXzQxvS5IKmMR9um0p6yB/HM5TMvE0A1KXDpZ24G0OaztCwsVqQFoRV1r59/vHblI42dNVJeXEPK5uRNc6m1XasjB+HLXBctxUFWFbG5Aemywchi58bMmmruGDtujaRj6QDltKQcygJsjOpgd9h7uzNqWoSpYOUcC1NSEKXXfOeLHHn4EANN2UIUgYVosqnBdHNHBuseDP+ekvBrPmJi2jSMlihAsmDqbkK/kNvG5D06hujI04MCypa4K2Z6xsiumlR4v5hUPu1OvzCg9sOt8amxVqcfXb9nSa2iirCzA4von6O2N09MXx+X2UlVRWWhj03awpeR6X0Z4hDi/vqHi0K0Z1OW/E9tW1+6OWfbRjr60CZDN2dKREoCysgB14TqqK0PF4tK0bNlv2eJcIt355fLQtwwfeDOUd7vl6V/TDA6bk5FXH9h5tjd15GrPzSwgLduRpu1IR8phTzZnSymljGdMfov2/vPh/ODeFbMDe4FCF6y9wQnNAWmCBzABxo1xHXDen2w3bG3r//FKpmFywOcPlXhymksTDIxpBXC6U9lce1+Ky2nz7y+erty37vHgbqC1uDw5iaLlN3kYmoAAh468PrHnk5+6Wnf+3rN4XyQ5KWRovnK3oaZzOedy2uwHLr8203/8g8YJPwBNt+wfREpsjjmxeR4xa6GXyAgEAXiB8P6zvZPiaXuMzyW6V8wa3QZEgHQ+wBGxJsolTQF5MiPdC71iJI4EUkDrMzPLWkci3AOK2NFt24ezSk9RJEIXOLtDTAcM4NpdBFRgHGA0RjlmDeXiBvSJunT9B65iESKwcVT9AAAAAElFTkSuQmCC
[Azure-AI-Vision-url]: https://azure.microsoft.com/en-us/products/ai-services/ai-vision/
[Azure-App-Services]: https://img.shields.io/badge/Azure_App_Sevices-0769AD.svg?style=for-the-badge&logoColor=white&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAACXBIWXMAAAsTAAALEwEAmpwYAAAFbUlEQVRIiY2VTWxcVxXHf+feN2/ezHhixx7HHge7NondhjZuSNo6kIi6UtUSKiEWiNIKVAlaIbFgA0gVQiLs+BASLIBNF2yKgCJoI1rR8pGqalRCQ5ImboLTfOI09tj1x9iejzfz7j0sJnGaOqGcxVvcd+//d8957/yPqCr/T1RjLxffi33cVFIWRopRexiY5Q87J/8LcPzCqp6YWuVnh5a5WHEECMnaW+XhgYgndnfy0PZ2I8JNhW4KOD8XP/uDl0qPO+d4/J42njta4c+XYowI3rf2eFUaQNN59vak+ckX+t7b2hN1f1Ar+ODCL/82q989uEDGCGEgPDDs+NxojgtLMF3xYBUHbMoYdhTT9OQDunKG45dqhVI50T0jbXLLDJ45WNJv/XWBbMqQEyFlDQMbAr59fxvluvKLN6rs3ByxvS9Nd96iCqqKqlJteFZjx+hAhl2DOVkHODS5rMcurfCjQ6tE1hBZQ2AtKSPs6Q95YiyDDSzTqwY81JrKubmYiek6J6YblBsJdedJW3jtG0PfL3aE+wEMQNz08urpMvm0oSeypKwhsIa0FbqzAWNbcqgEtEdQbFP+cb7Gz18v84eJKqdmExytbNPGsOLghy/Nfu+Gb/D80SV/uewY6Eyx+yMRhXyICJyedTy2K08+sizUYXalSXvaMbjR8MaUJR0IIoKIA1oli1R59t+rfGWqqqP9WQkAfvuvJSp1z9fH2/j8WEQYtEq4VHVMl5W5Zc9rZ+pMzDo+PWy5s2j48o6Q359ssBwreEMgHmuElAhWhN8cXmS0P9sq0aErMV+6r4PhYmZNHKAja9ncYTg10+TMvBKlLK9egGPvwmDB8ORYmt68ZbiQYnd/mnv7IrZ2BITAc6dWWyV6p1QvJcD9IxkVTSS52kmqioiQCZSPdgn/nBIUQUQ5PKUsVpXxrYavjkWAcN9QCoADx6s8/coCc7GjVG7uDxpN3WSMENmm1GrNdU0HUMi2YK3cWs/Tc7BYdezbBh/fLNTrDoBPbRH36LbIPnOyysJq8p2g6RTvYXa+QlferBNXVebLAaqpG9eBi2WlvBJTrepaxqpq84EDFGuEIJs2i8DGg2fqPPIxWQdoJPCXcxtadxfB6zWwR1U5XfLcVait7fceetvbGC960oF5OxgshF1O1f/4zYSRgtCba2KlpRI7y4rLUXdCnHgCY1DAeSXxDuc8x2cskQh3dMYkCpPzaTZsEB7ZlqG/EO4MwsDoZ4cynF1ISKJNXHGONydnyYQBg8UOrBEeHBYmpj0nS47R3hSBhfas4cW361QSOHA+4ndnQuqJp5YkqC7z2F05jKABwBfv2ciLJ5dRhQvzjhfOh4SBYWQhZs9QSFeb4c5e4cHbU9zd3/LHxEFkPL86UqHhPA3naXpHQz0rTc+uwRxw1So+s6Nddg5kUFWOXK7T9ErilLMLTX79Vo2JdxOcV3pyDWq1GrVajWajxgNbW8KJUxre01Cl7mEwZ9m3o8PC++x6z3AunpyJ04enqjRVcCgOQ0Ph5XM1jk1b7u5WKv66+6rCk/dGlKuexZpjvuJInOdr45sIrfgbAHf0ZaLJmbrOxJ6cFbyAKFijOGO4vJJwttRkS5dfA5RWLekgojtvKOSELV2WznzIrqGb2PW12P/HK/rTI2UypuWmgRUCBCPCeDFhrNigJ++YrRheOBux1LAEBpzzPPXJTh79RNetB861OHB0Sb/5pxJLiWJFCAEjgjHX/3WvileoeeXhgTRP7+thtD+7rpFuOfSX6y58+a1y/PyJMn//T0zNt2Bcne23ZQ3be9I8tbeLvbfn13fo+wDXT90iGk7NO9N110iUKCX12wrpvqsO8KHxX8prldq76f1xAAAAAElFTkSuQmCC
[Azure-App-Services-url]: https://azure.microsoft.com/en-us/products/app-service/
[Express.js]: https://img.shields.io/badge/Express-563D7C?style=for-the-badge&logo=express&logoColor=white
[Express-url]: https://expressjs.com/ 
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Sweet-Alert2]: https://img.shields.io/badge/Sweet_Alert_2-4A4A55.svg?style=for-the-badge&logoColor=white&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAXCAYAAAARIY8tAAAACXBIWXMAAAsTAAALEwEAmpwYAAAEfUlEQVRIiZWVy1NTdxTHPycvAyEkhISAvOQRBqKmqNUq07pw6qh11OnDTp3WLlqnnS678M/owkW76Ey7sovWWqed1im+xoJUBGt5RFEHBATlESBEbkguCffXBQVM44g9q/v7/e79fs7jnt8RpRQvamP3IspiM+Or8si/WwI8T8BuemF1ID6bQE+knt5ay7ukvGgESU1XidkkIoKjMBer3SJrfwWWDA9nEqr3Yj/b3wpitpolPpNQvefvMtIzjj3fRp7XgTIUT8bnSOuGqmkqJ3SwHrPFbDHSRvrG2TA7j25GTLICz4pg8NYj5SlzMdQ5wv0/hth+dBMbNrtQN5rBGkdps8iigbLncXeggNthC1ve3YKzyElsUqOuqTIjsmelSFq/6TAsNgsNewO4IpdRdzpQmoHYhPaRBjb5h3BMzYHXDHYTl3rr8DdtpfFw6L9pkyzAX+d6VTq5SNlGN5GWNkKuMGrWQJwmMMNsIg93jgbzCnJk6T8CLnaUUXNkF7Wvb82AmJRSucuL6GhMjfw9xivvhSgZOEPIFV46sAlKMwCWxIHHiz4exvwA9NxzUVsapfXrTgxdy/A4I4IrX11XwT01FE00o7rCiEvALDzRrDwYzedyqxuAQFWCHdvnWGcTUvMLdPQXUlajMzFspSTko/GjYytRZPTB9GCU4oI4DN8BAaXAMIRfW8ppOP4GJ1tOyMmWE1Lc1MB3PxQxNakoLNApcOgkdRP7jkfp75gBbVRlASJDM6ooUMj8cB8ISIEJsQi/XFnPB1/uJ6c+uOLVzk9flz2f1XPhmo+Wmz4C6zWGwjbSC0s1SU/dXq3Bw54xdfXbm0qLxMkvzqO9RQfgXqQCPW1jYNAOnvKsptp27FVJzgvB3Qmu9xUSeEnHYlPkexbRRodX3rNUhEqkIlTCUOeIEhE2lT2CFHjzYiQWbcgal4m/OsWR6unVogqgz65GsPyQW5CDFtHw5s2hdIXHPIt7nUZDXYJb37dnNUv32Ta1IbiQBdRiZnLy0tkAX3UhY3enEbsDLCC2pawceO0x7adv0/tz5wqk+2ybunCqj4Pvz2QB0guCLde5miKlVLGIjItJJN/vUNMJHx7zGCpqLBXbbeLE2w8495PO7190r0De/CSKPXcxQ7w/nEtlnQ7OqlWAiIwvLxoPB+k8Pcu+WsAhYILYnBWb1aCiOM6OA3NUBpJZXi9bV5uDQx9OIe767BQB+ANeya8upWeyGrEJj6YdXOj08+OlUgLlGtfPO7NEl+3aeTfBbfPYvaXgrl9tNKWUe3mxEF9QnppCJhbK6L7vAQXe4jSHPp7hapePilr9meJtzS7MVkXw5ThStjfjLOOqaD/Toxp2V+HyO+XPU7+px12D6CkTxz6PPFN4dMDOjctOAqEEoZ0apqp3wLPRxFOT7rkTbbC1R91v7iQ2qVNUmsLhMsCAWNTMzIQFf3mKxl0a+eu9SPl+cFZmiK8JWLFon4qEe4hPjCNGkjxXGk+xFXFUQMFGKNycJfz/AE+ZMlJKFGC2rjWTBTD/A+V63IMX4OsYAAAAAElFTkSuQmCC
[Sweet-Alert2-url]: https://sweetalert2.github.io/
[React-Router]: https://img.shields.io/badge/React_Router-FF2D20?style=for-the-badge&logo=react-router&logoColor=white
[React-Router-url]: https://reactrouter.com/



<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Disclaimer

This project is a concept demo and is for informational and educational purposes only. It references and uses the trade name of [Turners Car Auctions] as a conceptual basis. However, this project is not affiliated with, endorsed by, or officially connected to [Turners Car Auctions] in any way. All trademarks, service marks, trade names, and logos used in this demo are the property of their respective owners. The inclusion of the business name and any associated references are solely for illustrative purposes and do not imply any official association or representation of [Turners Car Auctions].

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Project Log

See... [Project Log](PROJECT_LOG.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Delvelopment Roadmap

- [x] [Sprint-01] Assemble Training/Validation Images Dataset
- [x] [Sprint-02] Create Training Code - Azure Custom Vision - Colab
- [x] [Sprint-03] Train Custom Vision Models
- [x] [Sprint-04] Deploy to Prediction Endpoint
- [x] [Sprint-05] Create Training Code - TensorFlow/Keras EfficientNet - Colab
- [x] [Sprint-06] Train EfficientNet Model
- [x] [Sprint-07] Create Model Wrapper Prediction API using FastAPI
- [x] [Sprint-08] Containerise API using Docker
- [x] [Sprint-09] Deploy Container to Azure Container Registry
- [x] [Sprint-10] Create and Azure ML Endpoint in an Azure ML Workspace
- [x] [Sprint-11] Give the ML Enpoint Pull Permission to Azure Container Registry
- [x] [Sprint-12] Setup ML Endpoint Environment to include Containerised Prediction API
- [x] [Sprint-13] Deploy the ML Endpoint to Production
- [x] [Sprint-14] Create an Express.js/Node.js backend to wrap the Prediction API's
- [x] [Sprint-15] Create a POC React web UI (Semantic UI, Tailwind CSS) to implement the new insurance quotation system, and interface with the Prediction API's on the backend.


See the [open issues](https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Research

- [x] Read [Computer Vision service on Azure](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/)
- [x] Read [Custom Vision service on Azure](https://learn.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/)


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

* [Img Shields](https://shields.io)
* [Choose a License](https://choosealicense.com/)
* [Azure Icon Set](https://code.benco.io/icon-collection/azure-icons/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Astrotope/mr-level-05-fsd-mission-01-ai.svg?style=for-the-badge
[contributors-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Astrotope/mr-level-05-fsd-mission-01-ai.svg?style=for-the-badge
[forks-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/network/members
[stars-shield]: https://img.shields.io/github/stars/Astrotope/mr-level-05-fsd-mission-01-ai.svg?style=for-the-badge
[stars-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/stargazers
[issues-shield]: https://img.shields.io/github/issues/Astrotope/mr-level-05-fsd-mission-01-ai.svg?style=for-the-badge
[issues-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/issues
[license-shield]: https://img.shields.io/github/license/Astrotope/mr-level-05-fsd-mission-01-ai.svg?style=for-the-badge
[license-url]: https://github.com/Astrotope/mr-level-05-fsd-mission-01-ai/blob/master/LICENSE.txt


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



