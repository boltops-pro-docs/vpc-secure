<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-pro/vpc-secure/blob/master/lib/vpc_secure/help/completion.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

## Examples

    vpc-secure completion

Prints words for TAB auto-completion.

    vpc-secure completion
    vpc-secure completion hello
    vpc-secure completion hello name

To enable, TAB auto-completion add the following to your profile:

    eval $(vpc-secure completion_script)

Auto-completion example usage:

    vpc-secure [TAB]
    vpc-secure hello [TAB]
    vpc-secure hello name [TAB]
    vpc-secure hello name --[TAB]
