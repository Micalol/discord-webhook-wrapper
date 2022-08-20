# discord-webhook-wrapper
**__Use discord webhooks easy__**

+ installation
```cmd
pip install easy_webhook=0.0.1
```



+ basic usage

```py
from easy_webhook import webhook

hook = webhook.Webhook("Hook URL")
hook.change_username("bruh")
hook.send("wsg retard")
```

+ send a file

```py
from easy_webhook import Webhook

hook = webhook.Webhook("HOOK URL")
hook.send_file("file_path", "file_name")
```
