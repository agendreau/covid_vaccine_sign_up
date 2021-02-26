# Kroger Covid Vaccine Monitoring and Automated Sign Up
Continually monitor Kroger's COVID vaccine availability and sign yourself up with a bot when one becomes available

This code is based on my recent medium article, which can be found at https://daniel-warren.medium.com/how-to-guarantee-a-covid-19-vaccine-with-python-f4084aaa7414.

This is still a work in progress, so please let me know if you find any issues or if there are specific features you would like me to add.

## Notes
The `requirements.txt` file should list all Python libraries that your notebooks
depend on, and they will be installed using:

```
pip install -r requirements.txt
```
Also, you will need to install a driver of your choice so Selenium can run bots in your browser. 
Please refer to the link below to install the driver of your choice on your computer.

https://selenium-python.readthedocs.io/installation.html

## To run the full automation
The `kroger_availability_status.py` file should be only file you need to run. This file should do the following 2 things:

1. Web scrape data from Kroger's website to determine if a vaccine is available
2. If a vaccine is available, start signing you up for that opening

To run this code, all you need to do is type the following in your terminal:

```
python kroger_availability_status.py.py
```

Happy botting!
