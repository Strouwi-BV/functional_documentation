# Introduction

Buildbase was created by Strouwi BV as a mobile application for construction companies which is usable by employees on
their mobile devices.  
The goal of this application is for employees to [register](#register-time) worked hours daily, for
specific [clients and projects](#manage-clients-and-projects).

The managers from construction companies who use buildbase will be able
to [consult these hours based on some parameters via file export](#consult-employee-hours).

The current plan is to build a custom frontend as a progressive web application. This means it will be accessible
everywhere with the only prerequisites being access to internet and a browser. The language used will be Vue.js.

As backend, we opted for the Java Spring-netflix cloud architecture. This means a microservice framework will be used to
handle default components like authentication, authorization, ... while the specific requirements will be created in a
standalone microservice component.  
All components will be connected using this framework.