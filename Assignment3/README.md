from selenium import webdriver
import time

driver_path = "C:/Selenium browser drivers/chromedriver.exe"

driver = webdriver.Chrome(executable_path=driver_path)

driver.get("https://www.instagram.com/accounts/login/")
time.sleep(5)

driver.quit()

