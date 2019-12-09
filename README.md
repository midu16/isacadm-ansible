# Description

This ansible-playbook is design to upload and keep to a valid version all the certificats for the ZXCLOUD R5300 G4 Rack Server.

ZXCLOUD R5300 G4 is ZTE’s new generation 2U 2-socket rack server, supporting latest Intel® Xeon® Scalable Processors. R5300 G4 uses high-density, modular design, providing high performance, high reliability, high scalability, easy management and other features, widely applicable to Internet, cloud computing, big data, NFV, SDN and other fields.

R5300 G4 has been verified by Intel as an Intel® Select Solution for NFVI Solution.

## Project Structure

```
.
├── LICENSE
├── README.md
└── zte-certs
    ├── inventory-isac-prod
    ├── inventory-isac-test
    ├── playbook-isacadm.yml
    └── roles
        └── isacadm
            ├── defaults
            │   └── main.yml
            ├── files
            ├── handlers
            │   └── main.yml
            ├── meta
            │   └── main.yml
            ├── README.md
            ├── tasks
            │   └── main.yml
            ├── templates
            ├── tests
            │   ├── inventory
            │   └── test.yml
            └── vars
                └── main.yml

11 directories, 13 files

```


# Contact

For any questions or observations, please send me with a e-mail : idumihai16@gmail.com
