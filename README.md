# audit_main

## centos
{ 'compliance': 'admin/linux-baseline' }
{ 'compliance': 'admin/cis-centos7-level1' }

## ubuntu
{ 'compliance': 'admin/linux-baseline'}
{ 'compliance': 'admin/cis-ubuntu16.04lts-level1-server' }
{ 'compliance': 'admin/cis-ubuntu18.04lts-level1-server' }

## redhat
{ 'compliance': 'admin/linux-baseline'}
{ 'compliance': 'admin/cis-rhel7-level1-server' }

# windows
{ 'compliance': 'admin/windows-baseline' }
{ 'compliance': 'admin/cis-windows2016rtm-release1607-level1-memberserver' }
{ 'compliance': 'admin/cis-windows2012r2-level1-memberserver' }

## metadata.rb
depends 'audit'

## recipes/default.rb
include_recipe 'audit::default'

