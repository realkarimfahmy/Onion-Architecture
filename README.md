# Onion Architecture In ASP.NET Core With CQRS

The onion architecture, overcomes the issues of the layered architecture with great ease. With Onion Architecture, the game changer is that the Domain Layer (Entities and Validation Rules that are common to the business case ) is at the Core of the Entire Application. This means higher flexbility and lesser coupling. In this approach, we can see that all the Layers are dependent only on the Core Layers.

## Overview
![alt text](https://teamsmiley.github.io/assets/clean-architecture-dotnet.png)

We will talk about Onion Architecture In ASP.NET Core and it's advantages. We will also together build a WebApi that follows a variant of Onion Architecture so that we get to see why it is important to implement such an architecture in your upcoming projects.

<!-- wp:paragraph -->
<p>Here is a list of features and tech we will be using for this setup.</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Onion Architecture</li><li>Entity Framework Core</li><li>.NET Core 3.1 Library / .NET Standard 2.1 Library / ASP.NET Core 3.1 WebApi</li><li>Swagger</li><li>CQRS / Mediator Pattern using MediatR Library</li><li>CRUD Operations</li><li>Inverted Dependencies</li><li>API Versioning</li></ul>

## About Me
- Twitter - [Karim Fahmy](https://twitter.com/itskarimfahmy)
- Linkedin - [Karim Fahmy](https://www.linkedin.com/in/devkarimfahmy/)


