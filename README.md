# GUI Modules

This repo contains modules for [Liberouter GUI](https://github.com/CESNET/liberouter-gui)

The repo serves as a submodule for Liberouter GUI.

# Currently Available Modules

* FTAS
* NERD
* Security Cloud
* NEMEA (currently not in this repo)

# Configuration

Each module must contain a `config.json` file which specifies a given folder is a module for Liberouter GUI. Example configuration is located in `examples/example_config.json`.

# Module Structure

A module consists of two parts: backend and fronend. Frontend is used in frontend modules in Liberouter GUI and backend is loaded via REST API of Liberouter GUI.
