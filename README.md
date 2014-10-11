mqtt-client-ruby
================

Example of connecting to ZADATA via MQTT using Ruby

``` bash
git clone git@github.com:zadata/mqtt-client-ruby.git
cd mqtt-client-ruby/

sudo gem install mqtt
```

To find your MQTT Username and Password
login into your `ZADATA` account on http://ZADATA.com and click navbar -> `Settings` -> `Credentials`

NOTE: you have two MQTT passwords (one for subscribers only, the other with subscriber and publisher priveleges - use the one for publishers).

``` bash
export MQTT_USER=...
export MQTT_PWD=...
ruby mqtt_client.rb
```
