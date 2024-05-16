Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).


- defaults: Bao gồm các giá trị mặc định cho các biến của role. Ở đây chúng ta định nghĩa 1 vài biến mặc định, nhưng chúng có độ ưu tiên thấp nhất và cũng thường bị ghi đè bởi các phương thức khác để customzie role
- files: Chứa các file tĩnh và custom mà role sử dụng để thực hiện một vài tasks nhất định
- handlers: 1 tập hợp các handlers mà có thể kích hoạt bởi các tasks của role
- meta: Bao gồm thông tin metadata cho role, nó có thể là các dependencies (phụ thuộc), tác giả, license, nền tảng khả dụng,…
- tasks: 1 danh sách các tasks để thực hiện bởi role. Phần này có thể hiểu tương tự như task section trong 1 playbook
- templates: Bao gồm các file template Jinja2 sử dụng bởi các tasks của role
- tests: Bao gồm các file cấu hình liên quan đến kiểm thử role
- vars: Chứa các biến được định nghĩa cho role (các biến ở đây có độ ưu tiên cao hơn defaults)