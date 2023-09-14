# kalkul
from tkinter import * from decimal import *  root = Tk() root.title('Calculator')  buttons = (('7', '8', '9', '/', '4'),            ('4', '5', '6', '*', '4'),            ('1', '2', '3', '-', '4'),            ('0', '.', '=', '+', '4')            )  activeStr = '' stack = []
