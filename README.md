# The Suave (Micro)Service generator

A [Yeoman](http://yeoman.io) generator for [Suave](http://suave.io/) and [Docker](http://docker.com).

Suave is an F#-based micro-framework.

## Installation

Install [Git](http://git-scm.com), [node.js](http://nodejs.org), [NuGet](http://www.nuget.org/), [F#](http://fsharp.org) and [Mono](http://mono-project.com/) for development on Windows/Linux/Mac OS X. Install FSharp on [Mac OS X](http://fsharp.org/use/mac/). Install [Docker](http://docker.com) for hosting Suave-(Micro)Services as Container.

Install Yeoman:

    npm install -g yo

Install the Suave-(Micro)Service generator:

    npm install -g generator-suave-microservice

## Creating a Suave (Micro)Service

In a new directory, generate the service:

    yo my-suave-microservice

Install dependencies for Mono:

    cd my-suave-microservice
    mono ./tools/paket.exe restore

Run the service for Mono:

    fsharpi src/service.fsx

Your (Micro)Service will run at [http://localhost:8080](http://localhost:8080).
