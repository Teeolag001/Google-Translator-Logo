# Google-Translator-Logo
from tkinter import *
import tkinter as tk
from tkinter import ttk
from PIL import ImageTk, Image      #pip install pillow
from googletrans import Translator  #pip install googletrans==3.1.0a0
from tkinter import messagebox

root = tk.Tk()
root.title('Langauge Translator')
root.geometry('800x400')
root.maxsize(800,400)
root.minsize(800,400)



img = ImageTk.PhotoImage(Image.open('translator.png'))
label = Label(image=img)
label.place(x=230,y=3)
