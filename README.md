# BCrypt-Core for VS3.5
Implementation of BCrypt algorithm for .NET Core.

Forked from work by [haryoncaetano](https://github.com/haryoncaetano/bcrypt-core/), licensed under MIT License.

I made this code, copied files one by one manually from haryoncaetano from a blank project. It's hard to find Blowfish implementation working in .NET 3.5, so I gave it a try and it somehow worked.

Seems to be compatible with Blowfish passwords generated in PHP (like Laravel's `crypt` function), but please make a comment if it doesn't work in you.

Needs Visual Studio 2017 to compile this code. 
