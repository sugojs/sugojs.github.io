# SuGoJS

SuGoJS is a highly modular, increidibly lightweight and simple HTTP micro-framework. It's goal is to provide simple, lightweight and elegant solutions to every day development use cases.

## Origin

We started developing the SuGoJS modules because we wanted a more "Modern Express", a framework that did not break compability with NodeJS and Express (like KoaJS) but used a more promised based approach.

## SuGoJS Development Manifest

SuGoJS follows a set of development standards and objectives:

### Do One Thing, Do It Well

Depelopers tend to think way to big when we are developing a module, package or project. We try to make packages that cover a lot of ground. This

### Simplier is better 

Try to make your solution simple and elegant. Do not make a mess of it because you want humans to understand your code. Simple solutions usually are easier to understand for developers who are using your package, reading the source code or even helping you develop. Even you can have troubles reading your own code.

### More Control, Less Magic

Your module will not fit into all use cases in the world, it is better give the developer solid building blocks and let him decide how to use them, than try to asume how the developer will use them. The concept of middleware fits really well with this, and it is one of the reasons ExpressJS has become so popular in contrast of more monolithic solutions.

### Promises, No Callback

Almost any NodeJS developer has suffered from "Callback Hell". Although there are times where callbacks are the appropiate solution, most times promises are easier to manage, to learn and to develop. Callbacks are everywhere in the NPM ecosystem because of all the legacy code that still uses them.

### NodeJS and Express Compatible

SuGoJS does not aim to overthrow the already standard NodeJS frameworks, rather coexists. Anyone who has worked in NodeJS development knows about ExpressJS and how it is the De Facto framework for building applications. ExpressJS extends the native NodeJS and so does SuGoJS, to keep compability with other NodeJS and ExpressJS applications.

### Minium dependencies

Given the sheer size of the NPM ecosystem, it is easy to deliver every solution with a third-party module, but many times those same modulos do not fit our needs or maybe you are just bringing a gun to a knife fight. With SuGoJS we aimed to use as less dependencies in the development of each module as possible, forcing us to be better developers and to find solutions by our selfs. We do not believe in "pure minimalism", so we do use third party packages when it is necessary. Also, having a lot of dependencies for your project can make your own project more vulnerable, as it depends on many uncoordinated sources.



## Inspiration

The idea behind SuGoJS manifest and design, came by mixing the approach of different frameworks

### [ExpressJS](https://expressjs.com/)

ExpressJS inspired the Sugo Router syntax and part of the middleware approach

### [KoaJS](https://koajs.com/)

From KoaJS, we took the async/await and promises aproach.

### [Symfony](https://symfony.com/)

From Symfony, we took the idea of a modular framework and that each individual modules could be used with or without other SuGoJS modules.

## Developers

- [Francisco Javier Sucre González](https://github.com/franciscosucre)
