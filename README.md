<p align="center">
    <a href="https://screego.net">
        <img src="docs/logo.png" />
    </a>
</p>


<h1 align="center">screego-audio/server</h1>
<p align="center"><i>screen sharing for developers</i></p>

<p align="center">
    <a href="https://github.com/screego/server/actions?query=workflow%3Abuild">
        <img alt="Build Status" src="https://github.com/screego/server/workflows/build/badge.svg">
    </a> 
    <a href="https://github.com/screego/server/pkgs/container/server">
        <img alt="Build Status" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fipitio%2Fghcr-pulls%2Fmaster%2Findex.json&query=%24%5B%3F(%40.owner%3D%3D%22screego%22%20%26%26%20%40.repo%3D%3D%22server%22%20%26%26%20%40.image%3D%3D%22server%22)%5D.pulls&logo=github&label=pulls">
    </a> 
    <a href="https://goreportcard.com/report/github.com/screego/server">
        <img alt="Go Report Card" src="https://goreportcard.com/badge/github.com/screego/server">
    </a>
    <a href="https://hub.docker.com/r/screego/server">
        <img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/screego/server.svg">
    </a>
    <a href="https://github.com/screego/server/releases/latest">
        <img alt="latest release" src="https://img.shields.io/github/release/screego/server.svg">
    </a>
</p>

## original project

screego/server：https://github.com/screego/server


## Intro

In the past, I encountered some issues when sharing my screen with friends. 
Commercial screen-sharing solutions often had a few seconds of video lag or 
poor image quality. Then I discovered the Screego project, which worked really 
well. However, the only downside was that it didn’t support audio. To address 
this issue, this project was born, and that's Screego-Audio (:.

## Features

* Support Audio
* Multi User Screenshare
* Secure transfer via WebRTC
* Low latency / High resolution
* Simple Install via Docker / single binary
* Integrated TURN Server see [NAT Traversal](https://screego.net/#/nat-traversal)

[Installation](https://screego.net/#/install) ᛫ [Configuration](https://screego.net/#/config) 
