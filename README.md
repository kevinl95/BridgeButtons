# BridgeButtons
![Security Scan](https://github.com/kevinl95/BridgeButtons/actions/workflows/main.yml/badge.svg)

Deploy a Tor bridge with presets so that it stays within Amazon Web Services' free tier for the first year it runs. This makes use of a t2.micro EC2 instance with a Torrc file set up so that bandwidth won't exceed 15GB/month. The goal is to make deploying a Tor bridge as frictionless as possible to help increase the number of Tor bridges available for activists, journalists, and others that are relying on Tor today.