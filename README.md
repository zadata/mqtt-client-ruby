mqtt-client-ruby
================

Example of connecting to ZADATA via MQTT using Ruby

``` bash
git clone git@github.com:zadata/mqtt-client-ruby.git
cd mqtt-client-ruby/

bundle install
```

If you have problems with `bundle install` then you can just run
``` bash
gem install mqtt
```
as it's the only gem used.


To find your MQTT Username and Password
login into your `ZADATA` account on http://ZADATA.com and click navbar -> `Settings` -> `Credentials`

NOTE: you have two MQTT passwords (one for subscribers only, the other with subscriber and publisher priveleges - use the one for publishers).

``` bash
MQTT_URL=mqtt://USER:PWD@mqtt.zadata.com:1883 ruby mqtt_client.rb
```
or

``` bash
MQTT_URL=mqtt://USER:PWD@mqtt.zadata.com:1883 ruby mqtt_client_threaded.rb
```
