---
Default values
---
nginx_state: "present"
update_cache: "yes"
project_name: "{{ lookup('env', 'CI_PROJECT_NAME') }}"
site_dir_mode: "755"
site_dir_owner: "www-data"
site_dir_group: "www-data"

