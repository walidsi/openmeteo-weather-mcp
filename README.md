# MCP Weather Server

A simple MCP server that provides hourly weather forecasts using the Open-meteo API.

## Setup

1. Install dependencies using `uv`:
```bash
uv venv
uv sync
```


## Running the Server

```json
{
    "mcpServers": {
        "open_meteo_weather": {
            "command": "uv",
            "args": [
                "--directory",
                "path/to/openmeteo-weather-mcp/",
                "run",
                "openmeteo_weather/openmeteo_weather.py"
            ] 
        }
    }
}
```
