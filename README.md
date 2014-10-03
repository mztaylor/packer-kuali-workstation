## Development Workstation using packer and chef-solo

## Setup

First run validate to ensure a stable build:

		packer validate ubuntu-13.04-desktop.json

Next, build a copy of your image

		packer build ubuntu-13.04-desktop.json