# SImpleWEBSever
# EX01 Developing a Simple Webserver
## Date: 12-10-2026

## AIM:
To develop a simple webserver to serve html pages and display the Device Specifications of your Laptop.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
from django.contrib import admin
from django.urls import path
from django.http import HttpResponse


def my_home_page(request):
    name = "JANADHYAKSHA G"
    ref_no = "26003462"

    return HttpResponse(
        f"<h1>Name: {name}</h1>"
        f"<p>Register Number: {ref_no}</p>"
    )


urlpatterns = [
    path('admin/', admin.site.urls),
    path('', my_home_page),
]

## OUTPUT:
<img width="1341" height="852" alt="Screenshot 2026-10-12 095205" src="https://github.com/user-attachments/assets/f2a92305-56ee-417b-9147-ec0d99571763" />



## RESULT:
The program for implementing simple webserver is executed successfully.
