from tkinter import *
import time

root = Tk()
root.title("Program Jam")

def waktu():
	jam = time.strftime('%I:%M:%S %p')
	label.config(text = jam)
	label.after(1000, waktu)


label = Label(root,bg='black', fg='white',
			  font=("system", 40))

label.pack(anchor ='center')

waktu()
root.mainloop()
