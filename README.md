# flask

Previous way to run app:

    - flask --app hello run --host 0.0.0.0

How to run now:

    - flask --app '__init__:create_app("development")' run --host 0.0.0.0