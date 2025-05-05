<img src=https://spaceport.com.co/assets/spacegal-rounded.svg width=250>


**Spaceport** is a comprehensive full-stack web application framework engineered to make building applications dynamic, fast, and scalable. Designed for rapid iteration, it features an opinionated yet flexible technology stack built upon mature and powerful components. Spaceport uniquely enhances server-client interaction with built-in capabilities like server actions, server reactivity, and server elements directly embeddable within your HTML. These features seamlessly integrate with robust backend systems developed using powerful Groovy modules, offering a cohesive development experience.

### A dynamic stack

Spaceport is built on a robust foundation of open-source components— Groovy, Jetty, and CouchDB, ensuring long-term support and transparency for your operations.

Groovy enables rapid application development and iteration through its dynamic nature and seamless integration and full interop with the mature Java ecosystem.

Jetty provides a high-performance web server platform, supporting modern protocols like HTTP/2 and WebSocket, for secure and accessible web applications.

CouchDB offers a flexible and scalable NoSQL database with built-in replication for reliable data backup and secure storage of evolving data structures, earning it the tagline — relax.

On the front-end, Spaceport fully recognizes the universal standard of HTML, CSS, and JavaScript. It's designed to embrace these core web technologies in their 'vanilla' form, providing intuitive mechanisms that seamlessly extend their capabilities and connect your front-end interactions directly to the Spaceport-powered backend.

### 2.0.X Pre-release

Spaceport has been a work in progress for nearly 10 years serving as a framework for many closed-source products, but is being released (eventually) as open source. There are some features that are still being built out, but Spaceport offers many mature core features that are ready to use. Development is focused on testing, code cleanup, and most importantly, documentation. Spaceport 2.1 strives to be a stable release with a fully open-source license. For now, Spaceport is closed-sourced, but free to use for both personal and commercial products. Contact jeremy@spaceport.com.co for an explicit license, if necessary.

### Getting Started

Spaceport currently offers two Starter Kits to get your application off the ground. 


##### Port-Echo Starter Kit

[Port Echo](https://github.com/spaceport-dev/port-echo) offers a basic scaffold and minimal boilerplate to get your application up and going without any additional assumptions. 


##### Port-Mercury Starter Kit

[Port Mercury](https://github.com/spaceport-dev/port-mercury) is a Spaceport starter kit that provides a basic app structure and configuration for building a Spaceport application with some key Spaceport features. If you are just getting started with Spaceport, consider using this Starter Kit.


### Other Pre-requisites
- Java 8 or higher
- CouchDB 2.0 or higher


### Startup
To start Spaceport, run the following command:

```bash
java -jar spaceport.jar --start config.spaceport
```

This will start the application using the configuration file `config.spaceport`. You can also use the `--no-manifest` argument to assume a default configuration. 

Don't have Spaceport yet? You can download it from the [Spaceport website](https://spaceport.com.co/builds/). Or, use
the following command to grab the latest version:

```bash 
curl -L https://spaceport.com.co/builds/spaceport-latest.jar -o spaceport.jar
```

### Learn more
For more information about Spaceport, visit the [Spaceport documentation](https://spaceport.com.co/docs).

As documentation is built out, feel free to join us on our [Discord Channel](https://discord.gg/rbdU6AD3a9) for questions not covered. 
