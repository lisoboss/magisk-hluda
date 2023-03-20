# MagiskFrida

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/lisoboss/magisk-hluda/main.yml?branch=master)
![GitHub repo size](https://img.shields.io/github/repo-size/lisoboss/magisk-hluda)
![GitHub downloads](https://img.shields.io/github/downloads/lisoboss/magisk-hluda/total)

> [Frida](https://frida.re) is a dynamic instrumentation toolkit for developers, reverse-engineers, and security researchers

> [MagiskHluda](README.md) lets you run hluda-server on boot with [Magisk](https://github.com/topjohnwu/Magisk)

## Supported architectures

`arm64`, `arm`, `x86`, `x86_64`

## Instructions

Install `MagiskHluda.zip` from [the releases](https://github.com/lisoboss/magisk-hluda/releases)

> :information_source: Do not use the Magisk repository, it is obsolete and no longer receives updates

## How fast are hluda-server updates?

Instant! This module is hooked to the [hluda](https://github.com/hzzheyang/strongR-frida-android) build process

## Issues?

Check out the [troubleshooting guide](TROUBLESHOOTING.md)

## Building yourself

```bash
poetry install
poetry run python main.py
```

- Release ZIP will be under `/build`
- hluda-server downloads will be under `/downloads`
