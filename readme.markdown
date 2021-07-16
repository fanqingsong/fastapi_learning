
# with reload option to support hot-load with python script
uvicorn router:app --reload


# access query URL
http://127.0.0.1:8000/items/5?q=somequery


# access docs
http://127.0.0.1:8000/docs





