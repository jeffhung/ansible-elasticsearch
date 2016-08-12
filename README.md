# Ansible Role: jeffhung.elasticsearch

Ansible playbook for installing Elasticsearch on CentOS/Debian Linux

Install this playbook:

	ansible-galaxy install jeffhung.elasticsearch


## Role Variables

### `elasticsearch_major_version`

(Default: `2`)

Set which Elasticsearch major version to use.


## Directory Layout

After installation, the directory layout of Elasticsearch would be the
following:

| Setting        | Path                               |
|----------------|------------------------------------|
| `path.home`    | `/usr/share/elasticsearch`         |
|                | `/usr/share/elasticsearch/bin`     |
| `path.conf`    | `/etc/elasticsearch`               |
| `path.data`    | `/var/lib/elasticsearch`           |
| `path.logs`    | `/var/log/elasticsearch`           |
| `path.plugins` | `/usr/share/elasticsearch/plugins` |
| `path.repo`    |                                    |
| `path.scripts` | `/etc/elasticsearch/scripts`       |

See: https://www.elastic.co/guide/en/elasticsearch/reference/current/setup-dir-layout.html


## License

BSD

