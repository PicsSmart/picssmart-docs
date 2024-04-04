# PicsSmart-Federated-Server

This component contains the federated server of the **PicsSmart** application. This can be deployed in any platform so that it has a public IP address. Then the Core application can connect to this using a gRPC tunnel.

## Deploying

### Clone the repository

```bash
git clone https://github.com/PicsSmart/picssmart-fed-server.git
```

### Prerequisites

- Python

### Install the dependencies

```bash
cd image-captioning
python3 -m venv ./venv
source venv/bin/activate
pip install -r requirements.txt
```

### How to run the application

```bash
cd image-captioning
source venv/bin/activate
python server.py
```