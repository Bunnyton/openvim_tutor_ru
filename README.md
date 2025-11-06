# OpenVim
Interactive tutorial for Vim. Initial version created and published in 2011.

## What is OpenVim?

OpenVim is a web-based project to let people quickly have a taste what kind of an editor Vim is.
Vim is considered to be very useful but can feel devastatingly opaque at first. Hopefully this tutorial makes people feel more comfortable to give it a chance.

OpenVim is based on a custom engine that interprets vim commands. 
Fun fact: the engine operates directly on the dom but could be easily refactored to a model that is not view-dependent.

## How to help?

If you want to help with actual code, look at the existing GitHub issues. Especially keybindings are hard for me to get right in different environments.

## License

MIT License.

## Fork

Тренажер является форком проекта https://github.com/anton-holmes/vim_interactive_ru (https://www.openvim.com) и адаптирован под русский язык

## Deploy

`docker build . -t bunnyton/openvim_tutor_ru`

`docker run -d -p 8889:80 --name=openvim_tutor_ru bunnyton/openvim_tutor_ru`

https://hub.docker.com/repository/docker/bunnyton/openvim_tutor_ru/
