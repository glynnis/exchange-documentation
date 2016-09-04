Steps to build documents
========================

1. Create virtual environment (venv)

   `demo:boundless exchange$ virtualenv venv`

2. Activate virtual environment

   `demo:boundless exchange$ source venv/bin/activate`

3. Install Sphinx

   `(venv) demo:boundless exchange$ pip install -r requirements.txt`

4. build html

   `make clean html`

   Output files will be located in `build/html`

5. build wheel package for exchange

   `make clean wheel`

   Output file will be located in `build\`
