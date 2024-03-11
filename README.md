# app

import tkinter as tk

# Create the main window
root = tk.Tk()
root.title("My Mini App")

# Create a label
label = tk.Label(root, text="Hello, World!")
label.pack(pady=10)

# Create a button
def button_click():
    print("Button clicked!")

button = tk.Button(root, text="Click Me", command=button_click)
button.pack(pady=10)

# Create an entry field
entry = tk.Entry(root)
entry.pack(pady=10)

# Start the main event loop
root.mainloop()
