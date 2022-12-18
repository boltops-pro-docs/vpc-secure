<!-- note marker start -->
**NOTE**: This repo contains only the documentation for the private BoltsOps Pro repo code.
Original file: https://github.com/boltopspro/vpc-secure/blob/master/lib/vpc_secure/help/network_acl.md
The docs are publish so they are available for interested customers.
For access to the source code, you must be a paying BoltOps Pro subscriber.
If are interested, you can contact us at contact@boltops.com or https://www.boltops.com

<!-- note marker end -->

## Examples

    $ vpc-secure network_acl acl-0f58e7867186b02cb --noop
    $ vpc-secure network_acl acl-0f58e7867186b02cb
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>1433, :to=>1433}, :protocol=>"6", :rule_action=>"deny", :rule_number=>70}
    Rule already exists. rule number: 70 {:cidr_block=>"0.0.0.0/0", :egress=>false, :icmp_type_code=>nil, :ipv_6_cidr_block=>nil, :port_range=>{:from=>1433, :to=>1433}, :protocol=>"6", :rule_action=>"deny", :rule_number=>70}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>1521, :to=>1521}, :protocol=>"6", :rule_action=>"deny", :rule_number=>71}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>3306, :to=>3306}, :protocol=>"6", :rule_action=>"deny", :rule_number=>72}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>5000, :to=>5000}, :protocol=>"6", :rule_action=>"deny", :rule_number=>73}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>5432, :to=>5432}, :protocol=>"6", :rule_action=>"deny", :rule_number=>74}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>5984, :to=>5984}, :protocol=>"6", :rule_action=>"deny", :rule_number=>75}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>9042, :to=>9042}, :protocol=>"6", :rule_action=>"deny", :rule_number=>76}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>11211, :to=>11211}, :protocol=>"6", :rule_action=>"deny", :rule_number=>77}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>27017, :to=>27017}, :protocol=>"6", :rule_action=>"deny", :rule_number=>78}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>50000, :to=>50000}, :protocol=>"6", :rule_action=>"deny", :rule_number=>79}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>6379, :to=>6380}, :protocol=>"6", :rule_action=>"deny", :rule_number=>80}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>8080, :to=>8080}, :protocol=>"6", :rule_action=>"deny", :rule_number=>81}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>28015, :to=>28015}, :protocol=>"6", :rule_action=>"deny", :rule_number=>82}
    create_deny_acl_rule {:cidr_block=>"0.0.0.0/0", :egress=>false, :network_acl_id=>"acl-0f58e7867186b02cb", :port_range=>{:from=>29015, :to=>29015}, :protocol=>"6", :rule_action=>"deny", :rule_number=>83}
    $
