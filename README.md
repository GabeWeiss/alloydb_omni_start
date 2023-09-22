# Shell script quickstart
Setting up AlloyDB Omni is incredibly easy....BUT, there's a bunch of steps to set it up. You need to install Docker, pull down the command-line tool, start the service. And that's the Omni piece, then you also either have to set up virtualization on your laptop, or create a VM somewhere, manage connecting to it securely so you can install everything on it.

This repo holds a shell script that can be run on a Debian-based Linux machine (wherever you choose to put it) to automatically install AlloyDB Omni and get it started up so you're ready to go with a single script.

For added oomph, you can set this as a startup script when creating a GCE (Google Compute Engine) VM, and in one step create a virtual machine with Omni all set to go.