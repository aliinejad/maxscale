# maxscale-helmChart

This Helm Chart  runs  MariaDB MaxScale for mariadb replication cluster 





| Parameter                 | Description                                     | Default                                                 |
|---------------------------|--------------------------------------------------------|--------------------------------------------------|
| ` server1.db `            | IP or Hostname of the first cluster node               | `master`                                         |
| ` server2.db `            | IP or Hostname of the 2nd cluster node                 | `slave1`                                         |
| ` server3.db `            | IP or Hostname of the 3rd cluster node                 | `slave2`                                         |
| ` server1.dbport `        | port of the first database node                        | `3306`                                           |
| ` server2.dbport `        | port the second database node                          | `3306`                                           |
| ` server3.dbport `        | port of the third database node                        | `3306`                                           |
| ` service.port1   `       |       readwrite maxscale service port                  | `4006`                                           |
| ` service.port2           |       readonly maxscale service port                   | `4008`                                           |
| ` service.port3   `       |       REST API maxescale service port                  | `8989`                                           |
| ` serviceUser   `         |       MaxScale service user name                       | `maxuser`                                        |
| ` servicePassword   `     |       MaxScale service user password                   | `maxpwd`                                         |
| ` monitorUser   `         |       MaxScale monitor user name                       | `maxuser`                                        |
| ` monitorPassword   `     |       MaxScale monitor user password                   | `maxpwd`                                         |



