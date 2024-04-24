# Backend

This project uses a number of Python packages for its functionality. The dependencies are listed in the `requirements.txt` file.

## Dependencies

Here are some of the key packages:

- `aiohttp`: Asynchronous HTTP client/server for asyncio and Python.
- `azure-ai-documentintelligence`, `azure-core`, `azure-identity`, `azure-keyvault-secrets`, `azure-monitor-opentelemetry`, `azure-search-documents`, `azure-storage-blob`, `azure-storage-file-datalake`: These packages are part of the Azure SDK for Python and are used for various Azure services.
- `flask`: A lightweight WSGI web application framework.
- `microsoft-kiota-abstractions`, `microsoft-kiota-authentication-azure`, `microsoft-kiota-http`, `microsoft-kiota-serialization-json`, `microsoft-kiota-serialization-text`: These packages are part of the Microsoft Kiota SDK for Python and are used for various Microsoft services.
- `msgraph-core`, `msgraph-sdk`: These packages are part of the Microsoft Graph SDK for Python and are used for various Microsoft Graph services.
- `numpy`: A package for scientific computing with Python.
- `opentelemetry-api`, `opentelemetry-instrumentation`, `opentelemetry-sdk`: These packages are part of the OpenTelemetry SDK for Python and are used for observability.
- `pandas`: A powerful data structures for data analysis, time series, and statistics.
- `quart`: A Python ASGI web microframework.
- `requests`: A simple, yet elegant HTTP library.
- `uvicorn`: A lightning-fast ASGI server implementation.

## Installation

To install these packages, you can use pip:

```sh
pip install -r requirements.txt