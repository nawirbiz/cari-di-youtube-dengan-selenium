from selenium import webdriver
import selenium
import time

driver = webdriver.Chrome("C:\Program Files (x86)\chromedriver.exe")
driver.get("https://www.youtube.com")
search = driver.find_element_by_xpath('/html/body/ytd-app/div/div/ytd-masthead/div[3]/div[2]/ytd-searchbox/form/div/div[1]/input')
search.send_keys("test")
submit_button = driver.find_elements_by_xpath('//*[@id="search-icon-legacy"]/yt-icon')[0]
submit_button.click()
