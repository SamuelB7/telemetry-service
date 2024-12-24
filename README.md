# Telemetry Service

Telemetry service made with open-telemetry collector, jaeger and open-search.

## Requirements

Docker

## Usage

```sh
git clone https://github.com/SamuelB7/telemetry-service.git
```

```sh
cd telemetry-service
```

```sh
docker compose up
```

You can access the jaeger GUI interface by accessing `localhost:8081`

## Set up

Install the open-telemetry sdk in the project that you want to monitor and set the spans to be sent to the receiver endpoint of this project. <br>
[open-telemetry-docs](https://opentelemetry.io/docs/getting-started/dev/)
