
<a id="readme-top"></a>
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="https://github.com/user-attachments/assets/17bbc27d-10f3-4d54-a203-39842d9713e3" alt="Logo" width="300" height="200">
    <img src="https://github.com/user-attachments/assets/10ecdb2e-64ef-4a39-9a22-501ce1c036d9" alt="Logo" width="300" height="200">
    <img src="https://github.com/user-attachments/assets/3e7c28fe-8e09-4801-baf1-2ac51927d1ce" alt="Logo" width="300" height="200">
  <h3 align="center">Cerberus</h3>

  <p align="center">
    A fully open-source automated malware analysis framework!
    <br />
    <a href="https://github.com/Emul4nt/Cerberus/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
    <li><a href="#roadmap">Roadmap</a></li>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project serves as a proof of concept on how an automated malware analysis framework works, when I am analysing malware I often find myself going to sites like https://tria.ge/ but unfortunately triage isn't 100% open-source about their project, so I decided this would be a fun project for me to try and do myself!

### Features

- 🔍 **Automated Static Analysis** - File hashing, entropy analysis, string extraction, and YARA rule matching
- 🏃 **Dynamic Analysis** - Sandboxed execution with behavior monitoring and network traffic analysis
- 🌐 **Web Interface** - Simplistic web application to submit malware and retreive results
- 📊 **Comprehensive Reporting** - Detailed analysis reports with IOCs, MITRE ATT&CK mapping, and threat intelligence assisted by Cisco's Sec8B Threat Intel LLM
- 🐳 **Containerised** - Isolated using Vagrant & Virtualbox


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

The web application is built with python/flask whereas the backend is going to be built with bash and utilising Vagrant for automatic VM deployment, python will also be used for log parsing & result formatting.

* [![Python][Python.py]][Python-url]
* [![Flask][Flask.py]][Flask-url]
* [![Bash][Bash.sh]][Bash-url]
* [![Vagrant][Vagrant.com]][Vagrant-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Begin Web Application
- [ ] Create Static Analysis Scripts
- [ ] Set up Vagrant Environment
- [ ] Integrate Sec8B Threat Intel LLM
- [ ] PDF Generation
- [ ] Interactive Dynamic Analysis
- [ ] VM Hardening

<img src="https://github.com/user-attachments/assets/96638590-beb3-4c28-afbd-8798bf31420b" width="80" height="80">



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/andrew-l-631047283/
[Python.py]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://python.org/
[Flask.py]: https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white
[Flask-url]: https://flask.palletsprojects.com/
[Bash.sh]: https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white
[Bash-url]: https://www.gnu.org/software/bash/
[Vagrant.com]: https://img.shields.io/badge/Vagrant-1563FF?style=for-the-badge&logo=vagrant&logoColor=white
[Vagrant-url]: https://www.vagrantup.com/
