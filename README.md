# society-vehicle-management-sys

A Flask app with OCR reader for society to track vehicles coming in.


Use Commands
```bash
set FLASK_APP=run.py
flask shell
```

> Only for first

```bash
from app import db

db.create_all()
```

Then to run
```bash

flask run --host=0.0.0.0 --port=5000
```
