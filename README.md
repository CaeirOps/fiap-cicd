# FIAP - CICD

[![Build Status](https://travis-ci.com/CaeirOps/fiap-cicd.svg?branch=master)](https://travis-ci.com/CaeirOps/fiap-cicd)

A finalidade deste projeto é realizar um deploy de uma aplicação web no Heroku utilizando Travis CI.
A esteira deverá identificar o commit na branch dev ou master, executar o teste escrito em Python para verificação do conteúdo da página, caso passe no teste e seja a branch dev a esteira irá parar, caso seja a master irá para etapa de deploy na plataforma Heroku.
