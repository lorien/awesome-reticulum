# Awesome Reticulum

This is a curated list of projects related to the Reticulum network.  
The source code of the list is hosted at [github.com/lorien/awesome-reticulum](https://github.com/lorien/awesome-reticulum)  
Also available at [awesome-reticulum.net](https://awesome-reticulum.net)

## Contents

* [Network Stack](#network-stack)
* [Application-Layer Protocols](#application-layer-protocols)
* [Node Firmware](#node-firmware)
* [Messengers and Browsers](#messengers-and-browsers)
* [Transports and Network Interfaces](#transports-and-network-interfaces)
* [Network Tools](#network-tools)
* [LXMF Bots](#lxmf-bots)
* [NomadNet Applications](#nomadnet-applications)
* [Flasher](#flasher)
* [Micron Markdown Format](#micron-markdown-format)
* [LoRa Tools](#lora-tools)
* [Custom Devices](#custom-devices)
* [Small Utilities and Code Examples](#small-utilities-and-code-examples)
* [Network Infrastructure](#network-infrastructure)
* [Community Discussions](#community-discussions)

## Network Stack

* [markqvist / Reticulum](https://github.com/markqvist/Reticulum) - The cryptography-based networking stack for building unstoppable networks with LoRa, Packet Radio, WiFi and everything in between.
* [ion232 / reticulum-zig](https://github.com/ion232/reticulum-zig) - An implementation of Reticulum in Zig targeting operating systems and embedded devices.
* [attermann / microReticulum](https://github.com/attermann/microReticulum) - Port of Reticulum Network Stack to C++ specifically but not exclusively targeting 32-bit and better MCUs.
* [BeechatNetworkSystemsLtd / Reticulum-rs](https://github.com/BeechatNetworkSystemsLtd/Reticulum-rs) - Reticulum Networking Stack implementation written in Rust.
* [Quad4-Software / Reticulum-Go](https://github.com/Quad4-Software/Reticulum-Go) - A high-performance and secure Go implementation of the Reticulum Network Stack.
* [sergst83 / reticulum-network-stack](https://github.com/sergst83/reticulum-network-stack) - An implementation of Reticulum network stack in Java.
* [int32 / reticulum_ex](https://codeberg.org/int32/reticulum_ex) - An implementation of the Reticulum Network Stack in elixir. This implementation is a work in progress and is definitely not ready for day to day use.
* [0xSeren / RTReticulum](https://github.com/0xSeren/RTReticulum) - Port of Reticulum Network Stack specifically for embedded microcontrollers.

## Application-Layer Protocols

* [markqvist / LXMF](https://github.com/markqvist/LXMF) - A simple and flexible messaging format and delivery protocol that allows a wide variety of implementations, while using as little bandwidth as possible.
* [markqvist / LXST](https://github.com/markqvist/LXST) - LXST is a simple and flexible real-time streaming format and delivery protocol that allows a wide variety of implementations, while using as little bandwidth as possible.
* [KC1AV / RRCd](https://github.com/kc1awv/rrcd) - Reticulum Relay Chat (RRC) is a live chat system built on top of the Reticulum Network, similar to IRC.

## Node Firmware

* [liberatedsystems / RNode_Firmware_CE](https://github.com/liberatedsystems/RNode_Firmware_CE) - An RNode is an open, free and unrestricted digital radio transceiver. It enables anyone to send and receive any kind of data over both short and very long distances. RNodes can be used with many different kinds of programs and systems, but they are especially well suited for use with Reticulum. The maintained firmware is a fork of the reference firmware: [markqvist / RNode_Firmware](https://github.com/markqvist/RNode_Firmware).
* [DanBeard / RETCON](https://github.com/DanBeard/RETCON) - RETCON enables quick creation of pre-configured Raspberry Pi images that automatically form resilient mesh networks once deployed.
* [strijar / RNS-Gate](https://github.com/strijar/RNS-Gate) - Standalone device for access and routing within the Reticulum Network Stack
* [gretel / reticulum-openwrt](https://github.com/gretel/reticulum-openwrt) - GitHub workflow for cross-compiling Reticulum Network Stack (RNS) packages for OpenWrt.

## Messengers and Browsers

* [markqvist / NomadNet](https://github.com/markqvist/NomadNet) - Off-grid, resilient mesh communication with strong encryption, forward secrecy and extreme privacy.
* [markqvist / Sideband](https://github.com/markqvist/Sideband) - Sideband is an extensible LXMF messaging and LXST telephony client, situational awareness tracker and remote control and monitoring system for Android, Linux, macOS and Windows.
* [liamcottle / reticulum-meshchat](https://github.com/liamcottle/reticulum-meshchat) - A simple mesh network communications app powered by the Reticulum Network Stack.
* [torlando-tech / columba](https://github.com/torlando-tech/columba) - A simple messaging app for the Reticulum network on Android using Bluetooth LE over Reticulum.
* [Quad4-Software / Ren-Browser](https://github.com/Quad4-Software/Ren-Browser) - A modern browser for the Reticulum Network using Reticulum-Go and Micron-Parser-Go.
* [kc1awv/ lxst_phone](https://github.com/kc1awv/lxst_phone) - A peer-to-peer voice calling application built on the Reticulum Network Stack.
* [fr33n0w / rBrowser](https://github.com/fr33n0w/rBrowser) - A modern, web-based UI for exploring NomadNet nodes and pages over the Reticulum network.
* [Quad4-Software / MeshChatX](https://github.com/Quad4-Software/MeshChatX) - All-in-one Reticulum client. An extensively modified and feature-rich fork of Reticulum MeshChat.
* [fr33n0w / lxmf-cli](https://github.com/fr33n0w/lxmf-cli) - Feature-Rich Terminal-based LXMF Messaging Client for Reticulum.
* [anonmesh / mobile_app](https://github.com/anonmesh/mobile_app/) - anonmesh is a messaging and off-grid transactions over Solana mobile app supported on : iOS / Android.
* [Colorado-Mesh / mesh-client](https://github.com/Colorado-Mesh/mesh-client) - Cross-platform desktop client for Reticulum (LXMF), Meshtastic, and MeshCore on macOS, Linux, and Windows.

## Transports and Network Interfaces

* [LFManifesto / ReticulumHF](https://github.com/LFManifesto/ReticulumHF) - Encrypted communication over HF radio using the Reticulum Network Stack and FreeDV digital modes.
* [torlando-tech /  ble-reticulum](https://github.com/torlando-tech/ble-reticulum) - A Bluetooth Low Energy (BLE) interface for Reticulum Network Stack, enabling mesh networking over BLE without additional hardware on Linux devices.
* [Quad4-Software / RNS-over-HTTP](https://github.com/Quad4-Software/RNS-over-HTTP) - HTTP interface for RNS that tunnels traffic over HTTP/S POST requests.
* [BeechatNetworkSystemsLtd / rns-tun-rs](https://github.com/BeechatNetworkSystemsLtd/rns-tun-rs) - Reticulum TUN adapter
* [BeechatNetworkSystemsLtd / rns-vpn-rs](https://github.com/BeechatNetworkSystemsLtd/rns-vpn-rs) - Library and application for VPN client over Reticulum mesh network.
* [BeechatNetworkSystemsLtd / rns-mavlink-rs](https://github.com/BeechatNetworkSystemsLtd/rns-mavlink-rs) - Bridges a flight controller connectd via serial port to a QGroundControl ground station over Reticulum mesh network.
* [RFnexus / reticulum-over-hf](https://github.com/RFnexus/reticulum-over-hf) - Resources on how to configure Reticulum to work over HF radio.
* [RFnexus / FreeDVInterface](https://github.com/RFnexus/FreeDVInterface) - A CustomInterface for Reticulum that provides a plug and play, cross-platform sound modem interface for HF radios using the FreeDV API. It supports VOX, serial, and Hamilb PTT.
* [R2AirVlad / Reticulum-Network-Over-Icom-D-star-Transceivers](https://github.com/R2AirVlad/Reticulum-Network-Over-Icom-D-star-Transceivers) - This custom RNS (reticulum.network) interface script enables transmission and reception of LXMF packets (MTU 500 bytes) through GMSK modems in Icom transceivers compatible with the D-star standard.
* [matvik22000 / rns-over-icmp](https://github.com/matvik22000/rns-over-icmp) - This small script allows using ICMP PING packets as a transport layer for Reticulum. It consists of two parts: a client and a server. The server must have a public IP address (or any other way for the client to ping it).
* [github.com/markqvist/Reticulum/discussions/1002](https://github.com/markqvist/Reticulum/discussions/1002) - Guide how to run Reticulum over DNS tunnel using Iodine server.
* [jardous / meshchat](https://github.com/jardous/meshchat) - Two chat console applications. One very simple p2p chat console application over Reticulum. The second can communicate with other LXMF clients (Reticulum MeshChat, Sideband)

## Network Tools

* [acehoss / rnsh](https://github.com/acehoss/rnsh) - An utility written in Python that facilitates shell sessions over Reticulum networks. It is based on the rnx utility that ships with Reticulum and aims to provide a similar experience to SSH.

## LXMF Bots

* [randogoth / lxmf-bot](https://codeberg.org/randogoth/lxmf-bot.git) - Python class to easily develop a simple Telethon style chatbot for the LXMF protocol.
* [Quad4-Software / LXMFy](https://github.com/Quad4-Software/LXMFy) - Extensible LXMF bot framework for the Reticulum Network with CLI, scheduling, cogs, spam protection, and offline NLP.
* [lxmfy / ollama-bot](https://lavaforge.org/lxmfy/ollama-bot) - Interact with Ollama LLMs using LXMFy bot framework.
* [apolosan / rns_hermes_endpoint](https://github.com/apolosan/rns_hermes_endpoint) - LXMF bridge forwarding Reticulum mesh messages to Hermes Agent for off-grid AI access.

## NomadNet Applications

* [Quad4-Software / rns-page-node](https://github.com/Quad4-Software/rns-page-node) - Serve NomadNet pages and files over the Reticulum network.
* [fr33n0w / thechatroom](https://github.com/fr33n0w/thechatroom) - An IRC-style chat room built for Reticulum NomadNet, optimized for MeshChat v2.1+. Made By F.
* [gralexey / lxmf-quick-chat](https://github.com/gralexey/lxmf-quick-chat) - A lightweight chat script for NomadNet nodes.
* [AutumnSpark1226 / nomadForum](https://github.com/AutumnSpark1226/nomadForum) - A forum application for the NomadNetwork.
* [voidw0rks/nomad-pages](https://codeberg.org/voidw0rks/nomad-pages) - A very simple page server for nomadnet, nomadnet-node compatible.
## Flasher

* [liamcottle / rnode-flasher](https://github.com/liamcottle/rnode-flasher) - A web based firmware flasher for Reticulum / RNode_Firmware.

## Micron Markdown Format

* [randogoth / micron-blog](https://codeberg.org/randogoth/micron-blog.git) - Pelican Plug-In and Theme for publishing a site in Micron markup format for Nomad Network Nodes.
* [randogoth / md2txt](https://codeberg.org/randogoth/md2txt.git) - Transform Markdown into arcane text formats (including NomadNet format).
* [RFnexus / micron-parser-js](https://github.com/RFnexus/micron-parser-js) - A JavaScript parser for Micron, a lightweight, terminal-friendly markdown format used in NomadNet and MeshChat.
* [fr33n0w / micron-composer](https://github.com/fr33n0w/micron-composer) - A powerful WYSIWYG editor for creating NomadNet-ready .mu pages using the Micron markup language.

## LoRa Tools

* [markqvist / LoRaMon](https://github.com/markqvist/LoRaMon) - This utility allows you to sniff LoRa networks with an RNode, and dump captured packets to the console or files.
* [randogoth / lora-transmit](https://codeberg.org/randogoth/lora-transmit.git) - Simple commandline raw LoRa packet transmitter for RNode hardware.

## Custom Devices

* [weltamdraht / ReticulumRasPiRelaySwitch](https://github.com/weltamdraht/ReticulumRasPiRelaySwitch) - This project switches on or off some electrical stuff if an according command is received through Reticulum's lxmf.

## Small Utilities and Code Examples

* [antlas0 / rns_tools](https://github.com/antlas0/rns_tools) - This package provides a small range of RNS tools, driven by my curiosity about Reticulum stack.
* [SebastianObi / RNS-Tools](https://github.com/SebastianObi/RNS-Tools) - Various small programs and tools which use the Reticulum Network Stack RNS
* [SebastianObi / LXMF-Tools](https://github.com/SebastianObi/LXMF-Tools) - Various small programs and tools which use the message protocol LXMF.
* [CyberKiska / lxmf-vanity-address-generator-py](https://github.com/CyberKiska/lxmf-vanity-address-generator-py) - A simple CLI tool to generate LXMF vanity addresses in Reticulum network.
* [SebastianObi / NomadNet-Pages](https://github.com/SebastianObi/NomadNet-Pages) - Various small example pages/programs for usage with the NomadNet node server or rns_server_page.
* [reticulum.network/manual/examples.html](https://reticulum.network/manual/examples.html) - Examples of using RNS in official documentation.

## Network Infrastructure

* [Reticulum Network Planner](https://github.com/0xSeren/Reticulum-Network-Planner) - Application that computes, based on geographical data, ideal locations for a predefined number of LoRa nodes within a predefined area.

## Community Discussions

* [rns.recipes](https://rns.recipes/) - Official forum for Reticulum related discussions. Also reachable via NomadNet: `9ce92808be498e9e05590ff27cbfdfe4`.
* [reticulum.zulipchat.com](https://reticulum.zulipchat.com) - Reticulum discussion on Zulipchat platform
* [#rns-space:matrix.org](https://matrix.to/#/#rns-space:yatrix.org) - Matrix platform space collecting Reticulum topical discussions
* [reddit.com/r/reticulum](https://www.reddit.com/r/reticulum/) - Reddit forum about Reticulum network
