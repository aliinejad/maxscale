# maxscale-helmChart

This Helm Chart  runs  MariaDB MaxScale for mariadb replication cluster 





| Parameter                 | Description                                     | Default                                                 |
|---------------------------|--------------------------------------------------------|--------------------------------------------------|
| ` db1 `                   | IP or Hostname of the first cluster node               | `master`                                         |
| ` db2 `                   | IP or Hostname of the 2nd cluster node                 | `slave1`                                         |
| ` db3 `                   | IP or Hostname of the 3rd cluster node                 | `slave2`                                         |
| ` port1   `               |       readwrite service port                           | `4006`                                           |
| ` port2   `               |       readonly service port                            | `4008`                                           |
| ` port3   `               |       REST API service port                            | `8989`                                           |
| ` serviceUser   `         |       MaxScale service user name                       | `maxuser`                                        |
| ` servicePassword   `     |       MaxScale service user password                   | `maxpwd`                                         |
| ` monitorUser   `         |       MaxScale monitor user name                       | `maxuser`                                        |
| ` monitorPassword   `     |       MaxScale monitor user password                   | `maxpwd`                                         |



