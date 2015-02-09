# See https://docs.getchef.com/config_rb_knife.html for more information on knife configuration options

current_dir = File.dirname(__FILE__)
log_level                :info
log_location             STDOUT
node_name                "chefadmin1"
client_key               "#{current_dir}/chefadmin1.pem"
validation_client_name   "njalb-validator"
validation_key           "#{current_dir}/njalb-validator.pem"
chef_server_url          "https://chefserver1.njlab.com/organizations/njalb"
syntax_check_cache_path  "#{ENV['HOME']}/.chef/syntaxcache"
cookbook_path            ["#{current_dir}/../cookbooks"]
