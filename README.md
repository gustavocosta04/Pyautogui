# Pyautogui
#A simple program that opens a live stream on YouTube using pyautogui.
import pyautogui
import time
#print(pyautogui.position())
pyautogui.moveTo(415, 1065)
pyautogui.click()
pyautogui.moveTo(529, 571)
time.sleep(3)
pyautogui.doubleClick()
time.sleep(2)
pyautogui.moveTo(636, 118)
pyautogui.click()
pyautogui.write('chaves ao vivo')
pyautogui.press('enter')
time.sleep(2)
pyautogui.moveTo(385, 619)
pyautogui.click()
time.sleep(1)
pyautogui.press('f')
