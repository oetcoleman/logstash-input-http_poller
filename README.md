# Logstash HTTP input plugin

Modified version of [this plugin](https://github.com/logstash-plugins/logstash-input-http_poller).  Allows `interval` to be set to zero, in which case the plugin will perform one poll of the url and then quit.

## Config

See [logstash documentation](https://www.elastic.co/guide/en/logstash/current/plugins-inputs-http_poller.html).

## Building

Use `vagrant up` to build.

## Installation

Run `bin/plugin update` followed by `bin/plugin install logstash-input-http_poller-2.0.3.gem`.

