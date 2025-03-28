# TrainSounds

Simple project for making easy train sounds.

## Set Up

```
python -m venv venv
source venv/bin/activate

pip install -r requirements.txt
```

## Compile

```
# optionally run
source venv/bin/activate

esphome run trainsounds/simple_train_sounds.yaml
```

If you want to use the pre-configured settings 
for WiFi and/or `Home Assistant` than this 
expects a `secrets.yaml` like the following:

```yaml
wifi_ssid: MyWiFi
wifi_password: mywifipassword

# For more on this, see docs: https://esphome.io/components/api.html#configuration-variables
encryption_key: "jjsZi7gTqBpkaie97GHMdQfDAmwZfVJnkiI4dvkXcB4="
```
