# maxscale-helmChart

maxscale helm chart for mariadb replication 



| Parameter                 | Description                                     | Default                                                 |
|---------------------------|--------------------------------------------------------|--------------------------------------------------|
| ` server1 `               | IP or Hostname of the first cluster node               | `master`                                         |
| ` server2 `               | IP or Hostname of the 2nd cluster node              | `slave1`                                         |
| ` server3 `               | IP or Hostname of the 3rd cluster node               | `slave2`                                         |
| ` port1   `               |       readwrite service port                           | `4006`                                           |
| ` port2   `               |       readonly service port                            | `4008`                                           |
| ` port3   `               |       REST API service port                            | `4008`                                           |


