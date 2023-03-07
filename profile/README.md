# [BicisBA](https://bicisba.github.io/)

This project aims at helping you find which [Buenos Aires rental bike](https://baecobici.com.ar/) station to go to while on the move.

Through predictive analysis, based on your location and the real-time availability of bikes at nearby stations, we try to find out the best station for you to get a bike from. This information can save you time and increase the likelihood of finding a bike when you need it most!

The particular problem that we want to solve is that as Buenos Aires is a busy city, sometimes you will see that a near bike station currently has only one or two bikes available. That's not ideal... you are 5 blocks away from that station! Is it worth risking your chances, walking all that distance, and finally finding out that all the bikes were taken? In such cases, our predictions are great at stopping you from walking all that distance and instead telling you exactly which other of your nearest stations is the optimal for you, even if your intuition tells you that it's not.

---

This project consists of 4 repos

- [The landing page](https://github.com/BicisBA/.github), which most importantly contains the whole report on how it was built.
- [The backend and ML model training](https://github.com/BicisBA/frame) that makes the different predictions and serves them on an API for the clients.
- [The front-end web client](https://github.com/BicisBA/BicisBA.github.io), built on React, to easily see the prediction results from your computer or phone.
- [The data research repo](https://github.com/BicisBA/research), which contains our core analysis of the data provided by the Buenos Aires "
API Transporte"
