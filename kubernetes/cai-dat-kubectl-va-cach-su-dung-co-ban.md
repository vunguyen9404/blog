# Cài đặt kubectl với Google Cloud SDK

## Cài đặt Google Cloud SDK trên Linux

{% hint style="info" %}
Cài đặt Google Cloud SDK cần python 2.7, để chắc chắn python 2.7 đã được cài đặt trên máy hãy kiểm tra với command: _python -V_
{% endhint %}

#### Download Google Cloud SDK phù hợp với hệ điều hành:

```bash
# kiểm tra linux 32bit hay 64bit
sudo uname -m
```

Với linux 32bit:

```bash
curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-231.0.0-linux-x86.tar.gz
```

Với linux 64bit:

```bash
curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-231.0.0-linux-x86_64.tar.gz
```

