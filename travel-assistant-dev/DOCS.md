# Home Assistant Add-on: Travel Assistant (dev)

The **Travel Assistant (dev)** add-on provides development and edge builds of Travel Assistant for Home Assistant.

> [!WARNING]
> This is a development build track (`dev` tag). It may contain experimental features or breaking changes.

## Features

- **Ingress Dashboard**: Directly accessible from the Home Assistant sidebar.
- **RESTful API**: Endpoints for service status, ping checks, and transport insights.
- **Lightweight Execution**: Powered by Python, Flask, and Gunicorn on Debian Bookworm.

## Configuration

Add-on configuration is managed via the **Configuration** tab in Home Assistant.

### Option: `log_level`

The `log_level` option controls the verbosity of log output.

- `trace`
- `debug`
- `info` (default)
- `notice`
- `warning`
- `error`
- `fatal`

## Ingress

This add-on supports Home Assistant Ingress. When started, click **Open Web UI** or access it directly via the Home Assistant sidebar.

## Support

For issues, feature requests, or questions, please visit the [GitHub Repository](https://github.com/stuart-c/travel-assistant).
