# Online Barcode and QR Code Reader with Python Django
The sample demonstrates how to create an online Barcode Reader with Python Django and [Dynamsoft Barcode Reader SDK](https://www.dynamsoft.com/barcode-reader/overview/).

## Prerequisites

- Python 3.7.9

    ```bash
    python --version
    ```

- Django 3.2.7
    
    ```bash
    python -m pip install Django
    python -m django --version
    ```
- [Dynamsoft Barcode Reader SDK v9.0](https://www.dynamsoft.com/barcode-reader/sdk-desktop-server/)
    
    ```bash
    pip install dbr==9.0
    ```

## Python Barcode SDK License
Apply for a [trial license](https://www.dynamsoft.com/customer/license/trialLicense/?product=dbr) and then update the following Python code:

```python
BarcodeReader.init_license("DLS2eyJoYW5kc2hha2VDb2RlIjoiMjAwMDAxLTE2NDk4Mjk3OTI2MzUiLCJvcmdhbml6YXRpb25JRCI6IjIwMDAwMSIsInNlc3Npb25QYXNzd29yZCI6IndTcGR6Vm05WDJrcEQ5YUoifQ==")
```

## Usage
1. Run the project:

    ```bash
    python manage.py makemigrations
    python manage.py migrate --run-syncdb
    python manage.py runserver
    ``` 
    
2. Visit `127.0.0.1:8000` in a web browser.

    ![python django online barcode reader](https://www.codepool.biz/wp-content/uploads/2022/02/python-django-online-barcode-reader.png)

## Blog
[Building Online Barcode and QR Code Scanning App with Python Django](https://www.dynamsoft.com/codepool/django-barcode-scanning-app.html)

