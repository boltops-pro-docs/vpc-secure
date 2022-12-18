<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/vpc-secure/blob/master/lib/vpc_secure/help/completion.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

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
