# nRF52RenodeDev
[[_TOC_]]

## Description
This Repo includes the files necessary to build the Hello World application and
start the Renode emulation of the application running on the nRF52840.

## Specification
nRF Connect: 3.7.0
nRF Connect SDK v1.6.1
Renode Version 1.12.0.25160
OS Version: Windows 10

## Installation

This project assumes that the Installation of the nRF Connect SDK and Renode are
already installed on the host system. If not see links below for installation
instructions

[Nordic nRF Connect](https://developer.nordicsemi.com/nRF_Connect_SDK/doc/latest/nrf/gs_assistant.html#gs-assistant)
[Renode]((https://github.com/renode/renode)

## Running application

1. Build binaries
  1. Clone git repo
  2. Open nRF Connect bash prompt
  3. Navigate to the hello_world directory
  4. Build project using
  ```sh
  west build -b nrf52840dk_nrf52840
  ```
2. Open Renode
3. Run Renode resc file using
```sh
 s @/Users/anton/nRF52RenodeDev/nrf52840HelloWorld.resc
 ```
