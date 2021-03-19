# auto-comment: u need to install python and the pyautogui (pip install pyautogui)
import pyautogui
import time


comment=["#ETB_EN_FORCE"]

time.sleep(5)

      for i in range (10):
        pyautogui.typewrite(comments[i])
        pyautogui.typewrite("\n")
        time.sleep(3)
