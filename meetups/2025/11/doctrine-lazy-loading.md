# Tackling the N+1 Problem in Doctrine

- __Speaker__: Adrian Brajković
- __Contact__: adrian.brajkovic@sofascore.com
- __Duration__: 35 min

## Description
Doctrine is a powerful tool for managing data persistence in Symfony applications, offering flexibility and abstraction that streamline development. However, its default lazy loading behaviour - while convenient - can easily trigger the N+1 problem, causing the number of queries behind a simple response to skyrocket.

In this talk, we'll delve into how lazy loading operates within Doctrine and how to mitigate the N+1 problem. We'll showcase some known solutions - like fetch joins and eager loading - and show why they are not always ideal. We'll also show how to keep the simplicity of findBy and short queries while avoiding the pitfalls of lazy loading.

## Speaker short bio
Backend developer at Sofascore
