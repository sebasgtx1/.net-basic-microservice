# Basic WebAPI in .NET - Introduction to Microservices

This repository contains a basic **WebAPI** service built in **.NET**, using the default **WebAPI** template from .NET. The project is **dockerized** to facilitate distribution and deployment and serves as an initial approach to **microservices** in the .NET ecosystem.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

This project is a basic **REST API** service built with **ASP.NET Core** using the default WebAPI template. The goal of this repository is to provide a starting point for learning and experimenting with microservices in .NET, with the added advantage of having the service prepared to run in a Docker environment.

## Features

- Basic RESTful API.
- Based on the default WebAPI template from .NET.
- Ready for Docker deployment.
- Ideal as a starting point for .NET microservices projects.

## Prerequisites

Make sure you have the following installed before starting:

- **Docker** 
- **Git** (to clone this repository)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/sebasgtx1/.net-basic-microservice.git
   ```
2. Navigate to the project root folder:
   ```bash
   cd .net-basic-microservice/MyFirstService
   ```
3. Build the container:
   ```bash
   docker build -t basic-webapi-dotnet .
   ```
   
## Usage

1. Run the container:
   ```bash
   docker run -d -p 8080:80 --name basic-webapi basic-webapi-dotnet
   ```

2. Access the API from http://localhost:8080


