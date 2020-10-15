# Hello-App-with-PYTHON-GUI
#Hello App with Python using Tkinter



from tkinter import*

window=Tk()
window.title("Hello World App")

def action ():
    Text=Label(window,text="Hello World")
    Text.pack()

Button_Principal=Button(window,text="click me",command=action)
Button_Principal.pack()
window.mainloop()
