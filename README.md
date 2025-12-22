# Awesome Reticulum

Hello! This is a list of awesome projects related to Reticulum Network. I add to the list only active projects whose most recent commit is within  the last six months.

## Contents

* [Network Stack](#network-stack)
* [Node Firmware](#node-firmware)
* [Messangers and Browsers](#messangers-and-browsers)
* [Transports and Network Interfaces](#transports-and-network-interfaces)
* [LXMF Bots](#lxmf-bots)
* [Content Server](#content-server)
* [Flasher](#flasher)
* [Micron Markdown Format](#micron-markdown-format)
* [Custom Devices](#custom-devices)
* [Small Tools and Code Examples](#small-tools-and-code-examples)

## Network Stack

* [markqvist / Reticulum](https://github.com/markqvist/Reticulum) - The cryptography-based networking stack for building unstoppable networks with LoRa, Packet Radio, WiFi and everything in between.
* [markqvist / LXMF](https://github.com/markqvist/LXMF) - A simple and flexible messaging format and delivery protocol that allows a wide variety of implementations, while using as little bandwidth as possible.
* [markqvist / LXST](https://github.com/markqvist/LXST) - LXST is a simple and flexible real-time streaming format and delivery protocol that allows a wide variety of implementations, while using as little bandwidth as possible.
* [ion232 / reticulum-zig](https://github.com/ion232/reticulum-zig) - An implementation of Reticulum in Zig targeting operating systems and embedded devices.
* [attermann / microReticulum](https://github.com/attermann/microReticulum) - Port of Reticulum Network Stack to C++ specifically but not exclusively targeting 32-bit and better MCUs.
* [BeechatNetworkSystemsLtd / Reticulum-rs](https://github.com/BeechatNetworkSystemsLtd/Reticulum-rs) - Reticulum Networking Stack implementation written in Rust.
* [Networks / Reticulum-Go](https://git.quad4.io/Networks/Reticulum-Go) - A Go implementation of the Reticulum Network Stack.

## Node Firmware

* [markqvist / RNode_Firmware](https://github.com/markqvist/RNode_Firmware) - An RNode is an open, free and unrestricted digital radio transceiver. It enables anyone to send and receive any kind of data over both short and very long distances. RNodes can be used with many different kinds of programs and systems, but they are especially well suited for use with Reticulum.
* [DanBeard / RETCON](https://github.com/DanBeard/RETCON) - RETCON enables quick creation of pre-configured Raspberry Pi images that automatically form resilient mesh networks once deployed.
* [strijar / RNS-Gate](https://github.com/strijar/RNS-Gate) - Standalone device for access and routing within the Reticulum Network Stack
* [gretel / reticulum-openwrt](https://github.com/gretel/reticulum-openwrt) - GitHub workflow for cross-compiling Reticulum Network Stack (RNS) packages for OpenWrt.

## Messangers and Browsers

* [markqvist / NomadNet](https://github.com/markqvist/NomadNet) - Off-grid, resilient mesh communication with strong encryption, forward secrecy and extreme privacy.
* [markqvist / Sideband](https://github.com/markqvist/Sideband) - Sideband is an extensible LXMF messaging and LXST telephony client, situational awareness tracker and remote control and monitoring system for Android, Linux, macOS and Windows.
* [liamcottle / reticulum-meshchat](https://github.com/liamcottle/reticulum-meshchat) - A simple mesh network communications app powered by the Reticulum Network Stack.
* [torlando-tech / columba](https://github.com/torlando-tech/columba) - A simple messaging app for the Reticulum network on Android using Bluetooth LE over Reticulum.
* [Ren / Browser](https://git.quad4.io/Ren/Browser) - A browser for the Reticulum Network.Target platforms: Web, Linux, Windows, MacOS, Android, iOS. Built using Flet.
* [kc1awv/ lxst_phone](https://github.com/kc1awv/lxst_phone) - A peer-to-peer voice calling application built on the Reticulum Network Stack.
* [fr33n0w / rBrowser](https://github.com/fr33n0w/rBrowser) - A modern, web-based UI for exploring NomadNet nodes and pages over the Reticulum network.
* [RNS-Things / reticulum-meshchatX](https://git.quad4.io/RNS-Things/reticulum-meshchatX) - A heavily customized fork of Reticulum MeshChat, any meaningful, stable and tested modifications will be submitted as a PR upstream.

## Transports and Network Interfaces

* [LFManifesto / ReticulumHF](https://github.com/LFManifesto/ReticulumHF) - Encrypted communication over HF radio using the Reticulum Network Stack and FreeDV digital modes.
* [torlando-tech /  ble-reticulum](https://github.com/torlando-tech/ble-reticulum) - A Bluetooth Low Energy (BLE) interface for Reticulum Network Stack, enabling mesh networking over BLE without additional hardware on Linux devices.
* [Reticulum-Interfaces/ RNS-over-HTTP](https://git.quad4.io/Reticulum-Interfaces/RNS-over-HTTP) - A Reticulum interface that tunnels traffic over standard HTTP/S POST requests. This allows Reticulum to operate on networks where only web traffic is permitted, effectively bypassing firewalls, DPI, and other restrictions.
* [BeechatNetworkSystemsLtd / rns-tun-rs](https://github.com/BeechatNetworkSystemsLtd/rns-tun-rs) - Reticulum TUN adapter
* [BeechatNetworkSystemsLtd / rns-vpn-rs](https://github.com/BeechatNetworkSystemsLtd/rns-vpn-rs) - Library and application for VPN client over Reticulum mesh network.
* [BeechatNetworkSystemsLtd / rns-mavlink-rs](https://github.com/BeechatNetworkSystemsLtd/rns-mavlink-rs) - Bridges a flight controller connectd via serial port to a QGroundControl ground station over Reticulum mesh network.
* [RFnexus / reticulum-over-hf](https://github.com/RFnexus/reticulum-over-hf) - Resources on how to configure Reticulum to work over HF radio.

## LXMF Bots

* [randogoth / lxmf-bot](https://codeberg.org/randogoth/lxmf-bot.git) - Python class to easily develop a simple Telethon style chatbot for the LXMF protocol.
* [lxmfy / LXMFy](https://github.com/lxmfy/LXMFy) - Easily create LXMF bots for the Reticulum Network with this extensible framework.
* [lxmfy / ollama-bot](https://github.com/lxmfy/ollama-bot) - Interact with Ollama LLMs using LXMFy bot framework.

## Content Server

* [RNS-Things / rns-page-node](https://git.quad4.io/RNS-Things/rns-page-node) - A simple way to serve pages and files over the Reticulum network. Drop-in replacement for NomadNet nodes that primarily serve pages and files.

## Flasher

* [liamcottle / rnode-flasher](https://github.com/liamcottle/rnode-flasher) - A web based firmware flasher for Reticulum / RNode_Firmware.

## Micron Markdown Format

* [randogoth / micron-blog](https://codeberg.org/randogoth/micron-blog.git) - Pelican Plug-In and Theme for publishing a site in Micron markup format for Nomad Network Nodes.
* [randogoth / md2txt](https://codeberg.org/randogoth/md2txt.git) - Transform Markdown into arcane text formats (including NomadNet format).
* [RFnexus / micron-parser-js](https://github.com/RFnexus/micron-parser-js) - A JavaScript parser for Micron, a lightweight, terminal-friendly markdown format used in NomadNet and MeshChat.

## LoRa tools

* [markqvist / LoRaMon](https://github.com/markqvist/LoRaMon) - This utility allows you to sniff LoRa networks with an RNode, and dump captured packets to the console or files.
* [randogoth / lora-transmit](https://codeberg.org/randogoth/lora-transmit.git) - Simple commandline raw LoRa packet transmitter for RNode hardware.

## Custom Devices

* [weltamdraht / ReticulumRasPiRelaySwitch](https://github.com/weltamdraht/ReticulumRasPiRelaySwitch) - This project switches on or off some electrical stuff if an according command is received through Reticulum's lxmf.

## Small Tools and Code Examples

* [antlas0 / rns_tools](https://github.com/antlas0/rns_tools) - This package provides a small range of RNS tools, driven by my curiosity about Reticulum stack.
* [SebastianObi / RNS-Tools](https://github.com/SebastianObi/RNS-Tools) - Various small programs and tools which use the Reticulum Network Stack RNS
* [SebastianObi / LXMF-Tools](https://github.com/SebastianObi/LXMF-Tools) - Various small programs and tools which use the message protocol LXMF.
* [CyberKiska / lxmf-vanity-address-generator-py](https://github.com/CyberKiska/lxmf-vanity-address-generator-py) - A simple CLI tool to generate LXMF vanity addresses in Reticulum network.
