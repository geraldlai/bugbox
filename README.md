bugbox: Full-blown toolbox for general purpose debugging
--------------------------------------------------------

This toolbox comes with GNU coreutils plus many more admin/networking and modern general command-line tools. Manpages are included, for convenience.

Please see Dockerfile for list of tools.

Image size: ~420MB (Alpine Linux based)


CoreOS / Container Linux usage
==============================

This may be used as the default CoreOS toolbox:

    $ sudo cat > ~/.toolboxrc << "EOF"
    TOOLBOX_DOCKER_IMAGE=geraldlai/bugbox
    TOOLBOX_USER=root
    EOF

Host filesystem is mounted as `/media/root`
