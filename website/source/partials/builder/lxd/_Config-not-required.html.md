<!-- Code generated from the comments of the Config struct in builder/lxd/config.go; DO NOT EDIT MANUALLY -->

-   `output_image` (string) - The name of the output artifact. Defaults to
    name.
    
-   `container_name` (string) - Container Name
-   `command_wrapper` (string) - Lets you prefix all builder commands, such as
    with ssh for a remote build host. Defaults to "{{.Command}}"; i.e. no
    wrapper.
    
-   `profile` (string) - Profile
-   `init_sleep` (string) - The number of seconds to sleep between launching
    the LXD instance and provisioning it; defaults to 3 seconds.
    
-   `publish_properties` (map[string]string) - Pass key values to the publish
    step to be set as properties on the output image. This is most helpful to
    set the description, but can be used to set anything needed. See
    https://stgraber.org/2016/03/30/lxd-2-0-image-management-512/
    for more properties.
    
-   `launch_config` (map[string]string) - List of key/value pairs you wish to
    pass to lxc launch via --config. Defaults to empty.
    