from selenium import webdriver
from selenium.webdriver.common.by import By
import time

driver = webdriver.Chrome()
driver.get('https://web.whatsapp.com/')
input('escanee el codigo qr y presione enter')
all_numbers = ['573128204694', '573023476635']
for i in range(2):
	time.sleep(5)
	#numero y mensaje a enviar
	#driver.get('https://api.whatsapp.com/send?phone='+all_numbers[i]+'&text=Hola%20prueba%20bot')
	driver.get('https://web.whatsapp.com/send/?phone='+all_numbers[i]+'&text=Hola%20prueba%20bot')
	#click al boton enviar
	#boton = driver.find_element('data-testid', 'compose-btn-send')
	boton = driver.find_element(By.XPATH, "//*[@data-testid='compose-btn-send']")
	boton.click()

	#busqueda flecha de envio
	#submit_button = driver.find_elements_by_xpath("//button[@class='_35EW6']") #retorna una lista
	#while(len(submit_button) == 0):
		#time.sleep(0.5)
		#submit_button = driver.find_elements_by_xpath("//button[@class='_35EW6']")

	#enviar el mensaje
	time.sleep(1)
	#submit_button = driver.find_elements_by_xpath("//button[@class='_35EW6']")
	#a = submit_button[0]
	#a.click()
	print("mensaje enviado")

	
