# asg_instance_ips

Get AWS auto scale groups (asg) list of instance ips.

Usage:

    $ asg_instances_ips [options]
    Options:
        --profile <profile>          AWS profile

Example output:

    $ asg_instances_ips --profile prod
        my-new-small-project: 10.8.12.173
        the-big-one: 10.102.113.81, 10.102.251.222, 10.102.154.235

