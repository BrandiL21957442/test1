# test1
import requests
import time
import json
import random

with open("proxy_list.txt", "r") as f:
    proxy_list = [row.strip() for row in f]
